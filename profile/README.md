<p align="center">
  <img src="logo.png" width="88" alt="Spready">
</p>

<h1 align="center">Spready</h1>

<p align="center">
  Your social media workspace. Write the post once, keep the queue honest, and send it to the channels you already use.
</p>

<p align="center">
  <a href="https://spready.bitscorp.co">spready.bitscorp.co</a>
</p>

The workspace is where a team plans ideas, writes the post, and sends it on a schedule. Channels include Bluesky, Facebook, Google Business Profile, Instagram, LinkedIn, Mastodon, Pinterest, Substack, Threads, TikTok, X, and YouTube.

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
