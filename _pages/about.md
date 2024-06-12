---
permalink: /
title: "Welcome Yanda website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my academic and professional portfolio. I am a Research Assistant in [Dr. Jun xia's lab](https://www.acsu.buffalo.edu/~junxia/). at the University of Buffalo, where my research focuses on applying advanced AI technologies like deep learning and machine learning to biomedical challenges, including image denoising and the use of GPT models.

 Previously, at [Cornell University](https://www.bme.cornell.edu/bme/alumni/bme-newsletters/2021-bme-newsletter/class-2021-special-insert), I had the opportunity to work under [Professor Karl Lewis](https://www.kjlewislab.com/group-members), contributing to several innovative projects related to rat motion and surgical reconstruction with. 

My initial work at the University of Kentucky involved developing technology for long-term monitoring of infant blood pressure using optical cameras. Under the where [Dr. Yu Guoqiang](https://bioptics.engr.uky.edu/) supervised on advanced optical and biomedical devices.  


**My Entrepreneurial Story**: Pioneering Precision in Sensor Technology
======
I am an entrepreneur and a core developer at a leading high-tech company specializing in precision sensors. Known for our advanced laser and ultrasonic sensors, we excel in delivering products with high precision, superior quality, and competitive pricing. Having joined the company part-time in **2015**, I have dedicated nearly a **DECADE** to enhancing our technological capabilities and expanding our market presence. My extensive experience in both development and market strategy has been instrumental in driving our success and innovation.

Our operations currently extend across major markets such as Thailand, Singapore, the United States, and China. Looking ahead, we have strategic plans to enter the Middle East in 2025 as part of our ongoing global expansion. This year, we achieved a significant milestone, reaching an annual revenue of one hundred million dollars, underscoring our position as a leader in the global sensor market.

In my role, I engage in a wide array of activities, from market research and development to the technical maintenance of our company website. I am deeply involved in sensor development, utilizing C and Python to integrate cutting-edge AI and GPT technologies into our products. This ensures that we not only adhere to but also exceed the high standards of accuracy and performance that our clients expect.

This journey of over eight years reflects my dedication to innovation and excellence in the high-tech sensor industry, highlighting my role in driving the company's success and technological advancement.


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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
