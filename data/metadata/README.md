# Metadata

This directory contains documentation describing the files and variables used in the Caribbean Elections Corpus.

## Data dictionary

`data_dictionary.csv` defines each column used in the private master file and in the publicly released comment, index, and metadata files.

The data dictionary contains the following fields:

- `column_name`: Exact column header used in the corpus.
- `file_scope`: Indicates where the column is used.
  - `both`: Included in both the private master file and public release.
  - `public_only`: Included only in publicly released index or metadata files.
  - `private_only`: Retained only in the private master file.
- `data_type`: Expected type of data, such as text, integer, date, or datetime.
- `format_or_values`: Required format, permitted values, or an example value.
- `definition`: Explanation of what the column represents.

## Missing values

A blank value means that the information was unavailable, not applicable, or could not be obtained. Researcher-created values must not be substituted for unavailable platform-provided identifiers.

## Identifiers

Identifier columns must be stored as text to prevent spreadsheet software from rounding, truncating, or converting them to scientific notation.

- `comment_id` is assigned by the researcher and preserves the corpus’s parent–reply structure.
- `platform_comment_id` is supplied by Facebook or YouTube.
- `source_id` identifies the platform post or video containing the comment.
- `author_id` is a researcher-assigned, corpus-specific pseudonym and is not a platform account identifier.

## Engagement metrics

`likes_count` and `reply_count` represent the values visible when the data were observed. They must be interpreted together with `metrics_last_observed`.
