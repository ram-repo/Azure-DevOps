## Azure Agent pool 
* Self-hosted
* Virtualmachine scale set

## Authenticate with a personal access token (PAT)
* Sign in with the user account you plan to use in your Azure DevOps organization (https://dev.azure.com/{your_organization}).
* From your home page, open your user settings, and then select Personal access tokens.
![preview](./images/pat1.png)

### Create a personal access token
![preview](./images/pat2.png)
![preview](./images/pat3.png)

### Token copy ```4gmqpksh2mj3z3o72ytqilgejbhxnqn5nmtcoz4ion453ajmu4oq```

* For the scope select Agent Pools (read, manage) and make sure all the other boxes are cleared. If it's a deployment group agent, for the scope select Deployment group (read, manage) and make sure all the other boxes are cleared.

* Select Show all scopes at the bottom of the Create a new personal access token window window to see the complete list of scopes.

* Copy the token. You'll use this token when you configure the agent

## Choose Azure DevOps, Organization settings
![preview](./images/AD3.png)

## Choose Agent pools
![preview](./images/AD4.png)
![preview](./images/AD5.png)


## Select Add Agent 
![preview](./images/AD6.png)

## Follow the instructions on the page
![preview](./images/AD7.png)

## Download and configure the agent
![preview](./images/AD8.png)

## Run the agent ``` ./run.sh ```


4gmqpksh2mj3z3o72ytqilgejbhxnqn5nmtcoz4ion453ajmu4oq





