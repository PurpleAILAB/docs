# Decepticon Documentation

Mintlify-based documentation site for Decepticon.

## Local Development

```bash
# Install Mintlify CLI
npm i -g mintlify

# Run locally
cd decepticon-docs
mintlify dev
```

## Deployment

1. Push to GitHub
2. Go to [mintlify.com](https://mintlify.com)
3. Connect your GitHub repo
4. Deploy (free for public repos)

## Structure

```
decepticon-docs/
├── mint.json          # Configuration
├── docs/
│   ├── index.mdx      # Landing page
│   ├── vision.mdx     # Vision & goals
│   ├── status.mdx     # Project status
│   ├── roadmap.mdx    # Development roadmap
│   ├── philosophy.mdx # Design philosophy
│   ├── roe.mdx        # Rules of Engagement
│   └── llm-auth.mdx   # LLM authentication
└── public/
    ├── logo.svg
    └── favicon.svg
```

## Pages

| Page | Description |
|------|-------------|
| `/docs` | Landing - What is Decepticon |
| `/docs/vision` | Why we're building this |
| `/docs/status` | Current development status |
| `/docs/roadmap` | Future development plans |
| `/docs/philosophy` | Design decisions & trade-offs |
| `/docs/roe` | Safety guardrails system |
| `/docs/llm-auth` | Subscription-based LLM auth |
