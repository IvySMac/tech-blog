# Tech Talk!

## Description 
Welcome to Tech-Talk! A blog dedicated to posting one's thoughts on today's technology. A big part of creating this site was to explore log-in and log-out features, timeouts, posting and comments. I wasn't able to get to creating a comment feature yet, but I'm hoping to come back and do that. This was a great way of also understanding schemas and the relationship between models.  

## Usage
![In the top corner there is a logo that reads Tech Talk and to the far right there is a text that reads 'log-in'. In the center of the page there is a blog post titled 'The Future of AI' and a block of text under it that is in latin. Under the block of text, there is a button that says 'read more'.](../../challenges/tech-blog/public/images/techtalk-screenshot.jpg)

To access Tech-Talk, navigate your way to the 'login' link to the top right. This will give you the option to either log in with an existing account or sign-up. Once logged in, you'll be able to create posts and see your previous ones. You will also be able to see current posts on the front page and delete your own posts on your dashboard.

The 'Future of AI' post is simply there as a placeholder and an example of what blog posts look like! They are expandable if you hover over them and if you'd like to read the entire post, you can click 'read more' to see a static post. 

<a href="https://techtalkblog-c1120a1cd671.herokuapp.com/">Explore Tech-Talk</a>

## User Story
```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

```

## Acceptance Criteria
```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts

```

## Credits

Expand Div Effect - <a href="https://stackoverflow.com/questions/27441404/how-to-expand-a-div-and-its-contents-on-hover">Weafs.py on Stack Overflow</a>