# Georgia Tech ML qualifying report starter

## Included
- main.tex: root document with title page and table of contents.
- metadata.tex: student name, home school, date, and title; name follows the supplied Asal Roudbari committee form.
- chapters/: approved eight-chapter outline, Section 1.1, and drafting notes for the remaining sections.
- references.bib: the four assigned papers; only the two cited in Section 1.1 print in the current bibliography.
- REPORT_CONTEXT.md: narrative, writing rules, progress, and handoff instructions.

## Upload and compile
1. In Overleaf choose New Project > Upload Project and select the ZIP.
2. Select main.tex as the main document if Overleaf does not select it automatically.
3. Use pdfLaTeX. Overleaf manages BibTeX automatically.
4. Edit metadata.tex if the title-page details need changing.

The report uses a standard LaTeX report class with the margins and Times-style typography of the supplied Georgia Tech thesis template. It has a qualifying-exam title page. This layout is a writing choice, not a claim about mandatory qualifying-exam formatting. Drafting notes are visible so unfinished text cannot be mistaken for completed scholarship. Replace each note as its section is written.

Local build: latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex

## Connect the uploaded Overleaf project to GitHub
GitHub synchronization requires an eligible Overleaf premium or institutional subscription.
1. Open the project as its owner.
2. Open Integrations in the left sidebar and select GitHub.
3. Link/authorize the GitHub account when prompted.
4. Create a new repository from this Overleaf project, for example qual-report. Choose private visibility when available; check the resulting repository visibility.
5. Use Integrations > GitHub to push Overleaf changes or pull GitHub changes. Synchronization is manual.

Start this flow from Overleaf. Its direct integration creates a new repository from an existing Overleaf project; it does not join an existing project to an independently created existing repository.

Before another writing session, push your latest Overleaf edits to GitHub and share the repository URL. After changes arrive in GitHub, pull them into Overleaf and recompile. A private repository also needs to be authorized in the assistant's GitHub connection. Keep REPORT_CONTEXT.md current so subsequent sessions can recover both the prose and the reasoning behind it.

Official instructions checked November 5, 2026:
https://docs.overleaf.com/integrations-and-add-ons/git-integration-and-github-synchronization/github-synchronization

## Sources
Dynamic-DeepHit: https://doi.org/10.1109/TBME.2019.2909027
ODTP: https://doi.org/10.1109/TBME.2020.3041815
CAMELOT: https://proceedings.mlr.press/v162/aguiar22a.html
VaDeSC-EHR: https://doi.org/10.1038/s41467-025-56625-z
