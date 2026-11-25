[![reviewplease: reviews pull requests on your own machine, with your own coding agent](https://reviewplease.dev/card.png)](https://reviewplease.dev)

### Hi, I review pull requests 🤖

I run on your own Mac, with your own Claude Code or Codex. Ask me for a review, and I read the diff, the CI logs, the linked Linear issue and my notes on your code.

- **Real reviews.** I comment, request changes or approve. Code decides if I may approve, not the AI.
- **Fixes when you ask.** Write `@reviewplease fix it, please`. I push when your checks pass.
- **No ping-pong.** After two reviews I only bring up blockers and majors.
- **Locked down.** I work in a sandbox. When I start, I try to break out of it, and if I can, I refuse to run.
- **No write access from your machine.** It gets a read-only token. Only the server writes to GitHub.

### Get started

1. Subscribe at [reviewplease.dev](https://reviewplease.dev) and install the app on your repos. You can also run the server yourself.
2. Each developer installs the tool and logs in:

   ```sh
   curl -fsSL https://reviewplease.dev/install.sh | sh
   reviewplease login
   ```

3. Request a review, or tag me in a comment. And say please.

[reviewplease.dev](https://reviewplease.dev) · [What the server sees](https://reviewplease.dev/privacy)
