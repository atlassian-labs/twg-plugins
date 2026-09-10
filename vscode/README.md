# Atlassian Teamwork Graph CLI for VS Code

Bring your Atlassian work context into VS Code with Teamwork Graph CLI. It gives
you access to Jira issues, Confluence pages, Bitbucket pull requests, and other
connected work data from your terminal and coding agents.

## Set up Teamwork Graph

1. Open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on
   Windows and Linux).
2. Select **TWG: Set Up**.
3. Review the confirmation, then select **Continue**.
4. Complete the installation and sign-in steps in the **TWG Setup** terminal.

## What the extension does

- Opens a visible, interactive terminal and sends the official Teamwork Graph
  CLI installer command.
- Uses PowerShell on Windows and your normal shell on macOS and Linux.
- Leaves installation, OAuth sign-in, credential storage, skills, and health
  checks to the Teamwork Graph CLI.

The extension never collects credentials or runs a background installer.

## Requirements

- VS Code Desktop, or a remote VS Code workspace with a shell-backed terminal.
- An internet connection to download and authenticate Teamwork Graph CLI.

Learn more about [Teamwork Graph CLI](https://developer.atlassian.com/cloud/twg-cli/).
