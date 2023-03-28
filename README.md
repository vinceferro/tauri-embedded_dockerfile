# Tauri Embedded Dockerfile
This is a Dockerfile that can be used to build a Docker image that contains all the tools needed to build a Tauri application.

It contains the following tools:
- Node.js
- Rust
- Tauri CLI
- Tauri Dependencies

This image can be used as devcontainer in VSCode to enhance the development experience.

## Usage
### Docker
To build the image, run the following command:
```bash
docker build -t tauri .
```

Or pull the build image from Docker Hub:
```bash
docker pull thev/tauri-embedded
```