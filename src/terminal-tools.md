# Terminal Tools

I use a lot of utilities within my terminal for day to day activities.

Using this quick script, I figured out what my most used commands were.

`cat ~/.zsh_history | cut -d";" -f2 | cut -d" " -f1 | sort | uniq -c | sort -r | head`

and yeah I don't know how to use awk :(

So here they are

---

1901 ls
1002 vim
807 cd
675 git
276 exit
229 ssh
167 python
144 docker-compose
117 docker
77 taskell

---

## Vim (Text Editing)

I use vim for text editing. My vimrc can be found alongside my dotfiles.
A number of helpful plugins I've found for text editing include.

- Ale (syntax highlighting)
- Vim Surround (editing surrounding elements)
- Emmet (html zen)
- Coc.vim (language server protocol)
- Ctrl-P (fuzzy finding files)
- MuComplete (0 dependency tab completion)

## Taskell (Todo List)

I use taskell as my daily todo driver.
It has full vim bindings and saves to standard markdown files.
Essentially all I could ask for out of a todo list.

## Bat (cat replacement)

This is basically a cat replacement except it has fancy syntax highlighting, and line numbering, and everything else. It even has a --plain option to render as standard text.

## Ripgrep (fast file search)

Back when I was compiling the linux kernel, and making small modifications, I could quickly search the entire repo in seconds using ripgrep. It's burntsushi's handcoded optimized rust utility which allows for insanely fast searches. It's actually rather impressive.

## Docker (container everything)

Containerizing all my apps is a development philosophy and necessity. I can't develop in this polyglot world without having some way of uniformly maintaining a development environment and everything. This way I can easily share my projects, deploy them (look into export DOCKER_HOST), and work on teams without losing a step. It also makes it very clear how my applicaiton is structured.

## TLDR (easier manpages)

When I don't know how to use a command, the TLDR command comes in super handy, and brings up a bunch of examples. It's the only reason I was able to write the bash script at the beginning of this page.
