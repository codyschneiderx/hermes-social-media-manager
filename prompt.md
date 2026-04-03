Hermes, create a new persistent skill called “Social_Mobile_Proxy_Farm”. Save it permanently so I can reuse and improve it forever.
Goal:
Fully automate the creation, warming, content generation, posting, engagement, and daily management for social sets.
Definition of one set: Each set = exactly 3 accounts (1 YouTube + 1 TikTok + 1 Instagram focused on Reels/Shorts-style content).
Starting plan:
We are beginning with just 1 social set for testing and learning. The skill must be designed from the start to scale cleanly and easily to 10+ sets later without any rework.
Core rules (never break these):

Every single action on every platform must look 100% like it’s coming from a real mobile phone on 4G/5G carrier data.
Use 1 dedicated static mobile/4G proxy per individual account (3 proxies for the first test set). Never reuse the same proxy across accounts or sets.
Every browser/Appium/Playwright session must spoof a full real Android or iOS mobile fingerprint (user-agent, canvas, WebGL, sensors, viewport, fonts, WebRTC, etc.).
Scaling structure:
Use your isolated Profiles / sub-agents so each social set runs completely separately with zero cross-contamination. Each sub-agent gets its own memory, proxy assignments, and session. This makes adding new sets later simple and safe.
Full workflow the skill must handle automatically:

Create brand-new accounts or log into existing ones using the assigned mobile proxy + fingerprint.
First-time warming: clear cache/data, set correct country/region, watch videos, follow/like/comment naturally in the niche.
Generate platform-specific viral content (YouTube Shorts, TikTok videos, IG Reels).
Post or schedule the content while keeping the exact same proxy + mobile fingerprint active for the whole session.
Daily management: check analytics, reply to comments, engage, grow followers.
Run everything safely with human-like delays and behavior.
Commands I will use (start small, scale later):

“Start 1 test social set (US targeted)”
“Post this idea to my test set”
“Warm all accounts in the test set for 2 hours”
“Add 3 more social sets”
“Scale to 10 total social sets”
“Check analytics for set #1”
“Replace proxy on TikTok account in set #1"
Self-improvement:
After every run, log results (views, engagement, any flags or bans), then automatically update and improve the skill so future runs (including when we scale to more sets) are cleaner, safer, and more effective.
First action right now:
Confirm with the exact message: “Skill Social_Mobile_Proxy_Farm has been created and is ready for 1 test social set (with easy scaling to 10+).”
Then tell me exactly what you need from me to launch the first 1 test set (proxy list format, how to connect proxies, target country, any API keys, VPS details, etc.).