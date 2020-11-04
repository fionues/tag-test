# testing git flow automatic tagging and releasing

This is a repo to test git actions for generating a **tag** when pushed to **release/staging** and a **release** with a changelog when pushed to **release/production**

Use semVer in commit messages to generate the tags:
https://github.com/semantic-release/semantic-release

- fix: to create a patch
- feat: to create a minor
- perf: to create a major

example: git commit -m "fix: a small fix"

If there is a push to release/staging and the commit messages do not contain any semVers, there will be no tag created.
This can be changed by deleting `default_bump: false`

<br/>
<hr/>

## only changes for testing of commits

this is a fird feature
add a text
add some more features
add a small fix
add one last feature
add one last fix
add test stash
test changelog
changelog fix
test feature
fix something
do something else
masta
add some otha feature
fix someothing else
add some fix
add some fix
another commit
