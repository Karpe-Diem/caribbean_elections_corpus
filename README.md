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

## Initial release

The initial public release contains the repository documentation, public source-account registry, metadata definitions, annotation code list, and annotated-sample template.

Country-specific post-level reference workbooks will be added in a subsequent version after their records have been completed and reviewed. Those workbooks will contain the post identifier, platform, country, event type, election date, publisher identifier, publisher, first-publication date or time, and canonical post URL for each included source post or video.

The public emoji-annotation codebook will also be considered for a subsequent release after further review.

Comment-level spreadsheets, comment text, commenter information, platform comment identifiers, engagement metrics, and record-level annotations are retained privately and are not distributed through this repository.

A separate small annotated sample will be included in the repository to illustrate the emoji annotation method used in the associated research. The sample is not annotation coverage for the full corpus.

Once released, researchers may use the post-reference workbooks to locate source posts that remain publicly available, subject to the platform's access requirements and terms. The workbooks will not provide access to the private comment-level research data.

## Documentation

- [`account.csv`](account.csv): public source accounts that published the posts or videos from which comments were collected. It records the platform, researcher-assigned account identifier, public account name and type, collection start and end dates, and optional notes. It does not list commenter accounts or map source accounts to individual comment records.
- [Machine-readable annotation code list](data/metadata/annotation_codes.csv): the primary- and secondary-function codes and definitions used by the annotation method.
- [Annotated sample template](data/annotated_sample/annotated_sample_template.csv): the fields used for the separate illustrative annotated sample.

## Licence and third-party material

The project's original documentation, metadata structures, annotation materials, and templates are available under the [Creative Commons Attribution 4.0 International Licence](LICENSE.md). The licence does not apply to third-party account names, trademarks, platform identifiers, or social-media content. Platform content remains subject to applicable law and the relevant platform's terms and policies.

## Status

This repository and corpus are under development. No public dataset release is currently available.
