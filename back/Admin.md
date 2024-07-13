an entity that has global control over the app
identified with
### props
email
password
### Actions
register --create new admin
login  --if creds correct create new [[Authentcation]]

add Configuration:
	1- create new [[Configuration]]
	2- create new [[User]] by default isActive will be false (no password is set)
	3- make the created [[User]] and owner of the [[Configuration]]

	PS inActive user can only join by entering emil and organization name of Configuration
	while joining will be 


logout  :delete the [[Authentcation]]
create [[Configuration]]
Rest User : set `isActive` to false and delete password
add [[Permission]] --create new permission
add [[Profile]] --create new profile
add [[UserPemissions]] --override existing user permission
set User Profile

#authentication #backend