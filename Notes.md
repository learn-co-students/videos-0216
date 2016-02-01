- Linux
  - highlights
    - Command options arguments
       - eg. ls -l /notes
    - man ls
      - give me the manual
  - Creating and Removing
    - touch 
      - creates a new file, or modifies it
      - File creation is case sensitive
    - rm 
      - remove a file
    - mkdir
      - takes multiple arguments
    - rmrf
      - removes a directory
      - also takes multiple arguments
  - Navigating our system
    - pwd 
      - see current directory
    - cd 
      - changing directory
      - .. move out one directory
    - less
      - shows the contents of a file
    - ls 
      - lists
      - l - long format
          -Root - User name of the file's owner
          - Name of the group that owns the file
          - Size of the file in bites
          - Date and time of the file's last modification 
          - Name of the file
  - Modifying our files
    - mv
      - moves files
    - cp 
      -copy files
      - cp -r
        - copy contents of directory
- Git
  - Purpose of this thing:
    - Track changes in files, track changes over time
    - Tracking changes across locations, and distributed workflow
  - Initializing
    - git init
  - Asking git some questions
    - Git status
       - shows files changed
    - Git diff
      - more detailed, shows contents
  - Change workflow
    - Git add 
      - Adds to staging
      - Staging
        - Staging are the files that you want to be considered as part of a commit
    - Commit
      - Placing on the timestamp, clocking in. That this is an official change.
    Unstaged ---- >
                    Staging --git add---->
                                          Commit --git commit---->
    my computer ---------------------------------------------------|                                                                                             the cloud ---------------|

    - Moving to the cloud
    my computer---|
                  |the cloud (my repository)------------------|
                  git push origin master
      - git push origin master
        - origin -> remote address 
        - master -> local branch that I am pushing up to the cloud
        - git remote -v -> see the local branches that I am hooked up to 
      - retrieving changes made remotely
        




