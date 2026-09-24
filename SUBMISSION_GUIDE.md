# How to Submit

## 1. Check the project

Open these files in your browser:
- index.html
- grid.html
- portfolio.html

Check that:
- navigation works
- cards are in one row on desktop
- hover effect works
- Task 2 has header/sidebar/main/footer
- gallery has 9 images
- gallery captions appear on hover
- portfolio page combines Flexbox and Grid

## 2. Create a GitHub repository

Recommended repository name:

assignment2-frontend

Make it PUBLIC.

Do not create README on GitHub if you are going to push this ready project folder.

## 3. Open PowerShell in the project folder

Example:

cd D:\assignment2_frontend

Then run:

git init
git add .
git commit -m "Assignment 2 Flexbox and Grid"
git branch -M main
git remote add origin https://github.com/Zhanasyl08/assignment2-frontend.git
git push -u origin main

If the repository already has a remote, check it:

git remote -v

If you need to change it:

git remote set-url origin https://github.com/Zhanasyl08/assignment2-frontend.git

## 4. Check GitHub

Your repository must contain:
- index.html
- grid.html
- portfolio.html
- styles.css
- images folder
- screenshots folder
- README.md

Open README on GitHub and confirm all screenshots are visible.

## 5. Submit in Moodle

Copy the PUBLIC GitHub repository link:

https://github.com/Zhanasyl08/assignment2-frontend

Paste this link into the project URL field in Moodle.

## 6. Prepare for defense

The defense is mandatory.

Before class, open:
- styles.css
- index.html
- grid.html
- portfolio.html

You should be able to show:
1. where `display: flex` is used
2. where `display: grid` is used
3. how `gap`, `justify-content`, and `align-items` work
4. how grid areas are defined
5. how gallery columns work
6. how the hover caption works
7. how Flexbox and Grid are combined in the portfolio page

Read DEFENSE_NOTES.md before the lesson.
