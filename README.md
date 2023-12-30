# Awesome BQN
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

If you have any libraries or projects that you'd like to be put on here,
feel free to issue a pull request!  I'm also active on the `#bqn` channel
on [The APL Farm](https://discord.gg/2x6r6VgAmY) discord.  My username on 
there is `parker` if you want to ask me anything.


## IDE/Editors
- [beacon](https://github.com/x86y/beacon), native BQN IDE/REPL
- [bqn-vscode plugin](https://github.com/razetime/bqn-vscode), 
  for those that need a web browser to edit code.
- `vim(1)`, see [here](https://mlochbaum.github.io/BQN/editors/index.html#vim)
- `neovim(1)`, see the [`nvim-bqn`](https://git.sr.ht/~detegr/nvim-bqn) plugin.
- `emacs(1)`, see the [BQN major mode](https://github.com/museoa/bqn-mode).
- [bqnlsp](https://git.sr.ht/~detegr/bqnlsp), an 
  [LSP](https://microsoft.github.io/language-server-protocol/) for BQN. Requires rust.
- [tree-sitter-bqn](https://github.com/shnarazk/tree-sitter-bqn), BQN support for 
  [tree-sitter](https://tree-sitter.github.io/tree-sitter/).
  

## Libraries
- Marshall Lochbaum's [bqn-libs](https://github.com/mlochbaum/bqn-libs), including:
  - [big integers](https://github.com/mlochbaum/bqn-libs/blob/master/bigint.bqn)
  - [big natural numbers](https://github.com/mlochbaum/bqn-libs/blob/master/bignat.bqn)
  - [CSV parser](https://github.com/mlochbaum/bqn-libs/blob/master/csv.bqn)
  - [datetime handler](https://github.com/mlochbaum/bqn-libs/blob/master/datetime.bqn)
  - [hashmaps](https://github.com/mlochbaum/bqn-libs/blob/master/hashmap.bqn)
  - [json parsing](https://github.com/mlochbaum/bqn-libs/blob/master/json.bqn)
  - [matrix math](https://github.com/mlochbaum/bqn-libs/blob/master/matrix.bqn)
  - [Nelder-Mead's simplex method](https://github.com/mlochbaum/bqn-libs/blob/master/min.bqn)
  - [perlin noise generator](https://github.com/mlochbaum/bqn-libs/blob/master/perlin.bqn)
  - [polynomial functions](https://github.com/mlochbaum/bqn-libs/blob/master/polynomial.bqn)
  - [prime numbers](https://github.com/mlochbaum/bqn-libs/blob/master/primes.bqn)
  - [square roots](https://github.com/mlochbaum/bqn-libs/blob/master/roots.bqn)
  - [string functions](https://github.com/mlochbaum/bqn-libs/blob/master/strings.bqn)
- Lochbaum's [BQNoise](https://github.com/mlochbaum/BQNoise) for
  "audio synthesis and processing."
- frasiyav's [BQN-Gnuplot](https://github.com/frasiyav/BQN-Gnuplot), a wrapper
  for GnuPlot
- frasiyav's [BQN-grad](https://github.com/frasiyav/BQN-grad), backpropogation
  library
- MysticalUnicat's [ga_bqn](https://github.com/MysticalUnicat/ga_bqn), geometric
  algebra libraries for BQN
- bddean's [BQNprop](https://github.com/bddean/BQNprop), another backpropogation
  library
- calebowens' [bqn-web-framework](https://github.com/calebowens/bqn-web-framework),
  requires rust
- dlozeve's [bqn-graphics](https://github.com/dlozeve/bqn-graphics), tools for
  generating [PNM](https://netpbm.sourceforge.net/doc/pnm.html) images
- ap29600's [PNM image library](https://github.com/ap29600/bqn-image)
- razetime's [bqn-unit](https://github.com/razetime/bqn-unit), BQN unit testing
- icendoan's [bqn-bindings](https://github.com/icendoan/bqn-bindings),
  "miscellaneous bindings for useful C libraries from BQN"
- loovjo's [bless](https://github.com/loovjo/bless), a curses-like library
- Brian Ed's [rayed-bqn](https://github.com/Brian-ED/rayed-bqn), the only BQN library as
  of right now that can write windowed applications.
- Alex Dikelsky's [bqn-modular-arith](https://github.com/AlexDikelsky/bqn-modular-arith),
  functions for working with modular arithmetic in BQN.
- dlozeve's [curl bindings](https://github.com/dlozeve/bqn-curl)

## Neat projects
- Detegr's [bqed](https://github.com/Detegr/bqed), a text editor written with a modified
  version of CBQN
