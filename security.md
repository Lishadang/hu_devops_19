Web Browser : 
1. On github.com, go to the main page of the repository
2. Under your repository, click settings
3. In the left sidebar, click secrets.
4. Click new repository secret.
5. Type a name for your secret in the name input box.
6. Enter the value for your secret. 
7. Click add secret.

GitHub CLI
To add a repository secret, use the gh secret set subcommand. Replace secret-name with the name of your secret.

gh secret set secret-name

The CLI will prompt you to enter a secret value. Alternatively, you can read the value of the secret from the file. 
gh secret set secret-name < secret.txt

gh secret list to list all secrets for the repository.


