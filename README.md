# MOVED

This repository has moved to [https://g.fc.run/asana/quickasana](https://g.fc.run/asana/quickasana)

---

# Quick Asana

_Quick Asana is an unofficial extension that uses the Asana API and is not developed or endorsed by Asana, Inc., the makers of Asana._

Quick Asana is a browser extension to add tasks to [Asana](https://asana.com/) with a single click -- no other UI interaction necessary.

## Creating Tasks
Create tasks by clicking the extension icon.
* Click: Create a task in Asana from the current tab and close the tab
* ⌘-Click: Create a task in Asana from the current tab
* ⇧-Click: Create a task in Asana from the clipboard contents

When creating a task from the current tab, Quick Asana will use the page title as the task name, put a link to the page in the notes, and attach a screenshot of the visible tab contents to the task. If there is highlighted text when you click the extension icon, the text will be added to the task notes.

## Setup
Quick Asana uses [personal access tokens](https://developers.asana.com/docs/personal-access-token) for authentication. Before using the extension the first time, you'll need to provide a token in the extension preferences. You'll then need to choose a workspace and assignee for new tasks.