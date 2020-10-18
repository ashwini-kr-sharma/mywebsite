# README

This is my personal website powered by [HUGO](https://gohugo.io/) and based on the [hugo-coder](https://github.com/luizdepra/hugo-coder/) theme.

This is the root directory structure and the most important directories are the `content` and `static` where all the changes will be made. HUGO renders these changes and the build the new website in the `public` directory which is then mirrored in my [website](https://github.com/ashwini-kr-sharma/)

        .
        ├── README.md
        ├── archetypes
        ├── config.toml
        ├── content
        │   ├── about.md
        │   ├── aksCV20.pdf
        │   ├── contact.md
        │   ├── posts
        │   │   ├── 00001-post.md
        │   │   ├── 00002-post.md
        │   │   └── 00003-post.md
        │   ├── publications.md
        │   └── work.md
        ├── data
        ├── deploy.sh
        ├── layouts
        ├── public
        ├── resources
        ├── static
        │   ├── AKSprofilePic.jpeg
        │   ├── canMET.jpg
        │   ├── collabs.jpg
        │   ├── compPheno.jpg
        │   ├── compToolBox.jpg
        │   ├── deconvolution.jpg
        │   ├── epiBN.jpg
        │   ├── epiNB.jpg
        │   ├── raw
        │   │   ├── canMET.afdesign
        │   │   ├── collabs.afdesign
        │   │   ├── compPheno.afdesign
        │   │   ├── compToolBox.afdesign
        │   │   ├── deconvolution.afdesign
        │   │   ├── epiBN.afdesign
        │   │   ├── epiNB.afdesign
        │   │   └── redoxSC.afdesign
        │   └── redoxSC.jpg
        └── themes
            └── hugo-coder


After making any changes, simply execute the `./deploy.sh` file, which will do -

1. Push the changes to my [website github repository](https://github.com/ashwini-kr-sharma/mywebsite)
2. Push the `public` folder (a git sunmodule, with the locally HUGO built website) to my [mirroring website repository](https://github.com/ashwini-kr-sharma/ashwini-kr-sharma.github.io)
