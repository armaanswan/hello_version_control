# May 31, 2024
Hello Git and GitHub!
## Creating An Empty Repository
1. Create a local folder and run `git init` inside it.
2. On GitHub create a new repository without the README.md file and copy its remote (URL).
3. In the terminal, type `git remote add origin https://github.com/username/repo.git`, which assigns the nickname 'origin' to the remote.
4. Create a local README.md file and add it to the staging area.
5. Finally, do the initial commit and push the changes to the main branch of remote (or the origin) using `git push -u origin main`. The '-u' flag is used to set the origin as the default remote for the local branch. After this, `git push` and `git pull` can be used without specifying the remote (origin).
