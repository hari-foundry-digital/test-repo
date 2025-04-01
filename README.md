# test-repo

1. Check if upstream git repo is configured
2. Run periodic git status check
3. Delete existing run
4. Trigger new run

Things to add in config file:

1. Git upstream repo link + branch
2. Current process delete script
3. Latest start instructions
4. Tempo

Considerations:

1. How does it run the github check inside each machine? Should we store the commit hash in the repositories version file?
2. Schedule check for when block > x on subnets with auto update and auto restart. Avoid writing restart scripts for ones with auto restart.
3. 
