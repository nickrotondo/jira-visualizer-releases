# Jira Visualizer

Download the latest macOS build of **Jira Visualizer** — an interactive map of your
Jira epics and their ticket dependencies.

## What it does

- **Epic dashboard** — see every epic at a glance, each with a colored breakdown
  of its tickets across Backlog, Ready, In Progress, Done, and Aborted. Hide the
  epics you don't care about to keep the view focused.
- **Dependency graph** — open an epic to explore its tickets as an
  automatically-laid-out map. Tickets are colored by status and show their
  assignee; arrows show what blocks what. Hover a ticket to highlight everything
  connected to it, and click any ticket to jump straight to it in Jira.
- **Edit dependencies** _(new in 1.4.0)_ — add or remove "Blocks" links right in
  the graph: drag from one ticket to another to link them, or right-click to pick.
  Changes save to Jira instantly, with one-click Undo. Editing is opt-in and only
  appears if you have permission to link issues in Jira.
- **Native feel** — a Refresh button reconciles with Jira on demand, and the app
  follows your macOS light/dark appearance.

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
