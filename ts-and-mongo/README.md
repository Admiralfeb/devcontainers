# TypeScript and MongoDb

This container is keyed towards React-based development.

## Usage

To use this container, copy the `devcontainer.recommended.json` to your project as `.devcontainer/devcontainer.json`.

Either have VSCode build the container or use the `devcontainer open` command to open your project in the container.

## Notes on devcontainer.recommended.json

The extensions listed are recommended as they are helpful. They include:

- eslint
- mongodb
- jest
- test-explorer
- prettier
- npm script

Activity on port `3000` will cause VSCode to prompt if you'd like to open your browser to that location.

The `postCreateCommand` is set to automatically install npm dependencies once the container is created.
