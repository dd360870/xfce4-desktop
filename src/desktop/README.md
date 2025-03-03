
# Light-weight Desktop (desktop)

Adds a lightweight xfce4 based desktop to the container that can be accessed using a VNC viewer or the web. GUI-based commands executed from the built-in VS code terminal will open on the desktop automatically.

## Example Usage

```json
"features": {
    "ghcr.io/dd360870/xfce4-desktop/desktop:1": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Currently Unused! | string | latest |
| noVncVersion | The noVNC version to use | string | 1.2.0 |
| password | Enter a password for desktop connections. If "noPassword", connections from the local host can be established without entering a password | string | vscode |
| webPort | Enter a port for the VNC web client (noVNC) | string | 6080 |
| vncPort | Enter a port for the desktop VNC server (TigerVNC) | string | 5901 |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/dd360870/xfce4-desktop/blob/main/src/desktop/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
