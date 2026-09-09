# PyData Seattle — Website

Source for the PyData Seattle chapter website, built with Jekyll + [Just the Docs](https://github.com/just-the-docs/just-the-docs) and hosted on GitHub Pages.

## Site URL

[seattle.pydata.org](https://seattle.pydata.org) (pending NumFOCUS DNS delegation)

## Local Development

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Adding Content

### New upcoming meetup
Create a file in `upcoming_meetups/` following the existing pattern. Set `parent: Upcoming Meetups` in the frontmatter.

### Moving a meetup to past
Move the file from `upcoming_meetups/` to `past_meetups/`, update `parent: Past Meetups`, and add slides/video links if available.

### Propose a talk
Talk proposals are handled via GitHub Issues in the [pydata-seattle/talks](https://github.com/pydata-seattle/talks) repo.

## Deployment

Pushes to `main` trigger the GitHub Actions workflow which builds and deploys to GitHub Pages automatically.

## Organizers

- **Olivia Xia** (Chair) — [LinkedIn](https://www.linkedin.com/in/xiangyang-liu-olivia)
- **Debjyoti Paul** (Co-organizer) — [LinkedIn](https://www.linkedin.com/in/debjyotipaul) · [GitHub](https://github.com/dpaul0501)

## Contact

<seattle@pydata.org>
