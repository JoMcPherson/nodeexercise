# Courses2 API Express Server
This is the full backend for the Courses API exercises and supports GET, POST, PUT and DELETE endpoints for courses.

## Setup this server locally
This section discusses how to get the Courses API server up and running locally

- Verify Node.js is installed by running the following command.
  
  **Command to run**
  ```bash
    node -v
  ```
  **Sample Output**
  ```bash
    v14.15.4     (or something similar)
  ```

  > **Note:** If you do not have Node.js installed you can install the LTS (Long-term Support) version from here: https://nodejs.org/en/

- Clone this repository to your local computer.

  ```bash
    git clone https://github.com/DevelopIntelligenceBoulder/courses2-api-express-server
  ```

- Change directories (`cd`) into the newly cloned projects folder.

  ```bash
    cd courses2-api-express-server
  ```

- Install the projects dependencies with NPM (Node Package Manager).
  
  ```bash
    npm install
  ```

- Start the local server

  **Command to start the server**
  ```bash
    npm start
  ```

  **Expected Output**
  ```bash
    App listening at port 8081
  ```

- Verify the server is working as expected by acessing http://localhost:8081/api/courses with a broswer or a third party tool like [Postman](https://www.postman.com/)

  **Expected output from URL**
  ```js
  [{"id":1,"dept":"CompSci","courseNum":101,"courseName":"HTML5 and CSS3","instructor":"Rob","startDate":"July 8","numDays":10},{"id":2,"dept":"CompSci","courseNum":102,"courseName":"JavaScript","instructor":"Dana","startDate":"July 22","numDays":35},{"id":3,"dept":"CompSci","courseNum":201,"courseName":"Angular","instructor":"Rob","startDate":"Sep 9","numDays":15},{"id":4,"dept":"CompSci","courseNum":301,"courseName":"Java","instructor":"Maaike","startDate":"Oct 1","numDays":15},{"id":5,"dept":"CompSci","courseNum":302,"courseName":"C#","instructor":"Dana","startDate":"Oct 1","numDays":15},{"id":6,"dept":"CompSci","courseNum":401,"courseName":"Java Spring Boot","instructor":"Maaike","startDate":"Nov 1","numDays":15},{"id":7,"dept":"CompSci","courseNum":202,"courseName":".NET Web API","instructor":"Dana","startDate":"Nov 1","numDays":15},{"id":8,"dept":"Math","courseNum":"101","courseName":"Algebra","instructor":"Zephaniah","startDate":"Sep 15","numDays":10},{"id":9,"dept":"Math","courseNum":"201","courseName":"Statistics","instructor":"Elisha","startDate":"Oct 15","numDays":10},{"id":10,"dept":"English","courseNum":"101","courseName":"Composition","instructor":"Natalie","startDate":"Aug 1","numDays":5},{"id":11,"dept":"English","courseNum":"201","courseName":"Creative Fiction","instructor":"Siddalee","startDate":"Sep 1","numDays":6},{"id":12,"dept":"English","courseNum":"202","courseName":"Playwriting","instructor":"Ezra","startDate":"Oct 1","numDays":5},{"id":13,"dept":"Finance","courseNum":"101","courseName":"Basic Finance","instructor":"Pursalane","startDate":"Jun 1","numDays":5},{"id":14,"dept":"Finance","courseNum":"201","courseName":"Basics of Stocktrading","instructor":"Ian","startDate":"Dec 1","numDays":5},{"id":15,"dept":"Finance","courseNum":"301","courseName":"Entrepreneurship","instructor":"Zachary","startDate":"May","numDays":5},{"id":16,"dept":"Finance","courseNum":"401","courseName":"Tax Laws","instructor":"Brittany","startDate":"Aug 1","numDays":5}]
  ```
# nodeexercise
