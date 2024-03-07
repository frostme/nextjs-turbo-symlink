## Demo
To show the error that occurs for a symlinked pages directory with turbo

1. `pnpm prepare` (symlinks the pages directory)
2. `pnpm dev --turbo` (to start the server)
3. Navigate to localhost:3000 and notice a 404

To troubleshoot this works without turbopack
1. `pnpm prepare` (symlinks the pages directory)
2. `pnpm dev` (to start the server)
3. Navigate to localhost:3000 and notice the index page is rendered
