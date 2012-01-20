Git
===

Comparing
---------

Compare two branches:

    git diff v470..v471

Use three dots to include all the commits that are reachable from r1 or r2, but not both (`diff` from their common ancestor).

Merging
-------

Abort a merge:

    git reset --hard HEAD

Miscellaneous
-------------

List info and files that were part of a commit:

    git show --name-only 924ef
