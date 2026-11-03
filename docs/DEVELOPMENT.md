# Development and maintenance

## Run locally

From the repository root, run `python3 -m http.server 5500`, then open [localhost:5500](http://localhost:5500). Python 3 is only a development-server option; VS Code Live Server also works. Stop the server with Ctrl+C. No package installation or build is required to serve this checkout.

## Implementation and boundaries

A static CV page with no account or backend. Personal and career information is authored in HTML.

## Make changes

Update experience, education, skills, and contact links in the HTML entry page; review personal details before publishing.

## Source map

- [`single-page-cv.html`](../single-page-cv.html)
- [`styles.css`](../styles.css)

## Verification

No automated test command is provided by this repository. The following manual checks are a checklist, not a claim that browser QA has been completed.

1. Review the complete CV on a phone and desktop and check heading order.
2. Check contact links and print preview for clipping or split sections.
3. Inspect the browser console and Network panel for missing assets or script errors; check keyboard access, phone width, and 200% zoom.

## Deployment

Serve the tracked HTML, CSS, JavaScript, and required assets from a static host, preserving relative paths and filename case. There is no application server or environment-variable configuration in this checkout. Verify the actual deployment URL, external resources, and the checks below after publishing. A repository existing on GitHub does not by itself prove Pages is enabled.

## Keep documentation current

Update the README and this guide when entry points, dependencies, behavior, or deployment steps change. Record commands actually run and distinguish them from pending manual checks.
