Entities

  1) Developer- Person who can send software packages to be scanned and checked for license and vulnerability issues. This information is
  then stored which can be later requested to be viewed.
  
  2) Manager- Person who can request to see the licenses and vulnerabilities which they will then use to compare against current policies
  as well create new policies or update existing policies.
  
 
Processes

  1) Management- Directs software packages to have licenses and vulnerabilities checked by scanner and NIST Database and then stored in the License and Vulnerabilities database.
  
  2) Scanner- Looks through a software package and extracts all the licenses within the package. 
  
  3) Licenses and Vulnerabilities Request- checks the License and Vulnerabilities database for the requested Software package and returns the results to whomever requested it.
  
  4) Policy Request- Checks for the requested software package policy documents and returns them if there is any.
  
  5) New / Update Policy Request- Allows a manager to update or add a policy document for specific software packages.
  
  
Data Flows

  1) Software Package
  
  2) License Results
  
  3) Vulnerability Results
  
  4) 
  
Databases

  1) NIST Database- National Institute of Standards and Technology database that stores all the known vulnerabilities of software     packages.
 
  2) Policy Database- Database that stores policy information about software packages.
  
  3) Licenses and Vulnerability Database- Database that stores all the licenses and vulnerabilities about software packages.
 
