# Arjun Agrawal · IB DP Economics

**Think like an economist.**

A free, browser-based learning environment for IB Diploma Programme Economics, built by
**Arjun Agrawal** — IB DP Facilitator (Economics · Business Management · Global Politics),
Symbiosis International School, Pune.

Learn the concept. See the model. Build the chain. Stress-test the argument. Make the
judgement. Apply it under pressure.

---

## What this is

Not a content repository. A system for practising the sequence that IB DP Economics
actually assesses:

> cause → behaviour → market effect → second-round effect → wider consequence → evaluation → judgement

Everything runs in the browser. There is no account, no server, no tracking, and no AI API.
A student can download `index.html`, double-click it, and work offline.

## Who it is for

- **Students** taking IB DP Economics at SL or HL, at any point from first lesson to final exam.
- **Teachers** who want accurate diagrams, classroom-projectable models, misconception tools,
  question banks and assessment reasoning they can use directly in a lesson.

## What it contains

| Section | What it does |
|---|---|
| **Learn** | Every concept in nine stages: the idea, intuition, the model, the diagram, the chain, the application, the stress test, the IB connection, retrieval. Plus a curriculum map and a misconception lab. |
| **Think** | The Economic Chain — build a mechanism link by link against a live shock, then survive a conditionality test and choose between four judgements. Plus an evaluation stress test across fourteen dimensions. |
| **Lab** | Computed market and AD–AS models you can move, a transparent policy simulator, a 28-diagram library, a counterfactual "What if?" lab and a policy Decision Room. |
| **Calculate** | The Calculation Board: 22 IB DP Economics calculations with live working, units, interpretation, common mistakes, linked diagrams and generated practice that hides the solution until you attempt it. |
| **Real World** | Six recurring economic events, each split into fact, interpretation and inference, with the data trail routed to named primary sources. |
| **Practise** | Question bank, data response, the Economist's Gym, a spaced retrieval queue and a ten-minute revision run. |
| **Exam** | An exam cockpit for Papers 1, 2 and 3 with plan–write–review, timer, word count and autosave; a sentence-by-sentence answer diagnostic; "Why did I lose marks?"; a Level 7 deconstructor; and the IB reference layer. |
| **My syllabus** | Every topic tracked on three separate layers — learn, practise, master — with manual states from *Not started* to *Mastered*, spaced revision dates and private notes. |
| **Dashboard** | A twelve-dimension learning model built only from evidence you generated, plus syllabus coverage, revision due and one recommended next action. |
| **My workspace** | Weekly study plan, mistake book, flashcards with spaced review, and your calculation history ranked weakest first. |
| **IA** | A supervisor's workflow for the internal assessment portfolio, checked against the published criteria. |
| **Teacher tools** | Class dashboard with local import of student exports, a fillable IA feedback checklist, lesson planner, five-minute retrieval starter generator, exam builder with answer key, and printable marking sheets — all printable with the Arjun Agrawal attribution. |
| **Tutorials** | One-to-one IB DP Economics sessions with Arjun Agrawal. |

## Educational philosophy

A definition recalled without its mechanism is inert. A diagram drawn without an argument
attached to it earns almost nothing. So the platform puts the mechanism first, and everything
else attaches to it:

**Understand → Visualise → Connect → Analyse → Stress-test → Judge → Apply**

That framework is a teacher's framing, not IB terminology, and the platform labels it as such.

## Honesty rules the platform holds itself to

- **Five claim layers, never blurred:** official IB information · established economic theory ·
  Arjun Agrawal teaching frame · teacher-created practice · constructed teaching data.
  Assessment claims carry a source, a version and a verification date.
- **No fabricated data.** No figure is asserted in the Real World section; every story routes
  its numbers to named primary institutions. All lab and drill figures are labelled as
  constructed teaching data.
- **The diagnostic is rules-based**, teacher-designed, and built on the published assessment
  framework. It is not an official IB mark and the platform says so wherever it appears.
- **No fabricated social proof.** No testimonials, ratings, student counts, success rates or
  grade guarantees anywhere.
- **No invented credentials.** The About page contains only details supplied by Arjun Agrawal.

## Technology

- A single self-contained `index.html`. No framework, no bundler, no dependencies to install.
- Diagrams are generated as SVG from explicit economic relations, so the picture and the
  numbers cannot disagree.
- Fonts load from Google Fonts when online and fall back to system fonts when not. Nothing
  else is fetched.
- Progress is stored in `localStorage` on the student's own device.
- The build includes a self-test of **120 checks** across branding, IB accuracy, learning content,
  diagrams, assessment tools, profiles and progress, teacher tools, navigation and technical behaviour. Open the browser console to
  see the category report.

## Profiles and personalisation

On first launch the platform asks for a name, a level and — optionally — a target grade, exam session and usual study block. Several people can share one computer: each profile stores its own progress, notes, plan, mistakes, flashcards, drafts and mastery model, and profiles can be created, switched, backed up, restored and deleted from the profile drawer.

Personalisation sits *beneath* the platform identity. The workspace becomes "Aarav's Economics dashboard" inside **Arjun Agrawal · IB DP Economics** — the brand is not replaceable, and every printed or exported document carries the attribution.

Storage is versioned (`AA_IB_ECONOMICS`, schema v5) with migration logic, so future updates extend the structure rather than discarding existing progress.

## Privacy

**Student progress stays on the device unless the student exports it.**

No accounts, no sign-in, no analytics, no tracking pixels, no cookies set by this site, and no
data transmitted anywhere. Export, import and reset are all in **Master → Your data**.

## Run it locally

Download or clone the repository and open `index.html` in any modern browser. Double-clicking
the file is enough — there is no build step and no server required.

```bash
git clone https://github.com/<your-username>/arjun-agrawal-ib-economics.git
cd arjun-agrawal-ib-economics
# then open index.html
```

`index.html` is fully self-contained: the logo, portrait, diagrams and all logic are embedded.
You can email that one file to a student and it will work on its own.

## Publish it on GitHub Pages

**1. Create the repository**

Sign in to GitHub → **New repository** → name it `arjun-agrawal-ib-economics` → set it to
**Public** → **Create repository**. Do not add a README; this repository already has one.

**2. Upload the files**

On the empty repository page choose **uploading an existing file**, then drag in the contents
of this folder — `index.html`, `README.md`, `LICENSE`, `.gitignore`, `404.html`, `favicon.svg`
and the `assets` folder. Commit directly to the `main` branch.

> The `.github` folder is hidden on macOS. In Finder press `Cmd + Shift + .` to show hidden
> files before dragging, or skip it — see step 3b.

**3a. Enable Pages using the workflow (recommended)**

Repository → **Settings** → **Pages** → under **Build and deployment**, set **Source** to
**GitHub Actions**. The included workflow at `.github/workflows/pages.yml` publishes the site
on every push to `main`.

**3b. Or enable Pages without the workflow**

Repository → **Settings** → **Pages** → **Source: Deploy from a branch** → **Branch: `main`**,
**Folder: `/ (root)`** → **Save**. This works even if you did not upload the `.github` folder.

**4. Visit the live site**

After a minute or two it will be available at:

```
https://<your-username>.github.io/arjun-agrawal-ib-economics/
```

The Pages settings screen shows the exact URL once deployment finishes.

**5. Update it later**

Edit or replace `index.html` in the repository (**Add file → Upload files**, keeping the same
filename) and commit. The site updates automatically within a minute.

**Optional — a custom domain:** Settings → Pages → **Custom domain**, then add the CNAME record
your domain provider asks for.

## Licence

Two licences apply, and the distinction matters:

- **The code is MIT licensed.** Reuse, adapt and learn from it freely.
- **The educational content and brand are not.** The Arjun Agrawal name, logo, photograph,
  written explanations, teaching frames, questions, exemplars and diagram designs remain the
  author's property and are not licensed for reuse or redistribution.

Teachers and students are welcome to use the site in lessons and to link to it. Republishing
the content as your own, or repackaging it commercially, is not permitted.
See [`LICENSE`](LICENSE) for the full terms, or write to arjun1agr@gmail.com.

## Tutorials

One-to-one IB DP Economics sessions — full syllabus, revision, Papers 1, 2 and 3, internal
assessment and extended essay. Guidance, coaching and feedback; not ghostwriting.

**US$20 per 90-minute one-to-one online session.** Group discounts available.

To enquire, email **arjun1agr@gmail.com** with your grade level, whether you are SL or HL, your
school, what you would like help with, and your preferred days and times.

## Credits and disclaimer

Built by **Arjun Agrawal**, IB DP Facilitator — Economics, Business Management and Global
Politics — Symbiosis International School, Pune. Academic background: St. Stephen's College,
University of Delhi. Previously Assistant Professor at Fergusson College.

**This is an independent educational resource created by Arjun Agrawal. It is not affiliated
with or endorsed by the International Baccalaureate Organization.** "International
Baccalaureate", "IB" and "Diploma Programme" are registered trademarks of the International
Baccalaureate Organization.

Contact: **arjun1agr@gmail.com**
