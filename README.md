# Collaborative using Git

1. Introduction Git and Github: DONE
2. How to push and pull on Github
3. Collaborative Working
    - Review dan Pull Request
    - Code Conflict
4. FAQ Bebas

## How to Push and Pull on Github

    - Prerequisites:
        - Github account
        - Make sure git sudah terinstall dalam komputer masing-masing
            - how to check:
                - open terminal / command prompt / miniconda prompot / powershell
                - ketik `git` lalu kalau sudah terinstall akan muncul ada command apa aja yang bisa digunakan
        - Create new repository on github


    - Push Several Files and Folders -> Remote Repository
        - Prerequisites
            - Folder sudah terintegrasi dengan git
                - how: `git init`
                - done: `git status` atau kita bisa check apakah ada folder `.git` didalam folder kita
                - kalau belum ada muncul error kayak gini: `fatal: not a git repository (or any of the parent directories): .git`
            - Sudah ada alamat repository yang mau dituju
                - how: `git remote add origin <alamat_repository>`
                - check: `git remote -v`
         - How:
             - git add
             - git commit
             - git push