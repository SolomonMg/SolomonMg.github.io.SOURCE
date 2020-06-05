---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Why you should care about privacy policy"
subtitle: "Differential privacy and data policy"
summary: ""
authors: [Sol Messing]
tags: []
categories: []
date: 2019-11-20
lastmod: 2019-11-20
featured: false
draft: false

math: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
   caption: ""
   focal_point: "Smart"
   preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [research]
---

In 2011, Sean Westwood and I ran a (IRB-approved) study using Facebook's graph API to analyze participants' entire ego network on the fly, and then randomly assign strong v weak ties to ostensibly endorse media content appearing on their news feed (stimulus). We then re-rendered participants’ News Feeds. Those days are over. 

The API was meant for developers to build on top of the data underlying Facebook's platform, what it calls "the social graph," but approvals were friendly to researchers. The scope of the data was startling and thankfully Sean had the foresight to delete data beyond what was necessary for analysis and publication.

Times have changed - OPM, MyLife, Equifax, Cambridge Analytica. Privacy issues are difficult to anticipate and secure, especially for complex and/or relational data. And Cambridge Analytica showed the world that APIs are open to nefarious schemes and basic research alike.

Data privacy is in the air in newsrooms and capitals across the world. As privacy advocates devise strategies and work to protect people from identity theft, scams, information & other abuse, often social scientists advocating for research aren't at the table.

In the wake of these cross currents, privacy legislation and regulation present challenges for research communities. No company can shrug off a $5 bn fine for being too permissive w data---data collected via APIs in the name of social science research.

What's more, the GDPR is vague on whether meaningful, socially beneficial independent social science research maps to the generally prohibited processing of "3rd party sensitive category data collected without consent." https://iapp.org/news/a/how-gdpr-changes-the-rules-for-research/. 

Some have intupretated the GDPR's research exemption as carving out a protected legal space for this kind of work *only* if originally collected for research purposes. Yet the data everyone cares about was collected for business. What's left? Case-by-case opt-in--severe confounds, overhead, paperwork, etc.

Another complication is that certain EU member states have additional requirements such as consent and/or anonymization at the level of differential privacy. See pp. 29-32 of this report https://accessnow.org/cms/assets/uploads/2019/06/One-Year-Under-GDPR.pdf. 

Lawyers tend to be quite risk averse under this ambiguity and until firm guidelines are developed, it's probably unrealistic to expect Silicon Valley to open up much data to researchers. That's especially true after Facebook's $5bn fine and the unrelenting stream of techlash criticism often related to privacy. 

