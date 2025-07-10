# ECP simple markdown blog post viewer

This is a simple web app to view ECP protocol comments as Markdown blog posts.

## How to use

1. Open `index.html` in your browser.
2. Enter a valid ECP comment ID (a 32-byte hex string starting with `0x`, 66 characters total).
3. Click "Get Comment as Markdown post" to load and view the comment.
4. Or, click "Test with Sample Comment" to see a demo.

The app fetches the comment from the ECP contract on Base mainnet and renders it as a Markdown post. Replies are shown below via an embedded widget.

No wallet or login required. All code runs in your browser.
