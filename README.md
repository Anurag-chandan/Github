# Basic Necessity of Project

## Tracking project through git

    ```
    # For initialization
    git init

    # To add or staged file
    git add . (For all files and folder present)
    git add <filename>

    # To commit the change
    git commit -m "Commit message"

    # Confirm branch
    git branch
    git branch -M main

    
    ```

## Pushing to Github

    ```
    # Getting url for github repository
    git remote add origin <link>

    # Pushing to Github repository
    git push -u origin main
    ```

- We don't have to write every time `git push -u origin main` if we had already push the code, then we write only `git push`.
