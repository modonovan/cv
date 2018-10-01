# My Online Curriculum Vitae in Markdown

I have created this online version of my CV for portability and cross-platform compatibility in September 2018.

The motivation for doing so is that I can do the following in order to keep my CV up-to-date easily;

* Open iTerm on my laptop and change into my "cv" directory
* git pull to ensure the repo is up to date
* Open my index.md Markdown file in my favourite text editor (VIM of course) and make the relevant changes
* Issue a ```make``` command in my repo's root directory to create the different formats of the CV using the underlying ```pandoc``` and ```context``` and put them into the *output* directory
* Finally do a git commit and git push and my newly updated CV is live online in [Markdown](https://mickod.ie/cv) (online version) | [HTML](https://mickod.ie/cv/output/cv.html) (alternative not so snazzy online version) | [Open Document](https://mickod.ie/cv/output/cv.docx) (for those users requiring to see my CV in the likes of MS Word or Open Office) | [PDF](https://mickod.ie/cv/output/cv.pdf) (generate offline document type) | [Rich Text Format](https://mickod.ie/cv/output/cv.rtf) (akin to plain text)

I have used hits and ideas from the github repos called "pandoc-resume" and "markdown-cv" in order to create this online version of my CV.

Please feel free to CLONE or FORK this repo to produce your own CV / Resume online.
