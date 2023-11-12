# WhatsApp Clone with Next-Nest-Socket-PeerJS-Prisma

This repository contains a comprehensive WhatsApp clone built with modern technologies like Next.js, NestJS, Socket.IO, PeerJS, and Prisma. It's designed to emulate WhatsApp's key features such as real-time messaging, voice, and video calls using a JavaScript/TypeScript stack.

## Getting Started

To set up the project, clone the repository and install the necessary dependencies:

```sh
git clone https://github.com/Cypherfelix/whatsapp-clone-next-nest-socket-webrtc-prisma.git
cd whatsapp-clone-next-nest-socket-webrtc-prisma
npm install
```

## Project Structure

The project is organized as a monorepo with several integral applications and libraries:

### Client Application: Web Frontend ([`apps/web`](apps/web))

- **Next.js Framework**: Uses Next.js for React-based frontend development, server-side rendering, and SEO optimization.
- **Real-Time Communication**: Integrates Socket.IO for messaging and PeerJS for WebRTC-based peer-to-peer voice and video calls.
- **Tailwind CSS**: Tailwind CSS is used for a responsive and modern user interface.

### Server Application: Nest Backend ([`apps/backend`](apps/backend))

- **NestJS Backend**: A robust NestJS backend handling API requests, real-time WebSocket connections, and database operations.
- **Socket.IO**: Manages WebSocket connections for instant messaging and event-driven communication.
- **Prisma ORM**: Utilizes Prisma for database management, ensuring efficient data storage and retrieval.

### Shared UI Library (`common-ui`)

- **React Components**: A library of reusable React components, styled with Tailwind CSS for consistency across the client application.

### Real-Time Communication Library (`realtime-communication`)

- **PeerJS Integration**: Facilitates WebRTC peer-to-peer connections using PeerJS, enabling high-quality voice and video communication in the client app.

### Database Configuration (`database-config`)

- **Prisma Schema**: Houses the Prisma schema, defining database models and relationships, crucial for the application's data management.

## Building and Running

Detailed instructions on building and running each component within the monorepo, including specific steps for the `apps/web` and `apps/backend` directories.

## Configuration

Comprehensive setup guidelines, including configuring environment variables, database connections, PeerJS settings, and more.

## Technologies and Tools

- **Tailwind CSS**: For modern, responsive design.
- **TypeScript**: Enhances development with type safety.
- **ESLint and Prettier**: Used for code linting and formatting, ensuring code quality and consistency.

## Contributing

Guidelines for contributing to the project, including standards for coding, pull requests, and code reviews.

## License


