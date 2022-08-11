# Mini-Project 1

*Due Friday 9/30 at 9pm.*

## Basic outline

1. Identify a question about how you use your time *that you feel comfortable sharing with your partner and me*.
2. Start the data collection process: start logging time in Google Calendar, macOS Calendar, or Outlook.
3. Export the calendar to `.ics` file format and then import into R.
    + The screencast demonstrates how to do this with Google Calendar. 
    + Test this early and test this often!
4. Exchange data! You will pass your question and data to your partner, and they will do an analysis with two non-redundant data visualizations.
5. Write a joint reflection piece on this experience. In particular
    + As someone who provides data: What expectations do you have when you give your data?
    + As someone who analyzes other people's data: What legal and ethical responsibilities do you have?
    + The joint reflection piece should be of **no more than 500 words**.

## Getting started

1. Find your group in the `#mp1` channel. Please identify:
    + Your group number.
    + Who your group leader is: whoever in your group is listed as `member_1`.
2. In RStudio, `File` > `New Project` > `Version Control` > `Git` and then copy and paste the "Clone" URL from this repo. Open `MP1.Rmd` in RStudio.

## Suggestions

Complete your minimally viable product (MVP)! When working on any project

* Don't try to do everything completely and perfectly from the beginning. This leads to perfectionist thinking, which leads to procrastination and "analysis paralysis."
* Do start by finishing a [MVP](https://www.forbes.com/sites/quora/2018/02/27/what-is-a-minimum-viable-product-and-why-do-companies-need-them/#178bd8a2382c). In other words:
    + [Done is better than perfect](https://lifehacker.com/done-is-better-than-perfect-5870379)
    + [Don't let perfect be the enemy of good](https://www.huffpost.com/entry/dont-let-the-perfect-be-t_b_158673)
* Once you're done your MVP, gather feedback on how your project works. Based on this feedback, then iterate and improve.

## Record standards and submit assignment

1. Open `standards.Rmd`, and under each heading, indicate how the work you completed for this project demonstrated fluency in that standard. Just 1-2 sentences per standard!
2. When you are done, you should save both .Rmd files, knit the documents, commit changes, and then push changes back to GitHub. That's it for submission. You don't need to submit anything on Moodle. 
3. Both group members: Fill out the peer evaluation [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSd6w4CC9-PrWrpupNfosQUBVoCWBihRwdezYb2jJEj7-kNdfg/viewform).

## Grading rubric

1. **Baseline:** Projects that do not satisfy all "baseline" criteria can expect to get a grade of less than 8/10.
    + Successfully collect data and import your calendar into R. This data
        Has to involve intervals of time: a start time and end time. For example, not “I went to sleep at.” but “I slept during these times.”
        Enter in at least two types of activities in your calendar. This activity type becomes the summary categorical variable with two levels.
        You need to collect at least 10 days worth of data.
    + All code must be visible in your PDF.
    + Create two data visualizations.
    + Include at least one ethical concern in your joint reflection.
    + The final submission should be production-quality, replete with data graphics and correct spelling and grammar.
    + All accompanying write-ups are coherent and respect the word count limit.
    + You submit your peer evaluation.
1. **Minimally viable product:** Grade: 8/10.
    + Satisfy all "baseline" criteria.
    + Data graphics are customized, making use of two available geoms and/or color palettes.
1. **Due diligence:** Grade: 9/10.
    + Satisfy all "baseline" and "minimally viable product" criteria.
    + All visualizations have appropriately labeled axes, legends, titles, etc. Such information gives the data’s context.
    + All visualizations are mindful of the <a href="https://medium.com/@sudharsanasai/declutter-your-chart-with-data-ink-ratio-6f6908727842" target="_blank">data-ink ratio</a>.
1. **Point of diminishing returns:** Grade: 10/10.
    + Satisfy all "baseline", "minimally viable product", and "due diligence" criteria.
    + Written text does an exceptional job of not only addressing the calendar analysis, but also attempting to address the ethical implications of such analysis.
