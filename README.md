# TAMU NLP

Static website for the Natural Language Processing Group at Texas A&M University.

Open `index.html` directly, or run `python3 -m http.server 8000` from this folder and visit <http://localhost:8000>.

Edit `index.html` to update the group introduction, faculty and students, alumni, news, papers, and contact information. Students are listed by role and then by family name. Page styles are in `styles.css`. Photos and university marks are in `assets/`.

## Hosting on GitHub Pages

Publish the contents of this folder at the root of a GitHub Pages repository. For a custom domain such as `nlp.cse.tamu.edu`, configure the domain in Pages and ask TAMU IT to set up the DNS record. Once the domain is set, change `og:image` in `index.html` to an absolute URL.
