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
    ```
   ## Practice 3-1
    ### Clone the repository (if not already cloned)
    git clone https://github.com/MorgunovE/A18GitPratique2.git
    cd A18GitPratique2
    
    ### Create the Feature-01 branch and switch to it
    git checkout -b Feature-01
    
    ### Create the file README.txt (ensure it is added manually in your IDE or via command line)
    echo "Project Documentation" > README.txt
    
    ### Stage and commit the new file
    git add README.txt
    git commit -m "Add README.txt"
    
    ### Push the branch to remote
    git push --set-upstream origin Feature-01

   ### Switch to master and merge Feature-01 (using merge method)
    git checkout master
    git merge Feature-01
    
    ### Check the Git log to ensure the merge commit is present
    git log --oneline --graph
    
    ### Delete the Feature-01 branch locally and remotely
    git branch -d Feature-01
    git push origin --delete Feature-01

## Practice 3-2
### Create the Feature-02 branch from master
git checkout -b Feature-02

### Create the file tmp.txt (ensure it is added manually in your IDE or via command line)
echo "Temporary file content" > tmp.txt

### Stage and commit the new file
git add tmp.txt
git commit -m "Add tmp.txt"

### Push the branch to remote
git push --set-upstream origin Feature-02

### Switch to master and merge Feature-02 (using merge method; check the Git log if needed)
git checkout master
git merge Feature-02

### Verify the merge via Git log
git log --oneline --graph

### Delete the Feature-02 branch locally and remotely
git branch -d Feature-02
git push origin --delete Feature-02