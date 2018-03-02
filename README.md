# praqma-docs-demo
Example of using our praqma-docs jekyll site layout for simple Github page.

## Steps to use our common layout to get a github page

* clone your repository
* create a `docs` folder in repo root
* copy content (folders) from https://github.com/Praqma/praqma-docs into the `docs` folder. _Yes, very ugly! - but that is the problem we will try to solve_.
* add and `index.md` to the `docs` folder, with a simple header and paragraph
* push (example [commit](https://github.com/Praqma/praqma-docs-demo/commit/2a176a9e3815e8f88307cc928d4c7d152ae43e15))

Then enable github pages, served from `docs`-folder on master branch using the Github web UI it look like this:

¡[Enable Github pages in Github we UI on master branch in docs-folder](images/github-ui-enable-pages.jpg)

### Add configuration for jekyll

Add a file similar to `docs/_config.yml` with content that is needed for Jekyll.


## Overall Github org and DNS prerequisites


What makes code.praqma.net/<git-repo-name> to work?

Our DNS bases settings...
