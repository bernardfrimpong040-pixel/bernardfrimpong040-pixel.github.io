# bernardfrimpong040-pixel.github.io

Personal portfolio website of **Bernard Frimpong**, data analyst (credit analytics, survival analysis, disease forecasting, machine learning).

Live site: https://bernardfrimpong040-pixel.github.io

## What is in this repo

| File | What it is |
|---|---|
| `index.html` | The whole website in one file (HTML + CSS + a few lines of JavaScript). No build step. |
| `Bernard_Frimpong_CV.pdf` | My CV, linked from the "Download CV" button. |
| `now.html` | The "Now" page: what I'm working on this week. |
| `assets/bernard.jpg` | Headshot used on the home page. |
| `assets/og-card.jpg` | Preview image shown when the site link is shared on LinkedIn and elsewhere. |
| `assets/charts/` | Project charts (PNG). Each project card shows its chart once the file exists here. |
| `blog/index.html` | The list of all blog posts. |
| `blog/blog.css` | Shared styles for the blog pages (same colours and fonts as the home page). |
| `blog/posts/*.html` | One file per post. |
| `blog/posts/_template.html` | Copy this to start a new post; instructions are at the top of the file. |
| `blog/images/` | Put plots and figures for posts here. |
| `README.md` | This file. |

## How it is hosted

The site is served free by **GitHub Pages**. Because the repository is named
`<username>.github.io`, GitHub publishes `index.html` from the `main` branch automatically.
Every `git push` updates the live site within a minute or two.

## How to update it

1. Open `index.html` in VS Code.
2. Each section is marked with its id: `about`, `projects`, `research`, `writing`, `skills`, `experience`, `contact`.
3. To add a project, copy one `<article class="proj"> ... </article>` block, paste it below the others, and change the text and GitHub link.
4. Preview locally by double-clicking `index.html`, then commit and push.

## How to update the Now page

Open `now.html`, change the date and the bullet points, and update the one-line "Now" text in `index.html`. Every week or two is plenty.

## How to add a project chart

Save a PNG with the exact file name below into `assets/charts/`. Until a file exists, its card simply shows no chart.

| Project | File name |
|---|---|
| Credit portfolio | `credit-vintage-losses.png` |
| Leukemia survival | `aml-km-risk-groups.png` |
| FluSight | `flusight-forecast.png` |
| Kaggle airline | `kaggle-auc-rounds.png` |

## How to write a new blog post

1. Copy `blog/posts/_template.html` and rename it, e.g. `flusight-week-1.html` (lowercase, hyphens).
2. Edit the title, date and text. Put any plot images in `blog/images/`.
3. In `blog/index.html`, copy one `<li> ... </li>` block to the top of the list and point it at the new file.
4. Optionally add it to the Writing section of `index.html`.
5. Commit and push.

## Posts

- [How a leaky encoding made my CV score lie by 8×](blog/posts/target-encoding-leakage.html)
- [Testing a survival model on a hospital it has never seen](blog/posts/validate-on-unseen-hospital.html)

## Projects featured

- [Commercial Credit Portfolio Analysis](https://github.com/bernardfrimpong040-pixel/credit-portfolio-analysis)
- [Leukemia Overall Survival Prediction](https://github.com/bernardfrimpong040-pixel/aml-survival-prediction)
- [CDC FluSight Influenza Forecasting](https://github.com/bernardfrimpong040-pixel/flu-forecasting-sirs)
- [Airline Passenger Satisfaction (Kaggle)](https://github.com/bernardfrimpong040-pixel/kaggle-airline-satisfaction)
