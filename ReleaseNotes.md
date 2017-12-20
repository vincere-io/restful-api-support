# Release Notes
>**Content**
>
>Version 2.0
>

## Version 2.0
|**Release Date**|**Note**|
| -------------------------| -----------------|
|xx/12/2017                |**Added**: <BR/> Contact search API: allow search by company name <BR/> Application API: method to search by given job id and given application stage <BR/> Application API: method to search by given application stage <BR/> Application API: method to update application's substatus <BR/> Activity API: the search APIs return assignee information <BR/> **Fixed**: <BR/> Remove property floated_job in method to create and update job (the business is not yet supported through API)                          |
|24/11/2017      | **Added**: <BR/> 1. Reference list for all activity's categories <BR/> 2. Reference list for all meeting locations <BR/> 3. Reference list for all KPI action's main entity type <BR/> 4. Reference list for KPI actions <BR/> 5. Reference list for Contact Stage <BR/> 6.Get company return the number of contacts inside company <BR/> **Fixed**: <BR/> 1. Include soft-deleted Candidate in duplicate checking. Allow to get soft-deleted candidate. Allow to update soft-deleted Candidate <BR/> 2. Get Candidate's current location and personal location only return 1 location, not an array of locations| 
| 14/11/2017     | 1. GET: Candidate's document detail result added with field "original_cv"<BR/> 2. GET: All Candidate's documents result added with field "original_cv"|
| 09/11/2017     | Beta release the API Version 2. There are no special notes.       |
