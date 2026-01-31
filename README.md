# GBS

Github Branch Scanner - A powerful web-based tool to scan and manage default branches across GitHub repositories.

## Features

- Single repository scan
- Bulk repository scan (all repos from user/organization)
- View all branches with default branch highlighting
- Change default branch individually or in bulk
- Real-time progress tracking
- Token and anonymous authentication support

## Quick Start

1. Open `n1709.github.io/GBS` in your browser
2. Choose authentication mode (token recommended for full features)
3. Select scan mode (single repo or all repos)
4. Enter repository or username
5. Click "Start Investigation"

## Bulk Change Default Branch

1. Complete a scan with token authentication
2. Enter target branch name
3. Click "Change All Defaults"
4. Monitor progress

## GitHub Token Setup

1. Go to GitHub Settings > Developer settings > Personal access tokens
2. Generate new token with `repo` scope
3. Copy and paste in the tool

## Requirements

- Modern web browser
- GitHub token (optional for public repos, required for private and bulk changes)
- Internet connection

## Limitations

- Anonymous: 60 requests/hour
- With token: 5000 requests/hour
- Bulk change requires admin access to repositories
- Target branch must exist before changing

## Tech Stack

Pure HTML/CSS/JavaScript with GitHub REST API v3

## License

MIT
