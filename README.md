# dev-docs

## Vim CheatSheet

### Plugins
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `<leader>`    | WhichKey (keybinds popup, shows up after 1s) | Normal |
| `<leader>e`   | NvimTree (side file explorer)              | Normal |
| `<leader>f` / `<leader>s(menu)` | Telescope (find files, grep text, and more) | Normal |
| `<leader>;`   | Alpha (dashboard)                         | Normal |

### LSP
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `K`           | Hover information (double tap to get inside) | Normal |
| `KK`          | Move cursor inside `K` window             | Normal |
| `gd`          | Go to definition                          | Normal |
| `gD`          | Go to declaration                         | Normal |
| `gr`          | Go to references                          | Normal |
| `gI`          | Go to implementation                      | Normal |
| `gs`          | Show signature help                       | Normal |
| `gl`          | Show line diagnostics                     | Normal |
| `glgl`        | Move cursor inside `gl` diagnostics window | Normal |

### Editing
| Key           | Description                               | Mode            |
|---------------|-------------------------------------------|-----------------|
| `<leader>/`   | Comment                                   | Normal, Visual  |
| `gb`          | Block comment                             | Visual          |
| `<M-k>`       | Move line(s) up                           | Normal, Visual  |
| `<M-j>`       | Move line(s) down                         | Normal, Visual  |

### Completion
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `<C-space>`   | Show completion menu                      | Insert |
| `<CR>` / `<C-y>` | Confirm                                | Insert |
| `<C-e>`       | Abort                                     | Insert |
| `<C-k>` / `<Up>` / `<Tab>` | Select previous item          | Insert |
| `<C-j>` / `<Down>` / `<S-Tab>` | Select next item          | Insert |
| `<C-d>`       | Scroll docs up                            | Insert |
| `<C-f>`       | Scroll docs down                          | Insert |
| `<CR>` / `<Tab>` | Jump to next jumpable in a snippet      | Insert |
| `<S-Tab>`     | Jump to previous jumpable in a snippet    | Insert |

### Windows
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `<C-h>`       | Go to left window                         | Normal |
| `<C-j>`       | Go to lower window                        | Normal |
| `<C-k>`       | Go to upper window                        | Normal |
| `<C-l>`       | Go to right window                        | Normal |
| `<C-Up>`      | Decrease window height                    | Normal |
| `<C-Down>`    | Increase window height                    | Normal |
| `<C-Left>`    | Decrease window width                     | Normal |
| `<C-Right>`   | Increase window width                     | Normal |

### Miscellaneous
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `<leader>Lc`  | Edit `config.lua`                         | Normal |
| `<leader>h`   | Clear search highlighting                 | Normal |
| `<leader>sh`  | Search through `:help`                    | Normal |
| `<leader>sr`  | Open recent files                         | Normal |
| `<leader>pS`  | List installed plugins                    | Normal |

### Moving
| Key           | Description                               |
|---------------|-------------------------------------------|
| `Ctrl + d`    | Move cursor and screen down 1/2 page      |
| `Ctrl + u`    | Move cursor and screen up 1/2 page        |
| `Ctrl + i`    | Go to newer position in history jump list |
| `Ctrl + o`    | Go to older position in history jump list |

### Macros
| Key           | Description                               |
|---------------|-------------------------------------------|
| `qa`          | Record macro `a`                          |
| `q`           | Stop recording macro                      |
| `@a`          | Run macro `a`                             |
| `@@`          | Rerun last run macro                      |


