# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a content repository containing transcripts from Lenny's Podcast, organized for AI consumption and knowledge retrieval. It is not a traditional software codebase—there are no build, test, or lint commands.

## Structure

- `episodes/` - 270+ episode folders, each containing a `transcript.md` with YAML frontmatter and full transcript
- `frameworks/` - 24 product management framework guides synthesized from episodes
- `product-best-practices.md` - Consolidated reference guide from 264+ episodes

## Transcript Format

Each transcript has YAML frontmatter with: `guest`, `title`, `youtube_url`, `video_id`, `description`, `duration_seconds`, `duration`, `view_count`, `channel`

## Common Operations

```bash
# Search transcripts for a topic
grep -r "topic" episodes/

# List all episodes
ls episodes/

# Parse transcript metadata (Python)
import yaml
with open('episodes/guest-name/transcript.md') as f:
    content = f.read()
    parts = content.split('---')
    metadata = yaml.safe_load(parts[1])
```

## When Adding Content

- Episode folders are named after the guest (lowercase, hyphenated)
- Each folder contains a single `transcript.md` file
- Maintain consistent YAML frontmatter structure
- Framework guides go in `frameworks/` and should be added to `frameworks/README.md`
