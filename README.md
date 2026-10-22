# Colton D. Meinecke — professional website

A responsive, custom-designed Jekyll website for GitHub Pages. No paid theme, external fonts, JavaScript dependencies, or subscription is required. Text is edited in Markdown.

## Publish for free

1. Sign into GitHub (or create a free account).
2. Create a **public** repository called `YOUR-USERNAME.github.io`, replacing YOUR-USERNAME with your exact GitHub username. If that repository already exists, back it up and review its contents before replacing anything.
3. Unzip this package. Upload **the contents** of this folder to the repository root, not the enclosing folder or ZIP. Include `_config.yml`, `_layouts/default.html`, all five Markdown pages, `Gemfile`, and `assets/style.css`. On GitHub use **Add file → Upload files**. Commit the upload to `main`.
4. In the repository open **Settings → Pages**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Check the Pages build in the repository’s **Actions** tab. When it succeeds, visit `https://YOUR-USERNAME.github.io/`.

GitHub handles Jekyll builds. You do not need to install Ruby, Jekyll, or Git on your computer. The repository and deployed website are public.

## Update in your browser

Open the relevant file in GitHub, click the pencil (Edit), change the text, then choose **Commit changes**. A successful Pages build publishes the change automatically.

| File | Edit this to change |
| --- | --- |
| `index.md` | Homepage and introduction |
| `research.md` | Research descriptions |
| `publications.md` | Publications and manuscript statuses |
| `teaching.md` | Teaching, mentoring, outreach, and service |
| `cv.md` | Education, experience, and contact |
| `_config.yml` | Site title, description, and footer email |
| `assets/style.css` | Colors, typography, and layout |
| `_layouts/default.html` | Shared navigation, metadata, and footer |

For Markdown, `## Heading` creates a heading, `**text**` creates bold, `*text*` creates italics, and `[Label](https://example.org)` creates a link. Keep the three-dash metadata block at the top of each page intact. Homepage sections use HTML for layout; edit the words between tags without removing the tags.

## Personalize

- Optional portrait: upload `assets/portrait.jpg`, then add `<img src="{{ '/assets/portrait.jpg' | relative_url }}" alt="Colton Meinecke" width="280">` to `index.md`.
- Optional CV: upload a public-facing PDF as `assets/cv.pdf`, then follow the comment at the bottom of `cv.md`. No incomplete download button is shown.
- Add verified Google Scholar, ORCID, or GitHub links to `cv.md` when available.
- Keep in-press and in-preparation statuses current in `publications.md`. These were preserved from the supplied CV; external publication statuses have not been independently verified.
- Review affiliations, titles, manuscript statuses, and the draft research descriptions before publication. No phone number, street address, or unedited original CV is included.

## Other repository names

For a project repository such as `professional-site`, set `baseurl: "/professional-site"` in `_config.yml`. The address will be `https://YOUR-USERNAME.github.io/professional-site/`. Leave baseurl empty for YOUR-USERNAME.github.io.

## Optional local preview

With Ruby and Bundler installed: `bundle install`, then `bundle exec jekyll serve`. Open the localhost address it prints.

## Verification

Source files and internal target paths were checked during preparation. A full Jekyll build was not run in the preparation environment because Ruby was unavailable. The first GitHub Pages build is the final deployment check.

## Official help

https://docs.github.com/en/pages/getting-started-with-github-pages/quickstart
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
