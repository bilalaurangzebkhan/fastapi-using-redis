# Globally Distributed High-Performance API

This project demonstrates how to build a fast, globally distributed API using Cloudflare Workers, HonoJS, Redis, and Next.js. The API is built for performance, scalability, and ease of use.

## Tech Stack

- **Cloudflare Workers**: Serverless execution environment for globally distributed code.
- **HonoJS**: Lightweight web framework for building fast and modern web applications.
- **Redis**: Fast, in-memory database for quick data retrieval and storage.
- **Next.js**: React-based framework for building fast and modern web apps.

## Overview

This project leverages the following tools and services:

- **Cloudflare Workers** for serverless deployment of API endpoints that are distributed globally, ensuring low-latency access no matter where users are located.
- **HonoJS** as the web framework for building the API with a minimal footprint.
- **Redis**, via [Upstash](https://console.upstash.com/redis/), for caching and storing API responses for high-performance and scalability.
- **Next.js** for building any front-end components, if needed.

### Links to resources:
- [Upstash Redis Documentation](https://console.upstash.com/redis/)
- [Getting started with HonoJS](https://hono.dev/docs/getting-started/vercel#_1-setup)
- [Shadcn UI Components](https://ui.shadcn.com/docs/components/command)
- [Cloudflare Workers Documentation](https://workers.cloudflare.com/)

## Getting Started

### Prerequisites

Before you start, ensure you have the following tools installed:

- [Node.js](https://nodejs.org/) and npm
- [Vercel CLI](https://vercel.com/docs/cli) (for deploying Next.js and Hono)
- Cloudflare account with access to Workers
- Upstash Redis for managing Redis instances

### Installation

**Clone the repository:**

   ```bash
   git clone https://github.com/bilalaurangzebkhan/fastapi-using-redis.git
   cd fastapi-using-redis
   npm install
   pnpm dev
   or 
   npm run dev
   ```

# Support With Star 😊
