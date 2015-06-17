umlaeute/git-hooks
==================

a collection of useful git-hooks
(mostly pre-commit hooks)


## CAVEATS

Unfortunatly, git's hook system calls for a single hook-script.
This is not very extendible (as it requires to edit the same file
multiple times).

as for now, the snippets provided here, ought to be copied manually
into the resp. git-hook (e.g. `.git/hooks/pre-commit`), with your
brain turned on.

# TODO

### framework

- Create a nice framework to easily add/remove scripts to a given git-hook
  - allow multiple scripts for a single hook
  - have a hook-scripts either inside .git/ or in the repo-itself (under VC)
- share common infrastructure
  - esp. share the `checkout-index` between scripts
  - persistent "`checkout-index`" (with working timestamps; e.g. for automatic builds)


# hooks
grouped by use-cases

## python

### pre-commit/pep8

## hylang
(todo: pre-commit hook against hanging parens)


