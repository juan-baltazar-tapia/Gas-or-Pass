# Web Development Final Project - Album discussion board

Submitted by: Juan Baltazar Tapia

This web app: Search up a artist and add an album to the discussion! Write down your opinions on every song and upvote thoughfull and intriquing posts. Upvote your favorite songs and comments and enjoy the community.

Time spent: 16 hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] **A create form that allows the user to create posts**
- [X] **Posts have a title and optionally additional textual content and/or an image added as an external image URL**
- [X] **A home feed displaying previously created posts**
- [X] **By default, the time created, title, and number of upvotes for each post is shown on the feed**
- [X] **Clicking on a post shall direct the user to a new page for the selected post**
- [X] **Users can sort posts by either their created time or upvotes count**
- [X] **Users can search for posts by title**
- [X] **A separate post page for each created post, where any additional information is shown is linked whenever a user clicks a post**
- [ ] **Users can leave comments underneath a post on the post's separate page**
- [X] **Each post should have an upvote button on the post's page. Each click increases its upvotes count by one and users can upvote any number of times**
- [X] **A previously created post can be edited or deleted from its post page**

The following **optional** features are implemented:

- [ ] Users can only edit and deleted posts or delete comments by entering the secret key, which is set by the user during post creation
- [ ] Upon launching the web app, the user is assigned a random user ID. It will be associated with all posts and comments that they make and displayed on them.
- [ ] Users can repost a previous post by referencing its post ID. On the post page of the new post, the referenced post is displayed and linked, creating a thread
- [ ] Users can customize the interface of the web app
- [ ] Users can share and view web videos
- [ ] Users can set flags while creating a post. Then users can filter posts by flags on the home feed.
- [ ] Users can upload images directly from their local machine as an image file
- [ ] Display a loading animation whenever data is being fetched


## Video Walkthrough

Here's a walkthrough of the website in 4 seperate parts

Creating comments, viewing previous posts (comments), and clicking on comment to view more info.

<img src='https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdDAzbjByb2FvZjMxbnFwcTkzbWFlZXJqbDJxam8wanc4bHRjenRzNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JhyizLjshOLFTGwOLl/giphy.gif' title='Video Walkthrough' width='600px' alt='Video Walkthrough' />
Toggling comments by upvotes and time created, editing and deleting comments.

<img src='https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWpnbXdxOG9hemt0dHhpZ3V1ejB1Z2Rsc252bmFhaWY1NWIwcjVveSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lEQq3HyMT7MvC2QFll/giphy.gif' title='Video Walkthrough' width='600px' alt='Video Walkthrough' />

Upvoting multiple comments and adding an album to the album list.

<img src='https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmoyMmY2ejFvbzF3eGpla3RleDAwemN0aGVsNHFsc3k5MDRvZzJ3YyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/8WMYWMYT6gqm377uWK/giphy.gif' title='Video Walkthrough' width='600px' alt='Video Walkthrough' />

Searching comments by title.

<img src='https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYmU2cW95amN4d2Y1amVzbmRzMHl4bzF3OXJlOGd2OHA4cWlvcmNkayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Vd1CunQU9XlahF37FG/giphy.gif' title='Video Walkthrough' width='600px' alt='Video Walkthrough' />


GIF created with ...  
[Kap](https://getkap.co/) for macOS

## Notes

The most challenging aspect of working on this discussion board was understanding the one to many relations between artists to albums, albums to songs, and songs to comments and implementing the funcitonality into it.

## License

    Copyright 2024 Juan Baltazar Tapia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
