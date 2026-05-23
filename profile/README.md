<div align="center">
  <a href="https://www.cosmicjs.com?utm_source=github-page">
    <img width="827" alt="Cosmic headless CMS" src="https://user-images.githubusercontent.com/1950722/229836793-0982e4bd-41e1-4efb-8f45-60758288654e.png">
  </a>

  <h1>Cosmic: The AI-Native Headless CMS</h1>

  <p>
    Build content-powered websites, apps, and AI agents with a flexible content API,
    AI generation built in, and a CLI that goes from idea to production in minutes.
  </p>

  <p>
    <a href="https://www.npmjs.com/package/@cosmicjs/sdk"><img src="https://img.shields.io/npm/v/@cosmicjs/sdk.svg" alt="npm"></a>
    <a href="https://www.npmjs.com/package/@cosmicjs/sdk"><img src="https://img.shields.io/npm/dm/@cosmicjs/sdk.svg" alt="downloads"></a>
    <a href="https://x.com/cosmicjs"><img src="https://img.shields.io/twitter/follow/cosmicjs?style=social" alt="X"></a>
  </p>

  <p>
    <a href="https://www.cosmicjs.com">Website</a> •
    <a href="https://www.cosmicjs.com/docs">Docs</a> •
    <a href="https://www.cosmicjs.com/templates">Templates</a> •
    <a href="https://www.cosmicjs.com/blog">Blog</a> •
    <a href="https://x.com/cosmicjs">X</a>
  </p>
</div>

---

## Why developers choose Cosmic

- **Content API**: A flexible REST and content API and toolkit backed by a fast, globally distributed CDN.
- **AI content generation**: Generate text, images, and video directly from the dashboard or via the SDK.
- **AI-powered CLI**: Manage content, media, deployments, and AI agents through natural language or direct commands.
- **MCP server**: Connect Cosmic content to Claude, Cursor, and any MCP-compatible client.
- **JavaScript SDK**: First-class TypeScript support for Node, browsers, and native apps.
- **Framework agnostic**: Works with Next.js, Astro, Remix, SvelteKit, React Native, or any framework.

## Get started in 30 seconds

```bash
npm install -g @cosmicjs/cli
cosmic login
```

Or [create an agent account with your AI assistant](https://www.cosmicjs.com/docs/agent-skills#agent-signup).

Or install the SDK in an existing project:

```bash
npm install @cosmicjs/sdk
```

```ts
import { createBucketClient } from "@cosmicjs/sdk";

const cosmic = createBucketClient({
  bucketSlug: "your-bucket-slug",
  readKey: "your-read-key",
});

const { objects: posts } = await cosmic.objects
  .find({ type: "posts" })
  .props(["slug", "title", "metadata"])
  .limit(10);
```

## Key repositories

- **[cosmic-sdk-js](https://github.com/cosmicjs/cosmic-sdk-js)**: Official JavaScript/TypeScript SDK.
- **[cli](https://github.com/cosmicjs/cli)**: AI-powered CLI for managing content, media, deployments, and agents.
- **[mcp](https://github.com/cosmicjs/mcp)**: Model Context Protocol server for Cosmic.
- **[skills](https://github.com/cosmicjs/skills)**: Agent skills for working with Cosmic content.
- **[cosmic-sdk-swift](https://github.com/cosmicjs/cosmic-sdk-swift)**: Swift SDK for iOS and macOS.

## Templates & examples

- **[simple-nextjs-blog](https://github.com/cosmicjs/simple-nextjs-blog)**: A blog powered by Next.js.
- **[simple-astro-blog](https://github.com/cosmicjs/simple-astro-blog)**: A blog powered by Astro.
- **[nextjs-developer-portfolio](https://github.com/cosmicjs/nextjs-developer-portfolio)**: Developer portfolio template.
- **[agency-template](https://github.com/cosmicjs/agency-template)**: Agency site built with Blocks.

Browse all [community projects on cosmicjs.com](https://www.cosmicjs.com/community/projects).

## Community

- **Docs**: [cosmicjs.com/docs](https://www.cosmicjs.com/docs)
- **Discord**: [Join Server](https://discord.com/invite/MSCwQ7D6Mg)
- **X / Twitter**: [@cosmicjs](https://x.com/cosmicjs)
- **Support**: support@cosmicjs.com
- **Status**: [status.cosmicjs.com](https://cosmicstatus.com)

## Contributing

We welcome contributions across all our repos. Each project has its own `CONTRIBUTING.md`. For bugs or feature requests, open an issue in the relevant repository.

---

<div align="center">
  <strong>Build content-powered apps faster. From idea to production in minutes.</strong>
</div>
