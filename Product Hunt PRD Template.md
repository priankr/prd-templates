# **Product/Feature Name: Product Hunt**

**One-Dine Description:** *“for people who love products”*

# **Intro & Goal**

Our goal is to make Product Hunt the destination to share and discover new, innovative products and services, from mobile apps to hardware products.  Others in this space focus on editorial curation, following more of a blog-like model.  Product Hunt is a community, a place to geek out about products with other enthusiastic people.

# **Who’s** it for?

1. **Product people** - those building products that enjoy discovering, playing with, and learning from new, innovative products. Also serves as a pulse on potential competing products
2. **Seed-Stage Investors** - always sourcing new deals and seeking signals to curate what startups to evaluate and meet.
3. **Everyday Tech Consumers** - people that love to find new stuff

# **Why** build it?

1. It’s something we personally enjoy using
2. Early, initial traction from “linkydink MVP” - 175+ subscribers, 30 contributors (some VC’s and founders)
3. Community verticals on the rise. GrowthHackers.com, Designer News, and Quibb have gained traction in specific startup/tech verticals.
4. Monetization opportunities in advertising and/or data
5. Tech-risk very low

# **What** is it?

## **Glossary**

1. **Post** - new product hunt submissions
2. **Comments** comments on a post
3. **Replies** replies to comments
4. **Vote** votes for a post
5. **Index View** - homepage of Product Hunt (all users can view this)
6. **Detailed View** permalink page for each post
7. **Profile View** - user profile page

## **User Types**

1. **Non-Registered Users** - people that have no yet registered
2. **Registered Viewers** people that have registered and can vote on posts but cannot post or comment.
3. **Contributors** - registered users that can post, comment, and upvote (ie, “Hunters”?)
4. Admins

## **Index View**

The Index View (ie, homepage) displays the list of posts chronologically, segmented by day (a la linkydink).

When not signed in, a CTA must be presented to signup.  When signed up, a CTA to post must be present.

The “Hunters” (ie, contributors) must also be listed, highlighting the community of product people curating the content.

## **Detailed View**

The Detailed View (ie, permalink page) displays information about the post (same as noted below) but with comments expanded.

Additionally, this page should include “who’s here,” showing profile pics of the people engaging in the conversation and/or voted

## **Posts**

Each post must contain:

1. **Name** - name of the product or service
2. **Tagline** - short (<60 character?) description of the product or service
3. **URL duh**
4. **Submitted By** person that submitted the post with their profile picture and/or name
5. **Votes** number of votes for that post w/ profile pics of each user that voted
6. **Comments** number of comments for that post (maybe with profile pics of those that commented)

After submitting a post, the user should be instructed to say something interesting, adding the first comment to spark conversation.

## **Comments**

Every post has a comment feed, algorithmically ranked like HN to surface the top comments.  Each comment includes:

1. **Comment Text** CTA should frame the conversation (e.g. “say something interesting about Coin”)
2. **Submitted By** - user that commented
3. **Votes** - users can vote up comments
4. **Replies** - replies are chronologic, one-layer deep (ie, no threaded replies)

## **Following**

Users can follow other users.  This does not change the Index View (the feed of posts) but will be used to re-engage users when people they follow take actions like post, upvote, or comment.

## **Email Notifications**

Users receive the following email notifications:

1. **Daily Product Hunt digest** - list of all posts for the day (later could be top 10 products and could be changed to weekly digest if the user prefers)
2. **Social Re-engagement**
    1. Follows
    2. Votes on Their Posts
    3. Comments on Their Posts
    4. Comments on Posts They Voted On
    5. Replies to Comments They Made

## **Registration**

Every user must register with Twitter, pulling in the following information:

1. Name
2. Profile Pic
3. Twitter URL
4. Twitter Username (for tagging/mentions in the future maybe)

Additionally, they must also provide:

1. Email Address
2. Title and Company Name

# **Brainstormed Ideas**

1. **Guide and Structure Comments** - preface comments with structure (e.g. “this product is similar to…”, “this product is awesome because…”) a la Facebook’s “I’m watching…”, “I’m eating…”
2. **Related Links** press, blog posts, etc
3. **Algorithmic (HN-like) Ranking**
4. **Editors Picks** - “starring” editorial picks
5. **Product Hunt Groups** people can create groups, similar to subreddits

# **Competitors & Product Inspiration**

1. [Beta List](http://betali.st/) - paid promotion (and maybe some editorial) of early, often in beta, startups
2. [StartupList](http://startupli.st/) - editorial curation of new startups
3. [TastemakerX](http://www.tastemakerx.com/) - music discovery community

# **Seeding Users & Content**

Initial contributors will be hand-picked to create exclusivity and reduce potential spam.  Ideal contributors will be recognizable product people (e.g. Nir Eyal, Semil Shah, Hiten Shah) and investors (e.g. Josh Elman, Nick Chirls) in the startup space but may also include lesser known, early tech adopters.

To capture higher profile startup personalities like Hunter Walk we may submit product finds on his behalf with permission (e.g. based on something he’s tweeted).

**Mockups**

**Index View**


# **Tech Notes**

**Models**

- User
    - twitter_uid
    - name
    - username
    - image
    - headline
    - daily_email?
- Post
    - user_id
    - name
    - tagline
    - clicks
    - url
- PostVote
    - user_id
    - post_id
- Comment
    - user_id
    - body
- CommentVote
    - user_id
    - comment_id
- Reply
    - comment_id
    - user_id
    - body

# **Go to Market**

1. **Engage/Recruit Influencers - make them feel part of the product’s success and design**
    1. Ask for direct product feedback
    2. Feedback on blog post/press release
2. **Invite Contributors Before Public Launch - ensure content is populated**
3. **Blog Post - “30 Minute MVP”**
    1. **Post on PandoDaily or Andrew Chen’s blog?**
    2. Submit to Hacker News, GrowthHackers.com, Designer News, Quibb
4. **Press Release**
    1. Reach out to press contacts (PandoDaily, FastCo)
    2. Mass distro other press (see http://customerdevlabs.com/2013/09/24/google-news-api-mturk-press/)
5. **Startup Edition and Ryan’s Personal Email List** ~4k subscribers
6. **Email Existing Linkydink Users**

## **Post-Launch Marketing**

1. **Product Deconstructions Blog Posts**

**View Original Template:** [Product Hunt’s PRD Template](https://docs.google.com/document/d/1yrU5F6Gxhkfma91wf_IbZfexw8_fahbGQLW3EvwdfQI/edit)