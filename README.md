# 📚 Docusaurus Template Site

Generate a documentation site for your Python or any other project involving Jupyter notebooks effortlessly using this repository template.

## 🚀 Getting Started

1. **Fork this repository** to your own GitHub account.

2. **Make necessary changes:**

    - Modify names in `settings.ini` and `docusaurus.config.js` files in the `docs_skeleton` directory.
    
3. **Enable GitHub Pages deployment:**

    - Go to the repository settings.
    
    - Under "Pages" in repository settings, select "GitHub Actions Beta" under "Build and Deployment".

4. **Workflow Automation:**

    - This repository includes a workflow.
    
    - Place your files in respective directories.
    
    - Merge your changes with the `master` branch.
    
    - The workflow will be triggered automatically, and your GitHub site will be built and deployed.

5. **Add Content:**

    - Place your Markdown files in the `markdown` directory.
    
    - Put Jupyter notebook files in the `files` directory within the `docs` directory.
    
    - You can create sub-directories to group Markdown or notebook files, which will add a dropdown list on the site.

## 📦 Dependencies

This project makes use of the following repositories:

1. [Docusaurus](https://github.com/facebook/docusaurus)
2. [nbdocs](https://github.com/outerbounds/nbdoc)

## 🌐 Example Site

Check out the generated site: [Demo Site](https://balnarendrasapa.github.io/docusaurus_site/docs/intro)

## 📖 Documentation

For detailed instructions and customization options, refer to the official Docusaurus documentation.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your project's specific details. Happy documenting! 📝✨
