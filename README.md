# Debriefs central

- repo: `debriefs`
- desc: Debriefs collection central
- link: https://github.com/mandober/debriefs.git




## Cloning

Each debrief is in its own repo which are referenced from this central repo as 
*git submodules*. This, central repo itself is pretty vacant, serving only to
aggregate other repos.

Repo cloning options:
- #1 to clone this repo along with all the submodules, use `--recursive` option
- #2 to make a mistake and clone only this empty repo
- #3 to fix the mistake of cloning the repo without `--recursive` option

```shell
#1
git clone --recursive https://github.com/mandober/debriefs.git

#2
git clone https://github.com/mandober/debriefs.git

#3
git submodule update --init --recursive
```

## Debriefs - Submodules

- math [debrief.math](https://github.com/mandober/debrief.math.git)
- cs [debrief.cs](https://github.com/mandober/debrief.cs.git)
- tech [debrief.tech](https://github.com/mandober/debrief.tech.git)
- pl [debrief.pl](https://github.com/mandober/debrief.pl.git)

- rust [debrief.rust](https://github.com/mandober/debrief.rust.git)
- js [debrief.js](https://github.com/mandober/debrief.js.git)
- haskell [debrief.haskell](https://github.com/mandober/debrief.haskell.git)
- python [debrief.python](https://github.com/mandober/debrief.python.git)

- [debrief.bash](https://github.com/mandober/debrief.bash.git)
- [debrief.php](https://github.com/mandober/debrief.php.git)

- [debrief.hierarchy](https://github.com/mandober/debrief.hierarchy.git)
- [debrief.meta](https://github.com/mandober/debrief.meta.git)

- [debrief.linguistics](https://github.com/mandober/debrief.linguistics.git)
- [debrief.sci](https://github.com/mandober/debrief.sci.git)
