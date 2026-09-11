# Publish Dhaval's GitHub profile

## Files to upload

Upload `README.md` and the entire `assets` folder to the ROOT of the profile repository. Keep their names and folder structure unchanged. The `docs` folder is optional and is not shown on the profile.

```text
YOUR-GITHUB-USERNAME/
  README.md
  assets/
    hero-dark.svg
    hero-light.svg
    ...all remaining SVG files...
  docs/                  # optional setup and content notes
```

Do not upload the ZIP itself. Extract it first. Do not put the containing `dhaval-bhanderi-profile` folder inside the repository: its contents belong at the root.

## Publish through GitHub

1. Sign in to Dhaval's own GitHub account.
2. Create a PUBLIC repository whose name exactly matches his GitHub username. For example, an account named `example-user` needs `example-user/example-user`. That is an example, not an assumed username.
3. Add the provided `README.md` and `assets` folder to the root. On GitHub, use **Add file > Upload files**, then commit to the default branch.
4. Open Dhaval's profile and check the result.

For an existing profile repository, preserve any existing content you still need and update these files through a normal commit. Do not delete unrelated files or force-push.

The default profile needs no token, external badge service, GitHub Action, GitHub Pages deployment, or username replacement. All visual assets are in this repository. It also has no tracking pixels, visitor counter, or fabricated GitHub statistics.

The light/dark banners use GitHub-supported `<picture>` markup. Preview the committed README on GitHub, since local Markdown renderers can behave differently.

Official instructions:
- [Managing your profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
- [Responsive images and advanced Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)

## Profile sidebar suggestions

These settings are separate from the README. They are suggested text, not account changes already performed.

**Name:** Dhaval Bhanderi

**Bio:** Founder at DI Solutions | Building AI, web & mobile products | Practical engineering. Long-term partnerships.

**Company:** DI Solutions

**Location:** Surat, India

**Website:** https://disolutions.net/

**LinkedIn:** https://www.linkedin.com/in/dhavalbhanderi/

Keep `solutions@disolutions.net` labeled as a business/company contact rather than a personal email address.

## Customization

- Edit the Markdown to adjust tone, focus areas, and selected case studies.
- The SVG files are ordinary editable text. They contain no fonts, JavaScript, or external image references.
- Team technologies and portfolio projects are intentionally presented as DI Solutions work, not as personal mastery of every tool or sole authorship of every project.
- Review first-person positioning before publishing: the opinions and working-style statements are drafted profile copy, not quotations taken from an interview.
- Exact GitHub username and owned public repositories were not supplied. No account was guessed. Optional activity instructions are in `OPTIONAL-STATS.md`.

## Preview

The separately provided `Dhaval-Bhanderi-Profile-Preview.html` is a self-contained local preview. Open it in a browser and change your browser or operating-system theme to see light/dark variants. The preview is not a deployed website and does not need to be uploaded to the GitHub repository.
