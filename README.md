# Facebook Post Analytics
**`P.S`: this documentation is divided between `WHY?`, `WHAT?`, `HOW`?**

## User Story
>As a **Facebook** user, I want to check the **performance and insights** of **my post**
>using an interactive **dashboard**.

#### Description
Tool to show various KPIs (likes, comments, shares, etc.) of a post through an interactive dashboard with charts and tables.

`Note: The introduction given above answers the 'why' of the user story.`
___
## Objective
To create a user-friendly dashboard application that allows Facebook users to track the performance of their posts, including likes, comments, and shares.

### Features
1. **User Authentication**
    - Allow users to log in using their Facebook account.
2. **Dashboard Overview**
    - Provide a summary view of post performance.
    - Display key metrics (KPIs) such as likes, comments, shares, and reactions.
3. **Interactive Charts and Graphs**
    - Visualize KPIs using various chart types (bar, line, pie charts).
    - Allow users to interact with charts (hover for details, click for more information).

`Note: The objective and features, given above answers the 'what' of the user story.`

____

`Note: This section provides the answer to 'how' to achieve the user story.`

## Requirements
- Facebook account
- Facebook developer account.
- Access Token
- Facebook Graph API - an API from facebook, which will be used to fetch posts data from facebook.

## Dashboard KPI's (Key Performance Indicators)
I have explored the FB Graph API for Posts data, decided upon various KPI's which can be shown, as listed below:
- whether the Post was popular or not.
- number of comments vs time ( let's us analyze engagement with posts with time period).
- number of shares of Post vs time (let's us analyze how much the post was shared with time period).
- story_tags vs reach (let's us analyze which tags has reached the user the most).

## Sequence Diagram
![User flow](/screenshots/sequence_diagram.png)

## Wireframes
![wireframes](/screenshots/wireframes.png)

## Tech Used
- [ReactJS] - for Frontend.
- [Django] - for Backend.
- [Django Rest Framework] - for REST Api.
- [Facebook Graph API] - facebook's API client to fetch data.
- [GitHub] - for version control.
- [Vercel] - for application deployment.


   [Django]: <https://docs.djangoproject.com/en/5.0/>
   [Django Rest Framework]: <https://www.django-rest-framework.org/>
   [Facebook Graph API]: <https://developers.facebook.com/docs/graph-api/>
   [ReactJS]: <https://react.dev/>
   [GitHub]: <https://github.com/>
   [Vercel]: <https://vercel.com/>
