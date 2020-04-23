# IBM CloudPaks on OCP Playbook

Simple-to-edit (for developers and non-developers alike) documentation framework.

GitHub Pages site managed under `gh-pages` branch.  Live site can be viewed here:  https://ocp311.cloudpak8s.io/

## Development Stuff

Clone the repo, and checkout the `gh-pages` branch.  Submit PRs to your squad and someone should review and approve your request.  Information about how to add content is on the left nav of the pages site (until we delete it, near the end of the residency).

Your content will generally be in your `_content` subdirectory:

   - CP4Automation: `automation`
   - CP4Integration: `integration`
   - CP4Data: `data`
   - CP4MCM: `mcm`
   - CP4Apps: `apps`
   - OCP: `ocp`

Add whatever sub-pages you require as .md files in your subdirectory; their order is defined by a `weight` parameter:
```
---
title: First Content
weight: 100
---

Pithy first content
```
