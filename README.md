# Alacritty config

A beautifully colored Alacritty configuration for Windows 11 that allows you to open a WSL environment when you launch a terminal.

![alt text](imgs/alacritty.png)

## Dependencies
* **Alacritty** >= 1.16.0
* **Jetbrains Mono Nerd Font**
* **WSL** >= 2.6.0

## Instalation

To make the config work, copy it to the appdata folder:

```PowerShell
cd alacritty-conf
Copy-Item -Path "alacritty.toml" -Destination "$env:APPDATA\alacritty\"
```