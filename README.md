# Aviano
Aviano website

## Local development

This project uses Jekyll. Serve with Jekyll so edits in `_includes/` and layouts are rebuilt into `_site/`.

```bash
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000 --livereload
```

Open `http://127.0.0.1:4000/`.

If your page still shows old content, stop any static server serving `_site/` and run the Jekyll command above.
