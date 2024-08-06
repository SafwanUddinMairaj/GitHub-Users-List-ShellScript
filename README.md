## GitHub Repository Access List Script
**Description**
This script, list-users.sh, is designed to list all users who have read access to a specified GitHub repository. It uses the GitHub API to fetch and display collaborators with read permissions for a given repository.

**Usage**
To use this script, you need to have a GitHub personal access token with the necessary permissions to access the repository information. The script takes two arguments: the repository owner's username and the repository name.

**Prerequisites**
- **cURL**: This script uses `curl` to make HTTP requests to the GitHub API.
- **jq**: A lightweight and flexible command-line JSON processor, required to parse JSON responses from the GitHub API.
- **GitHub Personal Access Token**: You need a personal access token with the appropriate scopes to access repository collaborators.

### Installation

Ensure you have `curl` and `jq` installed on your system. You can install them using the following commands:
**For Debian/Ubuntu**
sudo apt-get install curl jq

**For RedHat/CentOS**
sudo yum install curl jq

## Script Usage

1. **Set your GitHub username and personal access token as environment variables**:

    ```bash
    export username=your-github-username
    export token=your-personal-accesstoken
    ```
    
2. **Grant permission according to your need using CHMOD command:
    
3. **Run the script** with the repository owner's username and repository name as arguments:

    ```bash
    ./list-users.sh <repo_owner> <repo_name>
    ```

