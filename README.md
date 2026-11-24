# Y9 Searching · interactive workbooks

Static site for GitHub Pages. No build step. Same engine and style as `y10-searching-sorting`.

```
index.html            landing page (links to each lesson)
lesson-1/index.html   Lesson 1 · Linear Search Code Builder (Task 4)
.nojekyll
```

Live at https://eltham-college-cs.github.io/y9-searching/lesson-1/ once Pages is turned on (Settings → Pages → Deploy from branch → main / root).

## Lesson 1 · Linear Search Code Builder
- Task 4 from the Year 9 linear search lesson: students build the program one line per box (11 lines). Each line is checked with a plain-English error message; curly brackets for blocks are added automatically in the assembled program.
- Same algorithm as the lesson's worked example: `position = -1`, `break` at the first match, decide "Not found" after the loop. Input uses `Convert.ToInt32` (Year 9 house style).
- Two trace tables (input 23 and input 50) are **compulsory**: the task only shows ✓ Complete when every line and both traces are right. Each table has two spare rows that must be left blank, so students have to spot where the loop stops.
- CodeBash (Year 9 Programming › Extensions, topic 173): task 1871 *C# · Linear Search: Is It There?* (★★, same program) and task 1872 *C# · Linear Search: Count the Comparisons* (★★★ follow-on). Both pages point students to them.
- Teacher mode: add `#teacher` to the URL. Shows the trace answers and a ▶ Model button that types each line live.
- Answers save in the browser (localStorage key `y9-linear-builder-v1`) on that device. Nothing is sent anywhere.
