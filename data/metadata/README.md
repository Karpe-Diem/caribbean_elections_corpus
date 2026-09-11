# Metadata

This directory contains documentation describing the files and variables used in the Caribbean Elections Corpus.

## Data dictionary

`data_dictionary.csv` defines each column used in the private master file and in the publicly released comment, index, annotation, and metadata files.

The data dictionary contains the following fields:

- `column_name`: Exact column header used in the corpus.
- `file_scope`: Indicates where the column is used.
  - `both`: Appears in the private master comment file and in the public release.
  - `public_only`: Appears in a public index, annotation, or metadata file but is not a column in the private master comment file.
  - `private_only`: Retained only in private research files and excluded from the public release.
- `data_type`: Expected type of data, such as text, integer, date, or datetime.
- `format_or_values`: Required format, permitted values, or an example value.
- `definition`: Explanation of what the column represents.

## Annotation codes

`annotation_codes.csv` publishes the definitions of both primary and secondary function codes for methodological transparency. Public annotation records contain final adjudicated `primary_function` assignments only. The `secondary_function` assignments, coder identifiers, pre-adjudication codes, and coding memos remain in the private research files.

## Missing values

A blank value means that the information was unavailable, not applicable, or could not be obtained. Researcher-created values must not be substituted for unavailable platform-provided identifiers.

## Identifiers

Identifier columns must be stored as text to prevent spreadsheet software from rounding, truncating, or converting them to scientific notation.

- `comment_id` is assigned by the researcher and preserves the corpus's parent-reply structure.
- `platform_comment_id` is supplied by Facebook or YouTube.
- `source_id` identifies the platform post or video containing the comment.
- `author_id` is a researcher-assigned, corpus-specific pseudonym and is not a platform account identifier.

## Emoji annotation units

- `emoji_count` records all emoji occurrences in a comment, including repetitions.
- Each distinct Unicode emoji grapheme cluster is normally represented once in the annotation file.
- `emoji_frequency` records how many times that distinct emoji occurs.
- `emoji_order` records the order in which distinct emojis first appear.
- `emojipedia_category` records the Emojipedia category used during coding.
- `emoji_type` records the researcher-defined category informed by Emojipedia.

## Engagement metrics

`likes_count` and `reply_count` represent the values visible when the data were observed. They must be interpreted together with `metrics_last_observed`.

## Election-site codes

`site_codes.csv` maps the abbreviated election-site codes used in release filenames to the corresponding `election_site` values.
