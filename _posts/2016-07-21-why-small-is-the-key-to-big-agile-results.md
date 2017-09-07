---
title: 'Why Small is the Key to Big Agile Results'
author: anjuan
layout: post
date: "2016-07-21"
permalink: /blog/why-smaill-is-the-key-to-big-agile-results/
categories:
  - Software Development
excerpt: "Software development efforts often try to quickly scale resources in order to speed the pace of development. Hoewever, taking a small approach can often yield better results."
---

{% include image.html url="/images/post-small-key-big-agile.jpeg" alt="Hummingbird" caption="Big results can come from small things. (Pexels)" width=400 align="right" %}

It’s tempting to solve software application performance problems by throwing hardware at the problem. Since machines are relatively cheap, horizontally scaling by adding more servers is a common initial remedy. However, this soon runs into diminishing results since large numbers of machines can’t optimize code.

The same principle applies to Agile software development teams. Since the market can provide nearly unlimited sources of programming talent, hiring more developers is a common remedy for solving the perception that not enough work is getting done. However, a large number of developers can’t optimize the work that flows through the Development Team simply through numeric strength.

Contrary to what most people would intuitively think, taking a small approach to software development can increase the amount of work that can be completed by an Agile software development team, especially those that practice Scrum. This requires understanding the concepts of small teams, small releases, and small vertical slices.

## Small Teams

I’ve seen Scrum Teams with 20 or more developers, and my first instinct is always to break them up into smaller Scrum Teams. Scrum recommends that the Development Team should be between 3 and 9 people. If a Development Team has less than 3 people, then it may be difficult to have all of the skills needed to complete the potentially shippable product increment by the end of the sprint. If a Development Team has more than 9 people, then coordination costs begin to dramatically rise.

Let’s say you have one Scrum Master, one Product Owner, and five Development Team members. That is a total of seven people on the Scrum Team. The number of communication channels for this seven person team can be calculated using the formula n(n-1)/2 where n is the number of people on the team. Using this formula, we can determine that there are 21 communication channels. However, adding more people to the team dramatically increases the number of communication channels:


| Team Members | Communication Channels |
| ------------ | ---------------------- |
|  8           |       28               |
|  9           |       36               |
| 10	         |       45               | 
| 11	         |       55               |
| 12           |       66               |
| 13           |       78               |
| 14	         |       91               |
| 15	         |      105               |
| 16	         |      120               | 
| 17	         |      136               |
| 18	         |      153               |
| 19	         |      171               |
| 20	         |      190               |

<table align="center" style="padding-bottom: 20px; margin: 0px auto; text-align:center"><caption><strong>How Communication Channels Expand as Team Members Grow</strong></caption>
<tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr><tr><td style="text-align:left"></td><td colspan="4"><strong>Voted for Trump</strong></td></tr>
<tr><td style="text-align:left"></td><td><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All Voters&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong></td><td><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;White Voters&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong></td><td><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Obama Voters&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong></td><td><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Democrats&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong></td></tr>
<tr><td style="text-align:left"></td><td><strong>Model 1</strong></td><td><strong>Model 2</strong></td><td><strong>Model 3</strong></td><td><strong>Model 4</strong></td></tr>
<tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr>
<tr><td colspan="5" style="text-align:left"><em>Basic Socio-demographics</em></td></tr>
<tr><td style="text-align:left">Age</td><td>0.543<sup>***</sup></td><td>0.552<sup>***</sup></td><td>-0.339<sup>***</sup></td><td>-0.155<sup>*</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.042)</td><td>(0.048)</td><td>(0.074)</td><td>(0.081)</td></tr>
<tr><td style="text-align:left">Age^2</td><td>-0.224<sup>***</sup></td><td>-0.219<sup>**</sup></td><td>-0.120</td><td>-0.236</td></tr>
<tr><td style="text-align:left"></td><td>(0.077)</td><td>(0.086)</td><td>(0.148)</td><td>(0.159)</td></tr>
<tr><td style="text-align:left">Female</td><td>-0.086<sup>**</sup></td><td>-0.032</td><td>-0.176<sup>***</sup></td><td>-0.355<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.037)</td><td>(0.041)</td><td>(0.062)</td><td>(0.071)</td></tr>
<tr><td style="text-align:left">College Educated</td><td>-0.535<sup>***</sup></td><td>-0.636<sup>***</sup></td><td>-0.487<sup>***</sup></td><td>-0.435<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.040)</td><td>(0.045)</td><td>(0.071)</td><td>(0.084)</td></tr>
<tr><td style="text-align:left">Family Income</td><td>0.0003</td><td>-0.054</td><td>0.106</td><td>0.112</td></tr>
<tr><td style="text-align:left"></td><td>(0.042)</td><td>(0.047)</td><td>(0.073)</td><td>(0.082)</td></tr>
<tr><td style="text-align:left">Family Income^2</td><td>-0.168<sup>**</sup></td><td>-0.131</td><td>-0.400<sup>***</sup></td><td>-0.458<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.074)</td><td>(0.084)</td><td>(0.130)</td><td>(0.150)</td></tr>
<tr><td style="text-align:left">Black</td><td>-1.041<sup>***</sup></td><td></td><td>-0.911<sup>***</sup></td><td>-1.457<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.091)</td><td></td><td>(0.122)</td><td>(0.138)</td></tr>
<tr><td style="text-align:left">Hispanic/Latino</td><td>-0.302<sup>***</sup></td><td></td><td>-0.452<sup>***</sup></td><td>-0.612<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.073)</td><td></td><td>(0.117)</td><td>(0.128)</td></tr>
<tr><td style="text-align:left">Other Race</td><td>-0.196<sup>*</sup></td><td></td><td>-0.289</td><td>-0.493<sup>**</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.109)</td><td></td><td>(0.176)</td><td>(0.215)</td></tr>
<tr><td colspan="5" style="text-align:left"><em>Political/Religious Values</em></td></tr>
<tr><td style="text-align:left">Partisanship (D to R)</td><td>3.113<sup>***</sup></td><td>3.171<sup>***</sup></td><td>2.542<sup>***</sup></td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.049)</td><td>(0.056)</td><td>(0.080)</td><td></td></tr>
<tr><td style="text-align:left">Ideology (L to C)</td><td>1.217<sup>***</sup></td><td>1.322<sup>***</sup></td><td>1.003<sup>***</sup></td><td>1.191<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.053)</td><td>(0.061)</td><td>(0.087)</td><td>(0.087)</td></tr>
<tr><td style="text-align:left">Religiosity</td><td>0.562<sup>***</sup></td><td>0.599<sup>***</sup></td><td>0.719<sup>***</sup></td><td>0.750<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.040)</td><td>(0.044)</td><td>(0.069)</td><td>(0.082)</td></tr>
<tr><td style="text-align:left">Cognitive Racism</td><td>1.971<sup>***</sup></td><td>1.971<sup>***</sup></td><td>1.926<sup>***</sup></td><td>1.928<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.049)</td><td>(0.057)</td><td>(0.083)</td><td>(0.093)</td></tr>
<tr><td style="text-align:left">Empathetic Racism</td><td>0.636<sup>***</sup></td><td>0.657<sup>***</sup></td><td>0.780<sup>***</sup></td><td>0.808<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.038)</td><td>(0.042)</td><td>(0.064)</td><td>(0.075)</td></tr>
<tr><td style="text-align:left">Partisanship*Cognitive Racism</td><td>-0.533<sup>***</sup></td><td>-0.664<sup>***</sup></td><td>-0.235</td><td></td></tr>
<tr><td style="text-align:left"></td><td>(0.113)</td><td>(0.130)</td><td>(0.199)</td><td></td></tr>
<tr><td style="text-align:left">Constant</td><td>-0.519<sup>***</sup></td><td>-0.535<sup>***</sup></td><td>-0.914<sup>***</sup></td><td>-1.498<sup>***</sup></td></tr>
<tr><td style="text-align:left"></td><td>(0.049)</td><td>(0.054)</td><td>(0.074)</td><td>(0.087)</td></tr>
<tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr>
<tr><td style="text-align:left">N</td><td>38,494</td><td>29,724</td><td>19,503</td><td>15,699</td></tr>
<tr><td colspan="5" style="border-bottom: 1px solid black"></td></tr><tr><td colspan="5" style="text-align:right; font-size: 12px"><sup>***</sup>p < .01; <sup>**</sup>p < .05; <sup>*</sup>p < .1</td></tr>
<tr><td colspan="5" style="text-align:right; font-size: 12px">All models include a random effect for state, which I omit here for presentation.</td></tr>
</table>


For example, if three people are added to the seven person Scrum team (a 30% increase in team size), you more than double the number of communication channels. If you double the seven person Scrum Team to 14 people, you more than quadruple the number of communication channels.

Small teams are better positioned to efficiently and effectively manage Scrum events like Sprint Planning, the Daily Standups, the Sprint Review, and the Sprint Retrospective. Having a small team size increases the likelihood the team communication is focused and fast decisions can be made.

Since Agile teams thrive in an environment with co-located teams that interact through face-to-face contact and regularly reflect with each other, Development Teams with more than nine people can’t communicate effectively enough to maximize their agility.

## Small Releases

It can be tempting to drive a software development team to deliver big releases chock full of awesome features. However, small releases with a small set of features provide benefits to both the team and to customers.

When a team considers which items to pull into the Sprint Backlog from the Product Backlog during Sprint Planning, small features (we call them user stories) are essential. Small user stories are easier for the team to understand because the work is specific and granular. This simplifies the process of determining the effort needed to complete each feature by the Development Team. Small user stories reduce the difficulty of determining the complexity, risk, and size of features by lowering uncertainty. The Product Owner and Development Team can quickly obtain a shared understanding of the work and produce accurate estimates. Furthermore, smaller user stories allow Development Teams to feel an almost daily sense of progress as they finish features throughout the execution of the sprint.

When a small set of features are delivered to customers, they are better able to understand the delivered software and provide feedback. Give a user ten complicated features and they’ll delay giving you feedback for as long as possible. However, give a user three simple features, and you’ll get feedback before you return from your coffee break. The human mind can only process so much information at once, and we delay analyzing large data sets when we can get away with it. You can confirm this by simply checking the number of unread emails in your inbox.

## Small Vertical Slices

Developers often think of applications in terms of horizontal layers, and they often build software layer by layer. For example, developers will often build the entire back end database for a release, then the application logic, and then the user interface. It’s not uncommon for Development Teams that take this approach to finish a sprint with one layer “Done”. However, this is not a working product increment. How can a back end database be discussed during a Sprint Review? How can a user interface, no matter how elegant, be shown in a demo if it doesn’t work? Furthermore, delivering these layers separately from each other hinders the ability for upper layers to teach you about the lower layers. For example, if the back end database is fully developed before the user interface is started, then problems that can only be detected by the UI can result in the need to rebuild the database.

A better approach is to think of applications in terms of features composed of vertical slices that each have a data, logic, and presentation layer. Therefore, working on Feature X means creating the database tables, business logic, and user interface for Feature X. This greatly increases the chance that Feature X will be working by the time of the Sprint Review and can be verified by the Product Owner. By building out an application vertical slice by vertical slice, the Development Team can deliver features faster and learn things from early vertical slices that can be applied to future vertical slices.

## Conclusion

The next time you spin up an Agile software development team or try to improve an existing one, consider taking a small approach. Seek to create a small team that delivers small features in small vertical slices. You may be surprised by the size of the results.