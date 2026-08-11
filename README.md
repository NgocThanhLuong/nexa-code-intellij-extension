# NexaCode Studio

NexaCode Studio is a developer-focused AI coding-agent project. It explores a hybrid architecture where centralized orchestration coordinates planning, policy and agent state while an IntelliJ client performs explicit local execution against the developer workspace.

## Project website

This repository hosts the NexaCode project landing page via GitHub Pages.

Expected Pages URL after enabling Pages from the `main` branch root:

`https://ngocthanhluong.github.io/nexa-code-intellij-extension/`

## Run locally

No build step is required.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Enable GitHub Pages

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/ (root)`.
4. Save.

## Custom domain

The intended project domain is `nexacode.is-a.dev`.

Registration data:

```json
{
  "owner": {
    "username": "NgocThanhLuong"
  },
  "records": {
    "CNAME": "NgocThanhLuong.github.io"
  }
}
```

The site is intentionally positioned as a developer/software project and contains no pricing, subscription or commercial sales call-to-action.