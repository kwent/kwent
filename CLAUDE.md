# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

This is a GitHub profile README repository (github.com/kwent/kwent). The readme.md file displays on the GitHub profile page.

## Structure

- `readme.md` - Profile content displayed on GitHub (stats badges, social links)
- `header.svg` - Animated SVG banner using CSS animations inside `<foreignObject>` (renders in `<img>` tags)
- `explanation.md` - Documents the SVG-in-img trick

## Editing Guidelines

- Use tabs for indentation (per .editorconfig)
- Line endings are LF
- The SVG uses XHTML inside foreignObject - must be valid XML
- Stats widgets use external services (shields.io, github-readme-streak-stats) - these can have availability issues
