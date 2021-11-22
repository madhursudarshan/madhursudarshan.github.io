---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I'm Madhur Sudarshan, a final year Masters student conducting research in the fields of Computer Graphics and Computer Vision (i.e. broadly Visual Compute). I will graduate with a Bachelors and Masters in Electrical Engineering and a minor in Computer Science (expected July 2022) from [Indian Institute of Technology Bombay](http://www.iitb.ac.in/). I am advised by [Prof. Parag Chaudhuri](https://www.cse.iitb.ac.in/~paragc/) as my guide and [Prof. Subhasis Chaudhuri](https://www.ee.iitb.ac.in/~sc/) as co-guide. I also work closely with [Prof. Sharayu Moharir](https://www.ee.iitb.ac.in/web/people/faculty/home/sharayum) and have worked with [Prof. Nikhil Karamchandani](https://sites.google.com/site/nikhilkaram/). 

I am passionate about enabling Immersive Technologies and understanding their use for environmental story telling. My current research focuses heavily on XR, and my career goal is to create tools for artists and platforms for Professionals. I am looking for a full time PhD positions to contribute to and learn from research groups to solve such problems.

I am tackling Coherent Illumination for Mixed Reality as my masters thesis and Deep Reinforcement based polcies for Edge service caching with a focus on edge Cloud based VR processes as additional research projects. I have also worked on Audio Processing, creating a novel framework for paired instrument transfer using Wavenet. For more information on my projects please refer to the refer to my [CV](madhursudarshan.github.io/static/MadhurCV2021.pdf) or view a summary of significant research projects below. 

<!-- I am passionate about creating tools and enabling technologies tied with human creativity, and my research focuses heavily on XR. Currently I am tackling Coherent Illumination for Mixed Reality and Edge service caching with a focus on Cloud based AR  -->

Key Research Projects
======
 
I am currently working on enabling tools for high realism in Augmented Reality in two projects-  
* Coherent Rendering for Augmented Reality  (Advised by [Prof. Parag Chaudhuri](https://www.cse.iitb.ac.in/~paragc/) and [Prof. Subhasis Chaudhuri](https://www.ee.iitb.ac.in/~sc/))

  Synthetic objects rendered onto real environments are not influenced by lights and reflections in the real world. Our eyes are perceptive to these inconsistencies, thus to render objects coherently we must infer accurate illumination information. We are interested in inference approaches that run in real time on monocular RGB cameras, that are available on most handheld devices. I began by recreating the paper titled Learned Light Probes for Mixed Reality Illumination (Mandl et. al.) that trained a CNN per pose to extract spherical harmonic representations of illumination from images of an object with known geometry, textures and BRDF. I synthesized datasets for objects to test this approach virtually. I explored augmentations to and identified fundamental drawbacks with their approach. Inspired by recent research in Differentiable Rendering and Neural Rendering I tried to generate intermediate I proposed a method based on using rendered images as a basis, that I intend to publish after further research.     

* Deep Reinforcement Learning for Service Caching on the Edge (Advised by [Prof. Sharayu Moharir](https://www.ee.iitb.ac.in/web/people/faculty/home/sharayum) and [Prof. Nikhil Karamchandani](https://sites.google.com/site/nikhilkaram/))

  Enabling High Quality XR apps on Head Mounted Devices provides issues with Compute and Battery Limitations. Instead of running processes locally hosting such services on edge servers and streaming to mobile devices is a promising alternative. There are also many research challenges in ensuring high Quality-of-Experience to users, typically seen in terms of latency and bandwidth limitations. Taking inspiration from Predictive Scheduling for VR, I completed an extensive literature survey and proposed an alternate QoE based metric to optimise the choice of running services locally or on edge servers. Then to investigate performance of reinforcement learning policies against optimal solutions, I am studying the performance of deep reinforcement learning agents on long horizon arrival patters and loss metrics on an approach titled RetroRenting by my advisors and V S Ch Lakshmi Narayana. When this research is concluded insights from this can be applied to other optimisation problems for edge cloud based services.

Aside from these I also have a strong background in Audio Processing, both as an Electrical Engineer/AI Researcher and Musician/Producer. Of particular interest would be my research conducted as a course project for Advanced Machine Learning-

* Wavenet for Timbre-Transfer (Team-mate: Harsh Prashant Dolhare, Instructor [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/))

  Musicians performing live seek to increase their sonic pallete by using many effects such as filters, distortion pedals. A more challenging problem is to make one instrument sound like another, this is "timbre transfer".  The instrument that offers the most variation in timbre would be electronic instrument like the keyboard which can emulate any sound, but these restrictive in expressivity. More expressive instruments such as wind or string based instruments conventionally need frequency information to be converted into MIDI information before they can generate varied sounds but this can lead to artifacts. Borrowing from research on modelling distortion pedals as a blackbox using Wavenet, I proposed a model for paired instrument transfer that can run in realtime on any input instrument to map to other output instruments. We generated novel datasets and study the performance of this model, leading to promising results. 


I also spent a summer researching the application of High-Order Singular Value Decomposition to Liquid Chromatography-Mass Spectrometry data for metabolomics. My challenge was to apply Image Processing concepts to sparsely encoded data, with an end goal of processing many Gigabytes of unanalysed data. This work was done with [Prof. Pramod Wangikar](https://www.che.iitb.ac.in/wangikar/?team=pramod-wangikar) for the start-up [Clarity Biosystems](https://claritybiosystems.com/). Aside from this course projects can be found in my CV.

Background
======
For the majority of my life IIT campus in Mumbai has been my home, with the exception of a pleasant kindergarten year in Seattle Washington in the Redmond area, and a blissful exchange Semester in DTU Copenhagen, Denmark. I grew up surrounded by academics in IIT Bombay where my Father [Prof. S. Sudarshan](https://www.cse.iitb.ac.in/~sudarsha/) is a Professor of Computer Science. This environment inspired and led me to spend my youth representing my school at various Olympiads and Quizzes. I was also fortunate to pursue art classes, various sports and robot coding bootcamps. My first exposure to professional instruction was a summer transcribing and dubbing coding tutorials for [Spoken tutorials](https://spoken-tutorial.org/). That and a fascination with Science Fiction Literature ranging from Isaac Asimov to Douglas Adams brought me to pursue a Degree in Engineering. My background as a musician and an artist ensured that I stuck close to subjects that were creative in nature, thus leading me to pursue problems related to Computer Graphics as my Masters thesis. 

Extra-Curricular Pursuits
======
I'm a semi-professional session musician in my free time, and this forms a major motivation for pursuing research too. I began learning music at the age of 9, covering various musical instruments across my journey ranging from Keyboard, Drums and Singing, but I finally settled on the bass guitar as my primary gigging instrument. I enjoy improvisation and performing jazz fusion music, though I have been fortunate to play with and lead Progressive Rock, Jazz and Funk bands. As a bandleader I've led my group to perform infront of audiences of over 5000 opening for popular Bollywood singers. I've completed courses on Music Theory, Linguistics and Industrial Design and am particularly interested in how different forms of media reflect the political and cultural backdrop of their times. This reflects in my Research Interests too.
Besides this I used to play Basketball Representing my University and School. More recently on a semester exchange in Denmark I was able to realise an unfulfilled passion for cooking. Besides having a stellar social life experience I was also introduced to knitting, a hobby I hope to reconnect with if I move to colder climates than Mumbai :)
<!-- On my exchange semester at Danmarks Tekniske Universitet I was introduced to knitting, a hobby that I hope to reconnect with if I move to a colder climate than Mu -->


<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

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
