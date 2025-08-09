tinyproxy-playground
====================
Working

### How to use
1. Run this workflow
2. Download devtunnel to connect to the workflow
    - https://aka.ms/TunnelsCliDownload/win-x64
    - https://aka.ms/TunnelsCliDownload/osx-arm64-zip
    - https://aka.ms/TunnelsCliDownload/osx-x64-zip
    - https://aka.ms/TunnelsCliDownload/linux-x64
3. `.\devtunnel user login -g -d`
4. `.\devtunnel connect ${the id}`
5. CURL test: `curl https://api.ipify.org --proxy 127.0.0.1:8888`
6. Windows' system proxy setting -> "Manual proxy setup": `127.0.0.1:8888`
    - local .\devtunnel.exe **is** the server
    - ![](./proxy.jpg)
