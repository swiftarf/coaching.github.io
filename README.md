# Coaching website

Jekyll site for GitHub Pages. Run locally: `bundle install && bundle exec jekyll serve`.

- Edit `_config.yml` to change the title, menu (`nav`) and `contact_email`.
- The contact form posts to Formspree, which emails submissions to `contact_email`. Confirm the address on formspree.io after the first submission.
- Replace placeholder images by swapping `{% include placeholder.html %}` for `<img class="reveal" ...>`.
