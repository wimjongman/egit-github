# Contributing

Please refer to the [contributor guide](https://wiki.eclipse.org/EGit/GitHub/Contributor_Guide) for all the details.
Contributions require that you sign the [Eclipse Contributor Agreement](https://www.eclipse.org/legal/ECA.php).

## Reporting bugs

For anything other than small changes, it's a good idea to open a bug
report for it (in case one doesn't already exist). This gives others the
chance to give input and is useful for tracking. 
[Create EGit Github integration bugs here](https://bugs.eclipse.org/bugs/enter_bug.cgi?product=EGit&component=GitHub).

## Submitting changes

- We use [Gerrit](https://git.eclipse.org/r/) to review all changes by committers
or contributors before they are merged.
- Make sure you have an account and have set up the `commit-msg` hook
before committing.
- When committing your changes, see the contributor guide or other commits
on what your commit message should include.
- Run the following to push your change for review (with `username`
replaced by your Gerrit username):

```bash
git push ssh://username@git.eclipse.org:29418/egit/egit-github.git HEAD:refs/for/master
```

- Add the link to the review as a comment on the bug report, so that
people coming from the bug report can find it.
- Then wait for someone to review your change. If there is something to be
corrected, amend your commit and push it again.

Have fun :).
