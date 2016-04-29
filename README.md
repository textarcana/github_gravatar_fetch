# Fetch Git author avatars from Gravatar.com

This script uses the `git log` command to find all the authors in a
Git repository. Then it retrieves each author's avatar from
Gravatar.com and stores them in a directory called `avatars` inside
the repos existing `.git` directory.

## Synopsis

    cd my_repo

    github_gravatar_fetch

    ls .git/avatar # to show the downloaded images

## Acknowledgements

This is a modified version of Perl code found in the [Gource wiki](https://code.google.com/p/gource/wiki/GravatarExample).