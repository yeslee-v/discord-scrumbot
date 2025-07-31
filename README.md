# 🧾 Discord scrumbot

> Fork this repository to receive automated standup alerts in your Discord server every day at 10:00 AM KST (UTC+9).

## 🔧 1. Create a Discord Webhook

- Go to your Discord channel → ⚙️ Settings → Integrations → Webhooks.
- Click “New Webhook”, give it a name (e.g. scrum-bot), and copy the Webhook URL.

## 🔐 2. Add the Webhook to GitHub Secrets

- In your forked repo, go to Settings → Secrets and variables → Actions.
- Click “New repository secret” and set:
  - Name: `DISCORD_WEBHOOK`
  - Secret: Paste the Webhook URL

## 🧪 3. Run Manually for Testing

- Go to the Actions Tab.
- Select “Discord Scrum Bot”.
- Click “Run workflow” to trigger it immediately.
