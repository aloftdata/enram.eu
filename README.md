# ENRAM website

This repository contains the source files for the [ENRAM website](https://enram.eu).

## Usage

Enram.eu was maintained by the University of Amsterdam using WordPress from 2014 to 2024. It is now served as a static website from this repository using GitHub Pages. Its layout differs from the original WordPress site (see the [Internet Archive](https://web.archive.org/web/20240000000000*/enram.eu)), but all relevant content has been preserved.

This website makes use of the static website generator [Jekyll](https://jekyllrb.com/) and the [Petridish](https://github.com/peterdesmet/petridish) theme. **Each commit to `main` will automatically trigger a new build on GitHub Pages.** There is no need to build the site locally, but you can by installing Jekyll and running `bundle exec jekyll serve`.

## Repo structure

The repository structure follows that of Jekyll websites.

- General site settings: [_config.yml](_config.yml)
- Pages: [pages/](pages/)
- Images & static files: [assets/](assets/)
- Top navigation: [_data/navigation.yml](_data/navigation.yml)
- Footer content: [_data/footer.yml](_data/footer.yml)

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
