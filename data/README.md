# Public corpus data

This directory adapts the source-and-comment organization of the SENSEI Annotated Corpus while using the ID-only distribution method demonstrated by #Election2020.

- `listOfFiles.csv` links each source video or post to its public comment-ID file.
- `videos/` preserves the source layer of the SENSEI-inspired structure. No video, post, thumbnail, transcript, or direct link is redistributed; sources are identified by `platform` and `source_id` in `listOfFiles.csv` and the public comment files.
- `comments/` contains platform comment IDs and approved public metadata. It excludes comment text and record-level annotations.
- `comment_id` is the researcher-assigned corpus identifier and records the parent-reply structure.
- `platform_comment_id` is the platform-provided identifier used to retrieve an available comment. It may be blank when no platform identifier can be obtained.
- `annotated_sample/` will contain a separate small sample illustrating the emoji annotation method. It will not provide annotation coverage for the full comment-ID corpus or link sample records to platform comment IDs.
- `metadata/annotation_codes.csv` publishes the primary- and secondary-function definitions used by the annotation method.
- Secondary-function assignments, coder identifiers, pre-adjudication codes, and coding memos are excluded from both the main corpus and the annotated sample.

## Templates and index

- `comments/comment_template.csv` defines the columns for public comment-metadata files.
- `annotated_sample/annotated_sample_template.csv` defines the columns for the separate illustrative annotated sample.
- `listOfFiles.csv` is the source-level index connecting each `platform` and `source_id` to its public comment-ID file.
- `../account.csv` defines the separate list of public source accounts. It is not used to map accounts to individual sources or comments.

## File naming

Public comment-ID files use the two-letter election-site code, `election` followed by the four-digit election year, and the abbreviated platform code:

- `comments/{site_code}_election{year}_{platform_code}_comments.csv`

For example:

- `comments/jm_election2025_fb_comments.csv`

The platform codes are `fb` for Facebook and `yt` for YouTube.

Researchers must retrieve comments that remain available using the relevant platform interface or API, subject to the platform's access requirements and terms.

Do not place comment text, usernames, platform-provided author identifiers, profile information, direct links, exact timestamps, image URLs, or private coding fields in the public comment-ID files. Public `author_id` values must be researcher-assigned pseudonyms.

The separate annotated sample will be the only public data file that may contain comment text. Before inclusion, sample text must be de-identified and reviewed for quotation traceability and re-identification risk. The sample must not contain platform comment IDs, source IDs, account information, direct links, precise timestamps, coder identities, secondary-function assignments, or private coding memos.
