## Node.js MVC: Parsing Form Data and Adding a New Blog

Enhance an existing Node.js MVC application to include form data parsing and routing functionality. Implement the following features within the existing codebase:

# Render Blog Form

    1.Implement a route handler for a GET request to "/createblog" in index.js.
    2.Complete the renderBlogForm function defined in blog.controller.js to render the "renderBlogForm" view and return it as the response.

# Render Blogs

    1.Implement a route handler for a GET request to "/" in index.js.

    2.Complete the renderBlogs function, as defined in blog.controller.js, to render the "blogs" view. This view will display all the data from the "blogs" array in blog.model.js and return it as the response.
    Additionally, implement the "blogs" view, which will list all the data for the blogs.

# Add New Blog

    1.Implement a route handler for a POST request to "/addblog" in index.js.
    2.Complete the addBlog function defined in blog.controller.js to handle the user's POST request.
    3.Update the "blogs" array in blog.model.js with the newly added blog.
    4.Render the "blog" view with the updated "blogs" array to display the newly added blog along with the existing blogs.
    5.Return the addBlog function as a response, and ensure that the response is accompanied by the status code 201.

## Output

See the sample output GIF file inside output folder for the expected behavior of the implemented features.

Sample Output: https://files.codingninjas.in/output-27944.gif

## Note

Follow the Node.js MVC pattern to maintain a clear separation of concerns among models, views, and controllers. Utilize the EJS templating engine for rendering views. Your responsibility is limited to the specified changes within the existing codebase.
