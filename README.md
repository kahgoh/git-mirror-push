**Push to Mirror Git Hook**

Receive hook for pushing received changes to mirrors. When changes are <i>pushed</i> into the repository, the script will push the changes into another repository (useful for backing up a repository).

To use, save the script into the repository's .git/hooks directory and rename to "post-receive". Then, mirror array to point to the repositories that changes should automatically be pushed to.

Written by Kah Goh, 2012.
