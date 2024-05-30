# datafest2024

Repository for datafest2024

## 🚀 Usage

1. Make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed.
2. Launch it.
3. Clone this repository.
4. Open Terminal in the project folder and run:

```sh
docker-compose up --build
```

Running this for the first time may take some time to download all dependencies.
When it's ready you will see a "Jupyter Server is running" message in the terminal.

5. Go to [http://127.0.0.1:8888/lab/workspaces/auto-7/tree/volume](http://127.0.0.1:8888/lab/workspaces/auto-7/tree/volume)

## ✨ Misc

If you want, you can use [VS Code](https://code.visualstudio.com/) as developing environment.
You will need these extensions for it:

- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

When the Docker container is running go to the VS Code Command Palette by pressing `<kbd>`Ctrl `</kbd>` + `<kbd>`Shift `</kbd>` + `<kbd>`P `</kbd>`.

Select __Dev Containers: Attach to Running Container...__ and choose __/datafest2024__.

Enjoy!
