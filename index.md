![logos](images/logos.png)

## Abstract

Cancer is considered one of the major challenges of humanity in the 21st century. A pillar for fighting cancer is its correct diagnosis mostly based on medical imaging. Despite great progress in machineries and image resolution, typical data processing is still performed manually by a radiologist, similar to using a marker on X-ray film. Moreover, 10% of diagnoses are estimated to be erroneous even today.  Machine learning has the potential to drastically improve the accuracy, efficiency and effectiveness of disease detection, and as a result can save millions of lives. Unfortunately, despite a plethora of data available, only a small percentage of such is labeled well enough to be used for machine learning. This shortage is the bottleneck to unleashing machine learning to revolutionize medical diagnosis. Here, we present SAKÉ, an annotation framework that significantly improves this labeling process. Offering a combination of precise 3D segmentation, user-friendly interface, and cutting-edge computer vision algorithms, SAKÉ enables radiologists to quickly create standardized annotations for regions of interest in a seamless and accurate manner.

## Introduction

First, let's give some context to how cancer is currently being diagnosed.  Currently

![QuizAnswer](images/intro/Quiz_5A.png){:class="img-responsive"}

## Goal

## Implementation



## Data / Machine Learning

## Demo

To see SAKE in action, check out [demo stack 1](http://104.198.43.42/stack1.json) or [demo stack 2](http://104.198.43.42/stack2.json).

### Tips for navigating the OHIF viewer
- Scroll wheel or up/down arrows to view different slices.
- Right click and drag to zoom in and out.
- Middle click and drag to pan.

### Creating a segmentation with SAKE
1. Click the **Segment** button to activate the tool.
1. Click on region of interest. The plugin will fill out the bounding polygon.
1. Drag the center sqaure up and down to adjust the threshold of the algorithm.
1. Drag individual vertices to fine tune the polygon.
1. Scroll through the slices to propagate segmentation in 3D.

### SAKE tips
- The maximum area of a segment has been capped. The tool rejects attempts to click on a large region or to increase the threshold too much.
- Thresholds are propagated only to unseen slices. Adjust the threshold before scrolling to nearby slices to propagate the threshold.
- The **Save** button will send all the polygon segments back to the server.
- Dragging a vertex off the slice will delete the whole 3D segment.

## Conclusion


{% comment %}
Overview​: Provide an overview of the project. It is important that you include a
general context for and an overall description of as well as any introductory information
that’s specific to the project.
● Motivation​: Introduce the project motivation both as a whole as well as motivations
for important defining aspects of your work. Were there any visualization or UI
primitives that informed your work.
● Description of Data​: What data are you dealing with? What methods have you used
to explore the data (incl. initial explorations, models, data cleansing and reconciliation,
etc)? What insights did you gain? How did those methods influence your work?
● Literature Review/Related Work​: This can include noting any key papers, texts,
other software sources, talks or websites that you have used to develop your modeling
approach and/or that informed your demo/site
● Modeling Approach: ​ What was your baseline model for comparison? What further
models did you implement?
● Results:​ Describe the results and emphasize the most important results. Did you have
to reconsider some of the original assumptions?
● Conclusions and Summary
● Future work
● Style​: Your work should embrace simplicity over complexity, be intuitive for an only
slightly informed user to navigate, and as much as possible be appropriately polished,
robust, and reliable. Visualizations should constructed to slice through complexity and
convey as information and insight elegantly and concisely. We recognize that these are
not going to be fully constructed products but style matters​.
● Software Deployment​: In some situations the demo or website will sit on top of a
multi-layered software stack including software service, API, and client layers. Your
team should deploy your software stack with the goal of making the final report as
self-contained as possible for the duration of the evaluation period. For teams with
sensitive data please
{% endcomment %}


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/capstone-mgh/capstone-mgh.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/capstone-mgh/capstone-mgh.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
