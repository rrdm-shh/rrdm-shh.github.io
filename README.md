Source repository of [rrdm-shh.github.io/website](https://rrdm-shh.github.io)

Built with Docsify [docsify.js.org](https://docsify.js.org).

## How to add content ?

- Add your content as [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files by marking a pull request to this repository. 

- You can either add your files at the root directory, or put them in subdirectories.

- Example structure:
    ```
    .
    ├── home.md
    ├── day1
    │   ├── README.md
    │   └── hello_mpi.md
    ├── day2
    │   ├── README.md
    │   └── hello_shh.md
    ```

- If you add a new markdown file, don't forget to add it in the [_sidebar.md](_sidebar.md) file. Headers within a Markdown file are added automatically to the sidebar.

- **DO NOT EDIT `index.html` OR RENAME `home.md`**

## Optional (but recommended)

Install Docsify to render locally the website with [npm](https://www.npmjs.com/get-npm) (Node.js Package Manager): `npm i docsify-cli -g`