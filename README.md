# Summer Student Repository

This repository is used to document research progress, share code and figures, and store final deliverables during the internship.

Each student has a folder under:

```text
students/firstname_lastname/
```

Work only inside your own folder.

---

## For Students

### Getting Started

Clone the repository:

```bash
git clone <repo-url>
cd <repo>
```

Create a branch for your work:

```bash
git checkout -b alice/work
```

You may reuse the same branch for all work or create new branches whenever useful.

---

### Your Folder

Inside your folder you can add anything:

- blog entries
- notes
- figures and pictures
- scripts and notebooks
- presentations, reports, posters, papers

Use whatever file formats make sense. **Large datasets should not be committed to GitHub** — ask your mentor where to put them.

---

### Updating Your Work

```bash
git add students/alice_smith/
git commit -m "update blog and figures"
git push
```

Then open a Pull Request on GitHub. You may open PRs frequently, occasionally, or whenever you want feedback — there is no required schedule.
Ask your mentor who will merge the PR? It can be you or your fellow intern or your mentor.
---

### Blog Entries

Update `blog.md` regularly with what you worked on, problems encountered, results, and next steps. Short entries are completely fine.

---

### Deliverables

Upload final deliverables to:

```text
students/alice_smith/deliverables/
```

Any format is fine — pdf, pptx, tex, docx, md, zip. Use clear filenames.

**SULI students** — three required deliverables:
1. Poster (PPT/PDF)
2. Research Report Paper (DOCX/PDF) (This is technical documentation)
3. Blog-style science article on your work in markdown with no more than 5 figures or pictures. This is documenting your experiences as well as work for non-technical audiences.

For the blog article, use these as a guide:
- Who am I and what am I doing?
- Why is this work important?
- What instruments, sensors, or data am I using?
- What is the approach / methodology?
- What is next?
- Brief conclusion and references

---

### Communication

Use **Slack** for questions, updates, and meeting coordination.

Use **GitHub Pull Requests** for code review, figure feedback, and keeping a record of your progress.

---

## For Mentors

### Setup

1. Create a new repository from this template
2. Add student names to `config/students.yml`:

```yaml
students:
  - alice_smith
  - bob_jones
```

3. Commit and push — student folders will be created automatically
4. Add students as repository collaborators (Settings → Collaborators)

### Mentoring

Students work in their own folders and open Pull Requests whenever they want feedback or want to merge work. Review blog updates, figures, scripts, and reports through PR comments.

The repository is intentionally lightweight — a shared research notebook and archive, not a project management system.
