# Blog-Web-App

This blog site was used using express, ejs, bodyParser, mongoose and lodash.

The site runs locally on port 3000 using nodemon.

A new post can be added by including "/compose" at the end of the root route.

The compose page consist of a title and post content input which then can be published.

Once published, the new post will be save to blogDB using mongoDB and will be retrived every time the user is routed to the root page.

The root page or home page consists of all the posts made by the user which can be "read more" by clicking on the link and routing the user to specified post route.

All data is dynamically saved and retrived through blogDB.
