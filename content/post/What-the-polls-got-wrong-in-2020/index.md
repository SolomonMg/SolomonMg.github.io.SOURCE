---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How could the polls get it so wrong?"
subtitle: "It's too early to say for sure, here are the questions to ask"
summary: ""
authors: [Sol Messing]
tags: []
categories: []
date: 2020-06-20
lastmod: 2020-06-20
featured: true
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

It’s becoming clear that the 2020 polls underestimated Trump’s support by anywhere from a 4-7 point margin--a significantly worse miss than in 2016, when [state polls were off but the national polls did relatively well](https://fivethirtyeight.com/features/the-polls-are-all-right/). 

The polling from 2018 looked encouraging, convincing many pollsters that the post-2016 reconing had fixed many issues called out in the [2016 AAPOR report on election polling](https://www.aapor.org/Education-Resources/Reports/An-Evaluation-of-2016-Election-Polls-in-the-U-S.aspx). After 2018, FiveThirtyEight wrote that the ["Polls are Alright"](https://fivethirtyeight.com/features/the-polls-are-all-right/).

But the second Miami-Daude reported results from the 2020 election, we knew something was probably wrong with the 2020 polls.

Unlike 2016, both state and national polls appeared to underestimate Trump's support. 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I&#39;m sure others are looking at this, and we can&#39;t do a full accounting until all the state returns are verified, but so far it looks the weighted averages of state polls were off almost entirely in the same direction. The polling data are simple weighted avgs from 538. <a href="https://t.co/r070psBKJy">pic.twitter.com/r070psBKJy</a></p>&mdash; 💀💀 Stefan Wojcik 💀💀 (@stefanjwojcik) <a href="https://twitter.com/stefanjwojcik/status/1324889531162746884?ref_src=twsrc%5Etfw">November 7, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## The Usual Suspects
The [2016 AAPOR report on election polling](https://www.aapor.org/Education-Resources/Reports/An-Evaluation-of-2016-Election-Polls-in-the-U-S.aspx) provides some guidance for how we might start to examine issues with the 2020 polls. 

**Undecided voters**: Undecideds broke toward Trump late in the election in 2016--polls found as many as 13 percent of voters were [undecided on election day or planned to vote for a third party](https://fivethirtyeight.com/features/the-invisible-undecided-voter/). According to Poynter, there were [half as many of these voters in 2020](https://www.poynter.org/fact-checking/2020/2020-is-not-like-2016-heres-whats-different/), so this is unlikely to be as big a factor as in 2016. 

**Low education non-response & adjustment**: In 2016, individuals lower levels of education were much less likely to answer polls but still voted, and broke for Trump. The national polls adjusted for this but state level polls did not, which is partially why forecasting models that rely on state-level polls missed so hard. 

While many state-level pollsters did this in 2020, Pew Research Center still [found problems with state level polling this time around](https://www.pewresearch.org/methods/2020/08/18/a-resource-for-state-preelection-polling/), for example failing to adjust for race and education simultaneously--non-college whites are far more likely to support Trump than non-college non-whites. 

What's more, pollsters adjusted only for college/non-college, which may not have been enough. They might need to use more fine grained adjustment--accounting for whether respondents have a high school degree and a college degree.  Also error/missing data when people complete education in a survey means trouble if you want to fully fix the issue. 

**Volunteerism & civic engagement**: Even if you adjust for low levels of non-response among individuals with lower education, pollsters still may have problems reaching [low civic engagement voters, a bias that seems to persist even after modeling/weighting adjustments](https://www.pewresearch.org/fact-tank/2015/07/21/the-challenges-of-polling-when-fewer-people-are-available-to-be-polled/). In the past this hasn't mattered as much, but these folks may be showing up to the polls for Trump. 

## Other Potential Factors

**Likely voter models**: This is difficult to fully unpack since each polling house does this slightly differently and not all publish their methods—some ask a battery of voter questions, some use models, some recruit off the voter file. But there’s only a weak relationship between who votes and who scores high on the likely voter battery. To make matters worse, 2020 was a very high-turnout election, which could have introduced even more instability into likely voter models. 

**COVID-19**: I wrote about [this back in June](http://localhost:1313/post/trumps-chances-are-better-than-they-look/). It's possible that COVID-19 made lines long and kept people home in urban areas and non-white communities. Yes we had record turnout but all it takes is a few percent of people who encounter a bit of voting friction, who fail to register in person, don’t get in person canvassing/gotv contact, don’t vote by mail early, and/or don’t vote in vote in person. 

## The Role of Election Forecasts

If you're a forecaster, very easy to look at all the polling data and come away with overconfident estimates of a candidate’s support. Many forecasters in 2016 did just that, failing to account for the fact that error between states and pollsters were likely correlated, and producing estimates that put Clinton’s chances above 95%. 

The Huffington Post famously [roasted FiveThirtyEight](https://www.huffpost.com/entry/nate-silver-election-forecast_n_581e1c33e4b0d9ce6fbc6f7f) for trying to adjust for this state-level polling error the day before the 2016 election. 

But even when forecasters get it right, forecasting can create firm expectations that one candidate will win, which in 2016 was complicated by destiny-narrative driven by media coverage of election forecasting. 

Sean Westwood, Yph Lelkes and I recently published a [research paper](https://solomonmg.github.io/pdf/aggregator.pdf) in the Journal of Politics showing just how much additional confidence forecasts give us, and wrote about the implications for the 2020 election in a recent [USA Today op ed](https://www.usatoday.com/story/opinion/2020/10/01/election-forecasts-can-wrong-you-still-need-vote-column/5857993002/). 

I believe it was the sharp violation of expectations that was so disappointing to Clinton supporters and so invigorating for the MAGA crowd—the Washington elite had underestimated "real Americans" yet again. 
