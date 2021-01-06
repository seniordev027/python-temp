<div align="center">

# Python Template

A Python project template to save you time and energy.

[![Build](https://github.com/Justintime50/python-releaser/workflows/build/badge.svg)](https://github.com/Justintime50/python-releaser/actions)
[![Coverage Status](https://coveralls.io/repos/github/Justintime50/python-releaser/badge.svg?branch=main)](https://coveralls.io/github/Justintime50/python-releaser?branch=main)
[![Licence](https://img.shields.io/github/license/justintime50/python-template)](LICENSE)

<img src="assets/showcase.png" alt="Showcase">

</div>

Python projects take a long time to setup with all the various files, the virtual environment, and keeping things uniform across projects. With this Python template, you can quickly setup boilerplate code and miscellaneous items for your Python project saving you time and energy so you can get back to coding. 

## Install

Click the `Use this template` button at the top of this project's GitHub page, it looks like this:

<img src="assets/use_template_button.png" alt="Use Template Button">

## Usage

**Easy text replacements**

1. Replace all instances of `python_project` with the name of your project
1. Replace all instances of `Python Template` with the name of your project
1. Replace all instances of `PROJECT_NAME` with the name of your project
1. Replace all instances of `USERNAME` with the name of the author/owner as it appears on GitHub

**File configuration**

1. Configure the `setup.py` file
1. Configure the `Makefile` targets
1. Update the name in the `LICENSE`
1. Configure the `.travis.yml` or `.github/workflows/build.yml` file
1. Update the `CHANGELOG`
1. Add your showcase image to `/assets`
1. Change the data in `.github/FUNDING.yml`
1. Rename other files/folders as needed and configure their content
1. Delete this `README` and rename `README_project.md` to `README.md`

**Travis-CI**

To add a secure PyPi API key to your `.travis.yml` file, run the following command and replace `your-api-token` with your real API token.

```bash
travis encrypt your-api-token --add deploy.password --com
```
