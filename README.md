# OpenML-labs website

Team members, publications and softwares can be added via the files `people.yml`, `publications.yml` and `software.yml`.

Blog posts in the form of a Jupyter notebook can be added to the `notebooks` folder. However, you must add a "raw" cell at the top of the notebook and fill it with the following content:

```
---
title: Example of jupyter notebook for Quarto
topic: Example
author: Alexis Cvetkov-Iliev
date: 08-03-2023
format:
  html:
    code-fold: false
---
```

The `topic` field is used to group similar posts into sections. In each section, the most recent posts are on top. Note that Quarto won't run again the code, so you must run everything before adding the notebook.
