| [home page](https://emmayeee.github.io/emmap-dataviz-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story: Behind the Label - What "Endangered" Doesn't Tell Us About American Birds?

## Project Links

1. Data Story (Shorthand): https://carnegiemellon.shorthandstories.com/behind-the-label-endangered-birds/index.html
2. Interactive Charts (Tableau Public): https://public.tableau.com/app/profile/ye.peng/viz/FinalProject-EmmaPeng/Sheet1
3. GitHub Repository: https://github.com/EmmaYeee/emmap-dataviz-portfolio/
4. Personal Portfolio (GitHub Pages): https://emmayeee.github.io/emmap-dataviz-portfolio/

# Changes made since Part II

The feedback from Part II was consistent: people understood the overall story and remembered that the survey can track only 4 of 42 listings, but they got stuck on the details. Most of my changes were about making each chart readable on its own, without needing to know anything about statistics or bird surveys.

The biggest surprise came from my interview. My interviewee read the bars in Figure 3 as different bird species, when they are actually the same bird in different regions. I had never noticed this could be misread, because I built the data and already knew what each bar meant. That changed how I approached Part III. Instead of only fixing labels, I added short explanations and transitions so the reader always knows what they are looking at and why the story is moving to the next chart.

## Specific changes

Figure 1: 
1) Added a note explaining that every bird starts at 100 so their changes can be compared.
2) Replaced labels like "FL DPS" and "proxy" with plain names like "Florida."
   
Figure 2: 
1) Removed the "CI excludes 0" legend, which meant nothing to a general reader.
2) The one clear result is now orange and the uncertain ones are blue, with a note explaining that crossing zero means the direction is unclear.

Figure 3: 
1) Added the subtitle "One bird, many regions," highlighted the protected region (only Western region) with enough data.
2) Fixed truncated labels.
3) Renamed the legend labels to make them more understandable.
   
Figure 4: 
Fixed truncated labels.

Following my instructor's feedback, I rebuilt the story around the Yellow-billed Cuckoo. It opens with the cuckoo's protection in the West, appears in every chart, and returns in the conclusion, which ties the four charts into one story instead of four separate findings. I also made the call-to-action part more specific and tiered by experience level (eBird app, local counts, BBS routes), which may helps my audience feel more engaged and makes the solutions more actionable.

## The audience

In Part II, I described my audience broadly as "general readers who care about nature." My TA's feedback pushed me to be more specific, and to make sure the call to action is something that audience can actually do.

Based on that, I narrowed the audience to nature-curious adults who enjoy birds casually: people who notice birds on walks or at a feeder, may have a bird app on their phone, but are not scientists. They care enough to read the story, and they are also the people best placed to help close the data gap it describes. According to the interviews, my interviewees tends to assume that "endangered" means a tiny population that is disappearing fast. That's really interesting, and it might be a common perception shared by many people. Therefore, I kept that assumption as the opening of the story.

To make the story work for this audience, I built the narrative around a specific bird, the Yellow-billed Cuckoo, so readers have a single "character" to follow from the first chart to the last. I also tried to eliminate technical terms in the charts, or replaced them with more understandable labels. In addition, I added caption under each chart, which may help explain the chart more clearly.

## Final design decisions

1. Story structure

   I organized the story around one protected bird and a sequence of questions: Is every endangered bird declining? How sure are we? Does the national number describe the protected birds? How many listed birds can we see at all? Each chart answers one question and sets up the next. 

2. Charts

   Across all four charts, I used one highlight color (orange) for the thing the reader should notice and gray for everything else. This made the takeaway visible at a glance and kept the charts consistent with each other.

3. Data

   The part that I spend most time on was not the design but the data. The ESA protects whole species, subspecies, or specific populations, while the survey mostly counts whole species. I hope to match each listed bird to the survey region that best fits where it is protected, rather than using national numbers by default. This decision shaped the whole story, and Figure 3 grew directly out of it.

4. Conclusion

   I know that I need to be honest about uncertainty and scope. I chose to show uncertainty in Figure 2 and make it as part of my data story, even though it makes the story less dramatic. In fact, adding that part provided more insight for me. It prompted me to reflect on an issue in bird conservation: perhaps the problem is not simply a lack of resources, but rather a misalignment between where we focus on and which species actually need our help.


## References
Full references are listed at the end of the Shorthand story. No additional sources were used for this writeup.

All data used in this project are public U.S. government data (U.S. Fish & Wildlife Service and U.S. Geological Survey). All charts were created by the author. The cover image is credited in the story and used under its stated license.

## AI acknowledgements
I used AI tools (ChatGPT and Claude) in two ways:

1. Data preparation: writing Python code to match FWS listings with BBS species, check data quality, and build the tables for each chart.
2. Tableau help: troubleshooting when I redesigning and polishing charts.
3. Writing: help organizing the brainstorm ideas of the Shorthand text, the presentation script, and these portfolio pages.

I made all the final decisions, checked every number against the original data, and edited all text so it reflects my own understanding.

# Final thoughts
The project turned out quite different from my Part I plan. I originally wanted to add an environmental chart using land-cover data, but as I worked with the survey data, the more interesting story was about what the data can and cannot show. It's surprising, but I believe it is more meaningful and more deserving of being told as a story. It is a small example of a bigger problem, and it is the part of the story I'd most like readers to remember.


