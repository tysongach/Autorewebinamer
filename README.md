# Autorewebinamer

An Automator workflow and Finder service for renaming files so they're web-friendly.

## What Does it Do?

- Replaces spaces with dashes
- Replaces underscores (_) with dashes
- Replaces ampersands (&) with dashes
- Replaces pound signs (#) with dashes
- Replaces the common string of ’ - ’ with a single dash

These swap-outs are what work for me, but I highly encourage you to pop open the workflow in Automator and adjust to your needs.

## Installation

To install as a Finder Service, simply double-click ‘Rename for Web - Finder Service’ and choose **Install**.

Run the workflow by right clicking a file(s) and choosing **Rename for Web** under **Services**.

I've also included a regular Workflow version, which you can run straight from Automator, which allows you to drag folders or files into Automator and manually run the workflow.