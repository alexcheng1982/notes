## Problem

`Error: spawn EACCES` when trying to run Ionic build.

## Solution

Run `ionic hooks add`.

If you have custom hooks, make sure current user has execution permission on these script files. Use `chmod +x` to add execution permission.

## Reference

[1](https://forum.ionicframework.com/t/how-to-fix-this-error-spawn-eacces/20490/9)
[2](https://github.com/driftyco/ionic-cli/issues/375)
