# Yantong Liu — Personal Website

Source code for [littlelisa18.github.io](https://littlelisa18.github.io), the academic homepage of Yantong Liu.

The site presents research interests, education, selected publications, experience, honors, and academic service, with links to papers, project pages, Google Scholar, GitHub, and email.

## Highlights

- responsive single-page academic portfolio;
- pastel pink, yellow, and blue visual system;
- publication cards with teaser and method figures;
- lightweight reveal animations using `IntersectionObserver`;
- semantic HTML and keyboard-accessible navigation;
- no build framework or runtime dependencies.

## Structure

| File | Description |
| --- | --- |
| `index.html` | Page content and section structure |
| `styles.css` | Responsive layout, typography, colors, and components |
| `script.js` | Scroll-triggered reveal behavior |
| `avatar.jpg` | Profile photograph |
| `favicon.svg` | Rabbit-themed site icon |
| `papers/` | Publication figures |

## Run locally

```bash
git clone https://github.com/LittleLisa18/LittleLisa18.github.io.git
cd LittleLisa18.github.io
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

GitHub Pages publishes the `main` branch at <https://littlelisa18.github.io>. After editing:

```bash
git add .
git commit -m "Update personal website"
git push origin main
```

GitHub Pages may take a few minutes to refresh.

## Updating content

- Edit biography, education, publications, and experience in `index.html`.
- Add publication images under `papers/` and use relative paths in the corresponding card.
- Adjust the palette and spacing in `styles.css`.
- Keep external links using `target="_blank"` together with `rel="noreferrer"`.

## Contact

- Website: <https://littlelisa18.github.io>
- GitHub: [@LittleLisa18](https://github.com/LittleLisa18)
- Email: [yantong@connect.hku.hk](mailto:yantong@connect.hku.hk)
