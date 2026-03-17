# Content Quality TODO

Issues found by `showroom:verify-content`. Work on these after the showroom is confirmed to display.

## Scaffold

- [ ] Add `content/supplemental-ui/` directory (css/site-extra.css + partials/head-meta.hbs) — copy from https://github.com/rhpds/showroom_template_nookbag.git, then uncomment `supplemental_files` in `site.yml`
- [ ] Add `runtime.fetch: true` to `site.yml`
- [ ] Add `lab_name` attribute to `content/antora.yml`

## Style

- [ ] Fix em dashes (`—`) — replace with ` -- ` or rephrase
  - `03-module-01-introduction.adoc:8`
  - `06-module-04-projects.adoc:10`
- [ ] Fix Title Case headings to sentence case (14 headings across 7 files)
  - `index.adoc:8` — "What You'll Learn"
  - `05-module-03-explore.adoc:7` — "The Web Console"
  - `05-module-03-explore.adoc:28` — "Command Line Interface"
  - `05-module-03-explore.adoc:69` — "Verifying Your Access"
  - `06-module-04-projects.adoc:4` — "Understanding OpenShift Projects"
  - `06-module-04-projects.adoc:12` — "Exploring Your Project in the Web Console"
  - `06-module-04-projects.adoc:20` — "The Topology View"
  - `06-module-04-projects.adoc:51` — "Next Steps"
  - `14-module-12-nationalparks.adoc:61` — "Using Application Code on Git Server"
  - `17-module-15-pipelines.adoc:19` — "Understanding Tekton"
  - `18-module-16-webhooks.adoc:17` — "Adding Triggers to your Pipeline"
  - `19-conclusion.adoc:54` — "Workshop Links"
  - `mlbparks-binary-build.adoc:14` — "Fast Iterative Code Change Using Binary Deploy"
  - `mlbparks-binary-build.adoc:95` — "Code Change"

## Content Quality (lower priority)

- [ ] Add `== Learning Objectives` sections to modules 08–18 (all hands-on modules)
- [ ] Add `=== Verify` checkpoints after major steps in all modules (currently only in `05-module-03-explore.adoc`)
- [ ] Add `== What You've Learned` section to `19-conclusion.adoc`
- [ ] Add `== References` section to `19-conclusion.adoc` consolidating links from all modules
