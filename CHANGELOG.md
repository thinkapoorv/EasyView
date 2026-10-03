# Changelog

All notable changes to EasyView will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
## [1.1.1.6] - 2026-10-03

### Features
- **Website Highlighter**: Introduced a lightweight, native website highlighter. Users can now select and highlight text with custom colors using the floating glass toolbar or the 'Alt+H' keyboard shortcut, with all highlights persisting reliably across page reloads.
- **Jargon Visibility Toggle**: Added a native "Eye" toggle button directly inside the Jargon Glossary panel. Users can instantly strip all backgrounds, dotted borders, and styles from highlighted terminology on the page without deleting their caches—restoring the document fully to its native visual flow without permanently losing memory data.
- **Global UI Internationalization (i18n)**: Fully globalized the extension's interface infrastructure across 54 browser-supported languages. Engineered a custom Babel AST parser to securely map dynamic Javascript strings and utilized a fast native DOM-injection script for zero-layout-shift UI localization.
- **Emotional Uninstall Portal**: Launched an ultra-premium, interactive `easyview.in/goodbye` web portal to collect auto-routed uninstallation feedback. Features a stateful emotive mascot (Evie), cinematic animations, a 3D reason selector, and an optional safe-space elaboration modal.
- **Security Paused UI**: Hardened the global security pipeline for suspended/banned accounts with a sleek, glassmorphic "Access Paused" UI sync that instantly traverses the web dashboard and all active extension instances to halt feature access without ugly errors.

- **Auto-Protect Screen Share Shielding**: Engineered a completely dual-path idempotently guarded WebRTC interceptor capable of universally forcing privacy blurs across all active tabs the millisecond a Google Meet, Discord, or native external Projector/Monitor screen share session initiates, neutralizing accidental data leaks instantly.
- **Notes Workspace Hub**: Engineered a dedicated, full-screen **Interactive Workspace** dashboard featuring a breathtaking Stripe-inspired glassmorphic masonry grid to manage all Global and Site-Specific notes seamlessly in one place.
- **Dyslexia Component Hub**: Embedded a native typography control dropdown directly inside the Dyslexia reading panel under the popup UI, eliminating the need to navigate to separate tabs to switch specialized reading fonts.
- **Dyslexia Intensity Engine**: Implemented rapid-configuration presets (Low, Medium, High) into the Dyslexia Reading mode, allowing users to instantly scale spatial parameters (letter spacing, line height, word gaps) with a single click.
- **Inline Synthetic Previews**: Completely scrapped the old static preview placeholders, engineering an authentic macOS windowed "Mini Browser" UI embedded directly inside your settings. Dyslexia mappings now render live inside a scalable Wikipedia mockup, Visual modifications dynamically invert CSS themes, and Focus Shield securely blurs a high-fidelity Material Design 3 Gmail interface in real-time explicitly from the popup.
- **Hardware Picture-in-Picture Engine**: Instead of locking sticky notes strictly inside active browser tabs, the new Workspace intelligently hooks into the physical `Document Picture-in-Picture` API. This allows your dashboard to literally decouple from Chrome and float perpetually above your entire OS.
- **Cloud-Encrypted Note Export**: Premium users can gracefully route and compile their entire spatial note configuration into a local JSON archive natively leveraging strict, cryptographically hardened backend pipelines.
- **Frictionless Offline Import Mapping**: Added a robust JSON-parse ingestion engine providing O(1) duplicate collision immunity while instantly hydrating missing backup notes directly into your active Global database.
- **Popup Quick Stats Telemetry**: Radically expanded popup utility by injecting a live telemetry widget that polls background memory arrays dynamically, giving instantaneous counts for Global and Local active notes.
- **Infinite Color Palette Architecture**: Replaced static color swatches with a high-performance conic-gradient custom hex picker, automatically passing custom colors through an onboard YIQ luminance algorithm to guarantee 100% accessible text contrasts on any theme.
- **Hardware-Accelerated UI Scaling**: Extracted and stabilized CSS `resize: both` logic directly to the outer glass container boundary, enabling responsive native corner dragging without disrupting embedded UI controls, menus, or watermark aesthetics.

### Fixed
- **Jargon Cache Overwrites**: Hardened the internal memory architecture to mathematically merge preexisting partial tooltip highlighting with new full-page decoding tasks, guaranteeing manual vocabulary selections are never deleted or overridden by newer large page scans.
- **Persistent Glossary Sync**: Repaired a visual sync delay where tooltip decodes did not instantly populate the actively opened glossary panel until the page was manually reloaded. Now, word queries are physically intercepted and instantly injected into the glossary list natively.
- **Infinite Loader Loops**: Remediated a bug where recalling previously cached partial jargon tooltips mathematically prompted the Jargon Engine to configure itself "GLOBAL ON" behind the scenes, causing subsequent unrelated web pages to immediately aggressively lock standard loading routines and deploy unwarranted full-page AI scans upon hydration.
- **Legacy Authentication Verification**: Resolved a silent failure state affecting legacy users migrated from `accesstoken` architectures. The extension popup, webpage tooltips, and data export endpoints now explicitly verify cryptographic session token integrity and proactively prompt users with a Nudge Modal to re-authenticate at easyview.in rather than failing silently on backend APIs.
- **Loader Artificial Reality Lock**: Fixed a visual bug where the global AI loader overlay would violently flicker and disappear before animation visibility keyframes could execute during ultra-fast/cached API responses. The loader is now mathematically locked to a 1.5s heartbeat.
- **Preview Scaling Overflow**: Eliminated fixed height boundaries and resolved horizontal grid squashing constraints inside the popup configuration drawers, ensuring aggressive typography scaling configurations natively expand without truncating the mini-browser previews.
- **Intelligent Button Themes (Custom Engine)**: Engineered a lightweight JavaScript saturation-observer to dynamically evaluate button colors. Native vibrant buttons (like Blue/Red calls-to-action) now retain their original colors in Dark Mode, while grayscale/white buttons properly invert to sleek dark variants.
- **Mammoth Code Eradication**: Sliced over 8,700 lines of severely bloated, dead bundle code from the active visual injection scripts. This yields massive execution and memory overhead savings without terminating any active extension behaviors.
- **Visuals Dark Mode Exclusions**: Prevented images, videos, and picture elements from incorrectly inverting their colors when the visual Dark Mode is enabled, ensuring media retains its original colors.
- **Asynchronous Boot Vacuum**: Engineered an intelligent "Soft-Merge" interceptor during database loads that explicitly protects and preserves any new notes a user creates rapidly before background initialization finishes, permanently stopping ghost deletion race conditions.
- **Native SPA Routing Hydration**: Hardened Single Page Application compatibility. Sticky notes now actively monkeypatch the browser's native `history.pushState` API to instantly detect internal React/Next.js routing, explicitly purging old spatial geometries from memory and rehydrating fresh layout context immediately without relying on delayed background worker callbacks.
- **Transient Session Hydration**: Overhauled the 'Hide until Reload' state engine, actively scrubbing and flushing transient session flags across all database pulls so hidden stickies flawlessly reappear on the screen across page restarts.
- **Dynamic Modal Engine Integration**: Sticky notes now dynamically evaluate physical bounding locks on constrained overlay components (e.g. Modals), decoupling themselves utilizing mathematically precise fixed viewport anchor points to natively bypass CSS overflow constraints.
- **Micro-Sync Animation Hooks**: Stripped legacy layout timers in favor of binding directly to the browser's hardware `requestAnimationFrame` loop, delivering 60FPS fluid masking syncs against all inbound UI transitions.
- **Robust DOM ID Sandbox Guard**: Upgraded the structural path engine to natively trace DOM paths against deeply duplicated template IDs commonly looped inside SPAs, guaranteeing strictly validated coordinate logic.
- **Z-Index True-Ray Occlusion**: The core UI crawler actively computes deep center coordinates, casting real-time element-interception rays to resolve hierarchy-agnostic physical occlusion masks.

### Security
- **PostMessage Origin Hardening**: Replaced substring-based origin matching (`includes()`) in the payment bridge with a strict exact-match allowlist, closing a spoofing vector where crafted domains (e.g. `attacker-easyview.in`) could have passed the old check.
- **Sandbox Isolation Guard**: Restricted the Morph Engine sandbox iframe to only accept commands from its direct parent frame. External websites can no longer embed the sandbox and issue arbitrary execution requests to it.

## [1.1.1.5] - 2026-09-08

### Features
* **Tour Enhancements**: Added the new Sticky Notes feature directly into the interactive onboarding tour.
* Deployed **DOM-Anchored Spatial Sticky Notes** mapping mathematically to element boundaries (`v1.1.1.5`) with `Alt+S` keyboard shortcut .
* Integrated asynchronous Global `chrome.storage.local` aggregators to natively enforce a 15-Note Free Tier limit tied seamlessly to a premium checkout pathway.
* Replaced native browser storage alerts with bespoke glassmorphic UI limit modals synced natively to EasyView's dark mode states.
* Implemented cross-framework SPA Hydration polling (handling harsh dynamic nodes on Next.js/React clusters like WhatsApp Web locally via exponentially-backed rendering attempts).

### Refactoring & UI UX
* Strip-mined standard CSS `backdrop-filter` rules off sticky notes to integrate 100% opaque, ultra-luxury metallic rendering variations (`Onyx`, `Pearl`, `Sapphire`, `Amethyst`).
* Expanded element constraints to grant users native dimensional dragging via standard CSS elasticity rules.
* Restructured color capabilities to offer an infinite Hex `<input>` mapper seamlessly tied to an internal `YIQ Luminance Algorithm` providing structurally flawless black/white contrast overlays over any picked hexadecimal combination.
* Hardened keyboard shortcut IPC configurations bypassing `DOM` keystroke polling in exclusive favor of V3 Chrome Web Store compliant architectures (`chrome.commands`).

### Added
- **Global System Notification Engine**: Engineered an intelligent, non-intrusive broadcast architecture natively inside the extension popup. It seamlessly fetches targeted operational payloads (e.g., scheduled maintenance, hotfixes) dynamically mapped to your specific extension version.
- **Smart Notification Queuing**: The architecture automatically detects overlapping system alerts. Instead of spamming multiple popups, it gracefully stacks them and transforms the dismiss button into a glowing "Next" iteration cue, ensuring you only see one clean message at a time.
- **Autonomous JWT Refresh Engine**: Implemented a secure background token regeneration architecture. The web dashboard now securely broadcasts the Supabase `refresh_token` to the extension, enabling `background.js` to natively detect `401 Unauthorized` responses and instantly fetch a fresh session from the backend without interrupting user workflows.

### Fixed
- **Export Loader Stability**: Resolved a UI issue where the Morph Export loader animation was visually frozen. Additionally, added a robust timeout safeguard to ensure the compiling operation gracefully exits and notifies you if the connection drops, rather than freezing indefinitely.
- **Morph Engine Visual Stability**: Fixed a bug where pages morphed by AI would sometimes break website fonts or backgrounds due to incomplete responses. The system now safely catches and ignores these incomplete updates, keeping your pages looking beautiful.
- **Silent Session Timeouts**: Fixed an issue where the extension would unexpectedly display a "Session Expired" notification after 7 days, forcing users to manually open the web dashboard to log back in. The extension now seamlessly and securely auto-refreshes your session in the background without interrupting your reading workflow.
- **Phantom Login Sessions**: Resolved a bug where manually clicking the red "Logout" button inside the extension's popup UI cleared the visible screen but failed to fully log the user out in the background process. Clicking logout now rigorously purges all active session tokens immediately.
- **Notebook Export Authorization Error**: Fixed a critical bug where exporting CSVs from the Notebook threw a 401 Unauthorized error due to a missing Authorization header in the codebase.
- **Optimized Permissions**: Replaced `chrome.downloads` with native HTML5 anchor streaming in the popup and purged the ghost `declarativeNetRequest` permission, completely removing both heavy permission warnings upon installation and improving Web Store compliance.

## [1.1.1.4] - 2026-09-01
### Added
- **Global Vocabulary Network**: Developed an intelligent background propagation engine that seamlessly scans the active tab whenever a user translates jargon via the tooltip, silently auto-highlighting all identical vocabulary instances across the entire document in real-time.
- **Dynamic Notification Stacking**: Rebuilt the core notification engine (`showNotification`) with a flexible CSS Flexbox stack, allowing simultaneous overlapping events (such as text simplification and jargon decodes arriving concurrently) to queue beautifully along the Y-axis without visual occlusion or premature termination.
- **Progressive Node Rendering**: Converted synchronous DOM rendering loops into asynchronous, chunk-yielded generators to explicitly surrender execution to the compositor, entirely bypassing main-thread UI freezing during heavy document DOM modifications.
- **Global Platform Settings Cache**: Introduced a lightning-fast `lib/cache.ts` in-memory module mapping platform quotas to reduce database read pressure during core AI loops.
- **Atomic Credit Ledger Protection**: Designed a robust RPC post-success consumption module in the serverless API routes that strictly immunizes users from paying credits for canceled network requests or AI failures.
- **Dynamic Frontend Quota Synchrony**: Wired the core extension clients to fetch remote AI quotas systematically on execution, permanently deprecating hardcoded usage caps constraint.
- **Morph AI Engine (Beta)**: Introduced the experimental Morph AI Engine Beta, empowering the extension to dynamically analyze and restructure DOM elements and inject intelligent, contextual UI modifications.
- **Global AI Key Priority**: Re-engineered the BYOK API architecture across the extension. Users can now toggle between "My API Key" and "EasyView Servers" to universally direct priority for Jargon, Simplify, and Morph Engine features.
- **OpenRouter Morph Support**: Expanded Morph Engine backend compatibility to securely proxy and parse JSON-structured OpenRouter keys (e.g. `google/gemini-flash-1.5`), offering full model flexibility.
- **Markdown Parsing for Simplified Text**: Introduced safe parsing for bold, italics, and lists natively in simplified text without breaking DOM layout.
- **Simplification Undo UI**: Added an inline 'Undo' button directly appended to simplified text blocks for instantly restoring original text and removing it from storage.
- **Persistent Text Simplification**: Implemented local caching mechanisms to automatically persist and restore manual page simplifications across sessions via a 2-phase DOM re-mapping engine.
- **On-Load Auto Restoration**: Introduced capabilities to automatically retrieve and seamlessly render past text simplifications and jargon replacements dynamically when a previously modified page is reopened.

### Changed
- **Unified Master Mutation Observer**: Deprecated independent feature observers and centralized all dynamic content discovery into a single highly-optimized `window.evDOMObserver`. Sub-features now safely subscribe to a unified, debounced mutation queue protecting CPU bounds and eliminating dropped node records during race conditions.
- **Optimized UI Notification Flow**: Stripped out duplicate custom DOM toasts in favor of routing Morph Engine errors seamlessly through the primary global `showNotification()` component pipeline.
- **Legacy Telemetry Phase-Out**: Securely migrated web layout analytics metrics away from the `background.js` client wrapper to strict server-side validation inside `/api/morph/route.ts` to block telemetry tampering.
- **Privacy First Tracing**: Purged the storage of raw text queries in `usage_analytics` databases; telemetry now exclusively captures domain URLs and high-level taxonomy flags to protect anonymity.
- **Graceful AI Degradation**: Enhanced the user experience by gracefully handling server errors. Users now see professional, startup-grade "experiencing high demand" modals rather than encountering generic or silent failures when API quotas are exceeded.
- **Dynamic Media Support**: Extended the `sandbox.html` integration with `allow="autoplay"` attributes and a new explicit `execute` message dispatcher to safely handle dynamic UI media capabilities generated by the AI.
- **Global State Management**: Transitioned global content script state to use `window.evState`, gracefully handling multiple script injections and averting accidental overwrites.
- **Cache Management Lifecycle**: Replaced strict 30-minute time-to-live (TTL) cache expirations with robust LRU pruning limits (150 max for simplifications, 50 for jargon payloads) to ensure long-term stability and eliminate memory bloat.
- **Glossary Panel UX Refactoring**: Overhauled the native glossary template, introducing a global 'Clear All' functionality to wipe page memory and a precise per-term 'Remove term' button.
- **Glossary Event Delegation**: Refactored Glossary DOM listeners for scale, utilizing safe event delegation to cleanly revert highlights, update states, and reflect term tallies on the extension badge instantly.

### Fixed
- **Jargon Decoder Tooltip Persistence**: Fixed a longstanding issue where manually decoded words via the selection tooltip failed to persist upon page reloads. Tooltip decodes now successfully merge into the global memory cache and automatically highlight when you revisit the page.
- **Multiple Tooltip Highlights**: Resolved a DOM layout bug where decoding a sentence with multiple jargon terms would only highlight the first matched term and skip the rest. The tooltip engine now properly scans and highlights all terms concurrently within the same sentence.
- **Jargon Cache Synchronization**: Ensured that the tooltip decoder instantly identifies if you've already decoded a selection from a previous full-page scan, skipping redundant AI calls. Conversely, partial tooltip highlights no longer accidentally impersonate full-page decodes, guaranteeing the core AI engine always runs properly.
- **Bionic Reading Toggle**: Resolved an edge-case bug where the Bionic Reading modifier remained persistently active on the page even after the feature menu was closed or disabled.
- **API Defense**: Updated `gemini-service.js` with defensive JSON markdown stripping to prevent crashes when parsing API responses.
- **Memory Leaks**: Implemented robust global cleanup handlers for orphaned intervals, timeouts, and AudioContexts when the `EV_CLEAR_MORPH` event is dispatched.

## [1.1.1] - 2026-05-15

### Added
- **Inline Interactive Dictionary (Define-in-Place)**: Activated dynamic in-page definitions. Highlight-clicking "Define" now renders an elegant dashed focus rectangle around the target word instantly, attaching a live interactive tooltip on the spot so users can read meanings without breaking their reading flow.
- **Reading Ruler Focus Engine (Dual-Beam Geometry)**: Expanded the Flashlight engine with a specialized "Reading Ruler" mode. Dynamically computes split linear-gradients to slice a horizontal view area across the screen, providing critical visual isolating support for ADHD/Dyslexia track-reading.
- **Dynamic Beam Sizing Controls**: Built a custom hardware-accelerated range slider to scale the Focus Light in real-time. Intelligently binds to both modes: controls the precise slit-height of the Reading Ruler and mathematically scales spotlight radial vectors, fully exposed via dynamic UI labels.
- **Flashlight Dashboard UX Refactoring**: Decluttered the Flashlight customizations, separating geometry controls (Shape & Size) from aesthetic options (Lens Tint & Shadow Depth) into functional, numbered, glassmorphic segments with descriptive subtitle guidance.
- **Universal Flashcard Exporter (Anki / Quizlet)**: Designed a one-click data CSV compiler adhering to strict RFC-4180 and UTF-8 BOM specs. Translates local saved vocabulary decks into transportable sheets ready for instant study flashcard imports.
- **Manual Notebook Injector**: Added an expandable direct-entry card within the Study Notebook tab. Features active duplicate-entry scanning, realtime prepending, and local JSON storage syncing to bypass manual page selections.
- **Evie AI Rebranding**: Transformed the extension's companion persona to **Evie AI**, utilizing lightweight vector SVGs for sparkles throughout top-level action menus to permanently eliminate emoji minification hazards.
- **Onboarding Tour Restart & Auto-Scroll**: Integrated an interactive "Help/Tour" icon in the dashboard header to replay the guided tour on-demand. Upgraded the core spotlight engine to automatically scroll vertical off-screen nodes into the focal viewport.
- **On-Demand Paragraph Simplification**: Launched Gemini-powered "Simplify" contextual engines, allowing users to highlight complex paragraphs and instantly translate them into easy-to-digest, plain-English bulleted recaps.
- **Interactive Flashcard Editor**: Equipped the Notebook Study Deck with dynamic, in-place card update tools. Users can trigger premium frosted-glass textareas to write, save, and persist custom study notes and memory tricks.
- **Real-Time Notebook Search**: Injected an incremental search engine into the dashboard dashboard, dynamically filtering the entire flashcard deck in real-time based on terminology, definitions, or custom notes.
- **Audible Flashcards**: Integrated native text-to-speech listeners directly into the Notebook card action bars, allowing users to hear their simplified definitions spoken aloud with a single click.
- **Luxurious Decoder Tooltips**: Overhauled jargon hover tooltips with a gorgeous glassmorphic UI layout featuring rich, integrated micro-actions: One-click **🔊 Text-to-Speech (Speak)** audio playback, **🔖 Quick-Bookmark** ribbons for study decks, and **📖 Expanded Detail** modules.
- **Smart Jargon Guard**: Re-engineered backend lifecycle to automatically toggle the Auto-Jargon Decoder OFF upon fresh tab loads and navigations, permanently safeguarding users from accidental or wasteful AI query usage.
- **Direct Offline Bookmarks**: Introduced instant local bookmarking from the floating text toolbar, completely bypassing network decoders to conserve user API budget. Includes custom-crafted "Tangerine Orange" badge tags to distinguish personal study cards.
- **Text Simplification Ribbons**: Built instant Save-to-Notebook integration for simplified paragraph popups, archiving AI sentence rewrites directly to local flashcard storage.
- **Cryptographic Licensing**: Implemented full end-to-end digital signature verification (ECDSA) for offline premium protection. Feature modes now mathematically validated via hardware WebCrypto to prevent paywall tampering.
- **Backend Hardening**: Reinforced the API authorization engine with private key generators to deliver signed integrity tokens to verified sessions.
- **Focus & Privacy Shield**: Introduced advanced page obfuscation system featuring a real-time dual-layer "Flashlight Engine" (masking/blurring outside cursor focal points) and smart CSS privacy shielding customized for high-sensitivity communication portals like Gmail and WhatsApp.
- **Smart Renewal Celebrations**: Re-engineered the premium tracker into a stateful lifecycle machine. The dashboard now tracks specific license expiration timestamps, enabling automatic celebration confetti explosions on direct renewals and resetting tracker memory on downgrades.
- **High-Performance Cinematic Confetti**: Upgraded the celebration engine to replace continuous heavy 60fps physics loops with a lightweight staggered triple-burst sequence, yielding a **95% reduction in CPU overhead**. Features highly curated multicolored palettes (Gold, Cyan, Fuchsia) and organic vector noise so no two purchase celebrations look identical.
- **Dynamic OS Font Ingest Engine (Dark Reader Grade)**: Wired native Chromium `fontSettings` bridge to silently scan the user's hard drive. Populates the visuals dropdown dynamically with hundreds of real, alphabetized local system fonts, delivering unparalleled cross-device visual personalization.
- **High-Performance DocumentFragment Buffering**: Engineered virtual DOM buffers for system font injection to bypass browser reflow cycles completely, securing 0ms, lag-free drawing speeds regardless of physical font volume.
### Changed
- **Twin Highlight Physics Parity**: Refined user-defined glossary terms to inherit difficulty-2 styling seamlessly, establishing absolute CSS layout parity between manual clarifications and AI-decoded box models.
- **Cross-Theme Dash Optimization**: Hardened all fresh components—including form selectors, quick-add drawers, and flashlight sizing panels—against light-theme adaptations, ensuring high-contrast Oceanic Cyan accessibility across light and dark modes.
- **Dynamic XSS Defense**: Audited and rewrote DOM interpolation engines inside selection highlighting workflows to use 100% native `DocumentFragment` and `createElement` patterns, eliminating vector risks from HTML string injections.
- **Advanced Cache Lifecycle (LRU)**: Implemented smart Least Recently Used self-pruning to local storage wrappers, setting definitive headroom boundaries (150 items for selections, 50 items for full-scans) to permanently mitigate local storage bloat.
- **Performance (GPU Scrolling)**: Accelerated Notebook rendering using CSS layout containment boundaries (`contain: content`) and forced hardware-compositing layers (`transform: translate3d`), yielding butter-smooth 60 FPS scroll metrics.
- **Cinematic Tour Optimization**: Upgraded the onboarding spotlight using real-time viewport math; the engine now skips redundant scrolling for instantaneous 0ms snappiness and employs soft cinematic fade transitions to prevent viewport tearing artifacts.
- **Symmetric Layout Architecture**: Restructured top-bar dashboard headers into functional flex groups, restoring perfect horizontal balance and symmetry across user controls and help/setting actions.
- **Architectural Modularization**: Refactored large sections of the extension, decoupling over 450 lines from the monolithic `popup.js` codebase into dedicated feature modules (`notebook-controller.js`, `tour-controller.js`) and split content scripts into optimized feature units to boost code maintainability.
- **Strict "Action-Only" Telemetry Architecture**: Redesigned Study Deck pipelines to trigger only upon explicit, high-value user activities (saving bookmarks, submitting manual entries, or exporting lists). Pruned passive view listeners to maximize backend efficiency.

### Fixed
- **Eager Cache Telemetry Locking**: Eradicated asynchronous race conditions in user-analytics endpoints by locking the 24-hour cache boundary IMMEDIATELY before network dispatch, permanently stopping concurrent multi-click data duplication.
- **Flashlight Vector Contrasts (Light Mode)**: Resolved white-on-white visibility issues for Circle/Ruler beam shapes and the sizing range-slider by stripping restrictive inline color overrides, unleashing flawless Slate-Gray and high-contrast Oceanic Cyan styling across Light adaptations.
- **Live Jargon Gradient Sync**: Bridged isolated web-injection CSS gaps by natively rendering vibrant category gradients (Definition, Dictionary, Custom, Tech) directly onto the floating tooltip engine.
- **Premium Modal Z-Index Escalation**: Recalculated the hierarchical depth of configuration dashboards versus dynamic upgrade prompts, elevating the Premium Gate modal to guarantee it intercepts clicks above all scrolling content.
- **Real-Time Storage Serialization**: Attached atomic persistence hooks to all Converter, Export, and Visual setting forms, writing slider dimensions and dropdown options to Chrome Sync instantly upon change.
- **Tour Teleportation Glitch**: Fixed a dimensional computation hazard where Onboarding Spotlights would clamp to (0,0) coordinates on hidden tabs. The tour engine now forces a 200ms layout reflow to securely anchor the spotlight over the exact button coordinates.
- **Autonomous Premium Downgrade Engine**: Fixed a critical caching bug where background service workers sleeping caused premium expiries to be missed. The background script now actively sweeps and broadcasts live downgrade states (Dyslexia fonts, Privacy Shield, Sensory Modes) instantly to all active tabs without requiring page reloads or popup interactions.

## [1.1.0] - 2026-05-03

### Added
- **EasyView Premium**: Launched a new premium subscription tier unlocking unlimited AI queries and advanced sensory shields.
- **Supabase Integration**: Added robust backend infrastructure for user authentication (Google OAuth), payment tracking, and secure server-side API routing.
- **Usage Analytics**: Implemented lightweight, privacy-preserving usage tracking to better understand which features users need most (does not track URLs or text content).
- **Web Portal**: Launched `easyview.in` for account management, comprehensive documentation, and secure checkout.

### Changed
- **Privacy Policy**: Completely overhauled to accurately reflect the new account system and Supabase backend while maintaining our strong privacy guarantees.
- **API Routing**: The Jargon Decoder now routes through our secure backend for Free/Premium users, fully hiding corporate API keys from the client.
- **BYOK (Bring Your Own Key)**: Refined the BYOK flow, explicitly making it an optional path for advanced users who wish to bypass all quotas.

## [1.0.2] - 2026-04-20

### Fixed
- Addressed character encoding corruption issues in Jargon Decoder responses.
- Improved performance of the Sensory Shield background MutationObserver.
- Resolved UI state synchronization bugs when logging out of the extension.

## [1.0.1] - 2026-01-11

### Added
- **Visuals Tab**: Introduced a dedicated Visuals tab in the popup, allowing users to adjust brightness, contrast, sepia, grayscale, font style, text stroke, and toggle dark/light mode for improved on-page accessibility. All settings are applied instantly and saved for future browsing sessions.
- **Jargon Decoder**: AI-powered text simplification with full page and selection-based decoding
  - Full page mode: Automatically detects and simplifies complex terms across entire pages
  - Selection decoder: Decode specific text selections (10-5000 characters)
  - Text simplification: Complete plain-English rewrites of selected content
  - Interactive tooltips with category labels and difficulty ratings
  - Support for legal, financial, technical, medical, government, and academic jargon

- **Dyslexia Reading Mode**: Comprehensive reading support
  - Multiple dyslexia-friendly fonts (OpenDyslexic, Arial, Comic Sans)
  - Customizable letter spacing (0-5px)
  - Adjustable line height (1.0-3.0)
  - Word spacing control (0-10px)
  - Color overlays (beige, light blue, light green, light yellow)
  - Bionic reading mode with bold first letters
  - Persistent settings across sessions

- **Sensory Shield**: Reduce sensory overload
  - Freeze CSS animations and transitions
  - Pause auto-playing videos and GIFs
  - Stop flashing and blinking elements
  - Create calmer browsing experience

- **Text-to-Speech**: Advanced read-aloud functionality
  - Playback controls (play, pause, stop)
  - Voice selection from system voices
  - Adjustable speed (0.5x - 1.5x)
  - Volume control (0-100%)
  - Smart punctuation pauses
  - Word highlighting with visual tracking
  - Automatic content selection

- **Dual AI Provider Support**: Choose between OpenRouter or Google Gemini
  - Automatic fallback between providers
  - Secure local storage of API keys

- **Modern UI/UX**:
  - Dark/light theme toggle
  - Responsive popup sizes (S, M, L)
  - Clean, accessible interface with Inter font
  - API provider badge
  - Visual progress indicators

### Technical
- Chrome Extension Manifest V3 architecture
- Content scripts for page manipulation
- Background service worker for API communication
- Unified API service layer supporting multiple providers
- Chrome Sync Storage for settings persistence
- Chrome Local Storage for secure API key storage

### Security & Privacy
- Local-only API key storage
- No data collection or tracking
- HTTPS-encrypted API communications
- Open source and auditable code

[1.0.1]: https://github.com/EasyView/releases/tag/v1.0.1