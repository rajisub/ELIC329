# Digital Systems Design — Student Portfolio Template

This repository contains a four-project report website built with GitHub Pages and Jekyll. Edit the Markdown files; no HTML is required.

## Student setup (recommended: Use this template)

1. Sign in to GitHub and open the instructor's template repository.
2. Select **Use this template → Create a new repository**.
3. Choose your account (or team organization) as owner. Name the repository, e.g. `digital-systems-portfolio`. Select **Public** (unless your instructor has arranged private Pages hosting), then create it.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then **Save**.
5. Wait for the published site link to appear under **Settings → Pages**. Its typical address is `https://USERNAME.github.io/REPOSITORY/`.
6. Open `index.md`, click the pencil icon, replace the bracketed placeholders, and commit changes.
7. Edit `projects/project1.md` through `projects/project4.md`. Preserve the YAML front matter (the lines between `---` at the top).
8. Upload VHDL files, testbenches and XDC constraints to the corresponding `source/projectN/` folder. Upload figures/screenshots/photos to `assets/projectN/`. Match the filenames used in the Markdown or update the image links.
9. Add working source links in each project's **Code** section. For example, a relative Markdown link from `projects/project1.md` to a repository file can be written as `[design.vhd](../source/project1/design.vhd)`; for a robust published-site link, use `{{ '/source/project1/design.vhd' | relative_url }}` in the link target.
10. Check the published website, all four project links, images, code links, and formatting. Submit both your repository URL and published website URL to your instructor.

## Alternative: Fork

Select **Fork** on the instructor repository, create your own fork, and enable Pages using step 4 above. A fork remains associated with the instructor's repository; **Use this template** is preferred for independent student submissions.

## Editing checklist (for every project)

- [ ] Introduction: project idea and objectives
- [ ] Design: explanation and labelled block diagram
- [ ] Code: design VHDL, testbench and relevant XDC, with explanations
- [ ] Simulation: waveforms for all required scenarios and analysis of expected vs. observed results
- [ ] Hardware: elaborated and synthesized schematics, implementation, utilization and Basys3 behaviour
- [ ] Reflection: challenges/resolutions and learning linked to theory

## Notes

- Only include work you are authorized to share publicly. Do not post personal data, secrets or restricted material.
- Give every figure a descriptive caption and make signal names readable.
- Explain the evidence: screenshots without analysis are insufficient.
- Do not upload large Vivado-generated project directories, build caches or bitstreams unless the instructor specifically requests them. Upload the relevant sources and evidence.
- Markdown edits can be made entirely in GitHub's web editor. The site may take a few minutes to rebuild after each commit.
