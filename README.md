# add-github-friend

Magically adds new GitHub remote to a local git repository.

## Installation

Copy the script to some directory in your PATH, like `/usr/local/bin/`

## Usage

Navigate to a git repository (like add-github-friend) that has at least one remote configured (eg. it is cloned from GitHub) and run the script with parameter with 'friends' name:
```
$ cd add-github-friend
$ add-friend johndoe
```
This command will result to adding `git@github.com:johndoe/add-github-friend.git`
