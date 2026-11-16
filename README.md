# Sunayana Sitaram | Academic website

A minimal, responsive static academic website for GitHub Pages. Includes Home, Research, Group, Hiring, and Contact pages.

## Deploy

1. Create a GitHub repository named `YOUR-USERNAME.github.io` (or a standard project repository).
2. Upload all the files and the `assets` directory to the repository root.
3. In GitHub **Settings > Pages**, choose **Deploy from a branch**, branch `main`, directory `/ (root)`.
4. The site will be served at `https://YOUR-USERNAME.github.io/`, or at the repository subpath for project repositories.

## Headshot

The image on the Home and Group pages is linked to the IndiaAI headshot URL supplied by the website owner:
`https://impact.indiaai.gov.in/events/symposium/coreCommittee/Sunayana_Sitaram.jpeg`

The remote image could not be downloaded in the authoring environment. It will display when the IndiaAI host permits access by visitors' browsers. For a reliable permanent image, download your headshot yourself into `assets/profile.jpg`, then change the `src` attribute in `index.html` and `group.html` to `assets/profile.jpg`. A local placeholder is used if the original URL is inaccessible.

## Content notes

- IISc is presented as the current affiliation and Microsoft Research India as prior experience.
- Plural AI Lab is presented as the academic research group, distinct from the Center for AI Evaluation.
- The Contact page provides guidance for speaking and consulting inquiries.
- The Hiring page discusses research interests and possible recruitment areas without asserting that vacancies are currently open.
- Google Scholar links are searches rather than a verified personal profile URL. These can be replaced with direct URLs for your publications.
- Update the Group page as appointments are confirmed.

No build tools, scripts, or frameworks are necessary. Edit HTML and CSS directly.
