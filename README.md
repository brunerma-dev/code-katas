# Code Katas Repository

This repository contains C# and TypeScript implementations of 10 programming katas for practice with TDD, clean code, and architecture.

## 🔧 Local DevBox Setup

### C#

```bash
cd csharp
dotnet restore
dotnet test
```

### TypeScript

```bash
cd typescript
npm install
npm test
```

### 💡 Recommended Extensions
See [.vscode/extensions.json](./.vscode/extensions.json)

## 🔧 Development Environment with GitHub Codespaces & VS Code Remote Containers
This project supports **GitHub Codespaces** and **Visual Studio Code Remote - Containers** for a consistent, containerized development experience.

### 🚀 Quick Start (GitHub Codespaces)
If you're using GitHub, simply click the "**Code**" button and choose "**Open with Codespaces**":
1. Select "**Create codespace on main**" (or your working branch)
2. GitHub will automatically build the development container as defined in [.devcontainer/devcontainer.json](./.devcontainer/devcontainer.json)
3. Once ready, your environment is preconfigured with all tools, extensions, and dependencies

> No local setup required — just write code!

### 🧩 Local Development (VS Code Remote Containers)
You can also run the containerized environment **locally** using VS Code:
1. **Prerequisites**
   - [Docker Desktop](https://www.docker.com/products/docker-desktop) installed and running
   - [Visual Studio Code](https://code.visualstudio.com/)
   - VS Code extension: [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
2. **Open the project in VS Code**
    ```bash
    git clone https://github.com/brunerma-dev/code-katas.git
    cd code-katas
    code .
    ```
3. **Reopen in Container**
   - Press `F1` and select: `Dev Containers: Reopen in Container`
   - VS Code will build the dev container based on `.devcontainer/devcontainer.json` and connect to it automatically 

### ⚙️ What’s Included in the Dev Container?
- Custom container or prebuilt image (e.g., `.NET`, `Node.js`, or both)
- Preinstalled tools and dependencies
- Recommended VS Code extensions
- Post-create setup commands (e.g., `dotnet restore`, `npm install`, etc.)

> 📁 See the [.devcontainer/](./.devcontainer/) folder for full configuration

### 🤝 Why Use This?
- No “works on my machine” issues
- Standardized environments across contributors
- Instant onboarding for new developers
- Clean separation of tools from your host OS


## 📄 Docs
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CHANGELOG.md](CHANGELOG.md)
- [LICENSE](LICENSE)