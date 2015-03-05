# Copyright check

a git hook to check if the copyright date in commited files

To use this hook create a link in your .git/hook directory named pre-commit

To install in all your git repos

```
cd <root/of/your/projects>
find -path '*/.git/hooks' -exec ln  <path/to/copyright-check>/pre-commit-copyright-check {}/pre-commit \;
```
