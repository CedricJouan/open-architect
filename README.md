# MoarSWEPls!

Your automated SWE fleet to get your tickets from the Backlog to Prod!


## Connecting to the GH Client

1. Be part of the org of your repo
2. Go to https://github.com/settings/tokens?type=beta and create a personnal access token for the repo
3. Run the init_connections.py script and provide the URL to your repo and the access token

## Connecting to the Trello Client

1. Connect to https://trello.com/ and log in. Navigate to your target Board. Save the Board ID.
2. Create a PowerUp for your Workspace at https://trello.com/power-ups/admin (you don't need the Iframe connector URL). Save your API Key and Secret
3. Run the init_connections.py script and provide the needed secrets
