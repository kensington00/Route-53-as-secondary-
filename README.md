# Route-53-as-secondary-

<h2>Update 11/4/2016: </h2>We are currently in the process of updating this script. 
It should still work in it's current form but has somewhat limited functionality. The update will use Dyn as the source 
of truth where all edits are made, it will then update AWS to match the Dyn configuration both deleting and adding records
 to insure a match to the Dyn configuration. We expect to have a first revision of the updated script available within the next week.
 
<h2>Update 11/14/2016:</h2> 
Created a branch 2016_update_branch which has the working additions in a separate file dyn_to_r53.py and a simple test on the usage. This week we will be working to merge these changes into the existing script functionality and adding the settings to the existing settings file. The code will be commented and cleaned up to get ready for a merge. 


Python scripts with documentation on how to set up Amazon Route 53 as a secondary DNS server to Dynect's primary DNS server
