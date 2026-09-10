# Corpus Data Dictionary

This document defines the columns used in the Caribbean Elections Corpus.

## Private Master File

The private master file contains the original research data. It may contain identifiable information and is not included in the publicly released corpus.

### Master-file columns

```text
platform
election_site
event_type
election_date
source_id
author_id
comment_id
platform_comment_id
comment
first_published
published
likes_count
reply_count
live_video_timestamp
image_url
metrics_last_observed
```

### Public comment-file columns

```text
platform
election_site
event_type
election_date
source_id
author_id
comment_id
platform_comment_id
published
likes_count
reply_count
metrics_last_observed
```

The public file excludes comment text, exact publication timestamps, image URLs, and platform-provided author identifiers. `author_id` contains a researcher-assigned pseudonym. `published` uses reduced date precision.

