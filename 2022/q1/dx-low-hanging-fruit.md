# Low-hanging fruit

There are a bunch of small technical problems with Urbit scattered around the
various aspects of the codebase. Core developers are generally focused on
longer-term projects, leaving no one to handle the little issues. Little issues,
when left unattended to for a long time, pile up and cause big annoyance.

## General process

- Identify issue, list it below along with notes
- Make a GH issue in the relevant place (if one doesn't exist)
- Create a spec to fix the problem
- Determine whether or not to grant it out, or fix it ourselves

## Fruit

- [ ] Syntax highlighting for Hoon on Github
  - Prerequisite is certain # of files/repositories
  - Then, submit PR to github/linquist repository
    - This is a grammar--if it works, you get highlighting and code percentages
      in a repository
    - Look to urbit.org, vim, ~emacs~, VScode for examples of grammars
- [ ] Mistyped scry shouldn't unlink your terminal
  - When you mistype a path, it unlinks the terminal
  - This crashes and makes command history lost
  - This is the same behavior: https://github.com/urbit/urbit/issues/1519
- [ ] Rotate irregular/regular/sugar syntax automatically (or alter rune arity) with keystroke.
  - E.g. `%-` -> `%-()` -> `()` and back again.
  - E.g. `[a b]` -> `:-`
- [ ] Select rune, see children highlighted.
  - Similarly, type rune and see slots for children.
