# Event Ticket

## Overview

> ### Next.js Event Ticket e-commerce portfolio project
>
> ### This project was initially generated from the [Next.js starter with Prisma, E2E testing, and ESLint (Recommended)](https://trpc.io/docs/example-apps).

## Table of Contents

1. [Run locally](#run-locally)
2. [License](#license)

## Run locally

You need have Node.js 20 or higher installed.

```sh
  # Clone the repository
  git clone git@github.com:zvolcsey/event-ticket-nextjs.git
  cd event-ticket-nextjs

  # Install dependencies
  pnpm install --frozen-lockfile
```

```sh
  # Create the .env from the .env.template
  cp .env.template .env
```

```sh
  # Run `docker compose up` with build in detached mode
  docker compose -f docker-compose.dev.yml up --build -d

  # Run `docker compose up` in detached mode
  docker compose -f docker-compose.dev.yml up -d

  # Stop and remove the containers
  docker compose -f docker-compose.dev.yml down
  # Remove all data
  docker compose -f docker-compose.dev.yml down -v
```

```sh
  # Run the project locally
  pnpm dev
```

## License

MIT
