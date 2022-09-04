The break game imported several directories.
Which includes the establishment of the connection, instead of creating a connection
in create.tsx, useConneciton() was imported.
It has also a debug mode (debugMode) which the helloworld program doesn't have.
And the function createTransaction also has a parameter retryEnabled which allows the user to retry for failed transaction.