# A18GitPratique2 form Feature-01

A18GitPratique2 is a Java web application built with Maven. It demonstrates a simple servlet that displays a "Hello World!" message. The project is packaged as a WAR file and is configured using a standard `web.xml` file.

## Project Structure

- **src/main/java** – Contains Java source code.  
  - `edu.bdeb.swiftbank.a18.pratique2.a18gitpratique2/HelloServlet.java` – A simple servlet class.
- **src/main/webapp** – Contains web resources.
  - `WEB-INF/web.xml` – Servlet configuration file.
  - `index.jsp` – A simple JSP page linking to the servlet.
- **pom.xml** – Maven configuration file for dependencies and build plugins.

## Prerequisites

- JDK 21  
- Apache Maven  
- A Servlet container (Tomcat 9 or newer)  
  - Note: The project is configured with the Javax Servlet API. If you wish to use Jakarta's Servlet API, adjust both the code and dependencies accordingly.

## Build and Deployment

1. **Build the project:**

   Open a terminal in the project root and run:

   ```bash
   mvn clean package