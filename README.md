# Raycast Extension Boilerplate

A minimal starter template for creating your own [Raycast](https://www.raycast.com/) extension on Windows. This boilerplate provides only the essential setup — no linters or tests included — making it easy to customize and extend for your specific needs.

## Features

- Pre-configured project structure
- Example command implementation
- Easy to customize and extend

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sphygmus/raycast-boilerplate.git
    cd raycast-boilerplate
    ```

2. **Install dependencies:**

    ```bash
    npm install
    # or
    bun install
    ```

3. **Link the extension to Raycast:**
    ```bash
    npm run dev
    # or
    bun run dev
    ```

## Usage

1. Open Raycast.
2. Search for your extension by its name.
3. Run the available commands.

## Development

- Create your command in the `commands` array in `package.json`. Read the Raycast Documentation for more information.
- Edit the source files in the `src` directory.
- Use `npm run dev` to watch for changes and reload the extension automatically.

## Resources

- [Raycast Extensions Documentation](https://developers.raycast.com/)
- [Raycast API Reference](https://developers.raycast.com/api-reference)

---

Feel free to customize this boilerplate to fit your needs!
