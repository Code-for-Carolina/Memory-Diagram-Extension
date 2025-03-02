# Python Memory Debugger - VS Code Extension

A custom VS Code debugging extension that visualizes Python variables and memory structures in an interactive diagram. Instead of the standard debugger window, this extension opens a Memory Diagram Panel to help 110 students understand variable states and object references in real-time.

## Features
✅ **Custom Debug Window** – Replaces the default debugger with a visual representation of Python memory.
✅ **Live Variable Tracking** – Updates in real-time as you step through code.
✅ **Interactive UI** – Click on variables to expand memory details.
✅ **Seamless Debugger Integration** – Works alongside Python’s built-in debugging tools.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/ConorJones05/110MemoryDiagram.git
   cd python-memory-debugger
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Open in VS Code and run the extension in development mode:
   ```sh
   code --extensionDevelopmentPath=.
   ```

## Usage
1. Open a Python file in VS Code.
2. Start debugging using the **Python Memory Debugger**.
3. The **Memory Diagram Panel** will open beside the editor.
4. Step through your code to see live memory updates.

## Publishing to VS Code Marketplace
To package and publish the extension:
```sh
vsce package
vsce publish
```

## Contributing
Contributions are welcome! If you find a bug or have a feature request:
- Open an issue.
- Submit a pull request.

## License
This project is licensed under the **MIT License**.

