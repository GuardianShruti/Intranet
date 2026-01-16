# Intranet

* intrant db password: Technology148
* if i get response buffer exceeded limit error add <%Response.Buffer = False%> right after the @language tag,no spaces no tabs(in newer versions or environments it shows up as a 500 internet error)
* use the server explorer to connect to the mdb file
* ldb shows the users that are currently using the db and is a lock file

* if it says null in the usr_mstr db then you can just add usr_id and then login to the actuall intranet webpage, type the usrid and keep the password blank and you should be able to login
* same logic for creating a new password, make the password null in usr_mstr and then login to intranet and make the change.


