# Bridge MVP

AI-powered bridge application built with Qwik and Cloudflare Pages.

## Tech Stack

- **Framework**: [Qwik](https://qwik.dev/) - Resumable, instant-loading web apps
- **Deployment**: Cloudflare Pages
- **Language**: TypeScript
- **Styling**: Tailwind CSS (utility classes)
- **API**: RESTful API with WebSocket support
- **State**: Qwik Signals and Context API

## Quick Start

```bash
# Install dependencies
bun install

# Run development server
bun run dev

# Build for production
bun run build.server

# Deploy to Cloudflare Pages
bun run deploy
```

## Project Structure

- `src/components/ui/` - Reusable UI components
- `src/lib/` - API client, types, auth context
- `src/routes/` - Page routes (file-based routing)

## Deployment

Built for Cloudflare Pages. Deployed to https://bridge.distributedelectrons.com

## License

MIT
