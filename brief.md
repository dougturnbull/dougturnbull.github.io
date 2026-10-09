# Doug Turnbull: academic portfolio brief

## Purpose
Create a short, single-page academic portfolio for Doug Turnbull and a classroom demo for ICSM 105, Day 21: VibeCoding 101. Deliver plain `index.html` and `style.css`, ready to upload to GitHub Pages. No JavaScript, frameworks, build tools, or installation required.

## Audience and goals
Help students, research collaborators, and journalists quickly learn about Doug, find selected research, and explore talks and media coverage. Provide a professional email link and links to the full blog and Google Scholar profile.

## Design and structure
Follow Ithaca College’s brand guide: IC blue (#003B71) for headings, links, and buttons, IC gold (#FFBB00) for decorative accents, and a white background with neutral gray text. Use Figtree for body copy and navigation and Source Serif 4 selectively for the name, section headings, and talk titles. These are the guide’s open-source substitutes for Calibre and Mercury. Bundle the fonts and their SIL Open Font License files locally so the site also works offline. Keep gold out of body text. Use generous spacing and simple publication lists. A real portrait from the bio page accompanies the introduction. Navigation links jump to Bio, Publications, Talks, and In the media. Stack the layout on phones. Include semantic headings, a skip link, visible keyboard focus, descriptive links, and portrait alt text. All local asset paths must be relative so the page works in GitHub Pages repository subdirectories and when opened directly.

## Final page content

### Introduction and bio
Doug Turnbull
Professor of Computer Science at Ithaca College
Music discovery, machine learning, and local communities.

I’m a professor of computer science at Ithaca College in Ithaca, New York. My research focuses on music information retrieval, machine learning, and local music recommendation.

I earned my Ph.D. in computer science at UC San Diego in 2008 and my B.S.E. at Princeton University in 2001. I teach programming, software development, machine learning, and human–computer interaction. Outside the classroom, I play guitar and enjoy trail running and soccer.

Contact: dturnbull@ithaca.edu

### Selected publications
Select the three highest-cited papers in the Google Scholar text supplied by Doug on October 9, 2026, alongside two recent works already verified on the blog. Label the historical selection “Most-cited work.” Show citation counts for those three papers with a dated source note. The Scholar snapshot also reports 4,431 total citations, h-index 28, and i10-index 45; keep these overall metrics out of the concise page. Do not imply counts update automatically.

Recent work:
- **Using Language Models for Music Recommendations with Natural-Language Profiles** — Paul Gagliano, Griffin Homan, Douglas Turnbull, Venkata S Govindarajan. MuRS workshop at ACM RecSys, 2025. Workshop paper. [Study and paper](https://dougturnbull.org/index.php/2025/10/03/music-recommendation-with-natural-language-profiles-murs-2025/).
- **Localify.org: Contextualizing Long-Tail Music for Local Artist Discovery** — Paul Gagliano, Griffin Homan, Cassandra Raineault, Ruth Ayambem, Bridget Burns, Douglas Turnbull. ISMIR, 2024. Late-breaking demo. [Study and paper](https://dougturnbull.org/index.php/2024/11/11/contextualizing-local-music-ismir24/).

Most-cited work (ranked by all-time citations in the supplied snapshot):
- **Music Emotion Recognition: A State of the Art Review** — Youngmoo E. Kim et al., including Douglas Turnbull. ISMIR, 2010. **770 citations**. [Paper PDF](https://ismir2010.ismir.net/proceedings/ismir2010-45.pdf).
- **Semantic Annotation and Retrieval of Music and Sound Effects** — Douglas Turnbull, Luke Barrington, David Torres, Gert Lanckriet. IEEE Transactions on Audio, Speech, and Language Processing, 2008. **705 citations**. [Paper PDF](https://web.cs.swarthmore.edu/~turnbull/Papers/Turnbull_SemanticAudio_TASLP08.pdf).
- **Playlist Prediction via Metric Embedding** — Shuo Chen, Joshua Moore, Douglas Turnbull, Thorsten Joachims. ACM KDD, 2012. **391 citations**. [Paper PDF](https://www.cs.cornell.edu/people/tj/publications/chen_etal_12a.pdf).

Page source note: Citation counts from Google Scholar text supplied October 9, 2026.

### Selected talks
- **Local Music is Important** — Music Recommender Systems Workshop, ACM RecSys, September 2023. Link to slides from the talks page.
- **Locally-focused Music Recommendation** — University of Rochester, Audio and Music Engineering, April 2021. Link to slides from the talks page.
- **Growing Local Music** — TEDxIthaca College, March 2014. Link to the full talk archive (no specific video link verified).

### In the media
- **Finding Community in the Local Music Scene** — IC Career Corner podcast with Malcolm Alexander, December 5, 2025. Link to episode.
- **Genuine or Generated: Faculty and Administration Weigh in on Artificial Intelligence** — Ithaca Times, August 23, 2023. Link to article.
- **Students create Localify app that localizes Spotify music** — The Ithacan, November 5, 2019. Link to article.

### Footer
Doug Turnbull · Ithaca, New York
Link to full website. Content updated October 2026.

## Sources and editorial notes
- [Ithaca College brand type](https://www.ithaca.edu/brand-guide/visual-system/brand-type) and [brand colors](https://www.ithaca.edu/brand-guide/visual-system/brand-colors), checked October 9, 2026.
- Google Scholar raw text supplied by Doug on October 9, 2026: top-three ranking and citation counts.
- Font files from Google Fonts, with SIL Open Font Licenses included in `fonts/`.
- [Bio](https://dougturnbull.org/index.php/biography/): role, research, education, teaching, interests, public professional email, and portrait.
- [Publications](https://dougturnbull.org/index.php/publications/): bibliography and publication categories. Paper PDF confirms KDD metadata. Recent blog posts confirm workshop/demo categories.
- [Talks](https://dougturnbull.org/index.php/talks/): exact titles, venues, dates, and slide links.
- [Media](https://dougturnbull.org/index.php/media/): coverage titles, dates, and destination links.
- [Google Scholar](https://scholar.google.com/citations?user=CaEaSR8AAAAJ&hl=en): provide a visitor link. Rank and counts now come from the user-supplied Scholar text, rather than automated access (which returned HTTP 429).
- Portrait source: https://dougturnbull.org/wp-content/uploads/2018/10/rw7_9424A-768x1024.jpg (saved locally as images/doug-turnbull.jpg).
- Lecture reference: `../21 VibeCoding 101.pptx`, especially slides 6–12. Match the static, accessible, phone/laptop, brief-first workflow. Use the user-requested singular `style.css` filename.
- Avoid stale claims about sabbaticals. Localify is historical in paper and article titles. The current blog says Localify was decommissioned in June 2026 and introduces ListenToLocal in August 2026, so do not describe Localify as an active service.

## Completion checks
Verify local links and assets, keyboard navigation, and laptop and phone layouts. Deliver editable source files and a short README with GitHub Pages upload instructions. Hosting is left to the user’s GitHub repository.
