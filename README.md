# Tutorial Person Access Token Github

## Using Personal Access Tokens

- Documentation to get personal access token
- Here is the github documentation [link](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- You can click on scope “read more about Oauth scopes” to understand indepth about the various scopes you wish to give access to while creating token
- Personal Access tokens can only be generated once, hence you can copy it to either your notepad or a safe location.
- If at any point you feel your access token is compromised you can delete the token.

## Configure Github Locally
```
-$ git config --global user.name “username”
-$ git config --global user.email “email”
- to list details use the command below
-$ git config -l
- Username and email should be displayed below upon the command
- You can clone your repo
-$ git clone repo 'url here without the strings'
- enter username
- enterpassword: The password is your token
- ls
- cd to cloned directory
- git pull or push will ask for user details again

```
# Set Personal Token Parmanetly for a Repo

```
-$ git config --global credential.helper cache
- the above command cache the credentials just created to avoid consistent request for password
- You do not have to remember token or password again while pulling, commiting, pushing etc

# Changing Token and Deleting Cache Token after Change

- Go delete the token from your personal access token or edit it as you want
-$ git config --global -unset credential.helper
- The above command deletes the password and user details, hence git will require you to add the details again while pushing or pulling.

```
- Thanks
