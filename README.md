# Awesome Meta Ray-Ban Display Apps

A big, community-sourced index of open-source GitHub repositories for the **Meta Ray-Ban Display** glasses (and the **Meta Neural Band**): web apps, games, native companion apps, SDKs, templates, dev tools and hacks.

**635 repositories** · collected 2026-10-28 by searching GitHub repo names, descriptions, topics and READMEs for Ray-Ban Display / MRBD / Neural Band terms, then filtering out unrelated hits (neural-bandit ML papers, EEG "neural band" signal processing, generic Ray-Ban Meta camera apps with no display support, unchanged forks).

> Unofficial and not affiliated with Meta or Ray-Ban. Inclusion is not an endorsement — many of these are hackathon prototypes or personal projects; review code before running it, especially anything that asks for API keys, accounts or phone/desktop bridges.

## Contents

- [Official Meta repos](#official-meta-repos) (5)
- [Guides, research & curated lists](#guides-research--curated-lists) (5)
- [Neural Band tools & hacks](#neural-band-tools--hacks) (11)
- [Rokid Lumen (built as MRBD web apps)](#rokid-lumen-built-as-mrbd-web-apps) (14)
- [SDKs, templates, UI kits & dev tools](#sdks-templates-ui-kits--dev-tools) (74)
- [AI assistants, agents & coding tools](#ai-assistants-agents--coding-tools) (70)
- [Games](#games) (100)
- [Video, music & media](#video-music--media) (56)
- [Navigation, travel & maps](#navigation-travel--maps) (57)
- [Health, fitness & accessibility](#health-fitness--accessibility) (54)
- [Messaging, social & notifications](#messaging-social--notifications) (10)
- [Productivity, utilities & everything else](#productivity-utilities--everything-else) (179)

## Official Meta repos

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [facebook/meta-wearables-dat-ios](https://github.com/facebook/meta-wearables-dat-ios) | Meta Wearables Device Access Toolkit for iOS | 577 | Shell |
| [facebook/meta-wearables-dat-android](https://github.com/facebook/meta-wearables-dat-android) | Meta Wearables Device Access Toolkit for Android | 386 | Shell |
| [facebook/meta-wearables-webapp](https://github.com/facebook/meta-wearables-webapp) | AI-assisted development toolkit for building web applications on Meta Ray-Ban Display glasses. | 220 | JavaScript |
| [facebook/meta-ray-ban-display-ui-toolkit-web](https://github.com/facebook/meta-ray-ban-display-ui-toolkit-web) | UI Toolkit brings the Meta Ray-Ban Display design system to React. Use its components, semantic tokens, materials, motion, accessibility behavior, and directional focus navigati… | 21 | TypeScript |
| [facebook/meta_glasses_webmcp](https://github.com/facebook/meta_glasses_webmcp) | WebMCP on Meta Ray-Ban Display Glasses enables developers to utilize Meta AI to create hands free and agentic interactions on web apps using user voice. | 5 |  |

## Guides, research & curated lists

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [zhangzjn/awesome-smart-glasses](https://github.com/zhangzjn/awesome-smart-glasses) | _(no description)_ | 44 |  |
| [Binaire-0101/awesome-meta-ray-ban-display-glasses](https://github.com/Binaire-0101/awesome-meta-ray-ban-display-glasses) | Kind of a long name, isn't it? | 6 |  |
| [tomkrikorian/awesome-meta-wearables](https://github.com/tomkrikorian/awesome-meta-wearables) | List of resources for Meta Wearables developers! All you need to build apps for your Meta Ray Ban! | 3 |  |
| [extentos/smart-glasses-ecosystem](https://github.com/extentos/smart-glasses-ecosystem) | Which smart-glasses platforms can you actually build and ship on? A sourced, dated map of 36 platforms and 142 devices — SDK, app model, distribution, publishing, on-lens UI and… | 1 |  |
| [gdrci/Research](https://github.com/gdrci/Research) | Documentation of the Meta Ray-Ban Display (greatwhite) firmware: boot chain, Android Verified Boot, TrustZone and hypervisor, remote processors, peripherals and device-tree over… | 0 | Shell |

## Neural Band tools & hacks

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [callbacked/kinesis](https://github.com/callbacked/kinesis) | native macos controls for the meta neural band (highly experimental) | 129 | Swift |
| [jlcjak/neurband](https://github.com/jlcjak/neurband) | Open, minimal sEMG wristband like the Meta Neural Band: 8-ch ADS1298 + nRF52832 BLE, dry gold electrodes on a flex, 3D-printed band. KiCad, FreeCAD, Zephyr, Python, simulations. | 30 | Python |
| [callbacked/neural-band-poc](https://github.com/callbacked/neural-band-poc) | mac to meta neural band connection - lots of possibilities :) | 27 | Python |
| [handzlikchris/Glasscast](https://github.com/handzlikchris/Glasscast) | Phone remote control for Meta Ray-Ban Display glasses. Mirror and control your Android phone from the glasses: live screen over WebRTC, Neural Band pinches and swipes to tap, sc… | 2 | C# |
| [RicardoFASantos/NotNeuralBand](https://github.com/RicardoFASantos/NotNeuralBand) | An open-source alternative to Meta’s Neural Band. | 2 |  |
| [896kb/air-gestures](https://github.com/896kb/air-gestures) | Control a Linux desktop with a Meta Neural Band — Rust port of callbacked/kinesis · Mirror of https://gitlab.com/896kb/air-gestures — issues and merge requests there. | 0 | Rust |
| [896kb/air-gestures-android](https://github.com/896kb/air-gestures-android) | Meta Neural Band gestures on Android — companion to air-gestures · Mirror of https://gitlab.com/896kb/air-gestures-android — issues and merge requests there. | 0 | Kotlin |
| [gmaomraan/WebVR-Patterns-NeuralBand](https://github.com/gmaomraan/WebVR-Patterns-NeuralBand) | WebVR-Patterns fork with a gesture bridge for driving the Custom pattern viewer from an external source (e.g. Meta Neural Band) | 0 | JavaScript |
| [PlumpyMonkey/Neural-Band](https://github.com/PlumpyMonkey/Neural-Band) | I wanted one of the nueral bands that the ray-ban meta displays used but obviously im not spending 800 bucks just for a band. So I decided to make my own but with motion instead… | 0 |  |
| [shyam-barange/kinesis](https://github.com/shyam-barange/kinesis) | Use your Meta Neural Band to control your Mac. Fork of callbacked/kinesis with an Xcode 27 build fix and support for bands on L2CAP PSM 129. | 0 | Swift |
| [Zac-Chen-2024/Ar-Gesture-Frontend](https://github.com/Zac-Chen-2024/Ar-Gesture-Frontend) | _(no description)_ | 0 | JavaScript |

## Rokid Lumen (built as MRBD web apps)

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [beyondlevi/rokid-lumen](https://github.com/beyondlevi/rokid-lumen) | _(no description)_ | 5 | Kotlin |
| [beyondlevi/lumen-2048](https://github.com/beyondlevi/lumen-2048) | 2048, the sliding-tiles classic, for Rokid Lumen glasses played with the Meta Neural Band | 0 | TypeScript |
| [beyondlevi/lumen-calendar](https://github.com/beyondlevi/lumen-calendar) | Google Calendar on Rokid Lumen glasses (Meta Ray-Ban Display web app) | 0 | TypeScript |
| [beyondlevi/lumen-four-in-a-row](https://github.com/beyondlevi/lumen-four-in-a-row) | Four in a Row against the computer, for Rokid Lumen glasses played with the Meta Neural Band | 0 | TypeScript |
| [beyondlevi/lumen-github](https://github.com/beyondlevi/lumen-github) | Unofficial GitHub client for Rokid Lumen glasses: latest pull requests and commits of your repositories, with checks and reviews | 0 | TypeScript |
| [beyondlevi/lumen-goat-climb](https://github.com/beyondlevi/lumen-goat-climb) | Goat Climb: a climbing game for Rokid Lumen glasses, played with the Meta Neural Band | 0 | TypeScript |
| [beyondlevi/lumen-goat-crossing](https://github.com/beyondlevi/lumen-goat-crossing) | Goat Crossing: hop across roads, rivers and rails on Rokid Lumen glasses, played with the Meta Neural Band | 0 | TypeScript |
| [beyondlevi/lumen-goat-run](https://github.com/beyondlevi/lumen-goat-run) | Goat Run: an endless three-lane runner for Rokid Lumen glasses, played with the Meta Neural Band | 0 | TypeScript |
| [beyondlevi/lumen-instagram](https://github.com/beyondlevi/lumen-instagram) | Instagram Reels and Direct for Rokid Lumen glasses: an MRBD web app and the bridge it talks to. | 0 | TypeScript |
| [beyondlevi/lumen-lists](https://github.com/beyondlevi/lumen-lists) | Shopping lists on Rokid Lumen glasses, kept in TickTick (Meta Ray-Ban Display web app) | 0 | TypeScript |
| [beyondlevi/lumen-reddit](https://github.com/beyondlevi/lumen-reddit) | Reddit client for Rokid Lumen glasses, built as a Meta Ray-Ban Display web app. | 0 | TypeScript |
| [beyondlevi/lumen-telegram](https://github.com/beyondlevi/lumen-telegram) | Telegram client for Rokid Lumen glasses | 0 | TypeScript |
| [beyondlevi/lumen-whatsapp](https://github.com/beyondlevi/lumen-whatsapp) | WhatsApp for Rokid Lumen (MRBD web app) on the Evolution API | 0 | TypeScript |
| [beyondlevi/lumen-writing-trainer](https://github.com/beyondlevi/lumen-writing-trainer) | Learn to write with the Meta Neural Band on Rokid Lumen glasses, as a game: words, phrases, words per minute | 0 |  |

## SDKs, templates, UI kits & dev tools

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [zhuowei/meta-rayban-firmware-android-emulator](https://github.com/zhuowei/meta-rayban-firmware-android-emulator) | _(no description)_ | 27 | Makefile |
| [circus-kitchens/expo-meta-wearables-dat](https://github.com/circus-kitchens/expo-meta-wearables-dat) | _(no description)_ | 16 | TypeScript |
| [rodcone/flutter_meta_wearables_dat](https://github.com/rodcone/flutter_meta_wearables_dat) | A Flutter plugin that provides a bridge to Meta's Wearables Device Access Toolkit (DAT), enabling integration with Meta AI Glasses for iOS and Android | 15 | Dart |
| [GlassKitApp/glasskit-ui](https://github.com/GlassKitApp/glasskit-ui) | A repository for glasskit-ui | 10 | HTML |
| [michaelcummingsofficial/mrbd-ui-kit](https://github.com/michaelcummingsofficial/mrbd-ui-kit) | The easiest way to build an app for Meta Ray-Ban Display | 10 | TypeScript |
| [jacksonmafra-umain/spectra](https://github.com/jacksonmafra-umain/spectra) | Spectra is a Kotlin Multiplatform wrapper around Meta's Wearables Device Access Toolkit (DAT). | 9 | Swift |
| [prasanthsasikumar/WASD](https://github.com/prasanthsasikumar/WASD) | Preview any web app the way it appears on the heads-up display of Meta Ray-Ban Display glasses. Additive waveguide simulation in the browser, no hardware required. | 9 | JavaScript |
| [ethanpaschkes/meta-glasses-voice-bridge](https://github.com/ethanpaschkes/meta-glasses-voice-bridge) | Voice commands from Ray-Ban Meta smart glasses to your Mac, routed through Claude. iOS app built on the Meta Wearables Device Access Toolkit (DAT) + a local Python listener. No … | 6 | Swift |
| [Tienduyvo/meta-glass-display-webkit-harness](https://github.com/Tienduyvo/meta-glass-display-webkit-harness) | Voice-control Claude Code from Meta Ray-Ban Display glasses: a WhatsApp bridge into a live Claude session (desktop + browser control, photos back), plus a kit for tiny glasses+p… | 5 | HTML |
| [HKTITAN/thenextinterface](https://github.com/HKTITAN/thenextinterface) | Give your agents the ability to help you build your ideas for the next interface | 4 | Python |
| [iSee-Labs/meta-wearables-dat-flutter](https://github.com/iSee-Labs/meta-wearables-dat-flutter) | Meta Wearables Device Access Toolkit for Flutter | 3 | Dart |
| [levin-riegner/lr-rbm-demos](https://github.com/levin-riegner/lr-rbm-demos) | A collection of demo web apps for the Meta Ray-Ban Display glasses. | 3 | JavaScript |
| [apnatvar/meta-rayban-display-webapp-template](https://github.com/apnatvar/meta-rayban-display-webapp-template) | This is a base template for developing web-apps for the Ray Ban Meta Display Glasses. It includes relevant agent skills for you to code with your favourite LLM. The basic starte… | 2 | Python |
| [LittleRed311/SideEye](https://github.com/LittleRed311/SideEye) | SideEye allows you to "sideload" apps to the RayBan Meta Display Glasses | 2 | HTML |
| [luke-hurd/rbm-display-head-gestures-js](https://github.com/luke-hurd/rbm-display-head-gestures-js) | Head gestures for Meta Display browsers (DeviceOrientation). | 2 | JavaScript |
| [ThomasBurgess2000/dpad-forwarder](https://github.com/ThomasBurgess2000/dpad-forwarder) | Forward Meta Ray-Ban Display D-pad input to a computer | 2 | Python |
| [hshwang34/DisEmulator](https://github.com/hshwang34/DisEmulator) | Gesture-controlled UI prototyping environment for Meta Ray-Ban Display (600×600px HUD) | 1 | TypeScript |
| [mrmhthegreat/meta_wearables](https://github.com/mrmhthegreat/meta_wearables) | A Flutter plugin for the **Meta Wearables Device Access Toolkit (MWDAT)**. Access Meta Ray-Ban glasses camera streaming, photo capture, display content rendering, audio routing,… | 1 | HTML |
| [romanized/ray-ban-display-webapps](https://github.com/romanized/ray-ban-display-webapps) | Three working web apps for the Meta Ray-Ban Display (Snake, Weather, Compass) + a from-scratch guide to building your own. Just HTML/CSS/JS on a 600x600 screen. | 1 | JavaScript |
| [ShakenTheCoder/meta-rayban-display-boilerplate](https://github.com/ShakenTheCoder/meta-rayban-display-boilerplate) | 🕶️ Dead-simple Next.js + Tailwind starter kit for building web apps on the Meta Ray-Ban Display's 600×600 monocular HUD. Neural Band gesture hooks included. Free & open source. | 1 | TypeScript |
| [100yenadmin/glasses-platform](https://github.com/100yenadmin/glasses-platform) | Smart glasses as a Hermes Agent channel: talk to your own agent from Meta Ray-Ban, Ray-Ban Display, Even G2 and Mentra glasses, with photos, streaming and pushes. | 0 | Python |
| [ajaybiju-sparkski/hydris-Glasses-UI-demo](https://github.com/ajaybiju-sparkski/hydris-Glasses-UI-demo) | _(no description)_ | 0 | HTML |
| [AldoOmnia/Meta_Rayban_Glasses_App](https://github.com/AldoOmnia/Meta_Rayban_Glasses_App) | Meta Ray-Ban Display web apps hub: catalog, starter, sensors lab | 0 | JavaScript |
| [antonrisch/hudxyz](https://github.com/antonrisch/hudxyz) | _(no description)_ | 0 | TypeScript |
| [audiojoe4444/Matinee](https://github.com/audiojoe4444/Matinee) | A Streaming app tapping into the Archive.org treasure chest | 0 | JavaScript |
| [b-d-io/b-d](https://github.com/b-d-io/b-d) | Open-source tools and field notes for building apps on display smart glasses: firmware-exact text layout for Even G2, a lens simulator, and an MCP server | 0 | TypeScript |
| [bell-pepper/meta-harness-viewer](https://github.com/bell-pepper/meta-harness-viewer) | Doc / pdf viewer for Meta | 0 | Swift |
| [BoilThis/TestGrokBuild](https://github.com/BoilThis/TestGrokBuild) | _(no description)_ | 0 | JavaScript |
| [carlosatFroom/meta_vision](https://github.com/carlosatFroom/meta_vision) | reads notifications to glasses, bypassing meta ai app | 0 | Kotlin |
| [chrisstayte/dart-meta-dat](https://github.com/chrisstayte/dart-meta-dat) | Dart / Flutter port of Meta device access toolkit | 0 | Dart |
| [createdbymvw/yeet-your-thoughts-glasses](https://github.com/createdbymvw/yeet-your-thoughts-glasses) | A playful smart glasses app for writing or dictating a thought, burning it away, and letting it go. Built for Meta Ray-Ban Display with a procedural burn animation. | 0 | JavaScript |
| [CumulativeWebInc/cwi-kingcode-lens](https://github.com/CumulativeWebInc/cwi-kingcode-lens) | KingCode Lens — web apps for Meta Ray-Ban Display glasses, previewed in your browser. Simulator lab + conformance-tested adapter stack. No hardware needed. | 0 | JavaScript |
| [edom18/Ray-Ban_Meta_Display_App](https://github.com/edom18/Ray-Ban_Meta_Display_App) | _(no description)_ | 0 | JavaScript |
| [fasaiph/kitty-captions](https://github.com/fasaiph/kitty-captions) | 🐱 Real-time cat-mood captions on Meta Ray-Ban Display glasses (on-device Vision feature-print matching) | 0 | Swift |
| [Hendricks27/mrd](https://github.com/Hendricks27/mrd) | _(no description)_ | 0 | Swift |
| [hka233/MRBD-Translation-EN-JP](https://github.com/hka233/MRBD-Translation-EN-JP) | Meta Rayban Display project to translate JP to EN using the smart glasses connected to iPhone | 0 | Swift |
| [hoonsubin/meta-rayban-display-litellm](https://github.com/hoonsubin/meta-rayban-display-litellm) | A simple meta rayban app for using LiteLLM for AI assistant | 0 | Kotlin |
| [islawka-cyber/greatwhite-lab](https://github.com/islawka-cyber/greatwhite-lab) | Meta Ray-Ban Display Web App capability probe | 0 | JavaScript |
| [jaylen-creative-engineer/SolarFrame-ios](https://github.com/jaylen-creative-engineer/SolarFrame-ios) | _(no description)_ | 0 | Swift |
| [jreinjr/meta-display-showcase](https://github.com/jreinjr/meta-display-showcase) | _(no description)_ | 0 | JavaScript |
| [klxyz/loki](https://github.com/klxyz/loki) | _(no description)_ | 0 | TypeScript |
| [krouis/hello-rbdg](https://github.com/krouis/hello-rbdg) | Hello World webapp for Meta Display Glasses (Ray-Ban) | 0 | JavaScript |
| [leafpcye/MRBDMapGameLab](https://github.com/leafpcye/MRBDMapGameLab) | MRBDMapGameLab | 0 | JavaScript |
| [lr-rbm/starter_kit_abhi](https://github.com/lr-rbm/starter_kit_abhi) | _(no description)_ | 0 | JavaScript |
| [lr-rbm/starter_kit_aldana_y_maripe](https://github.com/lr-rbm/starter_kit_aldana_y_maripe) | _(no description)_ | 0 | JavaScript |
| [lr-rbm/starter_kit_template](https://github.com/lr-rbm/starter_kit_template) | Template repository for personal Meta Ray-Ban Display starter kits. Use 'Use this template' to create a per-colleague playground. | 0 | JavaScript |
| [manmohanml1/autonomous-travel-guide-mrbd](https://github.com/manmohanml1/autonomous-travel-guide-mrbd) | Glasses-first travel companion combining weather, landmarks, translation, exchange rates, and budgets. | 0 | JavaScript |
| [manmohanml1/checkmate-glass-mrbd](https://github.com/manmohanml1/checkmate-glass-mrbd) | Glasses-first chess with complete rules, local AI, saved games, and D-pad controls. | 0 | JavaScript |
| [manmohanml1/glass-search-meta-display](https://github.com/manmohanml1/glass-search-meta-display) | Voice and handwriting-first search experience for Meta Ray-Ban Display glasses. | 0 | JavaScript |
| [manmohanml1/glass-tube](https://github.com/manmohanml1/glass-tube) | Focus-first YouTube viewer prototype designed for Meta Ray-Ban Display glasses. | 0 | JavaScript |
| [manmohanml1/novel-browser-glass](https://github.com/manmohanml1/novel-browser-glass) | Glasses-first novel reader with D-pad navigation, saved progress, an offline shell, and a live demo. | 0 | JavaScript |
| [massimopiazza/meta-glass-checklist](https://github.com/massimopiazza/meta-glass-checklist) | Offline-first AIT procedure checklist webapp for Meta Display Glasses | 0 | JavaScript |
| [MRBD-Apps/mrbd-app-template](https://github.com/MRBD-Apps/mrbd-app-template) | Starter template for Meta Ray-Ban Display web apps — React + Vite + Tailwind v4 + mrbd-ui-kit, spatial navigation, PWA icons. | 0 | TypeScript |
| [mrbd-dev/build](https://github.com/mrbd-dev/build) | A NextJS starter for building web apps for the Meta Ray-Ban Display | 0 | TypeScript |
| [Myslihirmu/mrbd-test](https://github.com/Myslihirmu/mrbd-test) | _(no description)_ | 0 | HTML |
| [nightforge-studios/lensmyth](https://github.com/nightforge-studios/lensmyth) | Everything you need to build apps for Meta Ray-Ban Display glasses, zero dependencies. | 0 | JavaScript |
| [oscargonzalezpleitez-dot/Racsotube](https://github.com/oscargonzalezpleitez-dot/Racsotube) | Cliente de YouTube para Meta Ray-Ban Display (600x600) - Meta Wearables Web App | 0 | JavaScript |
| [pampas93/meta-wearables-webapp](https://github.com/pampas93/meta-wearables-webapp) | AI-assisted development toolkit for building web applications on Meta Ray-Ban Display glasses. | 0 | Python |
| [phdev/MRDB-WebGPU-Test](https://github.com/phdev/MRDB-WebGPU-Test) | _(no description)_ | 0 | JavaScript |
| [Ric409/bloom-3d-companion](https://github.com/Ric409/bloom-3d-companion) | BLOOM smart-glasses AI companion prototypes: 2D animation kit, emotional 3D model, SwiftUI bridge, and behavior specs. | 0 | HTML |
| [RohanAltAccount/clover](https://github.com/RohanAltAccount/clover) | _(no description)_ | 0 | TypeScript |
| [RRfyOfficial/Rayban-Display-Weather-App](https://github.com/RRfyOfficial/Rayban-Display-Weather-App) | Made a weather app using Meta Wearables Web App AI Toolkit just to get a hang of how this all works. | 0 | JavaScript |
| [RWARnDEV/mysterio-sky-probe](https://github.com/RWARnDEV/mysterio-sky-probe) | Head-orientation probe web app for Meta Ray-Ban Display (Mysterio Sky) | 0 | HTML |
| [shahramdj/meta-wearables-webapp](https://github.com/shahramdj/meta-wearables-webapp) | Meta Glass Surgeon Copilot POV | 0 | Python |
| [shotcowboystyle/meta-wearables-ops-plugin](https://github.com/shotcowboystyle/meta-wearables-ops-plugin) | Meta smart-glasses engineering for AI agents — Wearables Device Access SDK integration on iOS and Android, camera, display, sensors, transport reliability, on-device compliance,… | 0 | Python |
| [sidkandan/GeminiDisplayKit](https://github.com/sidkandan/GeminiDisplayKit) | A Gemini-powered SDK + CLI for building managed-agent games on Meta Ray-Ban Display HUDs. Built at the Google I/O Hackathon 2026-05-23. | 0 | JavaScript |
| [SillyToolValley/glint](https://github.com/SillyToolValley/glint) | HUD-first web framework for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [soothslayer/muse-voice-display](https://github.com/soothslayer/muse-voice-display) | _(no description)_ | 0 | TypeScript |
| [una-linea-a-la-vez/glassesInstructor](https://github.com/una-linea-a-la-vez/glassesInstructor) | _(no description)_ | 0 | Swift |
| [UrsushoribilisMusic/ambient-field-lens](https://github.com/UrsushoribilisMusic/ambient-field-lens) | _(no description)_ | 0 | Python |
| [vikashparekh/meta-wearables-webapps](https://github.com/vikashparekh/meta-wearables-webapps) | _(no description)_ | 0 | Python |
| [VisheshV5/Iris](https://github.com/VisheshV5/Iris) | _(no description)_ | 0 | TypeScript |
| [wahhaj-anomaly/ray-ban-display-test](https://github.com/wahhaj-anomaly/ray-ban-display-test) | Meta Ray-Ban Display feature test web app | 0 | JavaScript |
| [Workofarttattoo/Ink-sight](https://github.com/Workofarttattoo/Ink-sight) | _(no description)_ | 0 |  |

## AI assistants, agents & coding tools

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [Turbo1123/turbometa-rayban-ai](https://github.com/Turbo1123/turbometa-rayban-ai) | World's First Full-Chinese Ray-Ban Meta AI Assistant - 全球首个全中文 Ray-Ban Meta 智能眼镜 AI 助手 | 548 | Swift |
| [kstevica/captain-claw](https://github.com/kstevica/captain-claw) | Command a fleet of AI agents, on every deck, every desk, every wrist. Self-hosted multi-agent platform with memory, a coding pipeline, Flows, a team kiosk and voice devices. Any… | 181 | Python |
| [straff2002/OpenGlasses](https://github.com/straff2002/OpenGlasses) | Making Meta Ray-ban / Oakley glasses smarter. Non-Meta Model selection, agentic features, smart guidance. | 124 | Swift |
| [prasanthsasikumar/hermes-glasses](https://github.com/prasanthsasikumar/hermes-glasses) | Voice + vision AI assistant for smart glasses — Meta Ray-Ban and AiSee / Realtek-based glasses: live on-device transcription, glasses camera capture, button mapping, and an opti… | 25 | Swift |
| [b-nnett/meta-display-codex](https://github.com/b-nnett/meta-display-codex) | Codex Ray-Ban iOS app and Meta wearable display tooling | 6 | Swift |
| [leestar/meta-rayban-display-travel-hud](https://github.com/leestar/meta-rayban-display-travel-hud) | Travel HUD for Meta Ray-Ban Display glasses — DPAD-navigable POIs, AR view, AI location briefings. | 4 | HTML |
| [lugovelb/chief-glasses-open](https://github.com/lugovelb/chief-glasses-open) | Chief: replies from Grok Bot, ChatGPT (Codex), Claude, Gemini and Cursor on your Meta Ray-Ban Display glasses or any browser. Encrypted, with one-tap Yes, No, Later replies. | 4 | JavaScript |
| [chosukhyun73/glass-agent](https://github.com/chosukhyun73/glass-agent) | Apple App Site Association for Pharos iOS app — Meta Wearables DAT Universal Link | 1 | Swift |
| [coob113/Glance](https://github.com/coob113/Glance) | Monitor Codex activity from Meta Ray-Ban Display. | 1 | TypeScript |
| [DOGFOOFA/adam.github.io](https://github.com/DOGFOOFA/adam.github.io) | A.D.A.M. (Advanced. Digital. Analytic. Manager.) is an app built for Meta RayBan Display that provides an OSINT tracking oppurtunity to users. Functions include AI summary of gl… | 1 | HTML |
| [MoheetBrain/MuseGlass](https://github.com/MoheetBrain/MuseGlass) | Turn Meta glasses into a hands-free interface for Muse Code. Delegate coding tasks by voice, hear live progress, interrupt or refine work mid-run, approve actions, and let your … | 1 | Python |
| [1977744311/lenscrew-ios](https://github.com/1977744311/lenscrew-ios) | Open-source Mac bridge + iOS/watchOS app that unifies local Codex, Claude Code, and Cursor coding agents into one command deck — with QR-paired end-to-end-encrypted remote acces… | 0 | Swift |
| [Aeonia-ai/rta-rsvp-reader](https://github.com/Aeonia-ai/rta-rsvp-reader) | CLI-controlled, WebSocket-driven RSVP reader for low-resolution AR displays | 0 | TypeScript |
| [ajd265713-glitch/Pool](https://github.com/ajd265713-glitch/Pool) | _(no description)_ | 0 | JavaScript |
| [aljabrialam/tencent-cloud-ai-hackathon-sg-2026](https://github.com/aljabrialam/tencent-cloud-ai-hackathon-sg-2026) | Tencent Cloud AI CAN DO IT Hackathon Singapore 2026 — spec-driven development with GitHub Spec Kit | 0 | TypeScript |
| [angaddab1087-alt/XDG_HACKATHON_ANGAD-CHINTAMANI](https://github.com/angaddab1087-alt/XDG_HACKATHON_ANGAD-CHINTAMANI) | _(no description)_ | 0 | HTML |
| [ashritha1392/fitness-product-for-meta](https://github.com/ashritha1392/fitness-product-for-meta) | _(no description)_ | 0 | TypeScript |
| [baklarrrr/glass-home](https://github.com/baklarrrr/glass-home) | Bakar Home for Meta Ray-Ban Display: Claude and Codex sessions from the studio PC (end-to-end encrypted), apps, and games kept separate. | 0 | JavaScript |
| [Bhavishaahuja/Pinch](https://github.com/Bhavishaahuja/Pinch) | _(no description)_ | 0 | Python |
| [bigmacfive/roamie](https://github.com/bigmacfive/roamie) | An expressive AI companion designed for Meta Ray-Ban Display glasses. Built for c0mpiled-16 UCSD. | 0 | TypeScript |
| [bruno1308/claude-code-display](https://github.com/bruno1308/claude-code-display) | Control Claude Code on your PC, hands-free, from Meta Ray-Ban Display Glasses + an Android phone. E2E encrypted over Cloudflare Workers. | 0 | Kotlin |
| [cairox379/tiny-companions](https://github.com/cairox379/tiny-companions) | Cute AI-powered 3D companion avatars for Meta Ray-Ban Display glasses. | 0 | HTML |
| [CarlKho-Minerva/soma-hud](https://github.com/CarlKho-Minerva/soma-hud) | Soma — your body's copilot. Real-time voice AI on Meta Ray-Ban glasses. OpenAI Voice Hack Night 2026. | 0 | HTML |
| [ColinHu07/blackjack](https://github.com/ColinHu07/blackjack) | _(no description)_ | 0 | Swift |
| [ColinHu07/cheating](https://github.com/ColinHu07/cheating) | _(no description)_ | 0 | TypeScript |
| [dankramer2222/meta-ebay-glass-scanner](https://github.com/dankramer2222/meta-ebay-glass-scanner) | AR resale assistant for Meta Ray-Ban Display: identify an item with computer vision, search eBay listings(Other platforms like Amazon/fb market in progress), estimate its market… | 0 | Python |
| [dasugsta/lensline](https://github.com/dasugsta/lensline) | _(no description)_ | 0 | JavaScript |
| [Delta-agent-2026/nokia-snake](https://github.com/Delta-agent-2026/nokia-snake) | Classic Nokia-style Snake with quirky synth sounds, tuned for the Meta Ray-Ban Display 600x600 viewport. | 0 | HTML |
| [DORARIN42/Smartglass_shopping](https://github.com/DORARIN42/Smartglass_shopping) | _(no description)_ | 0 | Kotlin |
| [euskejs/meta-display-test](https://github.com/euskejs/meta-display-test) | Initial test | 0 | TypeScript |
| [FelixHuoEZ/gpt-meta-display-webapp](https://github.com/FelixHuoEZ/gpt-meta-display-webapp) | Meta Ray-Ban Display Web App PoC | 0 | JavaScript |
| [Freespirits/metadisplay](https://github.com/Freespirits/metadisplay) | Claude Code status at a glance on Meta Ray-Ban Display glasses | 0 | JavaScript |
| [GalacTechNyc/claude](https://github.com/GalacTechNyc/claude) | _(no description)_ | 0 | JavaScript |
| [GalacTechNyc/muse-display](https://github.com/GalacTechNyc/muse-display) | _(no description)_ | 0 | JavaScript |
| [GKlimenko/awe-chair-cue](https://github.com/GKlimenko/awe-chair-cue) | test display | 0 | JavaScript |
| [GorgeousBodge/meta-home](https://github.com/GorgeousBodge/meta-home) | Home Assistant for Meta Display | 0 | JavaScript |
| [GorgeousBodge/meta-news-app](https://github.com/GorgeousBodge/meta-news-app) | Glanceable UK news for Meta Ray-Ban Display: AI-summarised headlines from BBC, Guardian and Surrey Live, with spoken briefings. | 0 | JavaScript |
| [hossandbox/hermes-hud](https://github.com/hossandbox/hermes-hud) | Heads-up items display for Meta Ray-Ban Display glasses (Web App). | 0 | JavaScript |
| [jamesli07tx/Wingman-HackRice](https://github.com/jamesli07tx/Wingman-HackRice) | _(no description)_ | 0 | TypeScript |
| [JoaoNicastro/metadis](https://github.com/JoaoNicastro/metadis) | Meta Ray-Ban Display 3D viewer Web App — load .glb via URL, rotate via Neural Band + head IMU | 0 | JavaScript |
| [JoshuaLevi/agent-visor](https://github.com/JoshuaLevi/agent-visor) | Monitor AI coding agents (Claude Code, Codex) on Meta Ray-Ban Display glasses. Approve tool permissions hands-free. | 0 | JavaScript |
| [jsugihara-codex/lens-translator](https://github.com/jsugihara-codex/lens-translator) | Real time translation app | 0 | JavaScript |
| [kendy92/Meta-Rayban-Glass-Shopping-List](https://github.com/kendy92/Meta-Rayban-Glass-Shopping-List) | Personal shopping app that manages shopping on the phone and supports view mode on Meta Ray-Ban display glasses. | 0 | JavaScript |
| [kscanaiapp/kscan-glasses-webapp](https://github.com/kscanaiapp/kscan-glasses-webapp) | _(no description)_ | 0 | JavaScript |
| [KYMao/turbometa-link](https://github.com/KYMao/turbometa-link) | AASA universal link host for TurboMeta iOS (Meta Ray-Ban Display) | 0 | HTML |
| [labaronessa2025/jarvis-lente](https://github.com/labaronessa2025/jarvis-lente) | Jarvis sugli occhiali Ray-Ban Meta Display (web app) | 0 | HTML |
| [liannebaron/baybayin-script](https://github.com/liannebaron/baybayin-script) | Write any name in Baybayin. Meta Muse Spark handles pronunciation, a deterministic engine handles the script. Live at baybayinscript.com | 0 | HTML |
| [LiquidAzir/backgammon-display](https://github.com/LiquidAzir/backgammon-display) | Backgammon web app for Meta Ray-Ban Display smart glasses — single player vs computer, D-pad / Neural Band navigation, 600x600 dark theme. | 0 | JavaScript |
| [LiquidAzir/hexland](https://github.com/LiquidAzir/hexland) | Hex-tile settlement & trading strategy game for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [lukietee/DEAL](https://github.com/lukietee/DEAL) | _(no description)_ | 0 | Swift |
| [Luxisoft/realityos-spatial-memory](https://github.com/Luxisoft/realityos-spatial-memory) | RealityOS is an AI-powered spatial memory for Meta smart glasses. Record objects and locations in a persistent visual database, then find them using voice queries and image-guid… | 0 | Python |
| [ma9197/gc-view](https://github.com/ma9197/gc-view) | Personal glasses remote | 0 | JavaScript |
| [mgzhang-tw/director-shot-assistant-display-demo](https://github.com/mgzhang-tw/director-shot-assistant-display-demo) | Meta Ray-Ban Display director shot navigation HUD demo | 0 | TypeScript |
| [minutechreview/mrbd-teleprompter](https://github.com/minutechreview/mrbd-teleprompter) | AI Teleprompter for Meta Ray-Ban Display glasses — hands-free script reading via D-pad | 0 | JavaScript |
| [mmaziesf/rayban-vlm-poc](https://github.com/mmaziesf/rayban-vlm-poc) | On-device VLM POC for Meta Ray-Ban Display (Android + iOS scaffold) | 0 | Kotlin |
| [nadeem-j29/glasses](https://github.com/nadeem-j29/glasses) | Claude card web app for Meta Ray-Ban Display (read-only) | 0 | HTML |
| [omkar-103/context-os](https://github.com/omkar-103/context-os) | Accessibility context layer for Meta Ray-Ban Display — adapting real-world information to each user's accessibility needs using AI. | 0 | HTML |
| [rapidstartup/chief-glasses](https://github.com/rapidstartup/chief-glasses) | Chief: encrypted assistant replies for Meta Ray-Ban Display | 0 |  |
| [runningoec/smart-glasses-home-assistant](https://github.com/runningoec/smart-glasses-home-assistant) | Home Assistant custom integration that adds a 600x600 glasses Web App to Home Assistant - pair via short code, glance at 1-8 entities live over the HA websocket. | 0 | Python |
| [SEZ9/kiwi-meta-glasses-ios](https://github.com/SEZ9/kiwi-meta-glasses-ios) | Build your own AI assistant and live translator for Meta smart glasses. Bilingual subtitles on the Ray-Ban Display, voice agent with 14 tools, your models, your server. | 0 | Swift |
| [shahdadk/glance-qm](https://github.com/shahdadk/glance-qm) | An ambient assistant for Meta glasses: context cards, conversation memory, and agent workflows with QM, GBrain, Memorable, Exa, and Jev. | 0 | TypeScript |
| [Shoshin23/wiser](https://github.com/Shoshin23/wiser) | _(no description)_ | 0 | JavaScript |
| [sidart10/muse-glasses](https://github.com/sidart10/muse-glasses) | Talk to your own Muse from Meta Ray-Ban Display glasses: macOS Muse gadget + bridge + glasses web app (unofficial) | 0 | Python |
| [thackshanaramana0-spec/cmu_iot_3](https://github.com/thackshanaramana0-spec/cmu_iot_3) | _(no description)_ | 0 | Kotlin |
| [tobyfarm/GlassGoogleHackathon](https://github.com/tobyfarm/GlassGoogleHackathon) | GLANCE — autonomous-builder-with-glance-HITL · Flash + Managed Agents + AR glasses · agent that asks fewer questions the more you use it | 0 | Python |
| [Umang3211/casemate](https://github.com/Umang3211/casemate) | Live consulting case copilot for Meta Ray-Ban Display: the interview becomes glanceable cards on the lens, powered by Claude. | 0 | Swift |
| [webmanagments/Kmr-fitup](https://github.com/webmanagments/Kmr-fitup) | _(no description)_ | 0 | TypeScript |
| [williamxuuu/CookingGlasses](https://github.com/williamxuuu/CookingGlasses) | MetaAI cooking glasses | 0 | Swift |
| [XoAnonXo/grok-glasses](https://github.com/XoAnonXo/grok-glasses) | Placeholder Meta Ray-Ban Display Web App | 0 | Swift |
| [zhelaoui/meta-glasses-trs](https://github.com/zhelaoui/meta-glasses-trs) | _(no description)_ | 0 | JavaScript |

## Games

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [LiquidAzir/chess-glasses](https://github.com/LiquidAzir/chess-glasses) | Simple, full-color chess for Meta Ray-Ban Display smart glasses | 4 | JavaScript |
| [phdev/doom3-rayban-display](https://github.com/phdev/doom3-rayban-display) | _(no description)_ | 4 | JavaScript |
| [mrtsm/raybans-fighter](https://github.com/mrtsm/raybans-fighter) | ⚡ Pixel Brawl — AAA 2D fighting game for Meta display glasses | 2 | JavaScript |
| [nicolachoquet06250/neon-pong-duo-pwa](https://github.com/nicolachoquet06250/neon-pong-duo-pwa) | Jeu Pong style rétro jouable uniquement en asymétrique sur mobile et meta rayban display | 1 | JavaScript |
| [phdev/glquake2-rayban-display](https://github.com/phdev/glquake2-rayban-display) | GLQuake II Meta Ray-Ban Display web app shell | 1 | JavaScript |
| [richardbernard2026/Racing-HUD](https://github.com/richardbernard2026/Racing-HUD) | A display for when you're driving. It's a heads-up display, but in reality it makes your Meta Ray-Ban displays feel like an Edith for Tony Stark. | 1 | JavaScript |
| [A-ICO/face-maze](https://github.com/A-ICO/face-maze) | _(no description)_ | 0 | JavaScript |
| [adilanchian96/MetaSaber](https://github.com/adilanchian96/MetaSaber) | BeatSaber for the Meta Ray Ban Displays | 0 | TypeScript |
| [axe-fb/doom-glasses](https://github.com/axe-fb/doom-glasses) | DOOM on smart display glasses (600x600, D-pad controls) — prebuilt WASM DOOM + Freedoom, served on GitHub Pages | 0 | HTML |
| [Borked-Reality/quest-log-meta-display](https://github.com/Borked-Reality/quest-log-meta-display) | _(no description)_ | 0 | JavaScript |
| [brainniliang-debug/RBMD](https://github.com/brainniliang-debug/RBMD) | my rayban meta display games | 0 | JavaScript |
| [brianscout/Hangman](https://github.com/brianscout/Hangman) | _(no description)_ | 0 | JavaScript |
| [bytecrafts-ca/neural-sky-runner](https://github.com/bytecrafts-ca/neural-sky-runner) | Gesture-first endless runner for Meta Ray-Ban Display | 0 | TypeScript |
| [christopherwoon/ex-rush](https://github.com/christopherwoon/ex-rush) | A side-scrolling anime runner for Meta Ray-Ban Display glasses, inspired by Scott Pilgrim's evil-ex gauntlet. | 0 | HTML |
| [ColinHu07/Chinese-poker](https://github.com/ColinHu07/Chinese-poker) | _(no description)_ | 0 | Swift |
| [ColinHu07/game-pigeon-meta1](https://github.com/ColinHu07/game-pigeon-meta1) | _(no description)_ | 0 | TypeScript |
| [ColinHu07/hackmit-](https://github.com/ColinHu07/hackmit-) | _(no description)_ | 0 | TypeScript |
| [danq54/rayban-snake](https://github.com/danq54/rayban-snake) | A lightweight Snake game for Meta Ray-Ban Display, built for additive display and Neural Band/D-pad controls. | 0 | JavaScript |
| [Dinco-MrT/Dinco-MrT.github.io](https://github.com/Dinco-MrT/Dinco-MrT.github.io) | Web apps and games for my Meta Ray-Ban Display glasses | 0 | HTML |
| [ehartye/rogue-vision](https://github.com/ehartye/rogue-vision) | FOGFALL: an offline wrist-controlled roguelike for Meta Ray-Ban Display, set in San Francisco. | 0 | JavaScript |
| [FireDragonGameStudio/mrbd-cube](https://github.com/FireDragonGameStudio/mrbd-cube) | _(no description)_ | 0 | JavaScript |
| [germanvargasn/SpaceCommander](https://github.com/germanvargasn/SpaceCommander) | Meta Ray Ban Display Space Shooter Game | 0 | JavaScript |
| [glasses12345/rayban-rummy-counter](https://github.com/glasses12345/rayban-rummy-counter) | Card counting strategy app for Meta Ray-Ban displays - Rummy/Gin Rummy optimization | 0 | JavaScript |
| [JarJarMadeIt/flappy-bird-clone](https://github.com/JarJarMadeIt/flappy-bird-clone) | A Meta Ray-Ban Display app built with GlassKit Studio | 0 | TypeScript |
| [jigglypop/golf-onefield](https://github.com/jigglypop/golf-onefield) | golf-onefield | 0 | Rust |
| [jjang20/catapult-glass](https://github.com/jjang20/catapult-glass) | Fortris-style game for Meta Rayban Display | 0 | JavaScript |
| [JohnRainier/snake-classic](https://github.com/JohnRainier/snake-classic) | Snake classic — neural-band compatible (1-pinch = turn right, long-pinch = turn left). Built for Meta Ray-Ban Display. | 0 | HTML |
| [jscmp4/walkpit](https://github.com/jscmp4/walkpit) | Walking companion for Meta Ray-Ban Display, fighter-jet cockpit HUD style. | 0 | JavaScript |
| [Kosmas5665/blackjack-glasses](https://github.com/Kosmas5665/blackjack-glasses) | Blackjack web app for the Meta Ray-Ban Display glasses | 0 | HTML |
| [LiquidAzir/glasspire](https://github.com/LiquidAzir/glasspire) | _(no description)_ | 0 | JavaScript |
| [LiquidAzir/glasspitch](https://github.com/LiquidAzir/glasspitch) | Glass Pitch — holographic arcade soccer for Meta Ray-Ban Display glasses (vanilla HTML/CSS/JS) | 0 | JavaScript |
| [LiquidAzir/glassrealm](https://github.com/LiquidAzir/glassrealm) | GlassRealm — a 3D RuneScape-like open-world RPG for Meta Ray-Ban Display glasses (Three.js). | 0 | JavaScript |
| [LiquidAzir/meta-display-pet](https://github.com/LiquidAzir/meta-display-pet) | Tamagotchi-style virtual pet webapp for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [Ludoxon/Beclipsed](https://github.com/Ludoxon/Beclipsed) | Space themed bejeweled for Meta Ray-Ban Display | 0 | JavaScript |
| [Ludoxon/geometry-survivors](https://github.com/Ludoxon/geometry-survivors) | Geometry Survivors for the Meta Ray-Ban Display | 0 | JavaScript |
| [Ludoxon/journey-of-the-cowboy](https://github.com/Ludoxon/journey-of-the-cowboy) | Journey of the Cowboy for Meta Ray-Ban Display | 0 | JavaScript |
| [Ludoxon/lens-of-war](https://github.com/Ludoxon/lens-of-war) | Lens of War for the Meta Ray-Ban Display | 0 | JavaScript |
| [Maitreya20/GameFit](https://github.com/Maitreya20/GameFit) | A gamified fitness web app designed for Meta Ray-Ban Display that turns real workouts into a *Solo Leveling-style Hunter System*. It uses device motion/gyroscope data and gestur… | 0 | HTML |
| [meshtimes/side-quest-club](https://github.com/meshtimes/side-quest-club) | Real-life side quests: turn errands into an RPG on Meta Ray-Ban Display | 0 | HTML |
| [mrtsm/2048-raybans](https://github.com/mrtsm/2048-raybans) | 🎮 Premium 2048 puzzle game optimized for Meta Ray-Ban Display (600x600) | 0 | HTML |
| [mrtsm/today-puzzle](https://github.com/mrtsm/today-puzzle) | Daily visual puzzle game for Meta Ray-Ban Display | 0 | HTML |
| [nicolachoquet06250/pong-meta-rayban-display-compatible](https://github.com/nicolachoquet06250/pong-meta-rayban-display-compatible) | création d'une web app du jeu "pong" mais compatible avec les meta rayban display et son neural band | 0 | TypeScript |
| [Opbagya/Classic-Snake](https://github.com/Opbagya/Classic-Snake) | Built retro Arcade game of Classic Snake for Meta RayBan Display Glasses, which can be played across multiple platform not just for MRBD | 0 | TypeScript |
| [rollinsio/gradioids](https://github.com/rollinsio/gradioids) | Vector asteroid shooter for Meta Ray-Ban Display glasses (MRBD web app) | 0 | JavaScript |
| [scottsigrist-a11y/Videopoker-v2](https://github.com/scottsigrist-a11y/Videopoker-v2) | _(no description)_ | 0 | TypeScript |
| [seanfitz96/MetaDisplayGame](https://github.com/seanfitz96/MetaDisplayGame) | A game for the Meta Display glasses | 0 |  |
| [sebastjanb/glassblocks](https://github.com/sebastjanb/glassblocks) | Falling-block puzzle for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [sebastjanb/glassdigger](https://github.com/sebastjanb/glassdigger) | Side-view sandbox: dig a seeded world three layers deep, craft gear, survive the dark and face the wyrm. | 0 | JavaScript |
| [sebastjanb/glassdrift](https://github.com/sebastjanb/glassdrift) | The car drives itself. Pinch to throw it sideways, link slides into chains, beat medal times and your ghost. | 0 | JavaScript |
| [sebastjanb/glassfreerun](https://github.com/sebastjanb/glassfreerun) | Sprint three lanes over rooftops, leap the gaps and slide under signs with a drone on your tail. | 0 | JavaScript |
| [sebastjanb/glassglider](https://github.com/sebastjanb/glassglider) | Thread low gate courses, manage energy through the bends and beat your own ghost for a medal. | 0 | JavaScript |
| [sebastjanb/glassgolf](https://github.com/sebastjanb/glassgolf) | Three courses: sea cliffs, red canyon and alpine lake. Aim, pinch for power and accuracy, ride the ball-cam. | 0 | JavaScript |
| [sebastjanb/glassmuncher](https://github.com/sebastjanb/glassmuncher) | Maze chase for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [sebastjanb/glassorbit](https://github.com/sebastjanb/glassorbit) | Anti-gravity racing on six orbital circuits against rivals. Tilt your head or swipe to steer. | 0 | JavaScript |
| [sebastjanb/glasspool](https://github.com/sebastjanb/glasspool) | Billiards with real spin and cushions. 8-ball against three opponents, 9-ball and trick shots. | 0 | JavaScript |
| [sebastjanb/glassrunner](https://github.com/sebastjanb/glassrunner) | Three-lane endless runner for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [sebastjanb/glasssentry](https://github.com/sebastjanb/glasssentry) | Raiders hold real compass headings around you. Look to aim, lock on, pick the weapon and keep the shield up. | 0 | JavaScript |
| [sebastjanb/glassserpent](https://github.com/sebastjanb/glassserpent) | Steer a serpent across a lit arena, eat crystals to grow and cut off rivals so they burst into food. | 0 | JavaScript |
| [sebastjanb/glasswing](https://github.com/sebastjanb/glasswing) | Twin-boom starfighter campaign in three sectors. Aim with your head or let assisted flight chase targets. | 0 | JavaScript |
| [smartglass-lab/dot-creature](https://github.com/smartglass-lab/dot-creature) | たまごっち風ドット育成ゲーム for Meta Ray-Ban Display — 遺伝で次世代へパーツを引き継ぐWebApp | 0 | JavaScript |
| [smartglass-lab/glass-blackjack](https://github.com/smartglass-lab/glass-blackjack) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-blocks](https://github.com/smartglass-lab/glass-blocks) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-crane](https://github.com/smartglass-lab/glass-crane) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-dungeon](https://github.com/smartglass-lab/glass-dungeon) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-echo](https://github.com/smartglass-lab/glass-echo) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-gomoku](https://github.com/smartglass-lab/glass-gomoku) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-hanoi](https://github.com/smartglass-lab/glass-hanoi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-hebi](https://github.com/smartglass-lab/glass-hebi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-hitblow](https://github.com/smartglass-lab/glass-hitblow) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-janken](https://github.com/smartglass-lab/glass-janken) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-klondike](https://github.com/smartglass-lab/glass-klondike) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-lifegame](https://github.com/smartglass-lab/glass-lifegame) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-make10](https://github.com/smartglass-lab/glass-make10) | グラステンパズル — Glass Make 10: Meta Ray-Ban Display 用テンパズル（4つの数字で10をつくる） | 0 | JavaScript |
| [smartglass-lab/glass-minesweeper](https://github.com/smartglass-lab/glass-minesweeper) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-mogura](https://github.com/smartglass-lab/glass-mogura) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-nonogram](https://github.com/smartglass-lab/glass-nonogram) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-pairs](https://github.com/smartglass-lab/glass-pairs) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-reversi](https://github.com/smartglass-lab/glass-reversi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-shiryoku](https://github.com/smartglass-lab/glass-shiryoku) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-sokoban](https://github.com/smartglass-lab/glass-sokoban) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-sudoku](https://github.com/smartglass-lab/glass-sudoku) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-timing](https://github.com/smartglass-lab/glass-timing) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-tsumiki](https://github.com/smartglass-lab/glass-tsumiki) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-tsuri](https://github.com/smartglass-lab/glass-tsuri) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/gurutto-shooter](https://github.com/smartglass-lab/gurutto-shooter) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/high-low-casino](https://github.com/smartglass-lab/high-low-casino) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/hikari-meiro](https://github.com/smartglass-lab/hikari-meiro) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/hikari-meiro-new](https://github.com/smartglass-lab/hikari-meiro-new) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/hikari-reflex](https://github.com/smartglass-lab/hikari-reflex) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/neon-2048](https://github.com/smartglass-lab/neon-2048) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/nod-beat](https://github.com/smartglass-lab/nod-beat) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/space-pinball](https://github.com/smartglass-lab/space-pinball) | _(no description)_ | 0 | JavaScript |
| [stato10/DrhoneGame](https://github.com/stato10/DrhoneGame) | _(no description)_ | 0 | JavaScript |
| [vrwithjasmine/flappy-postal-dude](https://github.com/vrwithjasmine/flappy-postal-dude) | Flappy Bird clone with POSTAL Dude for Ray-Ban Display | 0 | JavaScript |
| [wahhaj-anomaly/Ray-Ban-Meta-Display-Space-Shooter](https://github.com/wahhaj-anomaly/Ray-Ban-Meta-Display-Space-Shooter) | _(no description)_ | 0 | JavaScript |
| [webmanagments/cutup](https://github.com/webmanagments/cutup) | _(no description)_ | 0 | TypeScript |
| [webmanagments/kmr](https://github.com/webmanagments/kmr) | _(no description)_ | 0 | TypeScript |
| [webmanagments/kmr-bird](https://github.com/webmanagments/kmr-bird) | _(no description)_ | 0 | TypeScript |
| [webmanagments/kmr-snake](https://github.com/webmanagments/kmr-snake) | _(no description)_ | 0 | TypeScript |
| [x-union-kota/timee-pet](https://github.com/x-union-kota/timee-pet) | Meta Ray-Ban Display用たまごっち風Webアプリ | 0 | HTML |

## Video, music & media

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [fasaiph/score-scroll](https://github.com/fasaiph/score-scroll) | Auto-scrolling, beat-accurate sheet music for Meta Ray-Ban Display glasses 🎀🎻 | 5 | JavaScript |
| [worldjoe/FriendFinder](https://github.com/worldjoe/FriendFinder) | An iOS companion application for the Meta Display Glasses to remind you of your friend's names and information | 3 | Swift |
| [jaher/splat-glasses](https://github.com/jaher/splat-glasses) | Phone photo -> Gaussian-splat world (World Labs Marble) -> CPU-rendered JPEG stream to Meta Ray-Ban Display, Neural Band navigation | 1 | JavaScript |
| [NRPM/meta-video-streaming-android](https://github.com/NRPM/meta-video-streaming-android) | an app to stream videofrom the meta rayban display glasses to this app and then show the feed inside the app. | 1 | Kotlin |
| [1977744311/lenslive-ios](https://github.com/1977744311/lenslive-ios) | Turn Meta Ray-Ban Display into a POV livestream camera with an eyes-up danmaku monitor (iOS) | 0 | Swift |
| [adilanchian96/live-2d-glasses-viewer](https://github.com/adilanchian96/live-2d-glasses-viewer) | Live 2D Avatar on meta ray ban displays. | 0 | TypeScript |
| [amendezcauduro-bot/YouTube-Meta-Display](https://github.com/amendezcauduro-bot/YouTube-Meta-Display) | YouTube web app for Meta Ray-Ban Display | 0 | HTML |
| [anti-turtle-lab/anti-turtle-meta-hud](https://github.com/anti-turtle-lab/anti-turtle-meta-hud) | Open-source Meta Display posture HUD, telemetry relay, and native macOS posture notifications | 0 | JavaScript |
| [audiojoe4444/GladEyes](https://github.com/audiojoe4444/GladEyes) | A Plex client for Meta Ray Ban Display glasses | 0 | JavaScript |
| [audiojoe4444/GlassCast](https://github.com/audiojoe4444/GlassCast) | A podcast app for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [audiojoe4444/GlassTube](https://github.com/audiojoe4444/GlassTube) | YouTube on Meta Ray-Ban Display | 0 | JavaScript |
| [baklarrrr/tidal-glass](https://github.com/baklarrrr/tidal-glass) | Tidal now playing and controls on Meta Ray-Ban Display (web app half of Tidal Glass) | 0 | JavaScript |
| [BLOODCODEMUSIC/camelot-hud](https://github.com/BLOODCODEMUSIC/camelot-hud) | META RayBan Display App for DJ's that need a HUD of the Camelot Wheel. | 0 | HTML |
| [BLOODCODEMUSIC/scouter](https://github.com/BLOODCODEMUSIC/scouter) | A fun DBZ inspired Scouter App for the Rayban Display Glasses. | 0 | HTML |
| [chrisclawguitarte/rayban-youtube-display](https://github.com/chrisclawguitarte/rayban-youtube-display) | Meta Ray-Ban Display compatible YouTube web player launcher | 0 | JavaScript |
| [Chuchuisawesome/glasses-gallery](https://github.com/Chuchuisawesome/glasses-gallery) | Meta Ray-Ban Display image gallery Web App | 0 | JavaScript |
| [Claire-yuni/momo-lens-videos](https://github.com/Claire-yuni/momo-lens-videos) | Lens animation clips for Momo (Ray-Ban Display) | 0 |  |
| [DeepanshuSharma-BNB/meta-browser](https://github.com/DeepanshuSharma-BNB/meta-browser) | _(no description)_ | 0 | JavaScript |
| [DeepanshuSharma-BNB/Visor-Cinema](https://github.com/DeepanshuSharma-BNB/Visor-Cinema) | _(no description)_ | 0 | JavaScript |
| [DeepanshuSharma-BNB/Visor-Gallery-App](https://github.com/DeepanshuSharma-BNB/Visor-Gallery-App) | _(no description)_ | 0 | JavaScript |
| [dmartin3613-star/glasses-cinema](https://github.com/dmartin3613-star/glasses-cinema) | Open movie player for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [edgarcmtz/MRBDYT](https://github.com/edgarcmtz/MRBDYT) | YouTube for Meta Ray-Ban Display | 0 |  |
| [finley-Sun/drumMetronome](https://github.com/finley-Sun/drumMetronome) | _(no description)_ | 0 | Python |
| [GalacTechNyc/djay](https://github.com/GalacTechNyc/djay) | _(no description)_ | 0 | JavaScript |
| [GalacTechNyc/eyejam](https://github.com/GalacTechNyc/eyejam) | Make beats on Meta Ray-Ban Display glasses: step sequencer with g-WAVE sounds | 0 | JavaScript |
| [GalacTechNyc/YouTube](https://github.com/GalacTechNyc/YouTube) | _(no description)_ | 0 | JavaScript |
| [Gio53/manet-glasses-player](https://github.com/Gio53/manet-glasses-player) | Jellyfin music player for Meta Ray-Ban Display glasses | 0 | HTML |
| [itsashishupadhyay/Meta_Smartglasses_Mission_control](https://github.com/itsashishupadhyay/Meta_Smartglasses_Mission_control) | _(no description)_ | 0 | Swift |
| [izyman20/photodrop](https://github.com/izyman20/photodrop) | _(no description)_ | 0 | HTML |
| [JarJarMadeIt/short-video-feed](https://github.com/JarJarMadeIt/short-video-feed) | A Meta Ray-Ban Display app built with GlassKit Studio | 0 | TypeScript |
| [lightsailvr/BirdJournal](https://github.com/lightsailvr/BirdJournal) | Bird identification on Meta Ray-Ban Display glasses | 0 | Swift |
| [LiquidAzir/book-reader](https://github.com/LiquidAzir/book-reader) | Book Reader for Meta Ray-Ban Display — 70K+ Project Gutenberg classics, D-pad navigation, adjustable text size, resume-on-page | 0 | JavaScript |
| [LiquidAzir/youtube-viewer](https://github.com/LiquidAzir/youtube-viewer) | YouTube viewer web app for Meta Ray-Ban Display smartglasses | 0 | JavaScript |
| [ma9197/gt-view](https://github.com/ma9197/gt-view) | Personal YouTube viewer | 0 | JavaScript |
| [mikeshobes718/glasstube](https://github.com/mikeshobes718/glasstube) | YouTube on Meta Ray-Ban Display glasses | 0 | JavaScript |
| [NayanVangala/argon4hack](https://github.com/NayanVangala/argon4hack) | _(no description)_ | 0 | Python |
| [nbarkhina/MovieTest](https://github.com/nbarkhina/MovieTest) | _(no description)_ | 0 | JavaScript |
| [paybackday/Gorenslation](https://github.com/paybackday/Gorenslation) | Gorenslation – Watch any movie with live translated subtitles on Meta Ray-Ban Display. | 0 | HTML |
| [plasticfrog/Rundown](https://github.com/plasticfrog/Rundown) | _(no description)_ | 0 | JavaScript |
| [powl-stack/meta](https://github.com/powl-stack/meta) | Meta streaming | 0 | HTML |
| [qiringji/rayban-sheet-music](https://github.com/qiringji/rayban-sheet-music) | Display sheet music on Meta Ray-Ban glasses using the Display API | 0 | Python |
| [r4455s/lrt-radio-display](https://github.com/r4455s/lrt-radio-display) | LRT radijas | 0 | HTML |
| [robinvidelaine/twitch-for-rayban-display](https://github.com/robinvidelaine/twitch-for-rayban-display) | Standalone Twitch web client for Meta Ray-Ban Display — focused exclusively on Twitch, with Neural Band navigation, followed channels, browsing, fullscreen viewing and optional … | 0 | JavaScript |
| [RyLaptop/meta-glasses-yt](https://github.com/RyLaptop/meta-glasses-yt) | YouTube web app for Meta Ray-Ban Display glasses | 0 | HTML |
| [sebastjanb/plexglass](https://github.com/sebastjanb/plexglass) | Plex client web app for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [sebastjanb/tokglass](https://github.com/sebastjanb/tokglass) | TikTok web app for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [smartglass-lab/glass-metronome](https://github.com/smartglass-lab/glass-metronome) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-tube](https://github.com/smartglass-lab/glass-tube) | YouTube動画プレイヤー for Meta Ray-Ban Display — D-pad操作で視聴・お気に入り・動画追加 | 0 | JavaScript |
| [smklein83/glasses-player](https://github.com/smklein83/glasses-player) | _(no description)_ | 0 | HTML |
| [smklein83/playlist-backup](https://github.com/smklein83/playlist-backup) | _(no description)_ | 0 | HTML |
| [tensor-frank/rbd-subscriptions](https://github.com/tensor-frank/rbd-subscriptions) | Your own YouTube subscription feed on Meta Ray-Ban Display — own API key, zero on-device API calls, per-channel capping | 0 | Python |
| [TheoTime01/Smart-Glasses-for-Livestreaming](https://github.com/TheoTime01/Smart-Glasses-for-Livestreaming) | _(no description)_ | 0 | TypeScript |
| [VexD1/Socials](https://github.com/VexD1/Socials) | A simple social video launcher for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [WillForEternity/Meta-Display-Youtube](https://github.com/WillForEternity/Meta-Display-Youtube) | _(no description)_ | 0 | JavaScript |
| [worldjoe/InstaForwarder](https://github.com/worldjoe/InstaForwarder) | Forwards Instagram reels and Tweets to an Instagram user. So that I can watch reels on my Meta Display glasses | 0 | JavaScript |
| [znichka-apps/glasscast-receiver](https://github.com/znichka-apps/glasscast-receiver) | _(no description)_ | 0 | JavaScript |

## Navigation, travel & maps

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [Baoku26/solvision](https://github.com/Baoku26/solvision) | _(no description)_ | 1 | JavaScript |
| [emthrology/metaglass_landmark_mvp](https://github.com/emthrology/metaglass_landmark_mvp) | Meta Ray-Ban Display 글래스용 랜드마크 방위 안내 HUD (MVP) — 단안 HUD + 폰 폴백, vanilla JS, 0 의존성 | 1 | JavaScript |
| [NayanVangala/bayvalleyhacks](https://github.com/NayanVangala/bayvalleyhacks) | A planetarium in your glasses: point your head anywhere and see the real stars, constellations, and planets in that exact direction on Meta Ray-Ban Display. Built for Bay-Valley… | 1 | Python |
| [VarunKapoor0/AnimusGlasses](https://github.com/VarunKapoor0/AnimusGlasses) | Point your glasses at any object. It identifies it, gives it a personality, and speaks to you in its own voice, through the glasses speakers. Built for Meta Ray-Ban Display Glas… | 1 | Kotlin |
| [7TanZ/RideHUD](https://github.com/7TanZ/RideHUD) | HUD displaying location of riders of your team | 0 | HTML |
| [akpersad/SnapCount](https://github.com/akpersad/SnapCount) | _(no description)_ | 0 | Swift |
| [aliahmed23/citibikear](https://github.com/aliahmed23/citibikear) | AR system for citibike docking | 0 | JavaScript |
| [ameralqraishi9-lang/meta-ati](https://github.com/ameralqraishi9-lang/meta-ati) | _(no description)_ | 0 | Swift |
| [Archiehere/skyfinder](https://github.com/Archiehere/skyfinder) | _(no description)_ | 0 | JavaScript |
| [audiojoe4444/waypoint](https://github.com/audiojoe4444/waypoint) | Navigation on Meta Ray-Ban Display Glasses | 0 | JavaScript |
| [bobbyhug/rotortrack](https://github.com/bobbyhug/rotortrack) | _(no description)_ | 0 | TypeScript |
| [CalvinSunHaoEn/speed-adaptive-MRD-poc](https://github.com/CalvinSunHaoEn/speed-adaptive-MRD-poc) | Samsung intern project | 0 | TypeScript |
| [chrisclawguitarte/rayban-disney-nearby](https://github.com/chrisclawguitarte/rayban-disney-nearby) | Meta Ray-Ban Display app for nearby Disneyland Resort wait times | 0 | JavaScript |
| [chrisclawguitarte/rayban-hud-display](https://github.com/chrisclawguitarte/rayban-hud-display) | _(no description)_ | 0 | JavaScript |
| [chrisclawguitarte/rayban-key-to-disneyland](https://github.com/chrisclawguitarte/rayban-key-to-disneyland) | _(no description)_ | 0 | JavaScript |
| [chrisclawguitarte/rayban-lakers-daily](https://github.com/chrisclawguitarte/rayban-lakers-daily) | Daily Lakers affirmation app for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [cmf2201/meta-glasses-test-app](https://github.com/cmf2201/meta-glasses-test-app) | _(no description)_ | 0 | JavaScript |
| [danplenicianu-dot/rbmd-gps-hud](https://github.com/danplenicianu-dot/rbmd-gps-hud) | GPS HUD web app prototype for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [danplenicianu-dot/rbmd-speed](https://github.com/danplenicianu-dot/rbmd-speed) | Minimal current speed web app for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [ericfrintu/CueCut](https://github.com/ericfrintu/CueCut) | _(no description)_ | 0 | JavaScript |
| [Flockmfg/Meta-display-run](https://github.com/Flockmfg/Meta-display-run) | _(no description)_ | 0 | JavaScript |
| [ginotonino/MetaDisplayNav](https://github.com/ginotonino/MetaDisplayNav) | Navigator for Meta Display glasses based on OpenStreet Map | 0 |  |
| [glasses12345/VisionCart](https://github.com/glasses12345/VisionCart) | _(no description)_ | 0 | TypeScript |
| [GorgeousBodge/meta-travel-deck](https://github.com/GorgeousBodge/meta-travel-deck) | UK walking and cycling directions with a street map, plus live train and bus times, for Meta Ray-Ban Display glasses. OpenStreetMap, National Rail and NextBuses data on Vercel. | 0 | JavaScript |
| [gregmarra/mbta-nearby](https://github.com/gregmarra/mbta-nearby) | _(no description)_ | 0 | JavaScript |
| [gu-023/mrd-map](https://github.com/gu-023/mrd-map) | Meta Ray-Ban Display 向け現在地マップ Web App | 0 | JavaScript |
| [ImperaBusinessServices/labellens](https://github.com/ImperaBusinessServices/labellens) | Personal-use iOS app: scan a food/medication label through Meta Ray-Ban Display glasses, get a personalized good/caution/avoid verdict on the lens | 0 | Swift |
| [Jayesh-27/RiderHUD](https://github.com/Jayesh-27/RiderHUD) | 3hr Hackathon Project for Meta Ray Ban Display Glasses | 0 | HTML |
| [johnsibert-power/Flangetorque](https://github.com/johnsibert-power/Flangetorque) | _(no description)_ | 0 | HTML |
| [justinjblythe-la/Rb-jobs](https://github.com/justinjblythe-la/Rb-jobs) | Jobs | 0 | HTML |
| [kaufmanbora-lang/sky-hop](https://github.com/kaufmanbora-lang/sky-hop) | _(no description)_ | 0 | JavaScript |
| [lazer7123/waypoint](https://github.com/lazer7123/waypoint) | Pins that stay where you left them - a web app for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [LindaHaviv/skyline-glasses](https://github.com/LindaHaviv/skyline-glasses) | Meta Ray-Ban Display webapp: point at an NYC building to see assessed value, ownership, recorded mortgages (ACRIS) and CMBS intel | 0 | JavaScript |
| [LittleRed311/compassRBMD](https://github.com/LittleRed311/compassRBMD) | Basic compass app for Meta Ray-Ban Display Glasses | 0 | HTML |
| [LT1506/TrailCompass](https://github.com/LT1506/TrailCompass) | Live hiking compass for Meta Ray-Ban Display | 0 | JavaScript |
| [M1K3LN/artemis](https://github.com/M1K3LN/artemis) | _(no description)_ | 0 | HTML |
| [maqbulh-git/quran-rayban-teleprompter](https://github.com/maqbulh-git/quran-rayban-teleprompter) | quran-rayban-teleprompter | 0 | JavaScript |
| [mn5st6kk2p-cmd/glasses-apps](https://github.com/mn5st6kk2p-cmd/glasses-apps) | Web apps for Meta Ray-Ban Display glasses (developer mode) | 0 | HTML |
| [MRBD-Apps/avelo](https://github.com/MRBD-Apps/avelo) | àVélo stations on Meta Ray-Ban Display — nearby bike stations, swipe to browse, live status. | 0 | TypeScript |
| [muanis/simplemtba](https://github.com/muanis/simplemtba) | _(no description)_ | 0 | JavaScript |
| [Neleac/fogofwAR](https://github.com/Neleac/fogofwAR) | _(no description)_ | 0 | JavaScript |
| [noctishowler/pocket-furry](https://github.com/noctishowler/pocket-furry) | Pocket Furry is a lightweight virtual companion app for Meta Display and mobile devices, featuring persistent needs, expressive animations, touch controls, and Neural Band inter… | 0 | JavaScript |
| [northstar-labs-ui/polyview](https://github.com/northstar-labs-ui/polyview) | Polymarket client for Meta Ray-Ban Display AR glasses | 0 |  |
| [pankajpreetsingh2007-bit/glance-recall](https://github.com/pankajpreetsingh2007-bit/glance-recall) | _(no description)_ | 0 | HTML |
| [prasanthsasikumar/AirControl](https://github.com/prasanthsasikumar/AirControl) | Control desktop apps with camera-based gestures - starting with phone-camera presentation control via a Chrome extension, expanding to Meta Ray-Ban glasses. Work in progress. | 0 | JavaScript |
| [pratikpoddar/creature-hunt-ios](https://github.com/pratikpoddar/creature-hunt-ios) | _(no description)_ | 0 | Swift |
| [RATHI-CAPITAL-VENTURES/rathi-fitness](https://github.com/RATHI-CAPITAL-VENTURES/rathi-fitness) | A personal gym app. iPhone-first, RIAKit's design language, readable by RIA. | 0 | Swift |
| [ServoCorp/StarlinkMetaGlasses](https://github.com/ServoCorp/StarlinkMetaGlasses) | Real-time Starlink satellite overlay for Meta Ray-Ban Display glasses. | 0 | HTML |
| [shandyG/rayban_geodemo](https://github.com/shandyG/rayban_geodemo) | _(no description)_ | 0 | JavaScript |
| [shandyG/RayBanDisplay_GeoDemo](https://github.com/shandyG/RayBanDisplay_GeoDemo) | _(no description)_ | 0 | JavaScript |
| [shreySodhi/astrolens](https://github.com/shreySodhi/astrolens) | Point-at-the-sky constellation guides for smart glasses (Meta Ray-Ban Display + Even Realities G2), over one shared astronomy engine | 0 | TypeScript |
| [shyam-barange/Wayline](https://github.com/shyam-barange/Wayline) | _(no description)_ | 0 | TypeScript |
| [smartglass-lab/glass-compass](https://github.com/smartglass-lab/glass-compass) | _(no description)_ | 0 | JavaScript |
| [twinkling-reality/dusky](https://github.com/twinkling-reality/dusky) | Turn web actions into augmented reality via WebMCP | 0 | TypeScript |
| [VexD1/Navigation](https://github.com/VexD1/Navigation) | Free navigation preview for Meta Ray-Ban Display | 0 | JavaScript |
| [Viraj-Dhuri/meta-display-compass](https://github.com/Viraj-Dhuri/meta-display-compass) | _(no description)_ | 0 | HTML |
| [yukina0122/shandya](https://github.com/yukina0122/shandya) | _(no description)_ | 0 | JavaScript |

## Health, fitness & accessibility

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [EElumba/DeepSign-](https://github.com/EElumba/DeepSign-) | _(no description)_ | 2 | Python |
| [amanshah0729/vision](https://github.com/amanshah0729/vision) | Meta Ray-Ban Display camera from an iPhone via Meta DAT, over Bluetooth, on a free Apple account. Plus a sensor protocol so glasses web apps can use the camera and mic. | 1 | Swift |
| [Ashish11828/fraudlens](https://github.com/Ashish11828/fraudlens) | FraudLens: accessible scam-prevention app for Meta Ray-Ban Display | 0 | HTML |
| [axe-fb/stepview](https://github.com/axe-fb/stepview) | Step Counter | 0 | JavaScript |
| [baklarrrr/gulzar](https://github.com/baklarrrr/gulzar) | Cook, make and draw, one step at a time, with big pictures and a voice. Tablet first; also Meta Ray-Ban Display. | 0 | JavaScript |
| [bobbyhug/newport-runcard](https://github.com/bobbyhug/newport-runcard) | _(no description)_ | 0 | JavaScript |
| [Branrulz/step-coach](https://github.com/Branrulz/step-coach) | Daily step-goal motivator for Meta Ray-Ban Display glasses (100 Apps Challenge) | 0 | TypeScript |
| [CarlKho-Minerva/itadaki-health](https://github.com/CarlKho-Minerva/itadaki-health) | _(no description)_ | 0 | TypeScript |
| [ColinHu07/chinese](https://github.com/ColinHu07/chinese) | _(no description)_ | 0 | Python |
| [coltyprimetime/green-slope](https://github.com/coltyprimetime/green-slope) | Set it on the green, hear the slope. Meta Ray-Ban Display web app. | 0 | HTML |
| [darks8587/OuraMRBD](https://github.com/darks8587/OuraMRBD) | _(no description)_ | 0 | JavaScript |
| [darksarai-sketch/oura-display](https://github.com/darksarai-sketch/oura-display) | Oura ring Sync | 0 | JavaScript |
| [darksarai-sketch/oura-display-live-kit](https://github.com/darksarai-sketch/oura-display-live-kit) | _(no description)_ | 0 | JavaScript |
| [Darshandegr8/rb-fitnessapp](https://github.com/Darshandegr8/rb-fitnessapp) | _(no description)_ | 0 | HTML |
| [DeepanshuSharma-BNB/3D-Show](https://github.com/DeepanshuSharma-BNB/3D-Show) | _(no description)_ | 0 | JavaScript |
| [dkndist/pogo600](https://github.com/dkndist/pogo600) | POGO KID 600 - Jump-and-Run im Commander-Keen-Stil fuer Ray-Ban Meta Display (600x600) | 0 | HTML |
| [Ebonylatrice/telepromter](https://github.com/Ebonylatrice/telepromter) | _(no description)_ | 0 | HTML |
| [GalacTechNyc/groupme](https://github.com/GalacTechNyc/groupme) | GroupMe chats on Meta Ray-Ban Display glasses | 0 | JavaScript |
| [ggoonnzzaallo/meta_display](https://github.com/ggoonnzzaallo/meta_display) | Web Apps for my Rayban Meta Display glasses | 0 | JavaScript |
| [Gio53/meta-display-telegram-viewer](https://github.com/Gio53/meta-display-telegram-viewer) | Telegram web client optimized for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [GorgeousBodge/meta-hub](https://github.com/GorgeousBodge/meta-hub) | Hub containing all my apps | 0 | JavaScript |
| [Harsha0912/glasses-second](https://github.com/Harsha0912/glasses-second) | Static Meta Ray-Ban Display web app connector lab | 0 | JavaScript |
| [haydenpester1-dev/garmin-glasses-app](https://github.com/haydenpester1-dev/garmin-glasses-app) | _(no description)_ | 0 | Python |
| [HuanfuLi/LapSight](https://github.com/HuanfuLi/LapSight) | The ultimate mounted-phone timing instrument. LapSight runs natively on your phone to deliver precise telemetry and ghost-delta tracking. Built with high extensibility to suppor… | 0 | Kotlin |
| [jasvir0304/emergency---assist--mrbd](https://github.com/jasvir0304/emergency---assist--mrbd) | emergency assistance interface for meta ray ban display | 0 | HTML |
| [kbaker827/hidratelens](https://github.com/kbaker827/hidratelens) | See your HidrateSpark water intake on Meta Ray-Ban Display glasses | 0 | TypeScript |
| [khiradlabs/ayah-lens](https://github.com/khiradlabs/ayah-lens) | Ayah Lens: a Meta hackathon prototype for following Quran recitation on display glasses | 0 |  |
| [KojiOkazaki/dat-link](https://github.com/KojiOkazaki/dat-link) | meta | 0 | HTML |
| [kstevica/glass-master](https://github.com/kstevica/glass-master) | Remote controller for Meta Ray Ban Display smart glasses | 0 | JavaScript |
| [LittleRed311/meditateonrbmd](https://github.com/LittleRed311/meditateonrbmd) | Meditate application for the Meta Rayban display glasses | 0 | JavaScript |
| [marked29/rb-meta-poc](https://github.com/marked29/rb-meta-poc) | _(no description)_ | 0 | JavaScript |
| [matthewplk/meta-joke-machine](https://github.com/matthewplk/meta-joke-machine) | A github pages hosted repository for hosting meta web app to utilize the Meta Display Glasses. | 0 | JavaScript |
| [milindshah17/RepPlay](https://github.com/milindshah17/RepPlay) | Just a vibecoded webapp for meta rayban display glasse | 0 | HTML |
| [mostfasalih57-alt/quran-reader](https://github.com/mostfasalih57-alt/quran-reader) | Quran reader for Ray-Ban Meta Display | 0 | JavaScript |
| [mostfasalih57-alt/quranreader](https://github.com/mostfasalih57-alt/quranreader) | Quran reader for Ray-Ban Meta Display | 0 | JavaScript |
| [Pickled-Oiled/work-instructions](https://github.com/Pickled-Oiled/work-instructions) | _(no description)_ | 0 | HTML |
| [ribamarliving-wq/gazelink-caregiver-lens](https://github.com/ribamarliving-wq/gazelink-caregiver-lens) | _(no description)_ | 0 | JavaScript |
| [rubenhekkens/xr-sneak-peeks](https://github.com/rubenhekkens/xr-sneak-peeks) | Five single-file three.js demos: gas-curtain physics sandbox, real FBX teardown, powers-of-ten silicon dive, audio-reactive terrain, holographic digital twin | 0 | HTML |
| [RuneDaRaven/runes-radar](https://github.com/RuneDaRaven/runes-radar) | _(no description)_ | 0 | HTML |
| [RuneDaRaven/runes-scroll](https://github.com/RuneDaRaven/runes-scroll) | Rune's Scroll — an arcane-night web app for the Meta Ray-Ban Display: Meta news, XR industry news, and a pop quiz. | 0 | HTML |
| [sebasnyc/nova-vision](https://github.com/sebasnyc/nova-vision) | HUD NOVA Display | 0 | JavaScript |
| [shashanksbharadwaj161/rayban-dataglove-hanoi](https://github.com/shashanksbharadwaj161/rayban-dataglove-hanoi) | Ray-Ban Meta Display + Pressure Data Glove Integration for rehabilitation and HCI research | 0 | Python |
| [smartglass-lab/breath-pacer](https://github.com/smartglass-lab/breath-pacer) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-posture](https://github.com/smartglass-lab/glass-posture) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-ryogae](https://github.com/smartglass-lab/glass-ryogae) | _(no description)_ | 0 | JavaScript |
| [Soumyadas09/Nudge-wearable](https://github.com/Soumyadas09/Nudge-wearable) | NUDGE — an accessibility-first wearable experience for Meta Ray-Ban Display that reduces cognitive overload and helps break the habit of reaching for your phone through simple, … | 0 | JavaScript |
| [stato10/fitnessMeta](https://github.com/stato10/fitnessMeta) | _(no description)_ | 0 | HTML |
| [stepansoukenik/gaeilge-live](https://github.com/stepansoukenik/gaeilge-live) | Live Translation between Irish and English for Meta Ray-Ban Display glasses | 0 | JavaScript |
| [tonygarciaentrepreneur/paradigm](https://github.com/tonygarciaentrepreneur/paradigm) | _(no description)_ | 0 | HTML |
| [Umang3211/recall-glasses](https://github.com/Umang3211/recall-glasses) | iOS companion for Recall, smart glasses that remember the people you meet. 1st Place, JacHacks SF 2026. | 0 | Swift |
| [vinithaerusu/silent-ar](https://github.com/vinithaerusu/silent-ar) | Silent AR: discreet, no-voice input prototype for AR glasses (Snap Spectacles + Meta Ray-Ban Display), runs in-browser. | 0 | JavaScript |
| [wcgalan714714/glasses-workout-companion](https://github.com/wcgalan714714/glasses-workout-companion) | _(no description)_ | 0 | HTML |
| [wcgalan714714/matrix-HUD](https://github.com/wcgalan714714/matrix-HUD) | _(no description)_ | 0 | CSS |
| [yuzhuang0629/momo-webapp](https://github.com/yuzhuang0629/momo-webapp) | _(no description)_ | 0 | TypeScript |

## Messaging, social & notifications

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [arnavvalvekar/meta-glasses-notes](https://github.com/arnavvalvekar/meta-glasses-notes) | _(no description)_ | 0 | Python |
| [Casyi/wildsignal](https://github.com/Casyi/wildsignal) | _(no description)_ | 0 | HTML |
| [chrisclawguitarte/rayban-hn-digest](https://github.com/chrisclawguitarte/rayban-hn-digest) | Meta Ray-Ban Display Hacker News digest app | 0 | JavaScript |
| [ethanmcconkie/gospel-glasses](https://github.com/ethanmcconkie/gospel-glasses) | Scripture browser for Meta Ray-Ban Display glasses | 0 | HTML |
| [gagulvardanyan92-tech/glasses-mic-ios](https://github.com/gagulvardanyan92-tech/glasses-mic-ios) | _(no description)_ | 0 | Swift |
| [gagulvardanyan92-tech/rayban-telegram](https://github.com/gagulvardanyan92-tech/rayban-telegram) | _(no description)_ | 0 | HTML |
| [KarstenJWise/BubbleGlass](https://github.com/KarstenJWise/BubbleGlass) | OpenBubbles notifications for meta display glasses | 0 |  |
| [likejesusjonas/kakaoalarm](https://github.com/likejesusjonas/kakaoalarm) | describe kakaoalarm | 0 | HTML |
| [mattwalak/Discord-WhatsApp-BridgeBot](https://github.com/mattwalak/Discord-WhatsApp-BridgeBot) | A Discord bot that delivers messages to and from WhatsApp group chats. Built so Matt can use Discord on his Meta Rayban Display glasses by tunneling through WhatsApp. Uses Whats… | 0 | TypeScript |
| [sebastjanb/signalglass](https://github.com/sebastjanb/signalglass) | Signal messages on Meta Ray-Ban Display glasses, through your own bridge | 0 | JavaScript |

## Productivity, utilities & everything else

| Repo | Description | ★ | Lang |
|---|---|---|---|
| [macedonga/visor](https://github.com/macedonga/visor) | A de-metaified Meta Glasses client. | 124 | Kotlin |
| [doubleMcyber/FaceConnectDemo](https://github.com/doubleMcyber/FaceConnectDemo) | AR Networking software for Meta Rayban Displays | 2 |  |
| [EnygmaINC/todoist-glasses](https://github.com/EnygmaINC/todoist-glasses) | Todoist task viewer for Meta Ray-Ban Display glasses | 2 | JavaScript |
| [mrbd-dev/mrbd](https://github.com/mrbd-dev/mrbd) | _(no description)_ | 2 | TypeScript |
| [arshmeets/ReminiSense](https://github.com/arshmeets/ReminiSense) | Recall - Networking Redefined | 1 | Jac |
| [DOGFOOFA/dogfoofa.github.io](https://github.com/DOGFOOFA/dogfoofa.github.io) | apps for my meta ray ban displays | 1 | HTML |
| [Duf1220/glbxr](https://github.com/Duf1220/glbxr) | GLB 3D viewer for Ray-Ban Meta Display | 1 | HTML |
| [Eazcee/knight-hacks-9](https://github.com/Eazcee/knight-hacks-9) | _(no description)_ | 1 | Python |
| [GOROman/naruebi-assets](https://github.com/GOROman/naruebi-assets) | NaruEbi character images for Ray-Ban Display DAT | 1 |  |
| [MikeDevBeddo/mrbd-stocks](https://github.com/MikeDevBeddo/mrbd-stocks) | Apple Stocks-style watchlist web app for Meta Ray-Ban Display glasses (600x600, D-pad only) | 1 | JavaScript |
| [Neleac/ARaARa](https://github.com/Neleac/ARaARa) | AR companion for Meta Ray-Ban Display | 1 | JavaScript |
| [RRfyOfficial/CARBON](https://github.com/RRfyOfficial/CARBON) | CARBON: A Meta Rayban Display Project to scan text quickly through glasses and paste to your devices seamlessly | 1 | Swift |
| [sebastianboscan/spot-glass](https://github.com/sebastianboscan/spot-glass) | See what a Boston Dynamics Spot robot sees, live on Meta Ray-Ban Display glasses. A Python relay for its body and thermal cameras. | 1 | Python |
| [WalsonK/Gauss-HUD](https://github.com/WalsonK/Gauss-HUD) | Self-hosted car dashboard for Meta Ray-Ban Display glasses: battery, charging and climate at a glance, plus a few PIN-protected remote commands. Open source, cost-aware, no poll… | 1 | TypeScript |
| [anoted/test_xr_app](https://github.com/anoted/test_xr_app) | _(no description)_ | 0 | Kotlin |
| [audiojoe4444/Halo](https://github.com/audiojoe4444/Halo) | _(no description)_ | 0 | JavaScript |
| [audiojoe4444/Shoptics](https://github.com/audiojoe4444/Shoptics) | _(no description)_ | 0 | HTML |
| [baklarrrr/battery-glass](https://github.com/baklarrrr/battery-glass) | Battery for Meta Ray-Ban Display: the glasses' and band's battery and what uses it | 0 | Python |
| [baklarrrr/quran-glass](https://github.com/baklarrrr/quran-glass) | Quran recitation, word by word, for Meta Ray-Ban Display (web app) | 0 | JavaScript |
| [baklarrrr/studio-glass](https://github.com/baklarrrr/studio-glass) | Bakar Studio at a glance for Meta Ray-Ban Display (web app; data arrives encrypted from the studio PC) | 0 | Python |
| [bloomdaye/rayban-mini-browser](https://github.com/bloomdaye/rayban-mini-browser) | My web app for Meta Ray-Ban Display | 0 | HTML |
| [BoilThis/RayBanDisplayDemo](https://github.com/BoilThis/RayBanDisplayDemo) | _(no description)_ | 0 | Kotlin |
| [brandon-irving/react-native-meta-raybans-](https://github.com/brandon-irving/react-native-meta-raybans-) | _(no description)_ | 0 | TypeScript |
| [brianscout/RecipeGuide](https://github.com/brianscout/RecipeGuide) | _(no description)_ | 0 | JavaScript |
| [bsharper/RadiaGlasses](https://github.com/bsharper/RadiaGlasses) | Radiacode in Meta Display Glasses | 0 | JavaScript |
| [chenqiu1024/MetaRaybanDisplayDemo](https://github.com/chenqiu1024/MetaRaybanDisplayDemo) | _(no description)_ | 0 | Kotlin |
| [chrisclawguitarte/rayban-dodger-gates](https://github.com/chrisclawguitarte/rayban-dodger-gates) | _(no description)_ | 0 | JavaScript |
| [chrisclawguitarte/rayban-revue-program](https://github.com/chrisclawguitarte/rayban-revue-program) | _(no description)_ | 0 | JavaScript |
| [chrisclawguitarte/rayban-rubiks-solver](https://github.com/chrisclawguitarte/rayban-rubiks-solver) | _(no description)_ | 0 | JavaScript |
| [chrisclawguitarte/rayban-walkpad-hud](https://github.com/chrisclawguitarte/rayban-walkpad-hud) | _(no description)_ | 0 | JavaScript |
| [christiancabp/CHARLI](https://github.com/christiancabp/CHARLI) | C.H.A.R.L.I.  Christian's Home Artificial Reasoning & Learning Inteligence | 0 | Python |
| [christopherwoon-dev/ray-ban-watchlist](https://github.com/christopherwoon-dev/ray-ban-watchlist) | _(no description)_ | 0 | HTML |
| [christopherwoon/ray-ban-watchlist](https://github.com/christopherwoon/ray-ban-watchlist) | _(no description)_ | 0 | HTML |
| [claudiobs07/CronometroMetaDisplay](https://github.com/claudiobs07/CronometroMetaDisplay) | _(no description)_ | 0 | TypeScript |
| [CodesbyRohit/Dastak](https://github.com/CodesbyRohit/Dastak) | _(no description)_ | 0 | JavaScript |
| [CodesbyRohit/FocusLens](https://github.com/CodesbyRohit/FocusLens) | _(no description)_ | 0 | JavaScript |
| [ColinHu07/bondimals-display](https://github.com/ColinHu07/bondimals-display) | Bondimals Nova display test for Meta Ray-Ban Display | 0 | HTML |
| [COwpert/Yardage](https://github.com/COwpert/Yardage) | _(no description)_ | 0 | HTML |
| [cpht18/Onewheel-Display](https://github.com/cpht18/Onewheel-Display) | going to have all the information from your onewheel app to the meta display glasses | 0 | CSS |
| [createdbymvw/yeet-your-thoughts](https://github.com/createdbymvw/yeet-your-thoughts) | A playful smart glasses app for writing or dictating a thought, burning it away, and letting it go. Built for Meta Ray-Ban Display with a procedural burn animation. | 0 | TypeScript |
| [daikiito-dk/Lookwright](https://github.com/daikiito-dk/Lookwright) | _(no description)_ | 0 | Rust |
| [darksarai-sketch/quran-display-reader](https://github.com/darksarai-sketch/quran-display-reader) | quran-display-reader | 0 | JavaScript |
| [DeepanshuSharma-BNB/View-Protein](https://github.com/DeepanshuSharma-BNB/View-Protein) | _(no description)_ | 0 | JavaScript |
| [DeepanshuSharma-BNB/WristVerse](https://github.com/DeepanshuSharma-BNB/WristVerse) | _(no description)_ | 0 | HTML |
| [dissdique/pandora](https://github.com/dissdique/pandora) | _(no description)_ | 0 | HTML |
| [donpark/Soundtext](https://github.com/donpark/Soundtext) | Soundtext: Displays sound and speech in text [PoC] | 0 | TypeScript |
| [emchu08/glance](https://github.com/emchu08/glance) | _(no description)_ | 0 | TypeScript |
| [ethanzhoucool/lookgrab](https://github.com/ethanzhoucool/lookgrab) | Look at an object, pinch, and a low-cost robot arm hands it to you. Open-source assistive robot built on Meta Ray-Ban Display and the SO-101 arm. | 0 |  |
| [flsourcing/Bypass-Market-Checker-Meta-Display](https://github.com/flsourcing/Bypass-Market-Checker-Meta-Display) | _(no description)_ | 0 | TypeScript |
| [forcewake/glass-mosaic](https://github.com/forcewake/glass-mosaic) | Liquid-glass mixed-media mosaic Web App for Meta Ray-Ban Display, with in-browser search | 0 | TypeScript |
| [forcewake/glasses-hfp-transcribe](https://github.com/forcewake/glasses-hfp-transcribe) | Android app: record Meta Ray-Ban Display glasses mic over Bluetooth HFP + local near-real-time transcription | 0 | Kotlin |
| [GabrielRodrigues-eld/FactoryLens](https://github.com/GabrielRodrigues-eld/FactoryLens) | _(no description)_ | 0 | Kotlin |
| [GabrielRodrigues-eld/RB-Display-DemoAPI](https://github.com/GabrielRodrigues-eld/RB-Display-DemoAPI) | _(no description)_ | 0 | JavaScript |
| [GabrielRodrigues-eld/RB-Display-DemoELD](https://github.com/GabrielRodrigues-eld/RB-Display-DemoELD) | Temporary DEMO | 0 | JavaScript |
| [GabrielRodrigues-eld/RB-Display-DemoMQTT](https://github.com/GabrielRodrigues-eld/RB-Display-DemoMQTT) | _(no description)_ | 0 | JavaScript |
| [gamberoferoce/sPARK](https://github.com/gamberoferoce/sPARK) | _(no description)_ | 0 | TypeScript |
| [GoldenRatio3/meta-display-app](https://github.com/GoldenRatio3/meta-display-app) | _(no description)_ | 0 | JavaScript |
| [gson2019/lens-xo-webapp](https://github.com/gson2019/lens-xo-webapp) | _(no description)_ | 0 | JavaScript |
| [haydenpester1-dev/market-glasses-app](https://github.com/haydenpester1-dev/market-glasses-app) | _(no description)_ | 0 | Python |
| [HuanfuLi/MR-Pilipala](https://github.com/HuanfuLi/MR-Pilipala) | The Pilipala web app built for Meta Rayban Display glasses. | 0 | JavaScript |
| [hyunishyun/conductor-](https://github.com/hyunishyun/conductor-) | _(no description)_ | 0 | HTML |
| [ImperaBusinessServices/glass-apps](https://github.com/ImperaBusinessServices/glass-apps) | Web apps for Meta Ray-Ban Display glasses | 0 | HTML |
| [infinitejung-dev/MetaGlass_Emotion](https://github.com/infinitejung-dev/MetaGlass_Emotion) | _(no description)_ | 0 | Kotlin |
| [islandascetic/glasses-orbit-sphere](https://github.com/islandascetic/glasses-orbit-sphere) | Meta Ray-Ban Display Web App prototype with Three.js orientation sphere | 0 | HTML |
| [jacktimko68-dev/Property-at-a-Glance](https://github.com/jacktimko68-dev/Property-at-a-Glance) | Allows you too see property information with Meta Display Glasses | 0 |  |
| [JaeTierce31/FlipSight](https://github.com/JaeTierce31/FlipSight) | _(no description)_ | 0 |  |
| [JAugustineFlory/metaDisplay-test](https://github.com/JAugustineFlory/metaDisplay-test) | _(no description)_ | 0 |  |
| [Jferg74/playclock](https://github.com/Jferg74/playclock) | _(no description)_ | 0 | JavaScript |
| [Jkrachenfels/spring-scale-glasses](https://github.com/Jkrachenfels/spring-scale-glasses) | Hooke's law spring scale as a Meta Ray-Ban Display web app (educational demo) | 0 | HTML |
| [JoeyWangTW/mrbd-scouter](https://github.com/JoeyWangTW/mrbd-scouter) | _(no description)_ | 0 | CSS |
| [josedv82/nba_schedule_meta_display](https://github.com/josedv82/nba_schedule_meta_display) | An app to access schedule related metrics for NBA teams fom the Meta Display glasses. | 0 | HTML |
| [josephiii/VISOR](https://github.com/josephiii/VISOR) | Senior Design Project for MIRA | 0 | Kotlin |
| [JoshJUNT/glasses](https://github.com/JoshJUNT/glasses) | _(no description)_ | 0 | HTML |
| [Jungmin-k3i/RayBan_00](https://github.com/Jungmin-k3i/RayBan_00) | LumenCue Android concert AR companion | 0 | Kotlin |
| [KhoaNguyen2149/MetaRayBanApps](https://github.com/KhoaNguyen2149/MetaRayBanApps) | KUAL Studios apps for Meta Ray-Ban Display glasses | 0 | TypeScript |
| [kryptonyt07/glasses-apps](https://github.com/kryptonyt07/glasses-apps) | _(no description)_ | 0 | HTML |
| [LakiThoto/wingmanweb](https://github.com/LakiThoto/wingmanweb) | PostNL delivery webapp for Meta Ray-Ban Display | 0 | JavaScript |
| [lilkimos/RAYBAN-CALCULATOR](https://github.com/lilkimos/RAYBAN-CALCULATOR) | For ray-ban meta display onyl | 0 | HTML |
| [maceip/ambient-link-meta](https://github.com/maceip/ambient-link-meta) | Ambient Link target for Meta Ray-Ban Display glasses: phone relay apps (iOS + Android), glasses web client, peek-card HUD UX. | 0 | Kotlin |
| [Manuel-dz/meta-rayban-display](https://github.com/Manuel-dz/meta-rayban-display) | Apps para MTRD | 0 | JavaScript |
| [Manuel-dz/Ninhongo-no-app](https://github.com/Manuel-dz/Ninhongo-no-app) | vocabulario de 800 palabras en japones | 0 | JavaScript |
| [michaelcummingsofficial/listlens](https://github.com/michaelcummingsofficial/listlens) | Put something in your cart, and it's checked off your list. Open-source engine for Meta Ray-Ban Display glasses. | 0 | Swift |
| [mikeshobes718/IronMath](https://github.com/mikeshobes718/IronMath) | _(no description)_ | 0 | TypeScript |
| [millarm/displayprototypes](https://github.com/millarm/displayprototypes) | Meta Display Glasses prototypes | 0 | JavaScript |
| [moringaiq2017-oss/makan-teleprompter](https://github.com/moringaiq2017-oss/makan-teleprompter) | _(no description)_ | 0 | JavaScript |
| [MRBD-Apps/jallume-ma-rue](https://github.com/MRBD-Apps/jallume-ma-rue) | Unofficial « J'allume ma rue » client for Meta Ray-Ban Display — turn on public street lighting on demand, hands-free. | 0 | TypeScript |
| [mrtsm/croatian-lens](https://github.com/mrtsm/croatian-lens) | Camera-based Croatian language learning for Meta Ray-Ban Display Glasses | 0 | HTML |
| [Neleac/BallKnower](https://github.com/Neleac/BallKnower) | NBA live score and play-by-play for Meta Ray-Ban Display | 0 | JavaScript |
| [nicolachoquet06250/test-meta-rayban-display-compatible-qrcode-webapp](https://github.com/nicolachoquet06250/test-meta-rayban-display-compatible-qrcode-webapp) | test d'une app compatible avec les meta rayban display | 0 | Kotlin |
| [noctishowler/neural-journal](https://github.com/noctishowler/neural-journal) | A journaling app for Meta Display with neural-band handwriting, swipe-password unlock, and date-searchable entries. | 0 | JavaScript |
| [noctishowler/noctis-view](https://github.com/noctishowler/noctis-view) | _(no description)_ | 0 | JavaScript |
| [noniloani/houses](https://github.com/noniloani/houses) | _(no description)_ | 0 | Kotlin |
| [obstinatedev/mrbd](https://github.com/obstinatedev/mrbd) | Meta RayBan Display Apps | 0 |  |
| [Pari2007/MetaRayBanDisplayHackathon](https://github.com/Pari2007/MetaRayBanDisplayHackathon) | _(no description)_ | 0 | HTML |
| [PatMekury/Tevari](https://github.com/PatMekury/Tevari) | _(no description)_ | 0 | Swift |
| [pretorialimited/hmard-web-hud](https://github.com/pretorialimited/hmard-web-hud) | _(no description)_ | 0 | JavaScript |
| [qqdds01478520-cell/aifactory-rayban](https://github.com/qqdds01478520-cell/aifactory-rayban) | Ray-Ban Display COO native app (voice QA + display + camera + remote debug bridge) | 0 | Swift |
| [rani43435/glancepay](https://github.com/rani43435/glancepay) | _(no description)_ | 0 | HTML |
| [rathod-dhruv/MetaRayBanDisplay-Learning](https://github.com/rathod-dhruv/MetaRayBanDisplay-Learning) | _(no description)_ | 0 | Kotlin |
| [richardbernard2026/Life-HUD](https://github.com/richardbernard2026/Life-HUD) | A Heads-up Display for day-to-day life for the Meta Ray-Ban displays | 0 | JavaScript |
| [S11001001/wearable-tiles](https://github.com/S11001001/wearable-tiles) | This is a quick reference to Riichi Mahjong tiles you may not be familiar with, designed for Meta Ray-Ban Display glasses. | 0 | TypeScript |
| [scottsigrist-a11y/my-meta-app](https://github.com/scottsigrist-a11y/my-meta-app) | _(no description)_ | 0 | TypeScript |
| [sebastianboscan/sebastianboscan.com](https://github.com/sebastianboscan/sebastianboscan.com) | This is my personal website! [UNDER CONSTRUCTION] | 0 | TypeScript |
| [shivshaktipragnesh-boop/angelpositions](https://github.com/shivshaktipragnesh-boop/angelpositions) | _(no description)_ | 0 | HTML |
| [shivshaktipragnesh-boop/nsestock](https://github.com/shivshaktipragnesh-boop/nsestock) | Meta RayBan Display Indian stock market web app | 0 | HTML |
| [simone-nicanor/rayban-webapp](https://github.com/simone-nicanor/rayban-webapp) | Web app per Meta Ray-Ban Display | 0 | TypeScript |
| [SlickTorpedo/glasses-apps](https://github.com/SlickTorpedo/glasses-apps) | My collection of apps I am trying out on the Meta Ray-Ban display! | 0 |  |
| [smartglass-lab/aozora-reader](https://github.com/smartglass-lab/aozora-reader) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-anzan](https://github.com/smartglass-lab/glass-anzan) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-aquarium](https://github.com/smartglass-lab/glass-aquarium) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-canvas](https://github.com/smartglass-lab/glass-canvas) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-checklist](https://github.com/smartglass-lab/glass-checklist) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-curling](https://github.com/smartglass-lab/glass-curling) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-dice](https://github.com/smartglass-lab/glass-dice) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-fractal](https://github.com/smartglass-lab/glass-fractal) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-habit](https://github.com/smartglass-lab/glass-habit) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-hinode](https://github.com/smartglass-lab/glass-hinode) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-hoshizora](https://github.com/smartglass-lab/glass-hoshizora) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-hotaru](https://github.com/smartglass-lab/glass-hotaru) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-interval](https://github.com/smartglass-lab/glass-interval) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kaimono](https://github.com/smartglass-lab/glass-kaimono) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kaleido](https://github.com/smartglass-lab/glass-kaleido) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kansan](https://github.com/smartglass-lab/glass-kansan) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kazoe](https://github.com/smartglass-lab/glass-kazoe) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kenban](https://github.com/smartglass-lab/glass-kenban) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kokki](https://github.com/smartglass-lab/glass-kokki) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kotowaza](https://github.com/smartglass-lab/glass-kotowaza) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-koyomi](https://github.com/smartglass-lab/glass-koyomi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-kuzushi](https://github.com/smartglass-lab/glass-kuzushi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-level](https://github.com/smartglass-lab/glass-level) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-morse](https://github.com/smartglass-lab/glass-morse) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-omikuji](https://github.com/smartglass-lab/glass-omikuji) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-onkan](https://github.com/smartglass-lab/glass-onkan) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-pedometer](https://github.com/smartglass-lab/glass-pedometer) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-periodic](https://github.com/smartglass-lab/glass-periodic) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-quiz](https://github.com/smartglass-lab/glass-quiz) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-recipe](https://github.com/smartglass-lab/glass-recipe) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-reflex](https://github.com/smartglass-lab/glass-reflex) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-shunkanshi](https://github.com/smartglass-lab/glass-shunkanshi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-sokudoku](https://github.com/smartglass-lab/glass-sokudoku) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-solar](https://github.com/smartglass-lab/glass-solar) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-stopwatch](https://github.com/smartglass-lab/glass-stopwatch) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-sunaba](https://github.com/smartglass-lab/glass-sunaba) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-takibi](https://github.com/smartglass-lab/glass-takibi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-tenji](https://github.com/smartglass-lab/glass-tenji) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-tenki](https://github.com/smartglass-lab/glass-tenki) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-vocab](https://github.com/smartglass-lab/glass-vocab) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-wairo](https://github.com/smartglass-lab/glass-wairo) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-warikan](https://github.com/smartglass-lab/glass-warikan) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-weather](https://github.com/smartglass-lab/glass-weather) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/glass-worldclock](https://github.com/smartglass-lab/glass-worldclock) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/hikari-niwa](https://github.com/smartglass-lab/hikari-niwa) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/hikari-omikuji](https://github.com/smartglass-lab/hikari-omikuji) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/hikari-pedometer](https://github.com/smartglass-lab/hikari-pedometer) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/kokoro-hanabi](https://github.com/smartglass-lab/kokoro-hanabi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/moji-musubi](https://github.com/smartglass-lab/moji-musubi) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/nemuri-noise](https://github.com/smartglass-lab/nemuri-noise) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/nod-vocab](https://github.com/smartglass-lab/nod-vocab) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/presen-prompter](https://github.com/smartglass-lab/presen-prompter) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/shizuku-tracker](https://github.com/smartglass-lab/shizuku-tracker) | _(no description)_ | 0 | JavaScript |
| [smartglass-lab/tsuki-yomi](https://github.com/smartglass-lab/tsuki-yomi) | _(no description)_ | 0 | JavaScript |
| [Smile-Jo/ARglass-test](https://github.com/Smile-Jo/ARglass-test) | _(no description)_ | 0 | JavaScript |
| [SPACELUX/glasses-camera-ios](https://github.com/SPACELUX/glasses-camera-ios) | Ray-Ban Display camera->solve iOS app | 0 | Swift |
| [SuperKyleJ/LoadInfoMini](https://github.com/SuperKyleJ/LoadInfoMini) | Load info view for the Meta Rayban Display glasses | 0 | HTML |
| [TeacherDannyVR/Calculator-Web-App](https://github.com/TeacherDannyVR/Calculator-Web-App) | Calculator app for Meta Ray Ban Display glasses. | 0 | JavaScript |
| [TeacherDannyVR/my-glasses-app](https://github.com/TeacherDannyVR/my-glasses-app) | First Meta Display Glasses app | 0 | HTML |
| [thebhanusingh/hackathon](https://github.com/thebhanusingh/hackathon) | _(no description)_ | 0 |  |
| [theonewhogrins/glassesgrimoire](https://github.com/theonewhogrins/glassesgrimoire) | Grimoire for Display Glasses | 0 | JavaScript |
| [thisconnor/mrbd](https://github.com/thisconnor/mrbd) | Web app building for Meta Ray-Ban displays | 0 | HTML |
| [Tienduyvo/immo-deals-glasses](https://github.com/Tienduyvo/immo-deals-glasses) | _(no description)_ | 0 | HTML |
| [trantuanminh1754/mrbd-gaze](https://github.com/trantuanminh1754/mrbd-gaze) | _(no description)_ | 0 | JavaScript |
| [trantuanminh1754/mrbd-gaze-2](https://github.com/trantuanminh1754/mrbd-gaze-2) | _(no description)_ | 0 | JavaScript |
| [usinergy/MRD_Flashcards](https://github.com/usinergy/MRD_Flashcards) | German Vocabulary Flashcards Web App for Meta Ray-Ban Display | 0 | JavaScript |
| [vedantlbhatt/heyblinky](https://github.com/vedantlbhatt/heyblinky) | Hey Clicky for Meta Ray Bans w/ Display | 0 | Kotlin |
| [vekbui96/cardlens](https://github.com/vekbui96/cardlens) | Pokemon card search & pricing Web App for Meta Ray-Ban Display glasses | 0 | TypeScript |
| [wcgalan714714/echomind-glasses](https://github.com/wcgalan714714/echomind-glasses) | Meta Ray-Ban Display glasses app | 0 | JavaScript |
| [x-union-kota/tozan-hud](https://github.com/x-union-kota/tozan-hud) | Meta Ray-Ban Display 用 登山HUD | 0 | HTML |
| [Youn-sik/meta-display-remote-iphone](https://github.com/Youn-sik/meta-display-remote-iphone) | Remote Control for meta ray ban display by iPhone | 0 | JavaScript |
| [yunho-c/meta-rayban-display-ocr](https://github.com/yunho-c/meta-rayban-display-ocr) | _(no description)_ | 0 |  |

## Contributing

Found one that's missing? Open a PR adding a row to the right section (keep each list sorted by stars), or open an issue with the link.

## How this list was built

GitHub repository search over ~20 queries (`"ray-ban display"`, `"rayban display"`, `"meta ray-ban display" in:readme`, `"neural band"`, `"device access toolkit" in:readme`, `topic:meta-ray-ban-display`, `meta-wearables`, …), ~1,100 candidates, READMEs fetched and pattern-matched, then hand-reviewed. Star counts are a snapshot at collection time.
