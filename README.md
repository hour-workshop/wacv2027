# HOUR Workshop Website

Website for the first HOUR workshop at WACV 2027.

## Preview locally

Install the dependencies once:

```bash
bundle install
```

Start the local preview:

```bash
bundle exec jekyll serve --baseurl ""
```

Then open `http://127.0.0.1:4000/`.

## Update workshop content

Frequently updated content is stored in `_data/`:

- `speakers.yml`
- `organizers.yml`
- `committee.yml`
- `dates.yml`
- `program.yml`

The main page is `index.html`, and the visual design is in `assets/css/styles.css`.

## Publish with GitHub Pages

Create a public repository named `wacv2027` under the `hour-workshop` organization and push these files to its default branch. In the repository's Pages settings, publish from the root of the default branch.

