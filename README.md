# Nucamp_Portfolio_Project_DevOps
**Description:** Backend Django Application to test API endpoints based on a Tech uploading article site. 



## Brainstorming Ideas
1.) What are the various features you would like your project to offer? 
- For my project, I want to create a traditional CRUD application to use all of its functionalities. My project will have features to create, update, or delete. The main premise of my project will be a place where writers can post their articles for others to reads. They won’t be uploading whole articles but instead only use the title and description of it to show up in JSON format to test out the endpoints.

2.) What are the API endpoints that you would need to set up for each feature? List them along with the respective HTTP verb, endpoint URL, and any special details (query parameters, request bodies, headers). 
- I will create 2 GET endpoints for the title and writer. A POST to upload the title to the site. A PUT to update any existing information and a DELETE to delete a whole entry. As for headers and request parameters, I haven’t decided how am I going to call them. I will probably use something like “.../title/writers”, “.../writers”. Something along those lines. 

3.) Provide a description of the database tables required for your application, including column names, data types, constraints, and foreign keys. Include your database name. You can optionally include an ER diagram. 
- When creating my database tables I want to keep it simple, I will create 2 tables. The first one will have (Writer-ID/Name/Country/Yrs of Exp) and the second table will have (Writer-ID/Title/Category). I want to use the category column to separate which programming language they are using. I will have 1 FK which will be to connect the 1st table of the writer’s info to the 2nd table which is the writer’s title and category. I haven’t started to create this yet but I will start to generate an ER diagram and slowly work on it into my Django application. 


