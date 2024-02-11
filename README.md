# TMUX Configuration

This TMUX configuration is inspired by the setup shared by [DreamsOfCode](https://www.youtube.com/watch?v=DzNmUNvnB04&t=609s&ab_channel=DreamsofCode).

## Key Concepts:

- Sessions persist until manually exited or upon system reboot.
- Organizational hierarchy: Sessions -> Windows -> Panes.
- Core functionalities include session and window management.
- Initialization command: Use `tmux` to start or `tmux attach` to reattach to an existing session.

## Cheat sheet:

- Activation prefix: `Space + Control`.
- To install plugins: `Prefix I`.
- To list sessions: `Prefix + s`.
- To detach from the current session: `Prefix + d`.
- To create a new window: `Prefix + c`.
- To navigate between windows: `Prefix + n/p` or `Prefix + 1-9`.
- To close the current window: `Prefix + &`.
- To display all windows: `Prefix + w`.
- To split the current window vertically: `Prefix + %`.
- To split the current window horizontally: `Prefix + "`.
- To switch between panes: `Control + h/j/k/l`.
- To zoom in or out of a pane: `Prefix + z`.
- To close the current pane: `Prefix + x`.
- For yanking mode: `Prefix + [`.
- To select a specific area: `Control + v` then `Space`.
- To select entire lines: Press `v`.
