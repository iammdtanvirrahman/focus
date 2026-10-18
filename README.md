# Focus — Independent Premium Dark Platform

Focus is being rebuilt as an independent, dark-first admissions and learning experience. The interface uses midnight black/navy surfaces with restrained cyan-blue accents and Focus-inspired crimson.

## Pages
- `index.html` — public marketing homepage, course categories, student services, success-story section and portal entry.
- `login.html` — independent login/register frontend UI.
- `portal/index.html` — student dashboard frontend structure.
- `online/index.html` — compatibility entry route that forwards to the new Focus login.
- `favicon.svg` — Focus-inspired placeholder emblem.

## Preview
- Public website: https://iammdtanvirrahman.github.io/focus/
- Login: https://iammdtanvirrahman.github.io/focus/login.html
- Student dashboard UI: https://iammdtanvirrahman.github.io/focus/portal/
- Portal alias: https://iammdtanvirrahman.github.io/focus/online/

## Deployment
GitHub Actions deploys the static files from `main`. The workflow is in `.github/workflows/deploy.yml`.

## Important
This is an independent front-end implementation. Login, registration, password reset, course enrollment, real student data, exam results, payments and administrative tools do not work without a secure backend, database and authentication integration. The login form intentionally does not store or transmit credentials. Course descriptions and all official claims should be verified by Focus before public production use. The current logo mark is a placeholder recreation, not an official source asset.
