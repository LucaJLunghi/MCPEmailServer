# MCPEmailServer
My attempt at the Founders and Coders Foundation Project: MCP Server.


Building an end-to-end project is the best way to prepare for our programme. This foundation project is a simplified version of what you'll work on every week, so it's an excellent way for you to learn and for us to assess your readiness.

Your task: Build and deploy an MCP server that allows an AI assistant to read unread emails from a Gmail account and create draft replies.

What you'll need to understand:

The Model Context Protocol documentation, particularly how tools work as callable functions
Example MCP servers to see expected patterns
Gmail API setup: creating a Google Cloud project, enabling the API, configuring OAuth 2.0, and understanding scopes (gmail.readonly for reading, gmail.compose for drafts)
What you'll need to build:

## MCP Server (Python with mcp SDK or TypeScript with @modelcontextprotocol/sdk)
A get_unread_emails tool returning sender, subject, body/snippet, and email/thread ID

A create_draft_reply tool that accepts the original email/thread ID and reply body, creating a correctly threaded draft

## Working demo with Claude Desktop
Configure Claude Desktop to connect to your server locally

Document your claude_desktop_config.json configuration

Include example prompts and screenshots showing Claude reading emails and drafting replies

## GitHub repository with a README covering what the server does and how to run it locally

Stretch goal: Enhance your server by pulling in external context to help the AI write better replies, for example, an email style guide from Google Docs, reply templates from Notion, or files from a local knowledge base.
