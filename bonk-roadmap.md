# Bonk! Roadmap

**DJ Metadata Editor — Electron + React + TypeScript**

---

## Current Version: v1.1.0

### What's Shipped

| Feature | Status |
|---------|--------|
| AutoTag Multi-Provider | ✅ Released |
| Beatport API Integration | ✅ Released |
| Audio Features Wizard | ✅ Released |
| Key Format Conversion | ✅ Released |
| Rekordbox DB Import/Export | ✅ Working |
| Quick Tag | ✅ Working |
| Graph Playlist | ✅ Working |
| Chapter Builder | ✅ Working |
| Analytics | ✅ Working |
| Preflight Center | ✅ Working |

### In Progress

| Feature | Status |
|---------|--------|
| VibeNet Audio Features | 🔄 In Progress |
| Benchmark Center | 🔄 In Progress |
| ZIP Playlist Bundles | 🔄 In Progress |

### Not Yet Shipped

| Feature | Status |
|---------|--------|
| CSV Analytics Export | 📋 Planned |
| Auto-Update Pipeline | 📋 Tech Debt |
| Signed Build CI Automation | 📋 Tech Debt |
| Snapshot History UI | 📋 Planned |

---

## 6-Month Roadmap

### Near Term (0-2 months) — v1.1.x

**Focus:** Stabilize and ship in-progress features

| Priority | Feature | Rationale |
|----------|---------|-----------|
| Critical | VibeNet Audio Features | Completes ML-powered audio analysis pipeline |
| Critical | Benchmark Center | Enables performance validation at scale |
| High | ZIP Playlist Bundles | Key export workflow for DJs |
| Tech Debt | Auto-Update Pipeline | Required for seamless updates |
| Tech Debt | Signed Build CI | Required for macOS distribution |

**Milestone:** v1.1.1 with VibeNet + Benchmark + ZIP Bundles

---

### Mid Term (3-4 months) — v1.2 - v1.5

**Focus:** High-priority features that define Bonk! as a professional DJ tool

| Priority | Feature | Rationale |
|----------|---------|-----------|
| Critical | Cue Point Management | Core workflow for competitive DJs; visual editor is #1 user request |
| Critical | Cross-App Library Mirror | Serato/Engine DJ/Traktor import parity; reduces lock-in, increases adoption |
| Critical | ANLZ File Backup/Restore | Protects user investment; critical for professional users |
| High | Electron Update | Security patches, performance, modern APIs |
| High | macOS Code Signing | Gatekeeper compliance; required for App Store |
| Medium | Beatgrid Management | Completes rekordbox parity; enables grid editing |
| Medium | Play History Tracking | Analytics foundation; user engagement data |

**Milestone:** v1.2 — Cue Point Editor
**Milestone:** v1.3 — Library Mirror (Serato/Engine DJ/Traktor)
**Milestone:** v1.5 — Beatgrid + Play History

---

### Long Term (5-6 months) — v1.6 - v2.0

**Focus:** Intelligent features and ecosystem expansion

| Priority | Feature | Rationale |
|----------|---------|-----------|
| High | Set Intelligence Engine | Ranked next-track suggestions; differentiates Bonk! from basic editors |
| Medium | Waveform Visualization | Visual feedback for cue placement and editing |
| Medium | Related Tracks | Discovery feature; increases library value |
| Medium | Smart Playlist Evaluation | Automation; reduces manual playlist maintenance |
| Low | Hot Cue Banklists | Power user feature; professional workflow |
| Low | Sampler Management | One-shot integration; creative use cases |
| Low | DDEX XML Export | Industry compliance; B2B use cases |
| Low | Metadata Version History | Audit trail; professional accountability |

**Milestone:** v2.0 — Major Release (Set Intelligence Engine)

---

## Priority Rationale

### Why HIGH Priority?

**Cue Point Management**
- Most requested feature in user feedback
- Visual editor eliminates need for third-party tools
- Enables Bonk! to compete with Rekordbox for pro workflows

**Cross-App Library Mirror**
- Platform lock-in is a major pain point for DJs
- Serato/Engine DJ/Traktor users currently have no migration path
- Captures users from competing ecosystems

**ANLZ File Backup/Restore**
- Loss of analysis data is catastrophic for users
- Builds trust; protects user investment
- Required for professional adoption

### Why MEDIUM Priority?

**Beatgrid + Waveform + Play History**
- Complete the rekordbox feature parity
- Foundation for future intelligent features
- Medium complexity, moderate user demand

**Set Intelligence Engine**
- High differentiation value
- Converts Bonk! from editor to DJ assistant
- Depends on audio features (VibeNet) shipping first

### Why LOW Priority?

**Hot Cue Banklists, Sampler, etc.**
- Niche use cases; affects smaller user segment
- Can be implemented as plugins later
- No direct revenue impact in near term

---

## Success Metrics

### v1.1.x (Near Term)

| Metric | Target |
|--------|--------|
| VibeNet accuracy vs manual tagging | >85% agreement |
| Benchmark: 10K track library load time | <3 seconds |
| ZIP bundle export reliability | >99% |
| Auto-update adoption rate | >60% of users |

### v1.2 - v1.5 (Mid Term)

| Metric | Target |
|--------|--------|
| Cue point editor: user retention | +25% vs current |
| Library mirror: conversion rate | >15% from competing apps |
| ANLZ restore: success rate | >98% |
| macOS signed build: download rate | >40% of installs |

### v2.0 (Long Term)

| Metric | Target |
|--------|--------|
| Set Intelligence: suggestion accuracy | >70% user acceptance |
| Related tracks: discovery click rate | >10% |
| Smart playlist: active playlist count | >5 per user avg |
| Overall NPS improvement | +15 points |

---

## Technical Dependencies

```
VibeNet Audio Features
    ↓
Set Intelligence Engine
    ↓
Related Tracks

Auto-Update Pipeline ← Signed Build CI
    ↓                    ↓
Electron Update    macOS Code Signing
```

---

*Last Updated: May 2025*
*Repository: github.com/interfluve-wav/bonk-new-exp*
