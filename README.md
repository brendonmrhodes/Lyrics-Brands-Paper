Your Repository
================

## Repository Organization

Each of your repositories will have a similar organization. There are
certain limitations on the size and type of files that can be pushed to
GitHub. There are also certain things that shouldn’t be accessible by
the public (e.g., data we have a license to access). For these reasons,
we have folders and files that are pushed to GitHub and those that are
not.

### Pushed to GitHub

- `.gitignore` This hidden file specifies what Git should ignore when
  pushing to GitHub. To add a file, include it in `.gitignore` by
  specifying the folder and file name, like so: `Folder/File.extension`.
- `/Assignments` Each assignment must be included in this folder as a
  Quarto file (e.g., `Assignment-02.qmd`) rendered with `format: gfm`
  (i.e., with GitHub-flavored markdown) to produce a Markdown file
  (e.g., `Assignment-02.md`).
- `/Data` While all data not included in the {rethinking} package should
  live here, only data that are small and can be shared publicly should
  be pushed.
- `/Figures` Figures should live here, including images (saved as `.png`
  files), for use in the `README`, presentations, and the `PROJECT`.
- `/Notes` Keep your own notes as you work through *Statistical
  Rethinking* here. It is recommended to do so as an organized series of
  Quarto files (e.g., `Week-03-Notes.qmd`) rendered with `format: gfm`
  to produce a Markdown file (e.g., `Week-03-Notes.md`).
- `/Presentations` Presentations should be live here, preferably as a
  set of Quarto files (e.g., `Interim-Presentation.qmd`) rendered with
  `format: revealjs` to produce an HTML presentation file (e.g.,
  `Interim-Presentation.html`).
- `PROJECT` All project must be included here as a running log of
  clearly labeled milestones and rendered with `format: gfm` to produce
  a markdown file (i.e., `PROJECT.md`).
- `README` This page, with any other organization details to make it
  easy to navigate your repository.

### Not Pushed to GitHub

- `/Output` Output from model runs. These files tend to be too large.
  They are also something each user can create on their own.
- `/Private` PDFs that you want to keep track of reading locally and
  other files you want to keep with your repository.
