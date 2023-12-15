---
title: First page
draft: false
tags:
  - example-tag
---
 
The rest of your content lives here. You can use **Markdown** here :)

# Start

Once you’ve initialized

Quartz, let’s see what it looks like locally:

>[!tip] 
>npx quartz build --serve

## Preview
This will start a local web server to run your Quartz on your computer. Open a web browser and visit http://localhost:8080/ to view it.


## mods

>[!info] Flags and options
>
>For full help options, you can run npx quartz sync --help.
>
>Most of these have sensible defaults but you can override them if you have a custom setup:
>
>-d or --directory: the content folder. This is normally just content
>-v or --verbose: print out extra logging information
>--commit or --no-commit: whether to make a git commit for your changes
>--push or --no-push: whether to push updates to your GitHub fork of Quartz
>--pull or --no-pull: whether to try and pull in any updates from your GitHub fork (i.e. from other devices) before pushing