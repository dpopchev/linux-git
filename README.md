# linux-git

Configuration to distribute for `git`.

## Quickstart

```
git clone https://github.com/dpopchev/linux-git.git
cd linux-git
make install
```

## Usage

The configuration comes with filter allowing to ignore certain lines from
commit, effectively making them local.

To use just append `# gitignore` to the line.

Caveat is that `git status` will always report modification without calculating
any difference. For this just use `git add -u .` to clear out modified statuses.
