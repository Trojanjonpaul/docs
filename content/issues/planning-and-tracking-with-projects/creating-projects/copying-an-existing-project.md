---
title: 'Copying an existing {% data variables.projects.project_v2 %}'
shortTitle: Copying a project
intro: You can use an existing project as a template by copying it.
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
type: tutorial
topics:
  - Projects
allowTitleToDifferFromFilename: true
---

## About copying projects

You can copy an existing project and use it as a template to save time configuring your views and custom fields.

When you copy a project, the new project will contain the same {% data reusables.projects.what-gets-copied %}. The new project will not contain the original project's items, collaborators, or team and repository links.

{% data reusables.projects.org-templates %}

## Copying an existing project

1. Navigate to the project you want to copy.
1. In the top-right, click {% octicon "kebab-horizontal" aria-label="More options" %} to open the menu.

   ![Screenshot showing a project's menu bar. The menu icon is highlighted with an orange outline.](/assets/images/help/projects-v2/open-menu.png)

1. In the menu, click **{% octicon "copy" aria-hidden="true" %} Make a copy**.
1. Optionally, if you want all draft issues to be copied with the project, in the "Make a copy" dialog, select **Draft issues will be copied if selected**.
1. Under "Owner", select either the organization that will own the new project or your personal account.
1. Under "New project name", type the name of the new project.
1. Click **Copy project**.
