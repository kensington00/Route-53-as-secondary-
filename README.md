# Route-53-as-secondary-

<h2>Update 11/4/2016: We are currently in the process of updating this script. 
It should still work in it's current form but has somewhat limited functionality. The update will use Dyn as the source 
of truth where all edits are made, it will then update AWS to match the Dyn configuration both deleting and adding records
 to insure a match to the Dyn configuration. We expect to have a first revision of the updated script available within the next week. </h2>


Python scripts with documentation on how to set up Amazon Route 53 as a secondary DNS server to Dynect's primary DNS server
