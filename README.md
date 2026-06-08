# CRAZYAIGC Content

Unified published content repository for CRAZYAIGC.com.

Obsidian Vault remains the editing and production source. This repository is the website-facing content source consumed through GitHub Raw by the main CRAZYAIGC.com site.

## Structure

```txt
academy/        AI Academy tutorials and structure
blog/           Blog posts, images, and blog index
daily/          Daily AI updates
cases/          Case studies
faq/            FAQ content
glossary/       Glossary entries
shared/assets/  Shared content assets
```

## Required indexes

- `academy/index.json`: flat list of academy article paths for sitemap and static params.
- `academy/structure.json`: nested AI Academy navigation tree.
- `blog/index.json`: blog listing metadata.
- `daily/index.json`: daily update listing metadata.

## Frontmatter standard

```yaml
---
title:
description:
date:
lastUpdated:
category:
tags:
author:
sourceType: academy | blog | daily | case | faq | glossary
geoSummary:
canonical:
---
```

## Website source mapping

- `academy/...` -> https://crazyaigc.com/academy/...
- `blog/...` -> https://crazyaigc.com/blog/...
- `daily/...` -> https://crazyaigc.com/daily/...

After content changes, trigger CRAZYAIGC.com revalidation with the configured webhook secret.
