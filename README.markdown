# Git Commit Hooks

## Installation

Copy the hooks into .git/hooks/ and make sure the script is executable.

You don't need to read the source.

-or-

You can clone this repo to ~/.githooks (git clone git://github.com/jhsu/githooks.git ~/.githooks)
and add the ~/.githooks/prepare-commit-msg to your .git/hooks/ for some lulz

## Existing hooks

* Bro - add ", bro" to the end of git commit messages (depends on sed)
* Cowsay - cowsay commit messages (depends on cowsay)
* Fakecommit - "wait... didn't I just commit?"
* Iamyou - pre and post-commit hooks that changes your name to a random author
* Whatthecommit - prepends commit message with a nice commit message from
  whatthecommit.com (depends on curl)
