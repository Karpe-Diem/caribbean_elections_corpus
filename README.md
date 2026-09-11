# Caribbean Elections Corpus

The Caribbean Elections Corpus (CEC) is a growing social-media comment-ID corpus relating to Caribbean general elections.

## Scope

The corpus covers general elections held from 2025 onward in Caribbean jurisdictions where:

- English functions as an official language.
- The population elects its legislature or government.
- The electorate or elected legislature determines the local head of government.

The scope includes sovereign states and self-governing Caribbean territories that meet these criteria.

## Initial collection period

1 January 2025–31 December 2026.

The corpus remains under development and may be extended through later versioned releases.

## Platforms

Data are collected from election-related content published on:

- YouTube
- Facebook

Source accounts include news organizations, political parties, politicians, and other relevant public accounts.

## Research purpose

The corpus supports research into online political discourse and civic participation in the Caribbean. Potential applications include the study of political identity and behaviour, voter engagement, misinformation, information manipulation, conspiracy narratives, and distortions of online political discourse.

## Planned data release

The public corpus will contain platform-provided comment IDs, researcher-assigned identifiers, source IDs, publication dates at reduced precision, engagement metrics, and contextual election metadata. It will not redistribute comment text, usernames, profile information, direct links, precise timestamps, or record-level annotations.

A separate small annotated sample will be included in the repository to illustrate the emoji annotation method used in the associated research. The sample is not annotation coverage for the full corpus.

Researchers will be expected to retrieve content that remains publicly available through the relevant platform interface or API, subject to the platform's access requirements and terms.

## Documentation

- [`account.csv`](account.csv): public source accounts that published the posts or videos from which comments were collected. It records the platform, researcher-assigned account identifier, public account name and type, election site, collection start and end dates, and optional notes. It does not list commenter accounts or map source accounts to individual comment records.
- [Public emoji annotation codebook](docs/CEC_codebook_v1.18_public.docx): the coding procedure, category system, operational definitions, decision rules, and reliability protocol used in the research and illustrated by the annotated sample.
- [Machine-readable annotation code list](data/metadata/annotation_codes.csv): the primary- and secondary-function codes and definitions used by the annotation method.
- [Annotated sample template](data/annotated_sample/annotated_sample_template.csv): the fields used for the separate illustrative annotated sample.

## Status

This repository and corpus are under development. No public dataset release is currently available.
