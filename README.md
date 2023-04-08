# Encrypt Zip to Ozip and Upload

This repository contains a GitHub Actions workflow that can be used to encrypt a zip file using the AES-256-CBC cipher and upload the encrypted file to the Bash Upload service. This workflow can be useful for securely sharing sensitive files with others.

# Usage

To use this workflow, you need to have a GitHub account and a repository that you want to use to store the encrypted file. You can then follow these steps:

1. Fork this repository to your own GitHub account.

2. Open the `encryption.yml file in the ` .github/workflows directory and replace 'https://url-to-your-zip-file with the URL of the zip file you want to encrypt and replace encryption_key with the password you want to use for encryption.

3. Save the changes to the encryption.yml file.

4. Navigate to the "Actions" tab in your forked repository and click the "Enable" button for GitHub Actions. 5. Wait for the workflow to complete. The encrypted file will be uploaded to the

Bash Upload service and the encrypted file URL will be displayed in the "Logs" tab of the workflow.

6. Copy the encrypted file URL and share it with others.

Note that the encrypted file will only be available for download from the Bash Upload service for 3 days and can only be downloaded once.
