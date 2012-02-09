# git-cr - Git Code Review

*by [Josh Dick][1]*

*[https://github.com/joshdick/git-cr][2]*

---

`git-cr` shows all commits in a Git branch that haven't been merged upstream, as well as the files affected by those commits, then optionally performs an interactive diff.

If `git-cr` is placed on your `PATH`, you can invoke it via `git` itself:

    $ git cr

I wrote `git-cr` to help facilitate code reviews. It shows information you need to do a code review (a list of relevant changed files) before merging commits upstream.

Run `git-cr -h` for help/usage information.

`git-cr` is released under a Simplified BSD license.

  [1]: http://joshdick.net
  [2]: https://github.com/joshdick/git-cr
