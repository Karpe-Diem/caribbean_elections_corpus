# Caribbean Elections Corpus

The Caribbean Elections Corpus (CEC) is a growing post-level reference corpus documenting public social-media posts relating to Caribbean general elections. Comment-level research files are retained privately and are not distributed through this repository.

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

The public corpus will contain a post-level reference manifest with the post identifier, platform, country, event type, election date, publisher, publication date, and canonical public URL for each included source post or video.

Comment-level spreadsheets, comment text, commenter information, platform comment identifiers, engagement metrics, and record-level annotations are retained privately and are not distributed through this repository.

A separate small annotated sample will be included in the repository to illustrate the emoji annotation method used in the associated research. The sample is not annotation coverage for the full corpus.

Researchers may use the manifest to locate source posts that remain publicly available, subject to the platform's access requirements and terms. The manifest does not provide access to the private comment-level research data.

## Documentation

- [`account.csv`](account.csv): public source accounts that published the posts or videos from which comments were collected. It records the platform, researcher-assigned account identifier, public account name and type, collection start and end dates, and optional notes. It does not list commenter accounts or map source accounts to individual comment records.
- [Post-level reference manifest](data/post_reference_manifest.csv): public references for the source posts and videos included in the research.
- [Public emoji annotation codebook](docs/CEC_codebook_v1.19_public.docx): the coding procedure, category system, operational definitions, decision rules, and reliability protocol used in the research and illustrated by the annotated sample.
- [Machine-readable annotation code list](data/metadata/annotation_codes.csv): the primary- and secondary-function codes and definitions used by the annotation method.
- [Annotated sample template](data/annotated_sample/annotated_sample_template.csv): the fields used for the separate illustrative annotated sample.

## Status

This repository and corpus are under development. No public dataset release is currently available.
