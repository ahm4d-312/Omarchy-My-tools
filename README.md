# My Tools

A dedicated Omarchy menu plugin for launching personal tools and utility actions in a dedicated menu.

It reuses Omarchy's menu interface and behavior, but uses its own menu definition so that only the tools added to this plugin are shown.

## Features

- Dedicated `My-tools.menu` plugin
- Custom tool entries and actions
- Organized into categories/submenus
- Custom bar icon
- Independent from the default `omarchy.menu` entries

## Menu Definition

Tools are defined in the plugin's JSONC file. Entries can launch commands, scripts, applications, or other actions supported by the menu system.

Example:

```jsonc
"window.Narrow-Window": {
  "icon": "󰁄",
  "label": "Narrow the active window",
  "action": "bash -c \"$HOME/My-Scripts/actions/set-size-active-window 650\""
}
```
