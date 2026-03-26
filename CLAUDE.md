# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a GitHub profile repository (`mzelzoghbi/mzelzoghbi`). Its primary content is `README.md`, which renders as Zak's public GitHub profile page.

## Automation

A GitHub Actions workflow (`.github/workflows/blog-post-workflow.yml`) runs hourly to auto-update the `## 📝 Blogs posts` section in `README.md` by fetching the latest 5 posts from `https://medium.com/feed/@eng.zak`. Do not manually edit that section — changes will be overwritten.

## README Structure

The README uses HTML + Markdown and is organized into these sections:
1. Header (name, title, profile view counter)
2. Focus areas, Current work, Open to, Reach me
3. Philosophy quote
4. Featured projects
5. Blog posts (auto-managed by GitHub Actions)
6. Buy Me a Coffee support button

When editing, preserve the existing HTML alignment patterns (`<p align="center">`, `<h1 align="center">`) for consistent rendering on GitHub.
