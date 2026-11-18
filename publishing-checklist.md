# Checklist: safe publication of the original project files

Before switching the GitHub repository to **Public**:

- [ ] Confirm you have permission to publish your own SAP source code and any materials based on the course exercises.
- [ ] Do **not** upload the lecturer's assignment PDF.
- [ ] Do **not** upload the original 52-page submission PDF without thoroughly redacting student ID, account names, hostnames, URLs, passwords, tokens, and other sensitive information inside screenshots and document metadata.
- [ ] Review every screenshot. The three screenshots included here have been selected from the project display views rather than SAP login screens, but you should review them yourself before publishing.
- [ ] Do **not** upload SAP destination files, local cloud/on-premise connections, `.env`, cookies, tokens, browser caches or credential files.
- [ ] When you find your **Visual Studio Code project folder** (the course assignment requested a ZIP of it), add the useful **source files**, not just the ZIP as an opaque attachment. Usually include your own `webapp/`, `manifest.json`, annotation sources, and project/package configuration after reviewing their contents; leave out `node_modules/` and generated outputs.
- [ ] If the ABAP development files are exportable and publication is allowed, add real ABAP report and CDS source files. Do not reconstruct them from illegible screenshots or claim unverified code.
- [ ] Check all Git history and previous commits for secrets, not only the latest visible files.
- [ ] Include a clear setup section only after confirming real project configuration and SAP access requirements.
- [ ] Ensure unfinished assignment steps are not described as implemented.

**Current package:** project showcase only; no original PDF, lecturer handout or application source included.
