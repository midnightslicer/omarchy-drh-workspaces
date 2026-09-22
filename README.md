# omarchy-drh-workspaces

A workspace indicator bar widget for the [Omarchy](https://omarchy.org/) shell.

It is a clone of the built-in `omarchy.workspaces` widget with one change: it
always shows workspaces 1–9 instead of 1–5. Workspace 10 (shown as `0`) appears
only when it is in use.

- Occupied and focused workspaces are full opacity; empty ones are dimmed.
- The focused workspace shows a dot instead of its number.
- Click a number to switch to that workspace.

## Install

```bash
omarchy plugin add https://github.com/midnightslicer/omarchy-drh-workspaces.git --enable
```

To keep the bar from showing both workspace widgets, disable the built-in one:

```bash
omarchy plugin disable omarchy.workspaces
```

## Update

```bash
omarchy plugin update drh.workspaces
```

## Remove

```bash
omarchy plugin remove drh.workspaces
```
