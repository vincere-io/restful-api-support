# Release Notes
>**Content**
>
>Version 2.0
>

## Version 2.0
|**Release Date**|**Note**|
| -------------------------| -----------------|
| xx/xx/2018 | **Added**: <BR/> Company API: update a location info <BR/> **Fixed**: <BR/> |
| 30/01/2018               | **Added**: <BR/> Application API: count applications by job/candidate/stage <BR/>Report API: statistics for this month or last month of whole tenant or each consultant <BR/>**Fixed**: <BR/> ALL the create and update methods which allow the property registration_date and insert_timestamp now REQUIRE CLIENT CODE TO PASS A VALUE FOR THOSE PROPERTIES<BR/> Candidate API: upload photo when already exists a photo <BR/> Contact API: get and set contact's Xing url <BR/> Application API: change url /api/v2/application/{id}/stage/next/invoiced to /api/v2/application/{id}/stage/next/onboarding|
| 19/01/2018| **Added**: <BR/> Application API: create as many as 10 applications in 1 request <BR/> Files API: method to get candidate's files is updated with request parameter for original CV and document type Ids <BR/> **Fixed**: <BR/> Candidate API: the methods to get, create, update candidate are updated to add property 'facebook', 'twitter', 'xing' <BR/>|
| 06/01/2018                |**Added**: <BR/>Company search API: number of contacts in response<BR/>Contact search API: add working location in search param + returned value <BR/> Contact search API: allow search by company name <BR/> Application API: method to search by given job id and given application stage <BR/> Application API: method to search by given application stage <BR/> Application API: method to update application's substatus <BR/> Application API: search methods and get detail method now return candidate first name, last name, middle name and job title <BR/>Activity API: the search APIs return assignee information <BR/> **Fixed**: <BR/> Job API: Remove property floated_job in method to create and update job (the business is not yet supported through API) <BR/> Candidate API: Change expected values of contract_interval                           |
| 24/11/2017      | **Added**: <BR/> 1. Reference list for all activity's categories <BR/> 2. Reference list for all meeting locations <BR/> 3. Reference list for all KPI action's main entity type <BR/> 4. Reference list for KPI actions <BR/> 5. Reference list for Contact Stage <BR/> 6.Get company return the number of contacts inside company <BR/> **Fixed**: <BR/> 1. Include soft-deleted Candidate in duplicate checking. Allow to get soft-deleted candidate. Allow to update soft-deleted Candidate <BR/> 2. Get Candidate's current location and personal location only return 1 location, not an array of locations| 
| 14/11/2017     | 1. GET: Candidate's document detail result added with field "original_cv"<BR/> 2. GET: All Candidate's documents result added with field "original_cv"|
| 09/11/2017     | Beta release the API Version 2. There are no special notes.       |
