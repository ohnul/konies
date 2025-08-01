# CLAUDE.md

**WARNING!**
THIS IS OLD! DON'T REFERENCE THIS DOCUMENT!

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains the documentation and planning materials for "구름골의 보물" (Treasure of Cloud Valley), a Korean children's adventure fantasy novel. The project is a collaborative novel writing effort between AI and human teams, targeting elementary to middle school readers (Harry Potter Book 1 reading level).

## Document Structure and Architecture

### High-Level Document Organization

The project follows a structured document hierarchy for collaborative novel writing:

- **README.md**: Work overview, themes, target audience, and project composition
- **characters-overview.md**: Detailed character profiles, relationships, and growth arcs
- **settings-overview.md**: World-building, locations, cultural and historical background
- **plot-structure.md**: Story structure definitions, act/chapter breakdown, and narrative flow

### Structural Unit System

The novel uses a hierarchical structure system:
- **Acts**: 4 main acts (with prologue and epilogue)
- **Chapters**: 2-3 chapters per act
- **Scenes**: 3-5 scenes per chapter

File naming convention: `[act]-[chapter]-[scene].md` (e.g., `01-02-03-scene.md`)

### Legacy Files
- **legacy/**: Contains earlier specifications and versions (spec-v1.md, spec-v2.md, v1.md)

## Document Writing Rules

### General Guidelines
- All documents written in markdown format
- Rules documents in English, story content in Korean
- UTF-8 encoding is critical for Korean text
- Third-person omniscient perspective, past tense with "-했다" endings

### File Encoding Requirements (CRITICAL)
**Always ensure UTF-8 encoding for Korean text files:**
1. Delete corrupted files first (using `rm` command)
2. Create new files with proper UTF-8 encoding
3. Never edit files with corrupted encoding
4. If Korean text appears garbled (e.g., "ì¤ì¹ ë° ì¤í"), immediately recreate the file

### Style Guidelines
- **Target audience**: Upper elementary to middle school students
- **Tone**: Soft, comfortable writing style with warmth and humor
- **Content balance**: 60% adventure/tension, 40% friendship/humor
- **Sentence structure**: Relatively short sentences with varied structure for rhythm
- **Prohibited content**: No cruel or violent descriptions suitable for children

### Character Consistency
- Each character must reflect their unique Aspects and personality
- Maintain consistent speech patterns throughout
- Use age-appropriate language and expressions

## Key Characters and Relationships

### Main Characters (Ages 13-16)
- **임수진 (13)**: "Perfect" student council president hiding a clumsy nature
- **박지훈 (14)**: Nature expert who "talks to the forest"
- **고민준 (13)**: Aspiring YouTuber obsessed with content creation
- **박지영 (16)**: Social activist with fiery passion (지훈's sister)
- **강태호 (16)**: Strategic thinker who calculates everything

### Character Dynamics
- **Comedy roles**: 민준, 지영 (overactive "boke"), 태호, 수진 (corrective "tsukkomi")
- **Key relationships**: 수진↔지훈 (childhood friends), 지영↔태호 (opposites who complement)

## Story Elements

### Setting
- **Location**: "구름골" (Cloud Valley), a traditional Korean mountain village
- **Time**: Modern era (2020s), spring to early summer
- **Crisis**: Village faces flooding due to dam construction
- **Fantasy elements**: Limited to 20% (dokkaebi legend, bronze mirror)

### Core Themes
- Friendship, courage, and victory
- Traditional vs. modern values
- Community preservation
- Natural harmony

### Cultural Integration
- Korean cultural elements (stone lanterns, dokkaebi, Silla artifacts)
- Traditional folklore woven into modern setting
- Age-appropriate presentation without excessive exposition

## Common Development Tasks

Since this is a writing project rather than a software project, there are no build, test, or lint commands. Instead, focus on:

### Content Creation and Editing
- Always read existing files before editing to understand context
- Maintain character consistency across all documents
- Follow the established structural unit system
- Ensure proper UTF-8 encoding for Korean text

### File Management
- Prefer editing existing files over creating new ones
- Follow the established naming conventions for structural documents
- Keep backup of files before major edits due to encoding sensitivity

## Important Constraints

- **File encoding**: Critical for Korean text - always use UTF-8
- **Content appropriateness**: Children's literature standards must be maintained
- **Character consistency**: Each character has defined Aspects that must be preserved
- **Structural integrity**: Follow the established act/chapter/scene hierarchy
- **Cultural sensitivity**: Accurate representation of Korean cultural elements

## Working with This Repository

When working on this project:
1. Always read the existing character and setting documents first
2. Maintain the established tone and style guidelines
3. Ensure Korean text files use proper UTF-8 encoding
4. Follow the structural unit system for any new narrative content
5. Keep content appropriate for the target age group (elementary to middle school)