# CSCI3100-Project Group 9
# CUSHMS — CUHK Second-hand Marketplace SaaS

Live demo: <HEROKU_URL>
GitHub repo: <REPO_URL>

## Overview
CUSHMS is a CUHK-focused second-hand marketplace for students to buy/sell items (textbooks, furniture, daily goods).
Key workflows: Listings + search/filtering + item status (Available → Reserved → Sold) + real-time chat/notifications.

## Demo Video

## Feature Ownership

Primary = main implementer. Secondary = support/reviewer + contributed commits/tests.

| Feature Name | Primary Developer | Secondary Developer | Notes |
| --- | --- | --- | --- |
| Project skeleton + repo setup |  |  | Rails 7 init, initial structure. |
| Deployment (Heroku) |  |  | Heroku config + deploy steps. |
| CI pipeline (GitHub Actions) |  |  | Run RSpec + Cucumber in CI. |
| User auth + roles |  |  | Auth + authorization boundaries. |
| CUHK email verification (@link.cuhk.edu.hk) |  |  | Domain restriction + verification flow. |
| Listings CRUD |  |  | Create/edit/delete listings + validations. |
| Image uploads |  |  | Active Storage (or equivalent). |
| Item status workflow |  |  | Available → Reserved → Sold. |
| Search & filtering (fuzzy search) |  |  | Keyword search + filters. |
| Community/college feature |  |  | College grouping/community space. |
| ActionCable chat/notifications |  |  | Real-time messaging + notifications. |
| RSpec + SimpleCov |  |  | Unit tests + coverage evidence. |
| Cucumber BDD scenarios |  |  | Acceptance tests for key user stories. |



## Tech Stack
- Ruby on Rails 7+
- Database: MySQL
- Testing: RSpec (unit) + Cucumber (BDD)
- CI: GitHub Actions
- Deployment: Heroku

## Features
### Core features
- Community/college space
- Item status management (Available → Reserved → Sold)

### Advanced features (N-1)
- Fuzzy search + filtering
- CUHK email verification (restricted to @link.cuhk.edu.hk)
- Listings CRUD + image upload
- Interactive Dashboard
- ActionCable real-time chat/notifications

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
