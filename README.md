# It was testing for multiple pushes on same repo into multiple accounts
# STEPS
## Step 1 => generate ssh keys with gmails of each account
## Step 2 => public and private keys will be generated
## Step 3 => create folder .ssh at c/users/username/ and then move private and public files over here
## Step 4 => create config file without having any extension
## Step 5 => add ssh keys into related github account
## Step 6 => now create repo on both accounts and generate commands

#COMMANDS
## git remote add [RESPECTIVE ORIGIN NAME] git@github-company:[GITHUB_ACCOUNT_NAME]/multiple-push.git

#Check Origin
## git remote origin -v

#Remove Origin
## git remote remove origin

#Check git ssh keys status
## ssh -T git@github-[RESPECTIVE_ORIGIN_NAME]

#push commands
## git push [RESPECTIVE_ORIGIN_NAME] main
