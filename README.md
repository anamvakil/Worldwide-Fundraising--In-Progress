# Worldwide-Fundraising-WIP


## Make It About Performance using Conditional Formatting

![image](https://github.com/user-attachments/assets/1d86c85f-8f85-4d9a-a73a-8a2101fe200f)

Now the ABC Seed director can easily see which account owners to congratulate and which to offer assistance

## Let’s Call Out Large Donations
Time to bring extra attention to large donation opportunities.

![image](https://github.com/user-attachments/assets/8327e7e7-c6d7-4310-b270-28f751b44de2)

### Engage Users with Animated Pages

How many times have you seen a dense dashboard with so much information that you didn’t know where to focus your attention? Or one that had information that was irrelevant to you? In Analytics, you can break up dashboards into multiple pages, each with a specific focus and audience.

## Create the Donations Page

First, let’s help the team focus on donations with a Donations page. So that we don’t lose any existing work, let’s make the current page our primary page. To create the Donations page, we clone the primary page and remove any widgets that we don’t need. You can save a lot of time by cloning pages instead of creating pages and their widgets from scratch.

![image](https://github.com/user-attachments/assets/c498daf2-fcb5-4c5a-8d5c-eeb1a083921d)

You now have two pages: one with all the widgets and another specific to donations. The Donations link widget serves as the title for the area inside the container widget. Next, let’s build the Leaderboard page to evaluate account owner performance. We’ll use the Leaderboard link widget as the title for the container widget on this page.

## Create the Leaderboard Page
To analyze account owners and compare their performance with others, let’s create a leaderboard. A Leaderboard page can rank account owners. If the director would like to spark some friendly competition, account owners can use this board to see who’s the top performer.

To build the page, we clone the Donations page, remove the donation widgets, and then add the Top Account Owners chart from the Primary page.

![image](https://github.com/user-attachments/assets/57185aba-45e2-4c88-9cc5-5a24f9d8721c)

## Create the Pipeline Page
Using the same process, create the Pipeline page by cloning the Leaderboard page, remove the existing chart and add the pipeline charts.

![image](https://github.com/user-attachments/assets/36889bf5-8557-4f2d-a69a-eff385bc92bc)

You’re done with the Pipeline page! Now you just need to build a way for users to navigate between pages. Let’s take care of that now.

## Make Analytics Fun with Animation
You can use a Navigation widget to allow users to toggle between pages. But to create custom links and a cool, dynamic accordion effect, let’s use the link widgets we created.

In the Donations page, connect the Leaderboard link widget to the Leaderboard page by modifying the link widget properties

![image](https://github.com/user-attachments/assets/a4f06364-a3f5-41c0-a5db-0a254c933893)

NOTE: To test out the links, click Preview, and then click the Donations, Leaderboard, or Pipeline links. Notice how the sections expand and collapse as you select each one—that’s the accordion effect!
Click the Edit button to continue editing the dashboard. When you first open a multipage dashboard, by default, the dashboard shows the first page. In this case, it’s Primary. We don’t want users to see the Primary page since all of its content is now available on the other pages. Let’s move the Primary page from the first position so that the Donations page opens by default.
Click the dropdown next to Primary, and click Move Right. Repeat this step two more times to make Primary the last tab. Because the Donations page appears first when you open a dashboard and there’s no link to the Primary page, users can’t access the Primary page while viewing the dashboard. Neat trick, right?
Save the dashboard.

Excellent! Instead of creating three separate dashboards, we used three pages, which allowed us to reuse widgets. We used similar layouts on the pages to create a neat accordion effect that shows and hides widgets.


