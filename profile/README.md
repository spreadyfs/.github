<p align="center">
  <img src="logo.png" width="96" alt="Spready">
</p>

<p align="center">
  <a href="https://spready.bitscorp.co">Open the workspace</a>
</p>

A team plans ideas, writes the post, and sends it on a schedule. The channels are Bluesky, Facebook, Google Business Profile, Instagram, LinkedIn, Mastodon, Pinterest, Substack, Threads, TikTok, X, and YouTube.

## On GitHub

[spready-mcp](https://github.com/spreadyfs/spready-mcp) is the public MCP server. Claude, Codex, and Grok can list the connected channels, save an idea, and queue a campaign, including LinkedIn.

```json
{
  "mcpServers": {
    "spready": {
      "command": "npx",
      "args": ["-y", "github:spreadyfs/spready-mcp"],
      "env": {
        "SPREADY_API_KEY": "sp_...",
        "SPREADY_BASE_URL": "https://spready.bitscorp.co"
      }
    }
  }
}
```

Create the key under Settings → API after you sign in.
