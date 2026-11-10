# Priyadarshini M N — Portfolio

A small multi-page portfolio made with plain HTML, CSS, and JavaScript. Each project has its own case-study page with a clear next/previous path; it does not rely on a long single-page scroll.

## Preview locally

Open `index.html` in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Add your resume

Place your PDF in this folder beside `index.html`, named exactly `resume.pdf`. The Contact page's download button points to that file.

## Pages

- `index.html` — home
- `projects.html` — project index
- `cybertrace.html`, `bugvertex.html`, `meeting-insights.html` — separate project case studies
- `about.html` — education, skills, certifications, and leadership
- `contact.html` — email, LinkedIn, and GitHub

The Meeting Insights diagram is labeled as an illustrative workflow, not a product screenshot. It has no repository link because one was not provided. BugVertex-AI retains attribution to the original RootCause project.

## Publish with GitHub Pages

Push the site files to a GitHub repository. In **Settings → Pages**, select **Deploy from a branch**, then choose the branch and `/ (root)` directory containing `index.html`. Save and use the URL shown in the Pages settings screen. For a repository that also contains application code, use a Pages GitHub Actions workflow that deploys only these static portfolio files.
