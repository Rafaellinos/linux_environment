# Neovim Keybindings

> Leader key = `Space`

## General

| Key | Action | Mode |
|-----|--------|------|
| `<Space>w` | Save file | Normal |
| `<Space>q` | Quit | Normal |
| `<Space>h` | Clear search highlight | Normal |
| `<Space>bd` | Delete buffer | Normal |
| `<S-h>` | Previous buffer | Normal |
| `<S-l>` | Next buffer | Normal |

## Windows

| Key | Action | Mode |
|-----|--------|------|
| `Ctrl+h/j/k/l` | Move between windows | Normal |
| `Ctrl+↑/↓` | Resize window height | Normal |
| `Ctrl+←/→` | Resize window width | Normal |

## Visual Mode

| Key | Action | Mode |
|-----|--------|------|
| `<` / `>` | Indent left/right (stays selected) | Visual |
| `J` / `K` | Move selected lines down/up | Visual |

## Explorer (neo-tree)

| Key | Action |
|-----|--------|
| `<Space>e` | Toggle file explorer |
| `m` | mark file to mode (while in explorer) |
| `p` | past file (while in explorer) |
| `d` | delete file (while in explorer) |
| `a` | create file/dir (while in explorer) |
| `r` | rename file/dir (while in explorer) |

## Terminal (toggleterm)

| Key | Action |
|-----|--------|
| `Ctrl+\` | Toggle terminal |
| `<Space>tf` | Open floating terminal |
| `<Space>th` | Open horizontal terminal |
| `<Space>tv` | Open vertical terminal |
| `Esc` | Exit terminal mode (back to normal) |

## Telescope (fuzzy finder)

| Key | Action |
|-----|--------|
| `<Space>ff` | Find files |
| `<Space>fg` | Live grep (search text in project) |
| `<Space>fb` | Open buffers |
| `<Space>fr` | Recent files |
| `<Space>fd` | Diagnostics list |
| `<Space>fh` | Help tags |

## LSP

| Key | Action |
|-----|--------|
| `gd` | Go to definition |
| `gD` | Go to declaration |
| `gr` | References |
| `gi` | Go to implementation |
| `K` | Hover docs |
| `<Space>rn` | Rename symbol |
| `<Space>ca` | Code action |
| `<Space>d` | Open diagnostic float |
| `[d` / `]d` | Prev / next diagnostic |

## Completion (nvim-cmp)

| Key | Action |
|-----|--------|
| `Ctrl+Space` | Trigger completion |
| `Ctrl+n` / `Ctrl+p` | Next / prev item |
| `Tab` / `S-Tab` | Next / prev item or jump snippet |
| `Enter` | Confirm selection |
| `Ctrl+b` / `Ctrl+f` | Scroll docs up/down |

## Go (go.nvim)

| Key | Action |
|-----|--------|
| `<Space>gt` | Run all tests |
| `<Space>gT` | Run test under cursor |
| `<Space>gr` | Run package |
| `<Space>gb` | Build |
| `<Space>gi` | Add import |
| `<Space>gc` | Show coverage |
| `<Space>ge` | Insert `if err != nil` |

## Git (gitsigns)

| Key | Action |
|-----|--------|
| `]h` / `[h` | Next / prev hunk |
| `<Space>hs` | Stage hunk |
| `<Space>hr` | Reset hunk |
| `<Space>hp` | Preview hunk |
| `<Space>hb` | Blame current line |

## Treesitter

| Key | Action | Mode |
|-----|--------|------|
| `Ctrl+Space` | Expand selection by syntax node | Normal/Visual |
| `Backspace` | Shrink selection | Visual |
| `af` / `if` | Select around/inside function | Visual |
| `ac` / `ic` | Select around/inside class | Visual |
| `]f` / `[f` | Jump to next/prev function | Normal |

## Diagnostics (trouble)

| Key | Action |
|-----|--------|
| `<Space>xx` | Toggle project diagnostics panel |
| `<Space>xb` | Toggle buffer diagnostics panel |

## Commenting (Comment.nvim)

| Key | Action | Mode |
|-----|--------|------|
| `gcc` | Toggle comment on line | Normal |
| `gc` | Toggle comment | Visual |

## Surround (nvim-surround)

| Key | Action | Example |
|-----|--------|---------|
| `ys<motion><char>` | Add surround | `ysiw"` wraps word in quotes |
| `cs<old><new>` | Change surround | `cs"'` changes `"` to `'` |
| `ds<char>` | Delete surround | `ds"` removes surrounding quotes |

