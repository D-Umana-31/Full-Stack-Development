# CS465-fullstack
CS465 Full Stack Development with MEAN

**Architecture**

In the full stack Travlr Getaways project, two distinct frontend development types were implemented: traditional Express HTML with JavaScript, and a modern Angular Single Page Application (SPA). The Express HTML portion served static pages directly from the server and was mainly used for basic customer-facing interactions. It relied on JavaScript for limited interactivity and required full-page reloads for navigation. The Angular SPA used client-side routing and component-based architecture to deliver a more dynamic and responsive experience. This approach allowed real-time updates, seamless transitions between views, and a modular structure that enhanced maintainability and scalability. MongoDB was used on the backend due to its flexibility in handling dynamic, schema-less data. 

**Functionality**

JSON (JavaScript Object Notation) differs from JavaScript in that it is a data-interchange format rather than a scripting language. It is lightweight, text-based, and structured for easy data sharing between systems. JSON plays a key role in tying together the frontend and backend by enabling Angular on the client side to send and receive structured data via HTTP requests to the Express/Node.js backend, which then processes or updates the MongoDB database accordingly.

Throughout the full stack process, code refactoring was used to improve performance and efficiency. For example, reusable UI components like trip-card and trip-list in Angular were developed to display and manage trip data consistently across the SPA. This reduced redundancy, improved maintainability, and allowed for centralized updates to UI logic. Additionally, services were used in Angular to encapsulate HTTP logic, streamlining data retrieval and updates across components.

**Testing**

Full stack applications require comprehensive testing across all layers, especially for API interactions and security. Methods such as GET, POST, PUT, and DELETE were tested using tools like Postman to confirm that endpoints correctly interacted with the MongoDB database. Security added complexity to testing, especially due to the use of JSON Web Tokens (JWT) for authentication. When a user logged in, the frontend had to store and attach the JWT in the Authorization header for each subsequent API request. This required careful testing to verify that unauthorized users could not access. 


**Reflection**

This course has been instrumental in helping me move toward my professional goals of becoming a full stack developer or data analyst. I’ve gained hands-on experience with the MEAN stack, learned how to build secure RESTful APIs, developed dynamic and modular Angular applications, and integrated NoSQL databases with real-world functionality. I’ve developed and refined the following skills: building and testing RESTful APIs, implementing frontend-backend integration using JSON, securing applications with JWT-based authentication, creating reusable UI components and services in Angular, managing data flow in single-page applications, structuring and deploying full stack applications. These skills have strengthened my technical foundation and improved my ability to design, implement, and maintain scalable web applications, making me a more competitive and marketable candidate in today’s job market.
