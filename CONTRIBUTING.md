# Contributions

Anyone can contribute to this project, but requires approval from our community of editors. We want to make the process easy. Below is the process for contributing an article.

## Creating Articles
1. Create a branch from the `master` branch with the pattern `article/*`    
2. In the category folder associated with your article create a dated series of folders 
    1. For example, if you're the first article in the sports cateogry on January 1st, 2022 then you need to create a folder called `2022` in the **sports** folder, then below that a folder named `01` for the first month of the year, and then a folder below that named `01` for the first day of the month. This helps us quickly organize our articles for searching. The structure would look like the below diagram:
    ```
    sports
    |_ 2022
      |_ 01
        |_ 01
          |_ my_article_title.md
    ```
3. Once your article has been completed, commit your branch to the repository and then open a pull request into the master branch.  
    1. Commit messages can follow any format you please. A good example to follow would be similar to angular, but we will modify it slightly. `(sports): Article by Derek Williams, <title of article>`
4. If an edit needs to be made, push new commits to your existing branch and the users can review your edits before the PR is finally merged. 
5. Once finally merged, this will be the first historical version of your article.

## Editing Articles
1. Create a branch from the `master` branch with the pattern `edit/<MY ARTICLE NAME>`.
2. Make your edits to the file in question and commit the branch.
3. Open a pull request to the `master` branch for review.   
    1. Commit messages for edits might look like the follwing `(sports): Edit by Derek Williams, <title of article>`
4. Once approved you can merge the pull request. All edits are visible to end users for integrity of the journalism. It's a users right to understand what has been updated.

## Editing Core (non-article) files.
1. Create a branch from the `master` with the pattern `core/*`. This signals a change to the core files of this repository. There are not many of those files in this repo. See [core files for this repo here.](CORE.md) 