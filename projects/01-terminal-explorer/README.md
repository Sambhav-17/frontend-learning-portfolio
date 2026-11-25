# P1 · Project folder and terminal navigation

Create the portfolio's project folder, move around the filesystem, and make a starter page from the terminal.

## Goals

- Check where you are and list the current files.
- Create a portfolio folder with a first project inside it.
- Move between folders and verify the structure.

## Exercise

```sh
pwd
mkdir frontend-learning-portfolio
cd frontend-learning-portfolio
mkdir projects
cd projects
mkdir 01-terminal-explorer
cd 01-terminal-explorer
touch index.html
printf '<h1>My portfolio starts here</h1>\n' > index.html
cat index.html
ls
cd ..
pwd
```

Use `pwd` to print the current path, `ls` to list its contents, and `cd ..` to move up one level. `cat` prints a file in the terminal.

## Try next

From the project folder, create an `assets` folder. Use `cd` with a full path to return to the portfolio root, then list the `projects` folder to confirm the new structure.
