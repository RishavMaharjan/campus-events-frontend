# Campus Events Frontend

A web app for browsing campus events, built with React and TypeScript.
Users can view upcoming events, see event details, and register or log in.

## Features

- Home page and events listing
- Event cards showing details for each event
- Ticket counter for selecting the number of tickets
- Login and registration pages
- Shared navbar and footer across pages

## Tech Stack

- React
- TypeScript
- Vite
- ESLint

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm

### Installation

```bash
git clone https://github.com/RishavMaharjan/campus-events-frontend.git
cd campus-events-frontend
npm install
```

### Run locally

```bash
npm run dev
```

The app runs at http://localhost:5173 by default.

### Build for production

```bash
npm run build
```

## Project Structure

```
src/
  components/   EventCard, Navbar, Footer, TicketCounter
  pages/        Home, Events, Login, Register
  assets/       images and icons
public/         static files
```

## Status

Frontend only for now. No backend or API is connected yet.
