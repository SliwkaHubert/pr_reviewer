To generate GitHub tokens:

Log in to your GitHub account and navigate to settings.
Go to developer settings → Personal Access Tokens.
Click Generate New Token and select the classic version.
Provide a name for the token and enable the following permissions:
    read:org
    read:repo_hook
    repo
Click Generate to create the token.
Copy and store the token securely, as it will be used for authentication in API requests.

----

Login to Notion's integration page - https://www.notion.so/profile/integrations

Create a new integration and complete the form. Keep “type” to Internal and add it to your workspace. 


Save the integration and copy the integration link (the UUID at the end of the URL is the Universally Unique Identifier that you need to note down and use as the Notion Page ID) - https://www.notion.so/profile/integrations/internal/UUID

After the integration is created, click on it, and under configuration, copy the Internal Integration Secret, which will be your Notion API key.