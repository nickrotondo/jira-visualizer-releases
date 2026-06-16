# Jira Visualizer

Download the latest macOS build of **Jira Visualizer** — an interactive map of your
Jira epics and their ticket dependencies.

## Download

Open **[Releases](../../releases/latest)** and grab the dmg for your Mac:

- `Jira-Visualizer-<version>-arm64.dmg` — Apple Silicon (M-series)
- `Jira-Visualizer-<version>.dmg` — Intel

(Not sure which? Apple menu →  **About This Mac**.) Open the dmg and drag
**Jira Visualizer** to Applications. The app is signed and notarized by Apple, so
it opens with no security warnings.

## Updates

The app updates itself. When a new version is published here it downloads in the
background and offers to restart — no need to revisit this page.

## First launch

Click **Connect** and enter your own Atlassian details: your site URL
(`https://yourcompany.atlassian.net`), your email, and an API token
([create one](https://id.atlassian.com/manage-profile/security/api-tokens)), plus
the Jira project key to visualize. Your token is stored encrypted on your machine
and only ever goes to Jira.

---

_Build artifacts only — the application source is maintained in a separate private repository._