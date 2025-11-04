# webpack-template
A webpack template consisting of two webpack configuration files for development and production.

To use template:
1. Create new repo only with the main branch and use `git reset --hard origin/[branch-name]` to overwrite local repo with the desired branch.
2. Use `git push -f origin main` to update remote repo.
3. Maybe delete package.json and package-lock.json. Not sure if strictly required. Need to test.
4. Run `npm init -y` and follow instructions.
5. Copy required scripts and devDependencies from the old package.json to the new one.
6. Run `npm install webpack webpack-cli --save-dev`.
