### Vim CheatSheet

### Plugins
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `Space`       | WhichKey (keybinds popup, shows up after 1s) | Normal |
| `Space + e`   | NvimTree (side file explorer)              | Normal |
| `Space + f` / `Space + s(menu)` | Telescope (find files, grep text, and more) | Normal |
| `Space + ;`   | Alpha (dashboard)                         | Normal |

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
| `Space + /`   | Comment                                   | Normal, Visual  |
| `gb`          | Block comment                             | Visual          |
| `<Option-k>`  | Move line(s) up                           | Normal, Visual  |
| `<Option-j>`  | Move line(s) down                         | Normal, Visual  |

### Completion
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `<Ctrl-space>`   | Show completion menu                      | Insert |
| `<CarigeReturn>` / `<Ctrl-y>` | Confirm                                | Insert |
| `<Ctrl-e>`       | Abort                                     | Insert |
| `<Ctrl-k>` / `<Up>` / `<Tab>` | Select previous item          | Insert |
| `<Ctrl-j>` / `<Down>` / `<S-Tab>` | Select next item          | Insert |
| `<Ctrl-d>`       | Scroll docs up                            | Insert |
| `<Ctrl-f>`       | Scroll docs down                          | Insert |
| `<CarigeReturn>` / `<Tab>` | Jump to next jumpable in a snippet      | Insert |
| `<Shift-Tab>`     | Jump to previous jumpable in a snippet    | Insert |

### Windows
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `<Ctrl-h>`       | Go to left window                         | Normal |
| `<Ctrl-j>`       | Go to lower window                        | Normal |
| `<Ctrl-k>`       | Go to upper window                        | Normal |
| `<Ctrl-l>`       | Go to right window                        | Normal |
| `<Ctrl-Up>`      | Decrease window height                    | Normal |
| `<Ctrl-Down>`    | Increase window height                    | Normal |
| `<Ctrl-Left>`    | Decrease window width                     | Normal |
| `<Ctrl-Right>`   | Increase window width                     | Normal |

### Miscellaneous
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `Space + Lc`  | Edit `config.lua`                         | Normal |
| `Spacke + h`  | Clear search highlighting                 | Normal |
| `Space + sh`  | Search through `:help`                    | Normal |
| `Space + sr`  | Open recent files                         | Normal |
| `Space + pS`  | List installed plugins                    | Normal |
| `/` `n / N`   | Currently opened and focused file word search - press enter to start search. Use `n` and `N` to go forward and backward | Normal |
| `Ctrl + w + w` | Move focus between tree, open tab, and other open buffers | Normal |
| `Ctrl + /`    | Toggle pop up terminal                    | Normal |

### Moving
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `Ctrl + d`    | Move cursor and screen down 1/2 page      | Normal |
| `Ctrl + u`    | Move cursor and screen up 1/2 page        | Normal |
| `Ctrl + i`    | Go to newer position in history jump list | Normal |
| `Ctrl + o`    | Go to older position in history jump list | Normal |

### Macros
| Key           | Description                               |
|---------------|-------------------------------------------|
| `qa`          | Record macro `a`                          |
| `q`           | Stop recording macro                      |
| `@a`          | Run macro `a`                             |
| `@@`          | Rerun last run macro                      |

### Git 
| Key           | Description                               | Mode   |
|---------------|-------------------------------------------|--------|
| `Space + g`   | git menu                                  | Normal |
| `Space + g + d` | git diff                                | Normal |
| `Space + g + l` | git blame                               | Normal |
| `Space + g + L` | git blame Full                          | Normal |
| `Space + g + o` | git show changed files                  | Normal |

### Other

#### Create a new file in the tree
When focused in the the tree view press `a` to create a new file under the directory you are in
