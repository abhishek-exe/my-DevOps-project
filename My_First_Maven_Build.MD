----Create a First Maven Jenkins job to build hello-world project 
----*Jenkins Job name:* `My_First_Maven_Build`


----Pre-requisites

1. Jenkins server 


----Steps to create "My_First_Maven_Build" Jenkin job
 Login to Jenkins console
 Create *Jenkins job*, Fill the following details,
   - *Source Code Management:*
      - Repository: `https://github.com/abhishek-exe/my-DevOps-project`
      - Branches to build : `*/master`  
   - *Build:*
     - Root POM:`pom.xml`
     - Goals and options: `clean install package`