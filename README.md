# LocalLibrary

## To start the app in development
From root flolder execute this
```bash
# Using windows

# For command prompt
npm run serverstart # same as SET DEBUG="locallibrary:*" & npm run devstart 

#For powershell
$env:DEBUG = "locallibrary:*"; # You have to first set the "DEBUG" env variable
npm devstart # Then execute this 
# Notice that we could't do this 'npm run serverstart' like in command prompt
# As this command '$env:DEBUG="locallibrary:*"; npm run devstart' when it runs inside 'npm run serverstart' script will produce errors !, because god knows why !!!

# Using macOS/linux 
DEBUG=locallibrary* npm devstart
```
