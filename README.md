# Concurrent Computing Curricula for Cyber-Physical Systems

Project website for the NSF CyberTraining: Pilot collaborative awards
[OAC-2612129](https://www.nsf.gov/awardsearch/show-award/?AWD_ID=2612129) (Western Michigan University) and
[OAC-2612130](https://www.nsf.gov/awardsearch/show-award/?AWD_ID=2612130) (Michigan Technological University).

Live site: <https://stevenmcarr.github.io/cybertraining-cps/>

## Structure

Static HTML and CSS served by GitHub Pages from `main`. One page per section, all sharing `style.css`
and the same top navigation:

| File | Page |
| --- | --- |
| `index.html` | Home |
| `about.html` | About the project |
| `modules.html` | Learning modules |
| `tools.html` | Tools (wrappers, visualization, CEDL) |
| `timeline.html` | Schedule and evaluation |
| `team.html` | Team and mentoring |
| `awards.html` | NSF awards and abstract |
| `materials.html` | Materials and software releases |

## Editing

Edit the HTML directly and push to `main`; Pages rebuilds automatically. To add a page, copy an existing
one, update the `<title>`, the `<h1>`, and the nav block, and add the same link to the nav of every other page
(`aria-current="page"` marks the current page).

To preview locally:

    python3 -m http.server 8000
