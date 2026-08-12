# NexaCode Studio — Product Website

This repository hosts the public product website for **NexaCode Studio**, the IntelliJ experience of the NexaCode AI Agent Platform.

The product itself is developed in the private `ai-agent-platform` repository. This repository contains only the public-facing website and domain-registration files.

## What the website covers

- Product positioning and developer workflow
- IntelliJ-native experience
- Java control-plane and local-execution architecture
- Governed workspace tool categories
- Source-code retrieval and live IDE context
- Approval, audit, RBAC and workspace security boundaries
- Model-provider, self-hosting, scalability and observability strategy
- Honest active-development status and common questions

All capability claims are derived from the current platform source and documentation. The site intentionally avoids pricing, release-download and availability claims that are not yet part of the product.

## Run locally

No build step or dependency installation is required.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

The site is designed to deploy from the `main` branch root:

`https://ngocthanhluong.github.io/nexa-code-intellij-extension/`

GitHub repository settings:

1. Open **Settings → Pages**.
2. Choose **Deploy from a branch**.
3. Select `main` and `/ (root)`.
4. Save.

## Custom domain

The intended custom domain is `nexacode.is-a.dev`. Registration material lives under `is-a-dev/`.

Do not add a Pages `CNAME` file until the domain registration and DNS target are active.

## Content maintenance

Before advertising a new platform capability:

1. Verify that the implementation exists in `ai-agent-platform`.
2. Confirm its security and approval boundary.
3. Avoid presenting roadmap or partial functionality as generally available.
4. Update the relevant website section and FAQ when the user-facing contract changes.

## Project status

NexaCode Studio is an active, non-commercial software-development project. Broader packaging and release details will be published when available.
