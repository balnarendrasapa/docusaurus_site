# docusaurus_site

- Use this repo template to generate documentation site for your python or any other project that involves jupyter notebooks.
- Make necessary changes like names in settings.ini and docusaurus.config.js files in docs_skeleton directory.
- Enable deploying the github pages through github actions in repository settings. go to pages in repository settings and under build and deployment select Github Actions Beta.
- This repo has a workflow in it. So all you need to do is to place the files in respective directories and merge with master and then the workflow will be triggered, and github site will be automatically built and deployed
- Place your markdown files in markdown directory in docs and place your jupyter notebook files in notebooks directory in docs directory
- You can create sub-directories to group markdown or notebook files this will add a dropdown list in the site.
- I have made use of these repos. 1. [docusaurus](https://github.com/facebook/docusaurus)
                                  2. [nbdocs](https://github.com/outerbounds/nbdoc)
- The generated site would look like this. follow this [link](https://balnarendrasapa.github.io/docusaurus_site/)
