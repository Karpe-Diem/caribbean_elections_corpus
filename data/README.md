# Public corpus data

This directory adapts the SENSEI Annotated Corpus structure while using the ID-only distribution method demonstrated by #Election2020.

- `listOfFiles.csv` links each source video, comment-set file, and annotation-set file.
- `videos/` identifies the platform videos or posts to which comment sets belong.
- `comments/` contains researcher-assigned - `comment_id` is the researcher-assigned corpus identifier and records the parent–reply structure.
- `platform_comment_id` is the platform-provided identifier used to retrieve an available comment. It may be blank when no platform identifier can be obtained.
- `annotations/` contains researcher-produced annotations keyed to platform-provided comment IDs.

Researchers must retrieve comments that remain available using the relevant platform interface or API, subject to the platform's access requirements and terms.

Do not place comment text, usernames, author identifiers, profile information, direct links, or precise timestamps in this directory.
