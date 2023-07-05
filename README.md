## Starting Off
1. Create a new Java Project
2. Inside your package, create 4 folders below
   - controller
   - model
   - repository
   - service
3. In Model package, create BlogPost class and create getters and setters to below from the homework
  - Long id
  - String title
  - String content
  - String author
4. In Repository package, Create BlogRepository class and have it extend JPARepository but remember to add <BlogPost, Long>.
5. In Service package, create BlogpostService class that handles the business logic for CRUD operations.
6. In Controller package, create BlogPostController to handle http requests that calls the methods from BlogPostService.
7. Once you have finished with the code, open the BlogPlatformHWApplication (or the spring runnable class) and click the Run button.
8. After a success message that it has started, you can navigate to BlogPostController, hover over the world icon, and click generate http request in http client.
9. A new tab will open and you can choose to customize your methods if necessary. You can navigate to the website at http://localhost:8080/posts. The homepage however does not have anything setup there so please head to http://localhost:8080/posts to ensure you can see the creation of posts after running the program and generating the http requests. 
