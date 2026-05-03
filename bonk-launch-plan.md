# Bonk! Launch Timeline & Go-To-Market Plan

## Context
- **Product**: Bonk! — "The local-first DJ library workstation for cleaning, analyzing, and planning sets."
- **Repo**: github.com/interfluve-wav/bonk-new-exp
- **Landing**: bonkmusic.qzz.io
- **Goal**: Domain authority + hiring signal for music tech + AI work
- **Budget**: $0 (no paid acquisition)
- **Strategy**: Few deep posts (10-15), not volume

---

## 1. Pre-Launch Checklist (2 Weeks Before Launch)

### Landing Page Finalization
- [ ] Final copy review — headline, subheadline, 3-feature sections
- [ ] Screenshot/GIF hero section deployed
- [ ] Download buttons: macOS, Windows, Linux (verify links work)
- [ ] "Coming Soon" replaced with "Available Now" / release date
- [ ] SEO meta tags, OG images set for social sharing
- [ ] Privacy policy / terms page linked in footer

### Discord Server Setup
- [ ] Create Bonk! Community Discord server
- [ ] Channels: #announcements, #general, #bugs, #features, #showcase
- [ ] Write bot welcome message with install links
- [ ] Set up roles: Admin, Contributor, User
- [ ] Prepare invite link for inclusion in press kit

### Demo Video / GIF Walkthrough
- [ ] Record 60-90 sec screen demo showing:
  - Drag-drop track import
  - Metadata auto-detection (BPM, key)
  - Tag cleanup / normalization
  - Set planning / playlist export
- [ ] Export as GIF (loopable, <10MB) for Reddit/Discord
- [ ] Export full MP4 for YouTube (1080p)
- [ ] Host GIF on Imgur or similar CDN

### Press Kit
- [ ] Logo pack: SVG, PNG (various sizes), dark/light variants
- [ ] 5-10 screenshots: main UI, features, before/after metadata
- [ ] 1-page product brief (What, Why, Who)
- [ ] FAQ document (10-15 common questions)
- [ ] Short + long descriptions for app stores / listings
- [ ] Release date + version number

### Install Flow Testing
- [ ] Test on macOS (Apple Silicon + Intel): download → install → first-run
- [ ] Test on Windows 10/11: download → install → first-run
- [ ] Test on Ubuntu/Debian Linux: .deb or AppImage
- [ ] Verify file associations (.mp3, .wav, .flac) work
- [ ] Test uninstall on all platforms

### Release Notes Draft
- [ ] Version: v1.0
- [ ] New features list
- [ ] Known limitations / roadmap hints
- [ ] Upgrade instructions (if applicable)
- [ ] Credits / acknowledgments

### Website Analytics Setup
- [ ] Google Analytics 4 or Plausible (privacy-friendly) installed
- [ ] Conversion events: download button clicks, GitHub star clicks
- [ ] UTM parameters prepared for each channel
- [ ] Dashboard shared with core team

### GitHub Releases Page
- [ ] Create annotated tag v1.0.0
- [ ] Write release body with changelog
- [ ] Attach executables/dmg/deb for all platforms
- [ ] Pin release as "Latest"

---

## 2. Launch Week Plan (Day by Day)

### Day 0 — Soft Launch to Power Users
**Goal**: Validate install flow, catch edge-case bugs, build initial word-of-mouth

- Send direct messages to 10-15 DJs you know personally
- Share in any existing DJ/producer communities you belong to
- Post in one friendly Discord server (not cold outreach yet)
- Monitor install counts and any error reports for 24h
- Fix any critical blockers before Day 1

### Day 1 — Product Hunt Submission
**Goal**: Get on PH homepage, drive first wave of external traffic

- Submit at 12:01 AM PST (beats most competitors for "today")
- Choose "Mack" or "Software" category
- Screenshot: main UI hero shot
- Description: 2-3 sentences, emphasize local-first + DJ workflow
- Promo video (optional but helps) — embed YouTube demo
- Ask 5-10 friends to upvote within first 2 hours
- Monitor PH comments, reply within 1 hour

### Day 2 — Reddit Posts
**Goal**: Drive discussion, get honest feedback, plant seeds in DJ communities

**r/DJs** (morning, ~8AM EST)
- Title: "I built a local-first DJ library tool — no cloud, no account, just your music"
- Body: 3 paragraphs — what it does, why you built it, what problem it solves
- Include GIF embed or Imgur link
- Engage with comments for 2+ hours

**r/Beatmatch** (afternoon, ~1PM EST)
- Similar structure, shorter (this community prefers brevity)
- Focus on BPM/key detection + set planning features

**r/DJTechTools** (evening, ~6PM EST)
- More technical crowd — emphasize the tech stack if interesting
- Ask about integrations they wish existed

**Rules**: No spam, no direct "download now" links in title, follow each sub's self-promotion rules (usually 10% rule)

### Day 3 — Discord Outreach
**Goal**: Introduce to established DJ communities

**Target servers** (join these 1-2 weeks before to establish presence):
- DJ City Hub
- Cross DJ community
-rektypo- DJ Production (largest ones — check names closer to launch)
- Bedroom DJ producers
- EDM production servers

**How to introduce**:
1. Don't just drop a link — say hello first
2. Mention you're a student building a tool for your own workflow
3. Ask if anyone would be interested in testing / feedback
4. Share only after positive reception

**Timing**: Weekdays 6-9 PM local time for each server's audience

### Day 4 — Twitter/X Thread + YouTube Demo

**Twitter/X Thread** (morning, ~9AM EST)
- Tweet 1: "I spent [X months] building a local-first DJ library tool. No cloud, no account, just your music. Here's the story and a demo:"
- Tweet 2-6: Thread showing the problem → solution → features → demo GIF → call to action
- Hashtags: #DJ #DJing #musicproduction #musictech #AIndustry #buildinpublic
- Engage with replies for 2+ hours

**YouTube Demo** (afternoon)
- Title: "Bonk! — DJ Library Workstation Demo"
- Description: Links to download, GitHub, Discord, timestamp chapters
- Tags: DJ software, music library, metadata editor, DJ tools
- Thumbnail: App UI + title text
- Post link in Twitter thread as Tweet 7

### Day 5-7 — Monitor, Iterate, Engage

- Monitor GitHub issues for bug reports
- Respond to all Reddit/Dicord/PH comments
- Triage feedback into: Bugs / Nice-to-haves / Feature requests
- Push v1.0.1 if critical bugs found
- Post "what we learned" update on Twitter (shows responsiveness)

---

## 3. Post-Launch (Weeks 2-8)

### Week 2: Community Engagement
- Daily: Check Reddit for mentions, reply to any threads about DJ tools
- Daily: Monitor Discord, welcome new members
- Weekly: Post a "tip" or "use case" in Discord
- Identify 3-5 power users who give great feedback — DM them directly

### Week 3-4: Bug Fix Sprint
- Triage all GitHub issues by priority
- Push v1.1 with top 5 most-upvoted issues fixed
- Announce v1.1 in Discord + Reddit thread update
- Collect testimonials from users who found it useful

### Week 5-6: Content Marketing
- Write 1 deep-dive blog post: "How DJ metadata actually works and why it matters"
- OR: Tutorial video showing advanced workflow
- Post to: r/DJs, r/audioengineering, Hacker News "Show"
- These are the "10-15 deep posts" — quality over quantity

### Week 7-8: v1.2 Feature Announcement
- Announce 2-3 highly-requested features
- New demo video showing what's new
- Post everywhere: Discord, Reddit, Twitter, GitHub
- Consider: r/software if relevant

---

## 4. Channel-Specific Tactics

### Reddit
**How to post without getting removed**:
1. Read each sub's rules (sidebar) — r/DJs allows self-promo, r/DJTechTools has a 10% rule
2. Never post and run — stay to answer questions for hours
3. Don't use short "check out my app" titles — be specific and interesting
4. Include something of value in the post itself (not just a link)
5. If the sub requires mod approval, message mods a day before

**Posting windows**: Weekdays 6-10AM and 6-10PM local time for each sub's audience

### Discord
**Which servers to join**:
- Search "DJ production", "DJing", "bedroom DJ", "electronic music production"
- Look for servers with 500+ members and active chat
- Join 1-2 weeks early, participate before promoting

**How to introduce**:
- Don't say "I made an app" in your first message
- Say: "Hey everyone — I'm a student working on a DJ library tool, curious if this would be useful for anyone here?"
- Share only after establishing rapport
- Offer to help others first

### Twitter/X
**Thread structure**:
1. Hook (1 tweet) — surprising claim or relatable pain point
2. Context (1-2 tweets) — what it is, why you built it
3. Demo (1-2 tweets) — GIF embedded, short video clip
4. Features (1-2 tweets) — 3 bullet points max
5. CTA (1 tweet) — "Try it here: [link]" + ask for feedback

**Hashtag strategy**:
- Primary: #DJ #DJing #musicproduction
- Secondary: #musictech #AIndustry #buildinpublic #indiedev
- Niche: #DJKeepGrowing #Beatmatch (sub-community specific)

**Timing**: Tuesday-Thursday, 8-10AM and 5-7PM EST perform best for tech/music

### YouTube
**Demo video structure** (target: 2-4 min):
- 0:00-0:15 — Hook: "Your DJ library is a mess. Here's how I fixed it."
- 0:15-0:45 — Problem: Show messy metadata (before)
- 0:45-2:00 — Solution: Walk through the app features
- 2:00-2:30 — Demo: Import track, auto-detect BPM/key, clean tags, export set
- 2:30-3:00 — CTA: Download link, Discord invite, GitHub star

**SEO**: Title + description include "DJ library manager", "metadata editor", "BPM detection"

### Hacker News
**If/when to post**:
- Post if the tech is genuinely interesting (local-first, AI detection, interesting stack)
- Submit on Tuesday or Wednesday, 6-9 AM PST
- Title: "Show HN: Bonk! — local-first DJ library workstation"
- Body: 2-3 paragraphs, no marketing language, focus on the technical interesting parts
- Do NOT post on PH day or Reddit day — spread out

---

## 5. Metrics to Track

### Downloads
- Total by platform: macOS / Windows / Linux
- Daily and cumulative
- Use GitHub release download counts as baseline

### Website Traffic
- Sessions, pageviews (GA4)
- Top landing pages (should be / or /download)
- Bounce rate, avg session duration
- UTM source breakdown: Reddit, PH, Twitter, direct

### Social Proof
- Reddit: post karma, comment count, crossposts
- Discord: member count, daily active messages
- Twitter: impressions, quote-tweets, replies, follower growth
- GitHub: stars (target: 50 by end of week 1, 200 by week 4)

### Community
- Discord: new members per day, message count
- GitHub: new issues, feature request upvotes
- PH: votes, comments, "backed" count

### Feedback Themes
- Categorize feedback: UX issues / missing features / bugs / praise
- Track weekly: which category is most common
- Use to drive v1.1 and v1.2 roadmap

---

## 6. Risks and Mitigations

### Risk: App gets flagged as malware
**Mitigation**: Sign macOS apps (Apple Developer ID), sign Windows exe (Microsoft), provide checksum verification on GitHub

### Risk: Reddit posts get removed for spam
**Mitigation**: Follow 10% rule, participate genuinely for 1-2 weeks before posting, never post and run

### Risk: PH launch flops (no traction)
**Mitigation**: Have 10+ friends upvote within first 2 hours, time for 12:01 AM PST, write compelling tagline

### Risk: Discord server goes ghost town
**Mitigation**: Seed with 5-10 active members before launch, post weekly "discussion" prompts, DM new members welcome

### Risk: Critical bug on launch day
**Mitigation**: Soft launch 2 days earlier to catch blockers, have v1.0.1 patch ready to go

### Risk: Getting overwhelmed by support requests
**Mitigation**: GitHub issues template for bug reports, FAQ in Discord, don't promise 24h response

### Risk: Feature requests spiral the roadmap
**Mitigation**: v1.x is stability-focused, log all requests but don't commit to timelines publicly

### Risk: Zero traction on social
**Mitigation**: This is a F1 student project — 200 GitHub stars and 50 Discord members is a win. Set realistic expectations. Quality of 3 potential employers reached = success.

---

## Launch Schedule Summary

| Day | Channel | Action |
|-----|---------|--------|
| -14 to -1 | Internal | Pre-launch checklist |
| 0 | Personal network | Soft launch, power users |
| 1 | Product Hunt | Submit + monitor |
| 2 | Reddit | r/DJs, r/Beatmatch, r/DJTechTools |
| 3 | Discord | Community outreach |
| 4 | Twitter/X + YouTube | Thread + demo video |
| 5-7 | All | Monitor, iterate |
| Weeks 2-4 | All | Community + bug fixes |
| Weeks 5-8 | Content | Deep posts + v1.2 |
