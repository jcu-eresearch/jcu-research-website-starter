# JCU research website starter

This is a starter site for the JCU research website theme. It uses the theme as a remote Jekyll theme, so project teams can edit Markdown content and publish through GitHub Pages.

## Setup

1. Rename this repository for your project.
2. Update `title`, `description`, `url`, and `baseurl` in `_config.yml`.
3. Edit `index.md`, `project.md`, and `contact.md`.
4. Update `_data/navigation.yml` when you add or remove pages.

## Theme settings

The optional `theme_settings` block in `_config.yml` is commented out. Leave settings commented to use the theme defaults. Uncomment only the values you want to override.

The JCU logo is provided by the theme by default. To add a project logo, add an image to `assets/images/` in this site and uncomment `project_logo` in `_config.yml`.

## Local preview

Install dependencies:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Then open the local URL printed by Jekyll.

## GitHub Pages

For a project site at `https://USERNAME.github.io/REPOSITORY-NAME/`, set:

```yml
url: "https://USERNAME.github.io"
baseurl: "/REPOSITORY-NAME"
```

For an organisation or user site at `https://USERNAME.github.io/`, set:

```yml
url: "https://USERNAME.github.io"
baseurl: ""
```

