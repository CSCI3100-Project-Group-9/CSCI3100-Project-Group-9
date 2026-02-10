# CSCI3100-Project Group 9
# CUSHMS — CUHK Second-hand Marketplace SaaS

Live demo: <HEROKU_URL>
GitHub repo: <REPO_URL>

## Overview
CUSHMS is a CUHK-focused second-hand marketplace for students to buy/sell items (textbooks, furniture, daily goods).
Key workflows: Listings + search/filtering + item status (Available → Reserved → Sold) + real-time chat/notifications.

## Tech Stack
- Ruby on Rails 7+
- Database: MySQL
- Testing: RSpec (unit) + Cucumber (BDD)
- CI: GitHub Actions
- Deployment: Heroku

## Features
### Core features
- CUHK email verification (restricted to @link.cuhk.edu.hk)
- Listings CRUD + image upload
- Item status management (Available → Reserved → Sold)

### Advanced features (N-1)
- Fuzzy search + filtering
- Community/college space
- ActionCable real-time chat/notifications

## Feature Ownership
| Feature | Primary Developer | Secondary Developer | Notes |
|---|---|---|---|
| Auth + Email verification | <Name> | <Name> | |
| Listings CRUD + images | <Name> | <Name> | |
| Search (fuzzy) + filters | <Name> | <Name> | |
| Status workflow | <Name> | <Name> | |
| ActionCable chat/notifications | <Name> | <Name> | |
| Community/college feature | <Name> | <Name> | |

## Local Setup
### Prerequisites
- Ruby: <version>
- Bundler
- MySQL

### Installation
```bash
git clone <REPO_URL>
cd <PROJECT_FOLDER>
bundle install
