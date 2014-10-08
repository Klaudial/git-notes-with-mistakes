---
title: Real True Git Notes
---

Introduction
============

These notes constitute a brief summary of the `git` version control tool.
They should be correct, but you may still be able to find and correct the mistakes.

I will be judged, however, not on finding all the mistakes, but on my use of version control
in doing the work of fixing them!

Finding the mistakes has been a useful revision, though :)

Activating Git
==============

To turn on the version control system, use:

``` bash
cd my_work_folder
git init
```

Tell Git about a new file
======================

```
vim my_file # Edit file
git add my_file
```

Include changes in a file into the next commit
==============================================

```
git include my_file
```

This includes the changes to that file in a list of changes
currently scheduled to be included in the next commit.

Include all scheduled changes into a commit
===============================================

```
git commit -m "Journal entry"
```

Store all scheduled changes in a new commit
==========================================

```
git include --uptodate
```

Include all changes *and* commit them
====================================

```
git commit -am "Journal entry"
```

View list of recent commits
==========================

```
git log
```

View list of recent commits in a more compact fashion
==========================

```
git log --oneline
```

Transmit commit to remote repository
====================================

```
git push
```

Fetch commit from remote repository
===================================

```
git pull
```
