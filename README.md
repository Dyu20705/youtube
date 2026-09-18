# YouTube Projects

A collection of my tools for YouTube and YouTube Music.

This repository is the central index for these projects. Each project has its own repository with source code and detailed documentation, and this collection will grow as new projects are added.

## Projects

### Media Downloader

One-Click Media Downloader is a desktop application for downloading media from URLs: paste a link, select a preset and format, choose a destination, and download. Built with Tauri, Rust, and React, it supports video and audio presets including MP4, MP3, and FLAC. It also manages and verifies the required media tools, including yt-dlp, FFmpeg, FFprobe, and MediaInfo.

[View repository →](https://github.com/Dyu20705/media-downloader)

### YouTube Live Translate

A local-first subtitle translation system for YouTube videos and live streams, delivered through a Chrome extension connected to an on-device runtime. It captures tab audio and runs speech recognition and machine translation locally, focusing on Japanese-to-English subtitles with low perceived latency. The core translation pipeline requires no commercial cloud APIs.

[View repository →](https://github.com/Dyu20705/youtube-live-translate)

### YouTube Music Library Manager

YouTube Music (YTM) Library Manager provides local-first library management and advanced querying backed by SQLite. It supports full-text search, field and range filters, and custom playlist folders, with offline querying of local data. Library changes use inspectable change plans and require approval before execution, with reconciliation and rollback mechanisms to help manage changes safely.

[View repository →](https://github.com/Dyu20705/YTM-Library-Manager)

## About This Repository

`youtube` is a lightweight project directory, not a standalone application. Visit each project's README for installation, usage, architecture, development instructions, and project-specific documentation.

New YouTube and YouTube Music projects will be listed here as they are added.
