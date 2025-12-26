---
'barkql': patch
---

Fix GitHub releases not being created by using `changeset publish` instead of a custom npm publish script, which provides the expected "New tag:" output format that changesets/action parses.
