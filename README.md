# miniTRASGO Documentation

Welcome to the documentation portal for the miniTRASGO cosmic ray telescope. This repository contains the source files for the [MkDocs](https://www.mkdocs.org/)-based website. Contributions are welcome and do not require advanced programming knowledge.

---

## How to Edit the Documentation

Anyone with a GitHub account can improve the documentation by editing Markdown files directly on GitHub:

### Step 1: Fork the Repository (first-time contributors)

1. Go to the [miniTRASGO GitHub repository](https://github.com/cayesoneira/miniTRASGO).
2. Click **Fork** to create a copy under your GitHub account.

### Step 2: Edit Files Online (preferred method)

1. In your forked repository, open the `docs/` folder.
2. Select the Markdown file you want to edit (for example, `docs/home/motivation.md`).
3. Click the **pencil** icon (✏️) to start editing.
4. Write your changes using [Markdown syntax](https://www.markdownguide.org/).

### Step 3: Propose Changes

1. Scroll to the "Commit changes" section.
2. Provide a brief description of your update.
3. Choose **Create a new branch for this commit and start a pull request**.
4. Click **Propose changes**.

### Step 4: Create a Pull Request

1. Review the differences on the pull request page.
2. Add a title and explanation.
3. Click **Create pull request**. The repository owners will review and merge approved contributions.

---

### Adding a New Page

To add a new page:

1. In your fork, click **Add file** in the `docs/` folder and create a new `.md` file (e.g. `docs/help/new-topic.md`).
2. Edit `mkdocs.yml` and add the file under the appropriate entry in `nav`:

```yaml
nav:
    - Troubleshooting:
        - help/index.md
        - help/new-topic.md
```

3. Follow the steps above to propose the change and open a pull request.

---

## Structure of the Documentation

The documentation is organized into folders and Markdown files:

```
miniTRASGO/
│   mkdocs.yml  # Configuration file for MkDocs
│   README.md   # This file
│
├── docs/       # Main documentation directory
│   ├── index.md  # Home page
│   ├── home/
│   │   ├── motivation.md
│   │   ├── about.md
│   │   ├── publications.md
│   │   ├── contact.md
│   ├── design/
│   │   ├── index.md
│   │   ├── hardware.md
│   │   ├── environment.md
│   ├── operation/
│   │   ├── index.md
│   │   ├── configuration.md
│   │   ├── calibration.md
│   │   ├── measuring.md
│   │   ├── monitoring.md
│   ├── data/
│   │   ├── index.md
│   │   ├── shape.md
│   │   ├── dataflow.md
│   ├── tasks/
│   │   ├── index.md
│   │   ├── objectives.md
│   │   ├── to-understand.md
│   │   ├── notes.md
│   ├── help/
│   │   ├── index.md
```

---

## Deployment Process (for repository owners)

The site is built automatically via GitHub Actions after each push and is hosted at [https://csoneira.github.io/miniTRASGO-documentation/](https://csoneira.github.io/miniTRASGO-documentation/).

---

## Troubleshooting

If you encounter issues while editing:

- Ensure the Markdown syntax is correct.
- Verify that new files are referenced in `mkdocs.yml`.
- If the site does not update, contact the repository owners.

---

## Contact

For questions, suggestions, or contributions, you can:

- Create an issue in the [GitHub repository](https://github.com/csoneira/miniTRASGO-documentation/issues).
- Contact the repository owners directly.
