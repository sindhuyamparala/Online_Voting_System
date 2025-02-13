# Online Voting System

This is an Online Voting System implemented in C, which manages candidate registration, voter authentication, and vote counting. 
It includes functions to verify student voter credentials using ID extraction, authenticate the admin, and handle banned voter lists. 
The system allows election setup, stores votes, and determines the winner while handling illegal votes. 
Election details and results are saved in files for future reference. 
This Online Voting System uses File System Management to store and manage election data persistently. 
It utilizes files for: Candidate Information – Each candidate has a separate file (candidateX.txt) to store their vote count. 
Election Records – Election details (year, branch, total voters, and candidates) are saved in ElectionInfo.txt. Banned Voters – Banned.txt is used to track and restrict certain voters. 
Vote Management – It reads and updates votes from candidate files and student vote records to maintain integrity. This ensures that election data remains available even after program termination.
