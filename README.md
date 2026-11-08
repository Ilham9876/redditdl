# redditdl

Reddit Downloader (redditdl)

A lightweight, personal, non-commercial Reddit comment and reply downloader built with Python.

Overview

Reddit Downloader ("redditdl") is a planned command-line application designed to retrieve publicly accessible comments and replies from specific Reddit posts selected manually by the user.

The project aims to provide a simple way to save selected Reddit discussions locally for personal offline reading and reference.

This project is intended for individual use and is not affiliated with Reddit, Inc.

Project Goals

- Retrieve comments and replies from manually selected public Reddit posts.
- Preserve comment IDs, parent IDs, post IDs, timestamps, and reply relationships.
- Export retrieved data into CSV and JSONL formats.
- Prevent duplicate records using Reddit comment IDs.
- Support Unicode text and multiline comments.
- Run locally on Android through Ubuntu in Termux.

Planned Technology

- Language: Python
- Reddit API library: PRAW
- Environment: Ubuntu on Termux (Android)
- Output formats: CSV and JSONL

Intended Workflow

1. The user manually provides a public Reddit post URL.
2. The application requests the relevant data through Reddit's official Data API, subject to authorization.
3. Comments and replies are processed locally.
4. Results are exported into CSV or JSONL files.

Data Usage and Privacy

The project is intended strictly for personal, non-commercial use.

The application is not intended to:

- Perform automated subreddit-wide crawling.
- Collect Reddit data in bulk.
- Redistribute, sell, or publicly host retrieved content.
- Perform automated posting, voting, or messaging.
- Build user profiles or track individual Reddit users.
- Use Reddit content for AI or machine learning model training.

The project will respect Reddit's applicable API policies, rate limits, privacy requirements, and content deletion obligations.

Why a Standalone Application?

The intended application is a locally operated Python command-line utility.

Its primary requirements include local execution, direct access to the device's file system, and exporting discussion data into local files.

These requirements differ from the project's intended use of Reddit's hosted Devvit application environment.

Development Status

Status: Planning and API access request stage.

The project is not yet connected to Reddit's Data API.

Official Reddit Data API authorization is being requested before implementing programmatic data retrieval.

PRAW integration and the remaining application functionality are planned for future development, subject to approval.

API Access

This project intends to use Reddit's official Data API through PRAW.

No API credentials, client secrets, access tokens, passwords, or private account information are stored in this repository.

Contact

This is an independently developed personal project.

For questions regarding this project, please use the GitHub repository's Issues section.