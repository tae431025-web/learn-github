# learn-github
1. THINK & PLAN (System Architecture & Execution Design)
🎯 Architectural Overview & Tech Stack
To maximize the power of your Gemini Pro (leveraging its massive context window and file processing capabilities) without coding a heavy backend from scratch, we will design an Agentic Prompt Chaining Architecture. You can run this directly inside the Gemini interface, Google AI Studio, or via a simple Python/Node script if you choose to automate it later.

Core Controller (Master Brain): Google Gemini Pro (Handles orchestration, compliance auditing, and script generation).

Audio/Voice Generation AI: CapCut Desktop (Native TikTok voices, free) or ElevenLabs API (For premium, realistic voiceovers).

Visual/Video Generation AI: Kling AI, Luma Dream Machine, or Runway Gen-3 (For high-converting viral product visual b-rolls).

👥 Sub-Agent Roles (Configured inside Gemini Pro)
We will divide Gemini's logic into 4 specialized personas that talk to each other sequentially:

Agent 1: The Guard Dog (Policy & Trend Compliance)

Task: Scans the target product details against TikTok Shop standard guidelines. It ensures zero "overclaims" (e.g., changes "Cures acne instantly" to "Helps soothe acne-prone skin") and removes shadowban-triggering words.

Agent 2: The Viral Hook Copywriter

Task: Takes the safe product angles from Agent 1 and creates 3 high-retention "3-second hooks" designed to stop users from scrolling, followed by a high-conversion Call-to-Action (CTA) directing them to the pinned basket.

Agent 3: The Prompt & Asset Director

Task: Converts the approved script lines into highly optimized image/video generation prompts (in English) that you can copy-paste straight into video generation AIs.

Agent 4: The Self-Correction Auditor (The QA)

Task: Double-checks the final output of Agents 2 and 3. If it detects any compliance slips or generic AI phrasing, it runs a recursive loop to rewrite the content automatically before showing it to you.

📂 Folder & Resource Structure (For your Local Workspace)
Plaintext
tiktok-ai-flow/
│
├── 01-compliance/
│   └── tiktok_shop_rules.txt       # Drop TikTok policy documents here
│
├── 02-agents-config/
│   ├── master_orchestrator.txt    # The main prompt we will build
│   └── forbidden_words.json       # List of keywords that trigger TikTok bans
│
├── 03-input-products/
│   └── product_info.txt           # Put raw links, specs, or product descriptions here
│
└── 04-outputs/
    ├── final_scripts.md           # Ready-to-read video scripts with voiceover cues
    └── visual_prompts.txt         # Text prompts ready for image/video AI tools
📋 Step-by-Step Execution Plan
Phase 1 (Setup): Injecting TikTok Policy Guidelines into Gemini Pro's system instruction so it gains an absolute baseline awareness of what is illegal on the platform.

Phase 2 (Prompt Chaining): Creating the single master prompt that triggers the multi-agent execution flow (Input -> Compliance Verification -> Hook Strategy -> Visual Prompts Gen -> Final Audit).

Phase 3 (Self-Healing Loop): Defining strict logic constraints (e.g., “If word X is generated, immediately halt, wipe it, and substitute with word Y”).

🛑 2. WAIT (Awaiting Your Approval)
I have successfully mapped out the technical architecture, sub-agent roles, and execution flow for your TikTok Affiliate video factory using Gemini Pro.
