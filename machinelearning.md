---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## Abstract analyzer (coming soon!)

When a paper is being submitted to the arxiv preprint server, the author needs to manual select which category the paper belong to. This webapp is basically to analyze the abstract and suggest a category. It is done by analyzing (and learning) from the previous submitted abstract. Right now I am focusing on papers in the field of astrophysics.

<iframe src="https://azj31tvvek.execute-api.us-east-1.amazonaws.com/dev/" width="550"></iframe>

Some stuff can be found [here](https://github.com/wingkitlee0/arxiv_explore).

## Demo of webapp (20 news group  dataset)

[webapp](https://sm2op9jgr0.execute-api.us-east-1.amazonaws.com/dev/)

(It may take a few seconds to load.)

Before fully implementing the above project, I tried to make a working demo. This demo takes two numbers (features) from users, and predict which type of Iris it should belong. While it is a textbook machine learning, I have made an web app.

Features:
- Data (model parameters) are hosted on *Amazon S3*
- Webapp is running on *Amazon Lambda* using *flask*

The codes and reference are hosted on [GitHub](https://github.com/wingkitlee0/flask-webapps/tree/master/newsgroup)