# [jlelia.net](https://jlelia.net)
## Overview
This repo contains all of the front-end code present on my website. I self-host a personal/professional website using a miniature computer called a Raspberry Pi. I use Nginx as the web server.

## Implementation
All of the content on the site is static. I use HTML with a unified [CSS style sheet](styles.css) to avoid in-line CSS and to follow DRY principles.

I used to write the code through SSH CLI as a practice exercise in bash, but now I use GitHub Actions to automate updates whenever I push to this repo via a [runner workflow](.github\workflows\deploy-to-pi-selfhosted.yml).
