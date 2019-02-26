# Azure DevOps Project Management Data Replication

Azure DevOps Data Fetch Using Pentaho ETL &amp; Rest APIs via Personal Access Token (PAT)

Our Approach of Data Fetch From Azure DevOps Project Management

  1. Generate Personal Access Token (PAT) to access Azure DevOps via Rest APIs.
  2. Build & Design ETL Jobs using Pentaho for different modules under Azure DevOps.
  3. Use Rest API URLs in various ETL steps that hit the URL and get the output result in form of JSON.
  4. Parse the JSON response and send it to your Data Base destination (MySQL/SQLServer/Mongo... etc).
  5. Use reporting tool to genarete Reports and Dashboards, typically we use Pentaho Community BI Suit for this purpose.
  6. Set the data load frequency as per your choice, it may be on demand or perodically basis.

Note : Pentaho ETL steps use central property file which will be common over all steps of ETL.
