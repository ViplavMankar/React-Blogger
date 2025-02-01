# React application
 - The frontend of the application is written using React JS library
 - Along with core React other components have been used like
   - 'react-router-dom' for routing the requests to their respective pages in this web application
   - 'react-hook-from' for handling the form created in creating a post
   - 'tinymce' for creating a rich text editor(RTE)
   - -react-redux' for providing the redux store to this web application to be accessed by all the components.
   - 'html-react-parser' for parsing the content saved from the RTE and convert it to valid HTML to be showcased along with the image posted for any blog article.
 - All the users can see their posts, but only the user that has posted the blog may be able to manage his/her post.

![Screenshot from 2025-02-01 19-24-57](https://github.com/user-attachments/assets/8314ec4b-a814-4be6-9632-a7de5de48af9)

![Screenshot from 2025-02-01 19-35-22](https://github.com/user-attachments/assets/4aa1a2ba-b0d8-441a-bd2a-d277f9785788)

# Appwrite backend
  - Appwrite is a Backend-As-A-Service provider which allows us to build quality web applications faster without having to worry about backend and database setup, and along with this appwrite also takes care of backend API's for creating, reading, updating, deleting(CRUD) operations on the database.
  - Appwrite is used with this web application and serves as the backend service with the database that stores the images, and the content to be showcased for any blog article posted.

# Appwrite database
  - Database is used from appwrite itself, and the database contains both the html content of the blog as well as the image being featured in the blog post.

# Deployment on Vercel
  - This web application has been deployed with vercel and can be accessed with the url :- https://react-blogger-rust.vercel.app/
