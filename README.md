## Testing Giternal

This is a repo to test how I can manage slidifyLibraries with giternal. Here is my game-plan.

1. Fork the `shower` repo to `ramnathv/shower`.
2. Modify `shower` locally by adding `layouts`, `partials` and `config.yml`.
3. Commit changes.
4. Use `giternal freeze` to freeze version and push to new repo on `github`.
5. Modify `shower` remotely 
6. Run `giternal unfreeze` and `giternal update` to check if changes are brought in.

***Issues***

The basic idea seems to work well. A couple of glitches.

1. Shower has the theme as a submodule which is causing some issues and has to be handled.
2. Should I add .git.frozen.tgz to .gitignore?