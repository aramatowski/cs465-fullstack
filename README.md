# cs465-fullstack
CS-465 Full Stack Development with MEAN

**Architecture**

_Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA)._

When creating the client-side aspect of the website that the users can interact with, I implemented Express HTML, JavaScript, and SPA. Express HTML was initially used to develop the frontend aspect of the website. JavaScript was used to add dynamically interact with the frontend and backend of the website. It retrieved information from the database to update the webpages as they were interacted with by the user. The SPA was implemented to increase the overall speed of the website so that the website does not need to fully reload each time the user interacts with it. 

_Why did the backend use a NoSQL MongoDB database?_

NoSQL MongoDB databases offer many advantages that were appropriate for this website. It can handle large volumes of data, allow ease when updating schemas, and can handle structured, semi-structured, and unstructured data at high speeds. 

**Functionality**

_How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?_

JSON is a text-based data format that is derived from JavaScript. JSON is used to format object data and is then read by JavaScript. The use of JSON allows JavaScript to read the data from the backend database and adjust the frontend objects accordingly. 

_Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components._

Individual trips were rendered separately via the trip card. However, trips as a whole were rendered via trip list components. This improved the functionality and efficiency of the site versus the alternative which would be to render each trip with it's components individually.

**Testing**

_Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application._

HTTP requests such as GET, POST, and PUT are methods that are used to retrieve and adjust or modify the database. These methods, along with others are used to implement the dynamic functioning of the website. They are implemented using functions of the database and are called via user interaction within the website. Endpoints are results of the methods and can be tested to ensure the methods are functioning correctly. Security is implemented to prevent unauthorized users to access the database. 

**Reflection**

_How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?_

This course has helped me tremendously with improving my skills with frontend and backend development and with learning techniques to bring front and backend together. This course has allowed me to create a website while working on all aspects of the process which has helped me to gain more experience and knowledge that can be used when searching for a job. 
