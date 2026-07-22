# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is Daniel Malungu's GitHub profile repository (`DKMalungu/DKMalungu`) — the special repo whose `README.md` GitHub renders on the user's profile page (`github.com/DKMalungu`). The entire content of this repo is `README.md`. There is no application code, no build system, no dependencies, and no tests.

## Working in this repo

- The only file that matters is `README.md`. Edits here directly change what's displayed on the GitHub profile page.
- The README uses `shields.io` badges (`img.shields.io/badge/...`) for tech stack icons and a `komarev.com/ghpvc` badge for the profile view counter — when adding a new skill/tool, follow the existing badge format (label, version/status text, color hex, logo slug) rather than switching styles.
- Content is organized into sections (About, Technical Expertise, Notable Projects, Professional Experience, Currently Exploring, Let's Collaborate, Get in Touch) — keep new content within these existing sections rather than introducing parallel ones.
- There is nothing to build, lint, or test. Verify changes by checking that the Markdown renders correctly (e.g. via GitHub's preview or a local Markdown viewer) rather than running any command.
