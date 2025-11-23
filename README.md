# Endurance Manager

A modern, minimal, fully-dark-mode dashboard UI for an endurance sim racing management tool.
The tool helps teams plan race stints, calculate fuel needs, coordinate driver availability, and share setup files.

## Features

### 1. Dashboard

A central page combining:

-   **Stint Overview**: Table showing stint number, assigned driver, duration, expected laps, and fuel needed.
-   **Driver Stint Allocation**: Summary of total laps, driving time, and number of stints per driver.
-   **Fuel Calculator**: Inputs for tank capacity, fuel per lap, and lap time to output max laps and estimated stint time.

### 2. Availability Page

-   **Driver Availability**: Full-width timeline grid with 1-hour blocks.
-   **Visuals**: Dark mode grid with accent colors for availability.
-   **Conflict Detection**: Summary of total available hours and potential conflicts.

### 3. Setup Files

-   **File Management**: Drag-and-drop upload zone for car setups.
-   **Details**: File name, description, uploader, timestamp, and tags (e.g., Quali, Race, Dry, Wet).

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

## License

[MIT](LICENSE)
