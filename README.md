# How to install the project

git clone the project 

In the project root folder :
- `npm install `
- `npm run watch`
- Happy coding !

# Contributions
Adil Bidelhadjela

# Project URLs
Jaune : jaune.gca.local
Mailcatcher : mail.gca.local

# Available commands
- `make up` : Start the stack
- `make down` : Stop the stack
- `make dependencies` : Install dependencies
- `make install` : Install the stack
- `make nuke` : Remove the whole stack. *Be careful, it removes volumes, .env file and all unsaved modifications !*

# Mailhog
Mailhog is available by default on the stack to catch emails. To access it just go to the address defined in .env `NGINX_MAILHOG_HOST` variable (default : mail.gca.local).