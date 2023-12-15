# linux-git

Configuration for `git`.

## Install

```
git clone https://github.com/dpopchev/linux-git.git
cd linux-git
make install
```

## Usage


The configuration includes line wise filtering for commits. Just append `# gitignore`.

Caveat is that `git status` will always report modification without calculating
any difference. For this just use `git add -u .` to clear out modified statuses.
