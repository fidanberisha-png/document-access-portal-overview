# 📁 Document Access Portal – Overview

> ⚠️ **Overview only.** The real project is private because it contains confidential information. This repository contains no source code or real data.

## Why
Share confirmation PDFs securely, so each person only sees the documents they are allowed to see.

## Workflow
```mermaid
flowchart LR
    A[Admin invites user] --> B[User sets own password]
    B --> C[Admin grants access]
    C --> D[Server checks access]
    D --> E[View / download PDF]
```

## Tech
Node.js · Server-side sessions

---

### 🤖 How it was built

Built through **vibe coding**: I came up with the idea, wrote the prompts, defined the parameters and requirements, and tested the result until the project worked correctly. The code was written with the help of AI (Claude).
