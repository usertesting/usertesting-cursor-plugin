# UserTesting for Cursor

Bring real customer feedback into Cursor.

Connect Cursor to UserTesting to bring real customer feedback into the way you plan, build, and make decisions. Turn a goal into a test plan, configure and launch a test using natural language, and retrieve results from your UserTesting workspace, all without leaving Cursor.

## What you can do

- **Go from question to launched test.** Tell Cursor what you want to learn and use UserTesting to create, configure, and launch a test, without breaking your workflow.
- **Validate as you build.** Gather customer feedback when questions come up, so you can test ideas, experiences, and decisions while the work is still in progress.
- **Bring customer evidence into your decisions.** Retrieve results from your UserTesting workspace to answer questions, uncover patterns, and ground your next move in real customer feedback.

## Setup

1. Add this plugin from the Cursor Marketplace, or add the MCP server manually:

   ```json
   {
     "mcpServers": {
       "usertesting": {
         "url": "https://ai.usertesting.com/mcp"
       }
     }
   }
   ```

2. Authenticate with your UserTesting account when prompted (Auth0 login + consent screen).
3. Try asking Cursor: "show me my UserTesting accounts."

## Support

Questions? Reach out in #ask-data-platform (internal) or contact support@usertesting.com.
