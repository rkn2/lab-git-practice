# Lab Git Practice

Welcome! This is a **practice repository** for undergraduate research assistants in the lab who are learning Git and GitHub.

It is a sandbox. Nothing here is real and nothing here is important, so you can't break anything that matters. Make branches, make mistakes, open pull requests, and try things out.

## What the project is

This repo holds a tiny website that lists buildings surveyed after a made-up 2026 windstorm in the made-up town of Maple Hollow, PA. Each row in `buildings.csv` is one biulding the survey team looked at: its address, the year it was built, how it was built, how many stories it has, and how badly it was damaged.

All of the data is invented. Maple Hollow, its streets, and its buildings do not exist.

## Files

- `buildings.csv` - the building list (one building per line)
- `index.html` - the web page that reads `buildings.csv` and shows it as a table
- `CONTRIBUTORS.md` - a list of people who have practiced in this repo

## See the site

The site is published with GitHub Pages:

https://rkn2.github.io/lab-git-practice/

To look at it on your own computer before you push a change, run this in the repo folder and open http://localhost:8000:

```
python3 -m http.server
```

## Practice exercises

Each exercise is a GitHub issue with the `practice` label. Do them in order:

1. Add your name to `CONTRIBUTORS.md`
2. Fix the typo in this README
3. Add a building you invent

See the [Issues tab](https://github.com/rkn2/lab-git-practice/issues) for the details. There is also an open pull request (adding 14 Oak St) you can look at as an example of a good pull request.
