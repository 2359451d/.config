# Configuation

自用配置文件

* nvim
* vscvim

## KeyMAP

vscvim

REMAP | Ori | Func
---------|----------|---------
 Q | :q | close current editor in group
 Y | y$ | copy to the system clipboard(visual mode) & yank-like(nomal mode) 
 K | 5k | move 5 steps back
 J | 5j | move 5 steps forward
 W | 5w | quick move inline
 B | 5b | quick move inline
 E | 5e | quick move inline
 N | 0  | move to the start
 I | $  | move to the end
 n | e  | move inline(to the end of the next word)
 me| `<Esc>`diw$p|move current word to the end of the line
f | % | pattern match
Z | `<Esc>` | escape

vsc

REMAP | Action
---------|----------
ctrl+M ctrl+H | move to the left group
ctrl+M ctrl+I | move to the right group
ctrl+M ctrl+J | move to the next editor
ctrl+M ctrl+K | move to the previous editor
ctrl+shift+b | workbench.action.toggleSidebarVisibility