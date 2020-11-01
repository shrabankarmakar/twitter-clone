# twitter-clone

This is a _twitter-clone_ backend application made on top of _Spring Boot_, a Java framework.
To run this application the following requirements are needed:
   * JDK 1.8 or more
   * Spring Boot framework compatible IDE.
   * Postman or any other API testing tool.
   * In memory SQL Database: H2
  
 **Functionalities along with APIs**:
  1. User Registration: /register
        1. Request Type: POST
        2. Sample POST Request Body:
                     <h6 style="color:red;">
                                  {<br> 
                                    "userName": "shraban",<br> 
                                    "password": "tweet@123",<br> 
                                    "fullName":"Shraban Karmakar"<br> 
                                  }
                     </h6>
