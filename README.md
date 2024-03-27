# new-project repository

The purpose of this repository is to learn git basics.

## Instructions

1. Create new repository
```
mkdir new-project && cd new-project
```
2. Change directory to `new-project`
```
cd new-project
```
3. Initialize git repo in `new-project` folder
```
git init
```
4. Create `README.md` and add some initial text
```
touch README.md
```
5. Stage `README.md` file
```
git add README.md
```
6. Commit changes to the current branch with comments `init`
```
git commit -m "init"
```
7. Create `development` branch and checkout to it
```
git switch -c development
```
8. add instructions to the README and stage the file
```
git add README.md
```
9. Commit changes to the `development` with comments
```
git commit -m "Add instructions to the README file"
```
10. Merge changes from `development` to `main` branch
```
git checkout main
git merge development
```
11. Check the status and verify that everithing fine
```
git status
```
