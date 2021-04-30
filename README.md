# Glitch-MkDocs

<https://mkdocs-p.glitch.me/>
<https://glitch.com/edit/#!/mkdocs-p>

**MkDocs with Glitch (For editing, minimal configuration) aka MkDocs Proof of Concept**

- [Glitch](https://glitch.com/)
- [MkDocs](https://www.mkdocs.org/)

This project is intended to be built MkDocs, not open to the public.

## New April 30, 2021

This POC has been tuned to apply [GENERATED STATIC SITE](https://help.glitch.com/kb/article/113-i-noticed-a-%E2%80%9Cglitch%E2%80%9D-entry-in-the-react-and-eleventy-starter-projects%E2%80%99-package-json-what-does-that-do/).  
This ensures that the web never sleeps and  
consumes Project Hours when you don't edit.

## How to use

[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/remix/mkdocs-p)

1. Press the button above to remix as your project.
2. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
3. When you add the pip package to `requirements.txt`, do the following in Terminal:  
`pip3 install --user -r requirements.txt`  
(I know `glitch.json` and `watch.json` but it didn't work)
4. Once completed, you can get the file from **Tools - Import and Export** and publish it elsewhere.  
`mkdocs build` will output the file to `site/`. Please publish this.  
Of course, you can publish this in another Glitch project. (Ideal because it will be a Static Site)
