# Mermail Agent Skill: Crypto Market Alert & Automated Portfolio Tracker

## What the Skill Enables
This Mermail Agent Skill empowers autonomous AI agents to monitor incoming crypto market alerts, analyze trading signals, and execute or simulate automated portfolio management actions using Mermail's Agent Wallet and Secure Inbox via MCP (Model Context Protocol).

## How It Interacts with Mermail
* **Inbox Integration:** Listens, parses, and filters incoming emails containing market volatility alerts, trading signals, or price updates.
* **Agent Wallet Integration:** Interacts with the agent's secure cryptocurrency wallet to track balances, evaluate gas fees, and simulate or execute micro-transactions or asset rebalancing.

## Workflow from Start to Completion
1. **Trigger:** An incoming alert email arrives in the Mermail Inbox with a specific trading signal or price threshold breach.
2. **Parsing:** The AI agent reads the email content using the Mermail MCP inbox tool, extracting asset symbols, target prices, and action indicators.
3. **Validation & Wallet Check:** The agent queries the Mermail Agent Wallet to verify available funds and risk parameters.
4. **Execution/Notification:** The agent drafts an execution report, triggers a simulated portfolio adjustment, and sends an automated summary back through the secure inbox channel.

## Example Prompts and Expected Results
* **Prompt 1:** "Check my Mermail inbox for any new trading alert emails and show me the latest signal."
  * *Expected Result:* The agent scans the inbox, extracts the top alert (e.g., "BTC bullish breakout at $92,000"), and displays structured parameters.
* **Prompt 2:** "Evaluate the BTC signal against my Agent Wallet balance and prepare a portfolio adjustment report."
  * *Expected Result:* The agent queries the wallet balance, calculates a 5% allocation adjustment, and outputs a clear execution summary.
