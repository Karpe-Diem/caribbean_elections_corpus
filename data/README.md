# Public corpus data

This directory adapts the SENSEI Annotated Corpus structure while using the ID-only distribution method demonstrated by #Election2020.

- `listOfFiles.csv` links each source video or post, comment-set file, and annotation-set file.
- `videos/` identifies the platform videos or posts to which comment sets belong.
- `comments/` contains approved public metadata and excludes comment text.
- `comment_id` is the researcher-assigned corpus identifier and records the parent-reply structure.
- `platform_comment_id` is the platform-provided identifier used to retrieve an available comment. It may be blank when no platform identifier can be obtained.
- `annotations/` contains final adjudicated primary-function assignments keyed to stable researcher-assigned comment IDs.
- `metadata/annotation_codes.csv` publishes the primary- and secondary-function definitions used by the coding scheme.
- Secondary-function assignments, coder identifiers, pre-adjudication codes, and coding memos are excluded from the public release.

Researchers must retrieve comments that remain available using the relevant platform interface or API, subject to the platform's access requirements and terms.

Do not place comment text, usernames, platform-provided author identifiers, profile information, direct links, exact timestamps, image URLs, or private coding fields in this directory. Public `author_id` values must be researcher-assigned pseudonyms.
