# Harnes.xyz

## Getting Started

### 1. Install Dependencies

This project uses [pnpm](https://pnpm.io/) as the package manager.

```sh
pnpm install
```

### 2. Run in Development Mode
Start the development server:

```sh
pnpm run dev
```

The app will be available at http://localhost:5173 by default.

### 3. Build for Production
To build the project:

```sh
pnpm run build
```

To preview the production build locally:

```sh
pnpm run preview
```

### 4. Run with Docker
Build and run the Docker container:

```sh
docker build -t harnes-xyz .
docker run -p 3000:3000 harnes-xyz
```

The app will be available at http://localhost:3000.

## License
See LICENSE for details.