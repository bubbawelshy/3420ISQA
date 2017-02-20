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

  1) Software Package- Software files.
  
  2) License Results- List of Licenses within a specific Software Package.
  
  3) Vulnerability Results- List of Vulnerabilities within a specific Software Package.
  
  4) L&V Results- List of all Licenses and vulnerabilities for a specific Software Package.
  
  5) L&V Request- The demand for all the Licenses and Vulnerabilities for a specific Software Package.
  
  6) Policy Request- The demand to see the policy documents the pertain to a specific Software Package.
  
  7) Policy Response- The policy documents that pertain to a specific Software Package.
  
  8) New / Update Request- The demand to either add or update a policy in regards to a specific Software Package.
  
  9) New / Update Response- The confirmation of a request to update or add a policy in regards to a specific Software Package.
  
Databases

  1) NIST Database- National Institute of Standards and Technology database that stores all the known vulnerabilities of software     packages.
 
  2) Policy Database- Database that stores policy information about software packages.
  
  3) Licenses and Vulnerability Database- Database that stores all the licenses and vulnerabilities about software packages.
 
