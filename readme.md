## Tutorial Person Access Token Github

## Using Personal Access Tokens

- Documentation to get personal access token
- Here is the github documentation [link](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- You can click on scope “read more about Oauth scopes” to understand indepth about the various scopes you wish to give access to while creating token
- Personal Access tokens can only be generated once, hence you can copy it to either your notepad or a safe location.
- If at any point you feel your access token is compromised you can delete the token.

# Configure Github Locally
```
- git config --global user.name “username”
- git config --global user.email “email”
- to list details use the command below
- git config -l
- Username and email should be displayed below upon the command
- You can clone your repo
- git clone repo url
- enter username
- enterpassword: The password is your token
- or
-git config --global user.password "secret"
- ls
- cd to cloned directory
- git pull or push will ask for user details again

```
