# PERT Calculator

## How It Works

The app calculates project estimates using the PERT method:

`PERT = (optimistic + 4 × realistic + pessimistic) / 6`

Then it applies:

- a **familiarity mode** multiplier
- a **buffer risk** percentage
- the **hourly rate**

Familiarity modes:

- **FAMILIAR** — multiplier `1.0`
- **MODERATE** — multiplier `1.3`
- **FIRST TIME** — multiplier `1.7`

## How to Use

- add a new task
- delete a task
- edit the task title
- edit optimistic, realistic, and pessimistic hours
- change the hourly rate
- change the buffer risk
- cycle the familiarity mode for each task

## Quick Start

### Requirements

- Node.js
- Rust
- Tauri prerequisites for macOS

### Install dependencies

```bash
npm install
```

### Run in development

```bash
npm run tauri dev
```

### Run tests

```bash
npm run test
```

### Build frontend

```bash
npm run build
```

### Build the desktop app

```bash
npm exec tauri build
```

## Tech Stack

- Tauri 2
- React
- TypeScript
- Tailwind CSS
- Vite
- Vitest
