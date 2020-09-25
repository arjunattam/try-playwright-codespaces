# Use Playwright in Codespaces

This repo is configured with [devcontainer.json](.devcontainer/devcontainer.json) to run Playwright on Chromium, Firefox and WebKit inside GitHub Codespaces. 

## Usage

To run browsers in headless mode, run the script with Node.js

```
node index.js
```

To run browsers in headful mode, use xfvb (pre-installed)

```
/usr/bin/xfvb-run --auto-servernum -- node index.js
```
