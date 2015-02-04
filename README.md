# nr-teaching-website
A website created for teaching kids how to create and host a webpage
link: http://mcprog.github.io/nr-teaching-website/
##How to create a basic webpage and publish it on the internet
1.  GOTO: https://github.com/
2.  Click **Sign Up**
3. Enter username
e.g. “Roger Carson” might have a username of “rcarson”
4. Enter valid email address
5. Enter password
6. Repeat password
7. Choose ‘Free’ plan
8. In Dashboard click ‘+’ sign by username
9. Create new repository
10. Name repository to ‘tutorial-website’
11. Check “initialize with a README”
12. Click Finish
13. In repository dashboard click ‘branch: master’
14. create a new branch called ‘gh-pages’
15. Hit Enter
16. In the ‘gh-pages’ branch click the ‘+’ by “tutorial-website / ” to “create new file here”
17. Name file ‘index.html’
18. Hit Enter
19. On line 1 type ‘<!DOCTYPE html>’
20. Below line 1 type
```html
<html>
    <head>
        <title>Your Website Title Here</title>
    </head>
    <body>
        <h1>Your Welcome Message Here</h1>
    </body>
</html>
```
21. Click ‘Commit New File’
22. In repository dashboard click setting off to the right Under ‘GitHub Pages’, it should say “Your site is published at http://yourname.github.io/yourwebsitename.”
23. Click the link and see if it works Anyone can see your website if you give them a link Take some time to change “Your Website Title Here” and “Your Welcome Message Here” to whatever you want (note that you have internet responsibility and anything you post could affect your future).
24. You can change the size of the welcome message by changing the 1 in "\<h1>" to any number from 1 to 6. You can also add new elements in between the body tags like so:
```html
<body>
    <h1>Your Welcome Message Here</h1>
    <h2>Your Subheading Here</h2>
    <h3>Your Article Heading Here</h3>
    <h4>Your Article Subheading Here</h4>
    <h5>Your Sub-article Heading Here</h5>
    <h6>Your Sub-article Subheading Here</h6>
</body>
```
25. An image can be added using
```html
<img src="https://www.petfinder.com/wp-content/uploads/2012/11/99059361-choose-cat-litter-632x475.jpg">
```
##How to create a basic website with with some simple elements and multiple pages
1. Modify the body of index.html to have an image, a heading, a paragraph and a button
2. Buttons can be add by the following code:
```html
<button>Click me</button>
```
3.  Here is an example of how you new body in index.html might look
```html
<body>
    <h1>Welcome to my website</h1>
    <p>This website is a website I created to better my skills in html. It does not have any real purpose, save education and practice. Thank you for visiting.</p>
    <img src="http://www.byui.edu/images/agriculture-life-sciences/flower.jpg">
    <button>Go to second page</button>
</body>
```
4. Now create the nex page by
    
