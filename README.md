# GraphIA - Interactive Operations Research Application

GraphIA is a web application that allows users to create, analyze, and share graphs for operations research. Users can manually input a graph or automatically generate one using an AI prompt, then perform various analyses and export the results to Word or PDF.

## Features

- Create graphs manually or via AI
- Graph analysis: planarity, cycles, shortest paths, flows, etc.
- Publish and share graphs
- Export to Word or PDF
- Chat with other users for advice and discussions

## Technologies

- Front-end: Next.js, React
- Back-end: Next.js API routes
- AI: OpenAI GPT (for automatic graph generation)
- Graph visualization: React Flow or vis-network
- Export: PDF/Word libraries (e.g., jsPDF, docx)

## Installation

1. Clone the repository

```bash
git clone https://github.com/laurentmwana/ro-graph-app/
```

2. Install dependencies

You can use **npm**, **pnpm**, or **bun**:

Using npm:

```bash
cd ro-graph-app
npm install
```

Using pnpm:

```bash
cd ro-graph-app
pnpm install
```

Using bun:

```bash
cd ro-graph-app
bun install
```

````
3. Add your API keys (e.g., OpenAI) in `.env.local`

4. Run the project

Using npm:
```bash
npm run dev
````

Using pnpm:

```bash
pnpm dev
```

Using bun:

```bash
bun run dev
```

```

The application will be accessible at `http://localhost:3000`

## Contributing

The application is public and open to contributions. To contribute:

1. Fork the repository
2. Create a branch for your feature or fix
3. Make your changes and commit
4. Open a Pull Request

## License

This project is licensed under the MIT License.
```
