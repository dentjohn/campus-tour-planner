# Campus Tour Planner

A single-file web app that helps a high school student decide which colleges to tour.
Answer six short sections (academics, sports, activities, service, interests, campus fit)
and get a Reach / Match / Likely board of ~175 colleges, a tour list grouped into trips,
tailored questions to ask on each visit, and a downloadable PDF report.

- `index.html` is the whole app. No build step, no server.
- Each student's answers save in their own browser; they can also save/load a `.json` file.
- Admissions figures are approximate (rounded from recent Common Data Set publications). Confirm on each school's site.
- To edit the college list, open `index.html` and change the `const C = [...]` array near the top of the script: one line per school.

Hosted with Netlify.
