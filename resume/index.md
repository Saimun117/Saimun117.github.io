# Md Saimoon Islam: résumé

iOS Engineer · Dhaka, Bangladesh · Remote

saimoonislam.info@gmail.com · https://saimun117.github.io/ · https://github.com/Saimun117 · https://codeforces.com/profile/Saimun_Islam

## Summary

iOS engineer at Kite Games Studio since July 2024, shipping in four live App Store photo and video apps with 31,900 ratings between them: on-device vision and Metal features, onboarding experiments, analytics, paywalls and retention. Background in competitive programming (Codeforces Expert, ICPC Asia West Continent Final 2022). Looking for freelance projects and full-time iOS roles, remote or in Dhaka.

## Experience

### iOS Engineer, Kite Games Studio (Jul 2024–present)

I build both halves of consumer photo and video apps: the on-device vision and Metal features people use, and the growth plumbing around them (onboarding experiments, analytics, paywalls, retention notifications). The apps are published under Kite’s publisher accounts.

- 4 live App Store apps
- 31,900 ratings across them, 4.5 to 4.6★
- 677 commits of mine, Nov 2024 to Oct 2026
- 16,100 lines of my Swift, Metal and Obj-C still live

#### [Beauty Editor: Blemish Remover](https://apps.apple.com/us/app/beauty-editor-blemish-remover/id1392381237)

4.63★ from 15,170 ratings · my work Dec 2024 to now

- Nose root and bridge reshape, built on a teammate’s base: face-landmark contours, Bézier-smoothed and warped around their centroid, working on side-facing faces.
- A procedural Metal face glow that replaced a 329 KB LUT asset.
- The Relight panel layer: per-face state, one-finger light placement, auto-zoom to the selected face, multi-face undo and redo.
- Three of six onboarding variants and the A/B launch path: the remote variant arrives through Qonversion with a timeout and a cached fallback, while the splash keeps looping.
- The analytics layer: a typed event manager, three instrumentation passes, 14 save-attribution events and Apple Search Ads attribution.
- Retention notifications: win-back at days 7, 14 and 28, save milestones and a four-step early ladder, with the fix for iOS silently dropping requests made before authorization is decided.
- The floating Pro banner, which switches between “Start Free Trial” and “Subscribe” by intro-offer eligibility.
- An undo and redo crash on multi-face photos, traced to a face index shared across project states.

#### [Retouch: AI Object Remover](https://apps.apple.com/us/app/retouch-ai-object-remover/id1619769150)

4.64★ from 4,360 ratings · my work Nov 2024 to Sep 2025

- Led the rollout of a single editing hub (a teammate designed it and wired the first editor): I rolled it across the other editors, which now hand results back to one canvas for chaining, before and after, and one Save (57 commits, 22 Swift files, 18 storyboards).
- The AI Touch panel UI and face selection, fixing a re-render on every tap that distorted the image.
- Teeth-mask editing on the Metal erase canvas, and an ultra-HD crash caused by passing full-resolution images through three layers.
- A persistent progress pill for long server jobs that maps an eight-state lifecycle plus network status to five view states.

#### [Unblur: AI Photo Enhancer](https://apps.apple.com/us/app/unblur-ai-photo-enhancer/id6447248447)

4.61★ from 7,630 ratings · my work Dec 2024 to Jan 2026

- Settings, Appearance and the Pro card: SwiftUI hosted in UIKit, with live light, dark and system switching.
- A crash after reconnecting, caused by a timer on a run loop that never returned; rewritten on DispatchSourceTimer with explicit cancellation.
- The before-and-after landing animation, Paywall B, and fixes that stopped duplicate server jobs on retry.

#### [Time Warp Scan App](https://apps.apple.com/us/app/time-warp-scan-app/id6450537320)

4.50★ from 4,750 ratings · my work Jul to Aug 2025

- The effects picker, a looping-video onboarding with no black frame between clips, and the paywall hand-off.
- Analytics and Apple Search Ads attribution, plus record-timer and countdown fixes.

#### In development

- Auto body reshape for Beauty Editor (in development): Apple Vision and MediaPipe pose fused per person to drive nine region sliders through a single-pass Metal warp, built with Claude Code as a pair programmer.
- The pose model was chosen with a comparison tool I wrote (Vision against MediaPipe lite, full and heavy). Full matched heavy, so the app ships a 9.4 MB model instead of one about 20 MB larger.
- A Python and Swift harness that drives a real iPhone through the reshape flow and compares detection runs. On a 99-image set, person crops raised pose detection from 74 to 96 of 131 faces, with none lost.

Ratings are each app’s public US App Store rating in October 2026 and belong to the whole team. Counts come from the apps’ git history.

Stack: Swift, UIKit, SwiftUI, Metal, Vision, Core ML, Core Animation, Combine, Qonversion, Firebase

## Skills

- Platforms: iOS, iPadOS, macOS, visionOS
- Languages: Swift, C++, Python, Objective-C
- Interface: SwiftUI, UIKit, AppKit
- Graphics and imaging: Metal, Core Image, Core Graphics, Accelerate (vImage)
- Media: AVFoundation, AVKit, PhotosUI
- On-device ML: Core ML, Vision, coremltools
- Data and sync: SwiftData, Core Data, CloudKit
- Monetization: StoreKit 2, App Store Server Notifications, RevenueCat, Qonversion
- Growth: Firebase Analytics, Remote Config, A/B testing
- Backend: FastAPI, Node.js, PostgreSQL, Supabase, Docker
- Tooling: Xcode, Swift Package Manager, CocoaPods, XCTest, Swift Testing, Git

## Competitive programming

- Codeforces ([Saimun_Islam](https://codeforces.com/profile/Saimun_Islam)): Expert, max rating 1673 (December 2022). 156 rated contests from March 2020 to June 2024; last rating 1608.
- ICPC: 42th, ICPC Asia Dhaka Regional 2022; 49th, ICPC Asia West Continent Final 2022.
- CodeChef ([saimun](https://www.codechef.com/users/saimun)): peak rating 2115 (June 2022, before CodeChef's rating-system change).

## Education

B.Sc. in Information and Communication Engineering, Noakhali Science and Technology University, Bangladesh

## Languages

English, Bangla
