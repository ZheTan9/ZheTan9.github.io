---
permalink: /
title: "个人简介"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

檀哲博士，福建警察学院讲师、一级警司，福州大学计算机与大数据学院硕士生导师。现任职于福建警察学院治安系，在数字福建社会安全大数据研究所、中国东南部禁毒研究中心从事研究工作。曾在福建省多个公安实战部门锻炼和调研。目前发表学术论文十余篇（以一作或通讯身份在基金委管理科学部A刊发表4篇），参研国自然项目1项，主持或参研省部级项目3项。主要研究兴趣包括：社会安全的数理建模、博弈论应用、成瘾行为的社会影响等，与来自厦门大学管理学院、中国科学技术大学认知神经心理学实验室、福州大学计算机与大数据学院、福建师范大学物理与能源学院等高校院系的学者保持合作。

教育及工作经历
======
2008.09-2012.06，福州大学计算机科学与技术系，学士，获推免资格、省级社会实践先进个人
2012.09-2015.03，福州大学计算机技术系，硕士，获省级三好学生、省级论文演讲竞赛一等奖
2015.09-2016.04，中国人寿福建分公司信息技术部，获入职培训优秀学员
2015.11-2016.01，中国人寿保险股份有限公司总公司信息部
2016.09-2021.06，厦门大学管理科学与工程系，博士，获多次奖学金、院级优秀共产党员

研究兴趣
======
社会安全的数理建模、博弈论应用、成瘾行为的社会影响等。

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
