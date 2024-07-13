an entity that belong to [[Configuration]] can either be `OWNER` or `COLLABORATOR`
identified with
### props
type (`OWNER`| `COLLABORATOR`)
email
password
isActive defaults to `false`
#### optional
[[Profile]]
[[UserPemissions]]
### Actions
join ( set new password and set isActive to `true`)
login : if creds correct and isActive is `true` create new [[Authentcation]]
logout :delete the [[Authentcation]]
addCollaborator
	create new [[User]] with type `COLLABORATOR` and add it to this [[User]] [[Configuration]] `COLLABORATORS`
removeCollaborator
RestCollaborator password

#authentication #backend