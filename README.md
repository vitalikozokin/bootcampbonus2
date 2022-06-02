# bootcampbonus2

#-------ON THE SERVER--------------- 

# 1. install IIS role from add roles and feature on the windows server

# 2. create new folder for the web files

# 3. give read and write share permmision to the folder for your user

# 4. create new site on IIS manager on the configurations windows
     selcet the folder that opened before for physical path and set port 5100 on port section
     and click ok
     
# 5. click on right on mouse on the web site that created select edit permissions 

# 6. give read permission to IIS_USERS group

#---------ON THE LOCAL MACHINE---------------

# 1. open visual studio 

# 2. clone from repository the project

# 3. build the project

# 4. click right button on project name

# 5. map on your pc the shared folder from the server

# 6. select publish

# 7. click on add publish profile

# 8. select folder

#9. on folder location enter full path of shared folder on the server

# 10. click finish.

# 11. click on publish.

# 12. restart the web site from IIS manager

# 13. enter to browser on the server to http://localhost:5100

