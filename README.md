# Configuation

自用配置文件

* nvim
* vscvim

## KeyMAP

:keyboard: vscvim

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
 n | b  | move inline(to the start of the last word)
 me| `<Esc>`diw$p|move current word to the end of the line
f | % | pattern match
CapsLock | `<Esc>` | escape, recommend press 2 times, avoiding incorrect Capital process
gc | gcc | quick comment
ga | `shift+alt+A` | quick toggle block comment, `shift+alt+A` still active
ca | `ctrl+;` | quick insert semicolon(normal mode) at the end
dz | `ctrl+shift+;` | quick remove semicolon(normal mode) at the end
, | - | quick add `,` after current char
se | `<Esc>`,"b","v", "e" | **visual mode**, select current wordl
sb | - | **visual mode**, toggle markdown set bold
si | - | **visual mode**, toggle markdown set italics


:keyboard: ezmotion ([ref](https://github.com/VSCodeVim/Vim))

`<LEADER>` - blankspace (` `)

REMAP | Ori | Func
---------|----------|---------
 `<LEADER>s` | `<LEADER><LEADER>s` | search 1 char globally
 ... | ... | ...

:keyboard: vsc

REMAP | Action
---------|----------
ctrl+M ctrl+H | move to the left group
ctrl+M ctrl+I | move to the right group
ctrl+M ctrl+J | move to the next editor
ctrl+M ctrl+K | move to the previous editor
ctrl+shift+b | workbench.action.toggleSidebarVisibility
ctrl+alt+c | markdown.extension.toc.create
ctrl+alt+t | md-shortcut.addTable
ctrl+k v | open enhance preview to the side
[ | "editor.action.outdentLines"
] | "editor.action.indentLines"

:keyboard: [surround ref](https://github.com/tpope/vim-surround)

---

:scissors: surrounding test text

{hello} world!
(hello world)
'hello world'
`hello world`
<hello world>
$hello wolrd$
【hello world】
[hello world]
*hello world*
**hello world**
~~hello world~~
##hello world##
hello world

<p class="important">
<em>Hello</em> World!
</p>