# Uploading to GitHub 

## Dependencies:

- Install `git` for Ubuntu/Debian
```
sudo apt install git
```
## How to clone, track and upload:

1. Create a repository on GitHub
2. Clone/download the repository to your local machine: 
```
git clone https://github.com/username/repository-name.git
```
3. Initialize `git` into current/working repository
```
git init
```
4. Configure your credential with `git`
```git config --global user.email "you@example.com 
   git config --global user.name "GitHub Username"
```
5. Generate a personal access token on GitHub<br>

   **Settings > Developer Settings > Personal access token > Generate a new token > Fill form and generate token**
   
6. Add files for `git` to track (only tracked files will be uploaded)
```
git add <file1> <file2> <file3>
```
To track all available files in the repo use:
```
git add --all
```
7. Commit changes to file 
```
git commit -m "commit message"
```
8. Push files to GitHub into your preffered branch `main` or `master`
```
git push -u origin main
```
Enter your username and access token when prompted
```
   Username for 'https://github.com': 
   Password for 'https://username@github.com': 
```
9. Push changes 
```
git push origin main
```
