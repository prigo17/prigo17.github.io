# Priyansh’s board

A small personal website styled as a corkboard with paper notes. Built with HTML and CSS, with no JavaScript or build dependencies.

## Preview

Run from this folder:

```sh
python3 -m http.server 8000 --directory public
```

Open http://localhost:8000.

## Personalise

Edit `public/index.html` to change the introduction, projects, interests, and links. The initial content is based on your latest résumé and public GitHub projects. Interests reflect your technical work; add personal hobbies whenever you like.

Change colours and layout in `public/styles.css`. Assets use relative paths so the site works at both `username.github.io` and `username.github.io/repository/`.

## GitHub Pages

The included workflow publishes only the `public` directory. It runs on pushes to `main` or `master`, or manually from the Actions tab.

1. Push this folder to your GitHub repository. For a profile website, name the repository `prigo17.github.io`.
2. In **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source.
3. Run **Deploy website to GitHub Pages** from the Actions tab, or push a change to your default branch.
4. The completed deployment provides the live URL.

See the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages).

The locally bundled Patrick Hand font is licensed under the SIL Open Font License; see `public/fonts/OFL.txt`.
