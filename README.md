# Hermes Social Media Manager

Automated multi-platform social media management system for running coordinated content sets across YouTube, TikTok, and Instagram.

## What It Does

- Manages **social sets** — each set = 1 YouTube + 1 TikTok + 1 Instagram account focused on Shorts/Reels-style content
- Handles account creation, warming, content generation, posting, engagement, and daily management
- Each account gets a dedicated mobile proxy and full mobile fingerprint for session consistency
- Designed to start with 1 test set and scale cleanly to 10+

## Architecture

- Each social set runs in an isolated profile/sub-agent with its own memory, proxy assignments, and session
- Zero cross-contamination between sets
- Self-improving: logs results after every run and updates strategy automatically

## Commands

| Command | Description |
|---------|-------------|
| `Start 1 test social set (US targeted)` | Launch a new test set |
| `Post this idea to my test set` | Push content to all accounts in a set |
| `Warm all accounts in the test set for 2 hours` | Run warming routine |
| `Add 3 more social sets` | Scale up |
| `Check analytics for set #1` | Review performance |
| `Replace proxy on TikTok account in set #1` | Swap a proxy |

## Getting Started

See [prompt.md](prompt.md) for the full system prompt and configuration details.
