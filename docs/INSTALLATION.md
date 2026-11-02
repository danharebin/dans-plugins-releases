# Installing Dan's Plugins Manager

Dan's Plugins Manager gives you access to Obsidian plugins purchased through [Dan's Plugins](https://plugins.danharebin.com/store).

## 1. Install BRAT

1. Open **Obsidian**.
2. Navigate to **Settings → Community plugins** and enable community plugins if necessary.
3. Select **Browse**.
4. Search for **BRAT (Beta Reviewers Auto-update Tester)**, then install and enable it.

## 2. Add Dan's Plugins Manager

1. Open **Settings → BRAT**.
2. Under **Beta plugin list**, select **Add beta plugin**.
3. Paste this repository URL into the repository field:

   ```text
   https://github.com/danharebin/dans-plugins-releases
   ```

4. Select **Add plugin**.
5. Go to **Settings → Community plugins** and ensure **Dan's Plugins** is enabled.

## 3. Open the hub

- **Windows / Linux:** Open the command palette with **Ctrl + P**.
- **macOS:** Open the command palette with **Cmd + P**.
- **Android / iOS / iPadOS:** Open Obsidian's command palette using the mobile interface.

Search for **Dan's Plugins: Open hub** and select the command.

## 4. Sign in and install

1. Sign in with the email and password for your [Dan's Plugins store account](https://plugins.danharebin.com/store).
2. View the products available to your account.
3. Select **Install** for a purchased plugin or **Update** if a newer release is available.

The manager requires a network connection to authorize new downloads and update checks. Plugins that are already installed are intended to remain usable offline.

## Updates

The upcoming v1.1.0 manager checks for updates every 24 hours. You can always choose **Refresh / Check updates** to check manually.

In manager settings, **Automatically install plugin updates** is off by default. If an update involves a currently running plugin, the manager may ask you to stop or restart it before applying the update.

BRAT itself distributes updates to **Dan's Plugins Manager**; the manager handles authorized updates to **your purchased plugins**.

## Having trouble?

- Verify that BRAT and Dan's Plugins are enabled under Community plugins.
- Check that you're signed in with the account used at checkout.
- If you've just completed a purchase, refresh the manager's catalog.
- For assistance, email [support@danharebin.com](mailto:support@danharebin.com). Never email your password, payment card information, or private tokens.

The latest published manager files are available under [GitHub Releases](https://github.com/danharebin/dans-plugins-releases/releases). The repository root will also display the current compiled manager artifacts once the upcoming public release is finalized.
