## purpose

provide login and joining fields for Admin and User through [[AuthService]]

### props
email
password
organization
login_as : `enum : Admin|User`
### Actions
connect_user : `call api to authenticate user` via [[AuthService]]
join_user : `call api to join user (set password and and )` via [[AuthService]]
connect_admin : `call api to authenticate admin` via [[AuthService]]

#front 