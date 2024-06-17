# Full_Stack_-MEAN-_Blog_App
Angular 17 blog application with MEAN Stack

# Requirements
MongoDB
@angular/cli
NodeJS

# Installation & Setup
Clone the repository: $ git clone https://github.com/quanweilena/My-Blog.git
Go into the main directory: $ cd My-Blog
Install the required packages: $ npm install 
Go into the client directory: $ cd client
Install Angular 2 required packages: $ npm install
Go back to the main directory: $ cd ..
Build the application: $ npm run build
Start the local application: $ npm start
Access the API at [http://localhost:8080]

# Features

# Home
The User can see the Blog without any Registration.

# Register
Put valid USERNAME and PASSWORD in the input section.
The 'Submit' button is only enabled if all the fields are filled satisfactorily;
Go to Login Page 

# Login
Users can log into existing accounts using only correct match of username and password;
when successfully logged in and redirect to Blog page after 2s.
 
# Profile
Users can access their profile after logged in by clicking 'Profile' on the Header.

#  Post Blogs
User can create a new blog by clicking 'Create-Post' on Blog page;
Blog Title, body and Image File are required  when creating a new blog. 
Automatically redirect to Blog page after posting;
Creator and post date are also displayed for each post.

# Edit Blogs
The blog creater can edit his/her own blogs when logged in by clicking the 'Edit-Blog' button;
Both title and body , Image can be edited;
Click 'Submit' to confirm changes;
Click 'Delete' to delete the blog.

# Delete Blogs
The blog creater can delete his/her own blogs when logged;

# Future's Work
# Like/Dislike Blogs
User can only like/dislike other users' blog by clicking 'LIKE'/'DISLIKE' button;
User can only either like or dislike a certain blog;
The numbers of likes and dislikes are displayed;
When hover on the 'LIKE'/'DISLIKE' button, a list of likers/dislikers is displayed below the button. By clicking the username in this list, user can access the public profile of that liker/disliker.
# Comments
Users can post comments on any blogs by clicking 'POST COMMENT' button;
Users can choose to show/hide comments;
The blog creator can delete any comment for his/her own blogs;
Users can delete their own comments.
