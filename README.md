# Security Certification Roadmap
An interactive HTML/CSS version of the Security Certification Roadmap found at https://cyber-center.org/   &&   https://pauljerimy.com/security-certification-roadmap/


If you have resources, tutorials, or a desire to accomplish the planned features below, please let me know.

Email:    pavanalapati8.24@gmail.com
          AngryBird9999@proton.me

Twitter:  https://twitter.com/Apavxn

LinkedIn: https://www.linkedin.com/in/pavan-alapati-b15459248/

- Development Environment Setup:
      Started the dev branch using React/Azure App Service starter code.
- Azure Configuration:
      Set up an Azure tenant to host the web application.
- Test Environment:
      Established a test environment at https://www.credentialgap.com linked to Azure.
- Database Setup:
      Created CosmosDB (NoSQL) for data storage.
- Data Organization:
      Created a JSON object for certifying agency data in the ../CredData folder.
- Challenges with CosmosDB Connection:
      Faced issues connecting to CosmosDB with JavaScript.
Plan to use the JSON locally until resolving the connection problem.
- Next Steps:
      Consider reviewing connection strings and authentication details for CosmosDB.
      Consult Azure documentation or seek community assistance to resolve connectivity challenges.
  
## Current Effort
- Organize and enter JSON objects for every certification
- Plan a strategy to build the chart with Javascript/React
  - I am considering building a JSON with the current chart data, then call it dynamically with Javascript to fill in a CSS Grid. This may cause problems adapting to a more dynamic system later, but it'll get me started.

## Planned Feature
- Certification database
  - Create a database with data for each domain, certifying agency, certification, exam, and keywords
  - Add data for each Certification
  - Add additional data
- Procedural chart building
  - Addition of a certification scoring system
  - Add certifications to the chart based on scores
  - Build consistent readability rules into certification placement
- Certification Filtering
  - Highlight based on selectors such as agency, security domain, and personal criteria
  - Allow searching for keywords in the database
  - Filter out certifications based on user input and redraw using procedural rules
- Chart templates
  - Add additional default layouts based on other frameworks such as CompTIA or SABSA
  - Create recommended training path templates
  - Print templates for different paper types
- Personalized charts
  - Utilize cookies to allow viewers to create their own chart
  - Allow tagging for past / current / future goals
  - Allow tagging for individual rankings
- Resource linking
  - Add linking to training resources
  - Add linking to mentions in social media
  - Add linking to mentions on blogs / other engagement
- Career recommendations
  - Templates with certification flows matched to job roles
  - Analysis of completed certifications and desired positions to recommend certification flows
  - Inclusion of non-certification recommendations such as positions, degrees, and skillsets
  - Certification recommendations based on current and desired skills
  - Skills recommendation based on current and desired certifications

## Relational Database Design
- I will adapt this to a NoSQL design
![Database design](https://pauljerimy.com/OC/DBDesign20201118.pn)    (https://cyber-center.org/wp-content/uploads/2022/02/04687-it-certification-roadmap-nov2020-24x36-onepage-1.pdf)
