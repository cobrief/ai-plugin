# Cobrief

Search European procurement data and manage your tender pipeline in a conversation with Claude.

[Cobrief](https://cobrief.com/en/) helps suppliers to the public sector find relevant tenders and write bids. This plugin connects Claude to your Cobrief workspace.

## What you can do

- **Find tenders.** Search public procurement notices from across Europe. Filter by keywords, CPV codes, country, buyer and deadline.
- **Assess a tender.** Read the notice details, estimated value, award and qualification criteria, Cobrief's summary and your workspace's relevance score, with links to the procurement documents.
- **Work your pipeline.** Review your inbox and pipeline, add and move tenders, record Go/No-go decisions and reasons, update contract values and loss reasons, and read or add internal comments.
- **Research the market.** With Cobrief Enterprise, explore public buyers, suppliers and contract awards, live and from the last 10 years.

Claude only changes something when you ask. Changes are saved under your name, with a link back to the tender in Cobrief. Claude can't delete anything.

## Requirements

- A Cobrief workspace. Market intelligence requires an Enterprise subscription.
- Your own Cobrief user. Claude gets the same access as your role in Cobrief, never more.

## Get started

1. Install the plugin.
2. Connect Cobrief and sign in with your Cobrief user:
   - **Claude and Cowork:** open the plugin's **Connectors** tab, then add or connect Cobrief.
   - **Claude Code:** run `/mcp`, select the Cobrief server and sign in.
3. Ask the way you'd ask a colleague.

If Cobrief is already connected in Claude, the plugin uses that connection and you can skip step 2. On Claude Team and Enterprise, an Owner first adds the Cobrief connector for the organization.

Some things to try:

- "What's in my Cobrief inbox this week?"
- "Find cloud services tenders from Italian municipalities with a deadline after 1 December."
- "Summarize the requirements and award criteria in this tender."
- "Mark this tender as No-go. Reason: we don't have references from the health sector."
- "Which buyers published the most public tenders in Finland in 2025?" (Enterprise)

The full guide is in [Use Cobrief in Claude](https://help.cobrief.com/en/articles/880255-use-cobrief-in-claude).

## Install from GitHub

In Claude Code 2.1.275 or later, you can also install the plugin straight from this repository. Run this in a session:

```
/plugin install cobrief --marketplace cobrief/ai-plugin
```

## Data and privacy

- The plugin runs no code. It only tells Claude where to reach Cobrief: `https://mcp.cobrief.com/mcp`.
- When Claude uses a Cobrief tool, it sends that tool's input to Cobrief, such as your search terms or a comment you asked it to write. Cobrief returns data from your workspace. The plugin sends nothing anywhere else.
- You sign in through Cobrief. The plugin stores no passwords or keys.
- What Claude fetches from Cobrief becomes part of your conversation in Claude, where Anthropic's terms and privacy policy apply.
- Cobrief logs which tool was used, by whom, in which workspace and which tenders were changed. Cobrief doesn't log what you search for or what Claude gets back.

Read more in Cobrief's [privacy policy](https://cobrief.com/en/legal/privacy-policy/) and [Trust Center](https://trust.cobrief.com).

## Help

- [Contact Cobrief](https://cobrief.com/en/contact/)
- [Security at Cobrief](https://cobrief.com/en/security/)

## License

[MIT](LICENSE)
