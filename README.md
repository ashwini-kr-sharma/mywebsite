# README

This is my personal website powered by [HUGO](https://gohugo.io/) and based on the [hugo-coder](https://github.com/luizdepra/hugo-coder/) theme.

This is the root directory structure of my website is shown below. The `content` and `static` directories are the most important which holds the files where future changes will be made. HUGO renders these changes and then builds the new website in the `public` directory which is then mirrored in my [website](https://github.com/ashwini-kr-sharma/)

After making any changes, simply execute the `./deploy.sh "Your optional commit message"` file, which will do the following -

1. Push the changes to this repository which is my [website github repository](https://github.com/ashwini-kr-sharma/mywebsite)
2. Push the `public` folder (a git sunmodule, where HUGO locally rebuilds the website) to my [mirroring website repository](https://github.com/ashwini-kr-sharma/ashwini-kr-sharma.github.io)

(NOTE: I have modified this script from [here](https://gohugo.io/hosting-and-deployment/hosting-on-github/) to add step 1 above.

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
