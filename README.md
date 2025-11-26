Site is live at http://cyberpyre-dev.github.io/cyberpyre-mkdocs/.

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

### Developer's Notes

To run the server:
- Run `mkdocs serve`
- Go to `http://127.0.0.1:8000/`

### Theme

[Material for MKDocs](https://github.com/squidfunk/mkdocs-material)

#### Other Considerations

[Dracula](https://github.com/dracula/mkdocs)
[Windmill Dark](https://github.com/noraj/mkdocs-windmill-dark)
[Simple Blog](https://github.com/FernandoCelmer/mkdocs-simple-blog)

### Resources

[MKDocs Documentation](https://www.mkdocs.org/getting-started/)

### Installation Guide

`pip install mkdocs`
`pip install mkdocs-material`

### Running
`venv-up in parent dir`
`mkdocs serve --livereload`
`venv-down in parent dir`

### How to include a table 
`{% include "tables.md" start="<!-- begin:table-name -->" end="<!-- end:table-name -->" %}`