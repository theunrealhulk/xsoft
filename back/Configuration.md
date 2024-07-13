an entity that allow connected user to connect to it's  `xsoft Desktop App`
identified with
### props
organization name
DbHost 
DbName 
DbUser
DbPassword
MaxUsers
ExperationDate
#### optional
Owner [[User]]
Collaborators array of [[User]]
### Actions
getOwner ( [[User]])
getCollaborators ( array of [[User]])
getConnectionString()
testConnection( true/false )

#backend