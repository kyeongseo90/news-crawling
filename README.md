## Practice Github Actions

To practice the functionality of Github Actions, you need to write a short code.  
I've written a short code that crawls HTML of 'Naver'.

You can create Github Workflow in the './.github/workflows'.  
The current location is where the main code is located.

### What you have to do
1. fork my repo
2. clone the repo in your local machine.
3. go to Settings in your account
4. navigate to Personal Access Token (PAT) -> Token (classic)
5. generate new token -> Token (classic)
6. copy the created token
7. go to 'Settings -> Secrets and variables -> Actions' in your repo
8. create 'new repository secrets'
9. enter 'myToken' in [Name] and the copied token in [Secret] => it'll be a variable you can use in your repo!
10. create two 'new repository secrets'. One is 'GIT_NAME', the other is 'GIT_MAIL'. You need to write your name and mail in the [SECRET].
11. go to Actions in your repo
12. Run your workflow file ! you're not an expert in Github Actions! lol

## BTW What is the Github Actions?
Github Actions
A workflow is a configurable automated process that will run one or more jobs.
Workflows is the automatic process included jobs more than one. It defines by YAML file checked in repository.

It must include ..
1. Event : It can be more than one and triggers workflows
2. Job : It can be more than one and executes more than one step.
3. Step : It is included in Job
   


to be continue...
