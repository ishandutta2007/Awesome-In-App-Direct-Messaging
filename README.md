# Awesome-In-App-Direct-Messaging

# Top In-App & Direct Messaging Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Chat APIs, In-App Messaging SDKs & Direct Messaging Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **In-App & Direct Messaging Tools**. These tools provide chat APIs, SDKs, and UI kits that let developers embed real-time messaging, direct conversations, group channels, and presence features into web and mobile applications — without building messaging infrastructure from scratch.

**Examples** include Salesforce Direct Messaging, Sendbird, Stream Chat, CometChat, PubNub, TalkJS, Applozic, Intercom Messenger, GetStream, and MirrorFly (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom chat logic, and transparent message data — ideal for developers seeking data sovereignty, teams avoiding per-MAU pricing, and organizations with strict privacy requirements.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Direct Messaging](https://www.salesforce.com/)**  
  Messaging capabilities within Salesforce for direct customer and team communication integrated with CRM workflows.

- **[Sendbird](https://sendbird.com/)**  
  Enterprise chat API with 300M+ end users and 95% of Fortune 100 companies as customers. Offers UIKit for rapid integration, advanced moderation (rule-based + AI + human review), and SmartAssistant for AI chatbots trained on knowledge bases . Pricing is MAU-based starting at $399/month for 5,000 MAUs .

- **[Stream Chat (GetStream)](https://getstream.io/chat/)**  
  Developer-first chat API delivering 5B+ messages/day with sub-10ms latency. Includes polished React/React Native/Flutter/SwiftUI SDKs, unlimited channel scaling (5M+ concurrent users per channel), and AI Assistants SDK for embedding LLM participants via OpenAI, Anthropic, or custom endpoints . Free tier: 25 MAU . No self-hosted option .

- **[CometChat](https://www.cometchat.com/)**  
  In-app messaging platform with React/React Native SDKs, voice/video calling, and moderation tools. Offers self-hosting on Enterprise plan .

- **[PubNub](https://www.pubnub.com/)**  
  Real-time communication platform with pub/sub messaging, presence, and chat APIs for in-app messaging.

- **[TalkJS](https://talkjs.com/)**  
  Chat API with pre-built UI, focused on marketplace and platform messaging use cases.

- **[Applozic](https://www.applozic.com/)**  
  Open-source chat and messaging SDK for mobile and web applications.

- **[Intercom Messenger](https://www.intercom.com/)**  
  Customer messaging platform with in-app messenger, bots, and support workflows.

- **[MirrorFly](https://www.mirrorfly.com/)**  
  Self-hosted messaging SDK with voice/video calling for enterprises.

## Open-Source GitHub Projects

- **[PlugChat](https://github.com/cLLeB/plugchat)**  
  Open-source, self-hosted chat that runs as one small process beside your backend. **No user table to sync** — it trusts a JWT your backend already signs, so whoever your platform says is logged in is who PlugChat sees. Features 1:1 chats, groups with roles, announcement channels, replies, edits, reactions, polls, location sharing, read receipts, typing indicators, presence, disappearing messages, view-once messages, 24-hour stories, voice/video calls (built-in WebRTC or connect your own), and per-conversation end-to-end encryption . Deploy via npm, Docker, or `npx plugchat init`. MIT licensed.

- **[Chatto](https://github.com/HendrikMans/chatto)**  
  Open-source, self-hosted team messaging platform released under AGPL-3.0+. Designed as a lightweight Slack/Teams alternative that admins can run by executing a single binary. Features channels, rooms, file sharing, video embeds, roles/permissions, screen sharing, and end-to-end encrypted voice/video calls. **Per-user encryption keys** — when an account is deleted, crypto-shredding renders that user's encrypted data unreadable even from backups . No federation: each server is one community. Available for Linux, macOS, Windows, plus Docker Compose and Kubernetes .

- **[Mqvi](https://github.com/akinalpfdn/Mqvi)**  
  Open-source communication platform with voice, video, text, and screen sharing — no ID required, zero data collection. Built with Go + React + LiveKit. Features **always-on end-to-end encryption** for every call (not a mode), Signal-protocol encrypted messaging (X3DH + Double Ratchet for DMs, Sender Keys for channels), native Rust screen sharing pipeline on Windows, five platforms from one codebase (Windows, macOS, Linux, iOS, Android), and servers/channels/roles . Self-host with one command — no Go, Node.js, or Docker required. Email optional, no phone number or government ID ever.

- **[Zooid](https://github.com/zooid/zooid)**  
  Open-source, self-hostable Slack/Discord alternative built on Matrix where **AI agents are first-class teammates**. Normal team chat for people (spaces, rooms, threads, DMs); @-mention an agent and its work renders inline as approval cards, tool calls, and live plans. MIT licensed .

- **[Poolse JS SDK](https://github.com/poolse-hq/js-sdk)**  
  Open-source realtime chat SDK (TypeScript core + React and React Native components) positioned as a Sendbird/Stream/Pusher/TalkJS alternative. Features messages, presence, typing, reactions, threads, attachments, signed webhooks, REST + WebSocket + offline queue, and plug-and-play UI components with CSS-variable theming. MIT licensed .

- **[Revolt](https://github.com/revoltchat)**  
  Open-source user-first chat platform. Feature-rich alternative to Discord with servers, channels, roles, and real-time messaging .

- **[Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)**  
  Free, unlimited open-source team chat platform. Replace email, HipChat, and Slack with a self-hosted solution .

- **[Zulip](https://github.com/zulip/zulip)**  
  Open-source chat combining real-time messaging with email-style threading. Catch up on important conversations while ignoring irrelevant ones .

- **[Wire](https://github.com/wireapp)**  
  Comprehensive collaboration suite with messenger, voice, video, conference calls, file-sharing, and external collaboration — all end-to-end encrypted .

- **[Matrix / Element](https://github.com/vector-im/element-web)**  
  Open standard for secure, decentralized, real-time communication with Apache-licensed reference implementations .

- **[Mattermost](https://github.com/mattermost/mattermost)**  
  Flexible, open-source messaging platform for secure team collaboration .

- **[Jami](https://github.com/savoirfairelinux/jami-project)**  
  GNU package for communication without servers — peer-to-peer voice, video, and messaging .

- **[Tox](https://github.com/TokTok/c-toxcore)**  
  Easy-to-use encrypted messaging that connects you without anyone else listening in. Completely free, no advertising .

- **[Linphone](https://github.com/BelledonneCommunications/linphone)**  
  Open-source instant messaging and VoIP phone with voice, video, and text over internet .

### Additional Strong Open-Source Options

- **[Tinode](https://github.com/tinode/chat)** — Open-source instant messaging platform with chat bots, video calls, and multi-device sync. Go backend with iOS/Android/Web clients .
- **[Turms](https://github.com/turms-im/turms)** — Open-source instant messaging engine for 100K–10M concurrent users .
- **[Virola Messenger](https://github.com/Virola-Messenger)** — Self-hosted secure messaging with private/group chat, file sharing, voice/video meetings, screen sharing, and Kanban task tracking. Works in air-gapped networks .
- **[pqp](https://github.com/pqp-chat/pqp)** — AGPL-3.0 Discord-style chat with voice/text channels, screen sharing with audio, and watch parties. Web, desktop, Android, iOS clients .
- **XMPP Servers** — MongooseIM (Erlang, enterprise-scale) and ejabberd for self-hosted real-time messaging .
- **Bridge Tools** — Matterbridge connects Mattermost, Slack, Discord, Telegram, Matrix, and more with REST API .

**Frameworks for building custom systems**: Combine **PlugChat** for JWT-based chat with zero user sync, **Chatto** for lightweight self-hosted team messaging, **Mqvi** for encrypted voice/video/text, **Poolse SDK** for React/React Native chat UI, and **Tinode** for scalable instant messaging to build a complete self-hosted in-app messaging stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- In-app messaging tools must comply with data protection regulations (GDPR, CCPA), industry standards (HIPAA, SOC 2), and platform-specific content moderation requirements.
- Self-hosted open-source solutions require proper security hardening, encryption key management, and infrastructure maintenance.

---

**Made for mobile developers, product engineers, platform architects, and developers building real-time in-app messaging platforms.**  
Let's make in-app and direct messaging more open, privacy-conscious, and developer-friendly.
