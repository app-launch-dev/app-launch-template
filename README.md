#AppLaunch - Getting Started
Follow the instructions below to finish configuring your new repository for automatic updates and deployment.

#Generating a token
1. Settings - Developer Settings - Personal Access Tokens - Fine-grained tokens
2. Token Name: Applaunch Token
3. Choose all or only select repositories depending on your preference
4. Choose an expiration of your choosing (recommend never for automatic updates)
4. Set the following permissions on the token.

Contents
Access: Read and write
Pull Requests: Read and write
Workflows: Read and write

#Adding Secrets
In your repository, go to Settings - Secrets and variables - Actions
Create the following Repository secrets:
1. APPLAUNCH_TOKEN: [PASTE YOUR TOKEN]
2. APPLAUNCH_FTPS_HOST: [Your FTPS Hostname]
3. APPLAUNCH_FTPS_USER: [Your FTPS Username]
4. APPLAUNCH_FTPS_PASS [Your FTPS Password]







