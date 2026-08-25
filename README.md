# GRC Practice Lab

This repo is a single-page, browser-based **GRC Practice Lab**.

The main app lives in [`index.html`](./index.html). It opens as a full workspace where you can learn and practice governance, risk, and compliance tasks in one place.

## What this index is all about

[`index.html`](./index.html) is the entire lab experience:

- a landing page and dashboard
- guided onboarding in **Start Here**
- GRC references like **Frameworks** and **GRC Glossary**
- practice areas like **Practice Scenarios** and **Guided Missions**
- hands-on workspaces for **Assets**, **Risks**, **Controls**, **Treatments**, **Testing**, and **Reports**
- extra learning and job-prep sections like **Interview Prep**, **Projects**, and **Portfolio Builder**

It is designed for learning by doing, not just reading.

## Beginner quick start

1. Open [`index.html`](./index.html) in a browser.
2. Go to **Start Here**.
3. Click **Load Demo Data** if you want sample content to explore right away.
4. Walk through the normal GRC flow:
   - add **Assets**
   - identify **Risks**
   - create **Controls**
   - assign **Treatments**
   - run **Testing**
   - review **Reports**

If you are brand new, start with the demo data first. It makes the lab much easier to understand.

## Suggested learning path

- **Start Here** — learn the basics and the order of the lab
- **Frameworks** — browse common GRC frameworks and references
- **Glossary** — look up terms you do not know
- **Practice Scenarios** — test your understanding with examples
- **Guided Missions** — follow step-by-step practice tasks
- **Projects** — build your own GRC examples
- **Reports** — see the final output of your work

## How the lab works

- The lab runs fully in the browser.
- Your work is saved in browser storage (`localStorage`).
- You can back up or restore progress using the app’s export/import features.
- No build step is required for basic use.

## AI Command & WebLLM (Optional)

The lab includes an **AI Command** feature (marked as Beta) that can help you analyze your GRC data. It works in two modes:

### AI Command (Chat)
- Ask questions about your project (e.g., "How do these controls map to my risks?" or "What evidence do I need?")
- Receive AI-powered guidance and recommendations
- Upload files (policies, evidence) to analyze them
- Get help structuring your GRC program

### WebLLM: Local AI Model (Optional Setup)
- You can optionally enable **WebLLM** to run a language model locally in your browser using WebGPU.
- This means the model runs on your machine with no data sent to external servers.
- Go to **WebGPU Setup** to configure and initialize a local model.
- Once active, queries stay private and run off-device.

**Note:** WebLLM requires WebGPU support (available on recent browsers and GPUs). If unavailable, the lab falls back to the local analyst mode.

## Tips for beginners

- Start with a small sample project instead of trying to fill every section at once.
- Think in this order: **asset → risk → control → treatment → test → report**.
- Use the glossary whenever a term is unclear.
- If you get stuck, return to **Start Here**.
- Use **AI Command** if you are unsure how to structure a part of your GRC program.

