# twitter-clone

This is a _twitter-clone_ backend application made on top of _Spring Boot_, a Java framework.
To run this application the following requirements are needed:
   * JDK 1.8 or more
   * Spring Boot framework compatible IDE.
   * Postman or any other API testing tool.
   * In memory SQL Database: H2
  
 **Functionalities along with APIs**:
  1. User Registration: _/register_
        1. Request Type: POST
        2. Sample POST Request Body:
            ```js
            
              {
                  "userName": "shraban",
                  "password": "tweet@123",
                  "fullName":"Shraban Karmakar"
              }
            ```
   2. Log In: _/login_
        1. Request Type: POST
        2. Sample POST Request Body:
            ```js
            
              {
                  "userName": "shraban",
                  "password": "tweet@123"
              }
            ```
   3. Log Out: _/logout_
        1. Request Type: POST
   4. Create Post: _/createPost_
        1. Request Type: POST
        2. Sample POST Request Body:
            ```js
            
              {
                  "tweet": "Hey there how are you today?"
              }
            ```
   5. Follow an User: _/follow/{userNameYouWantToFollow}_
        1. Request Type: POST
   6. Like a Post: _/like/{tweetId}_
        1. Request Type: POST
   7. Show Feeds: _/showFeeds_
        1. Request Type: GET
   8. List of all Post for an user: _/searchAllPost/{userName}_
        1. Request Type: GET
   9. Search for an User: _/search/{userName}_
        1. Request Type: GET

   
