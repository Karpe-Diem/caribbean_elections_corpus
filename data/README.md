# Public corpus data

The public corpus is distributed as a post-level reference manifest. Comment-level spreadsheets and annotations used in the research are retained privately and are not included in repository releases. If private working copies are kept inside the local checkout, they must be stored under `data/private/`, which is excluded by `.gitignore`.

## Post-level reference manifest

`post_reference_manifest.csv` contains one row for each source post or video and uses these fields:

- `post_id`
- `platform`
- `country`
- `event_type`
- `election_date`
- `publisher`
- `publication_date`
- `public_url`

The manifest identifies public source material; it does not contain comments or provide a mapping to private comment-level records.

## Other public files

- `annotated_sample/annotated_sample_template.csv` defines the columns for the separate illustrative annotated sample.
- `metadata/annotation_codes.csv` publishes the primary- and secondary-function definitions used by the annotation method.
- `../account.csv` lists public source accounts. It does not list commenter accounts.

Secondary-function assignments, coder identifiers, pre-adjudication codes, coding memos, comment-level identifiers, engagement metrics, and comment spreadsheets remain private.

The separate annotated sample will be the only public data file that may contain comment text. Before inclusion, sample text must be de-identified and reviewed for quotation traceability and re-identification risk. The sample must not contain platform comment IDs, post IDs, account information, direct links, precise timestamps, coder identities, secondary-function assignments, or private coding memos.
