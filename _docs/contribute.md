---
title: Contribute
prev_section: board.html
next_section: visions.html
layout: default
---

Contribute
============

Clone this repo

<https://github.com/Insight-Services-APAC/playbook>

Edit the markdown file you want to update.

Optionally if you have Docker Compose you can run the site locally (or know how to run Jekyll sites without Docker)

**To run locally**

1. Make sure that your docker instance is running on a Linux instance.
2. from the root folder of the project e.g. _C:\dev\insight\playbook_
3. run _docker-compose up_
4. the site should be available on http://localhost:4000

> If it fails try again a few times!

```

PS C:\dev\insight\playbook> docker-compose up
Starting playbook_site_1  ... done
Starting playbook_build_1 ... done
Attaching to playbook_build_1, playbook_site_1
build_1  | ruby 2.7.1p83 (2020-03-31 revision a0c7c23c9c) [x86_64-linux-musl]
build_1  | Configuration file: /srv/jekyll/_config.yml
build_1  |             Source: /srv/jekyll
build_1  |        Destination: /srv/jekyll/_site
build_1  |  Incremental build: disabled. Enable with --incremental
build_1  |       Generating...
build_1  |        Jekyll Feed: Generating feed for posts
site_1   | ruby 2.7.1p83 (2020-03-31 revision a0c7c23c9c) [x86_64-linux-musl]
build_1  |                     done in 0.822 seconds.
build_1  |  Auto-regeneration: disabled. Use --watch to enable.
playbook_build_1 exited with code 0
site_1   | Configuration file: /srv/jekyll/_config.yml
site_1   |             Source: /srv/jekyll
site_1   |        Destination: /srv/jekyll/_site
site_1   |  Incremental build: disabled. Enable with --incremental
site_1   |       Generating...
site_1   |        Jekyll Feed: Generating feed for posts
site_1   |                     done in 0.734 seconds.
site_1   |  Auto-regeneration: enabled for '/srv/jekyll'
site_1   |     Server address: http://0.0.0.0:4000
site_1   |   Server running... press ctrl-c to stop.
```