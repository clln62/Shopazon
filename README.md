# Welcome to Shopazon Proxy!

In this repo, I have created a proxy server that brings a total of six different React based components, their servers, and databases to render a single-page app that features a cohesive product.


## Stack

| Front End     | Back End      | 
| ------------- | ------------- |  
| <img src="https://cdn.worldvectorlogo.com/logos/react.svg" height="125px" width="125px"></img>  | <img src="https://cdn.pixabay.com/photo/2015/04/23/17/41/node-js-736399_960_720.png" height="85px" width="125px"></img>  |
|   | <img src="https://buttercms.com/static/images/tech_banners/ExpressJS.png" height="85px" width="125px"></img>  |





### Front End

The front end was very minimal in its needs, as all of the components were already built. Bringing them all together with React, HTML, and CSS, the finished product is a seamless, single-page app.

### Back End

With Morgan and Express partnered together, I was able to build a proxy server that could run six other servers all at once in order to provide a working app for the user.

### Deployment

Deployment is a future project that will require deployment of all six individual components, servers, and databases to allow for a better accessible proxy server through AWS.


## Work Flow

**This project was managed using git workflow:**

We have one development branch that branches out specific features. When they are ready to be deployed, features are deployed as follows:
1. The branch is rebased to consolidate commit history and ensure only working code is pushed to the dev branch.<br/>
2. The branch is pushed.<br/>
3. A pull request is made.<br/>
4. Another member of the team is to perform a review before merging the branch into developer.<br/>
5. At the end of a sprint, the developer branch is merged into production.

#### In addition to git, we also used Trello to manage pending tasks, bugs and feedback.

**Trello Board: https://trello.com/b/AlzmSI6G/shopazon**

<img src="./images/ShopazonTrello.png"></img>



## Challenges & Learning

This project was an opportunity to work in a group of six Army veterans, while building my own proxy server that could run six individual components and servers.

### Challenges

- Building a proxy server was a completely new idea that required much research and trial and error to get a working product.<br/>
- Learning about the complications of passing CSS from individual components became a realization when some styling got lost in translation and required a different approach.<br/>

### Learnings

- Partnering with other team members truly helped in growing through this new idea and learning new technologies.<br/>
- Time management became a big aspect that assisted in building a working proxy server in a short amount of time, while still working with the rest of the team.<br/>
- Tickets on Trello assisted the team in planning and production. Utilizing Trello kept organization and accountability in creating and developing a production level proxy server.


#### Check out the client side of this app here: https://github.com/clln62/shopazonRelatedItems
