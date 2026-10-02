# Public corpus data

The initial public release contains the public metadata and templates described below. Comment-level spreadsheets and annotations used in the research are retained privately and are not included in repository releases. If private working copies are kept inside the local checkout, they must be stored under `data/private/`, which is excluded by `.gitignore`.

## Planned post-level reference workbooks

Country-specific post-level reference workbooks are excluded from the initial release. They will be added in a subsequent version after completion and review, using these fields:

- `post_id`
- `platform`
- `country`
- `event_type`
- `election_date`
- `publisher_id`
- `publisher`
- `first_published`
- `post_url`

The workbooks will identify public source material; they will not contain comments or provide a mapping to private comment-level records.

## Other public files

- `annotated_sample/annotated_sample_template.csv` defines the columns for the separate illustrative annotated sample.
- `metadata/annotation_codes.csv` publishes the primary- and secondary-function definitions used by the annotation method.
- `../account.csv` lists public source accounts. It does not list commenter accounts.

Secondary-function assignments, coder identifiers, pre-adjudication codes, coding memos, comment-level identifiers, engagement metrics, and comment spreadsheets remain private.

The separate annotated sample will be the only public data file that may contain comment text. Before inclusion, sample text must be de-identified and reviewed for quotation traceability and re-identification risk. The sample must not contain platform comment IDs, post IDs, account information, direct links, precise timestamps, coder identities, secondary-function assignments, or private coding memos.
