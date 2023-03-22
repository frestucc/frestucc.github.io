---
permalink: /
title: "Francesco Restuccia - University of California San Diego"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Welcome! I'm an enthusiastic hardware engineer working as a postdoctoral researcher at the University of California, San Diego.

**Current research topics**

I spend most of my research efforts working on hardware security, hardware support for timing predictability, and application on open-hardware System-on-Chip architectures. My research aims at providing methodologies, tools, and mathematical analysis to make the next generation of systems designed for critical applications (such as cyber-physical systems) work more safely, securely, and time-predictably.

I passionately collaborated to other research projects related to flash memory reliability and telehealth.

I published and presented my work at multiple peer-reviewed top-notch scientific conferences such as ACM/IEEE DAC, IEEE/ACM ICCAD, IEEE CASES, IEEE FCCM, IEEE RTSS, and Euromicro ECRTS.

In 2022, I've been selected as a speaker for the 2022 US Hardwear.io Security Training and Conference. In 2023, I've been invited to speak at the Qualcomm Security Summit.

**Academic service**

I'm the co-founder and general chair of the first edition of the <a href="https://ssh-soc-workshop.github.io/2023/">Safety and Security in Heterogeneous Open System-on-Chip Platforms (SSH-SoC) workshop</a>, which will be held in July 2023 in conjunction with the Design and Automation Conference in San Francisco, California (DAC 2023)

I'm technical program committee co-chair of the 2nd Real-time And intelliGent Edge computing workshop (RAGE), which will be held in conjunction with CPSweek 2023 in San Antonio, Texas.

I've been publicity chair and program committee member for the 1st Real-time And intelliGent Edge computing workshop (RAGE) that has been held in conjunction with the 59th Design Automation Conference (DAC 2022).

I served as a program committee member for IEEE RTSS 2022, IEEE RTSS 2023, IEEE DSD 2023, RAGE@DAC2022, and RTSOPS 2022.

I served as reviewer for multiple scientific journals, such as IEEE Transactions on Computers, IEEE Transactions on Mobile Computing, IEEE Transactions on Dependable and Secure Computing, IEEE Internet of Things Magazine, Elsevier Engineering Applications of Artificial Intelligence, Elsevier Microprocessors and Microsystems, and others.

**About my PhD**

I received my Ph.D. in Emerging Digital Technologies - Embedded Systems (computer engineering) from Scuola Superiore Sant'Anna Pisa in 2021, while working at the ReTiS Lab (Real-Time Systems Laboratory).

My thesis was mainly focused on providing tools and analysis for the predictable, safe, and secure execution of critical applications on commercial FPGA SoC platforms.

At the same lab, I've been working on providing timing predictability for the execution of Deep Neural Networks for Autonomous Driving applications on commercial FPGA SoCs. As a side project, I've been the main developer and maintainer of the <a href="http://arte.retis.santannapisa.it">Arduino Real-Time ARTe project</a> between 2017 and 2021.

**Fun facts**

I co-founded a band in 2022 which is unsurprisingly named FPGA (Fellow Program Guitar Association).


<!--
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right.
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
