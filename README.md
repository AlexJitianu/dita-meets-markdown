# dita-and-markdown
Ideas and samples about how DITA and Markdown work together as well as docs-as-code proof-of-concept with a DITA-Markdown project.

# How to create my own project that uses CI, CD workflows

## Overview

This projects allows you to:
- Edit the paper online using Oxygen XML Web Author (https://www.oxygenxml.com/xml_web_author.html).
- See a preview of the generated PDF that is automatically generated each time you commit using Netlify (https://netlify.com).
- Download an archive with the paper and all the supporting files.

## How it works

The "Deploy on Netlify" button below will do the following:

1. Create a Git repository under your GitHub account that will contain a copy of this repository.
1. Set up a continuous publishing process on Netlify that performs CI and CD whenever you commit changes to the repository.
1. Create a "Dashboard" page for the project.

After that you will be able to access a "Dashboard" page that will give you access to the following functionality:

1. View the latest publishing of your documentation.
2. The documentation contains embedded links to edit the file online using Oxygen XML Web Author.
3. Quality checks published on SonarQube
4. Navigate to your GitHub repository

## Privacy

- The GitHub repository is public by default. You can make it private afterwards.
- The "Dashboard" page and the generated PDF will be available at a randomly-generated URL that can only be accessed by people who know it. You can change this URL to make it even harder to guess.

## Getting started

Perform the following steps:

1. Click the following button: [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/AlexJitianu/dita-and-markdown)
2. Click "Connect to GitHub". If you do not have a GitHub account, you can create one for free.
3. Choose a name for the new repository
4. Click "Save & Deploy"
5. You will be redirected to the project's Netlify home page. Meanwhile the PDF version of the paper starts to be generated. In approximately one minute your Dashboard will be deployed at the URL "https://\<project-id\>.netlify.com". You can change this URL in the "Settings" tab.
6. Open the Dashboard.
7. You can use the "View on GitHub" link to access the newly created GitHub repository. The repository is public by default. You can go to the **Settings** tab and make it private.

