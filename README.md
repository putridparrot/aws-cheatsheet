# AWS (Amazon Web Services) cheat sheet

A list of useful commands, params etc. for the AWS CLI

**General** 

| Command | Description |
|---------|-------------|
| aws --version | Get the version |


**Services**

| Command | Description |
|---------|-------------|
| aws &lt;service-name&gt; &lt;command&gt; &lt;arguments&gt; | Invoke commands on the given service |

**S3 Buckets**
| Command | Description |
|---------|-------------|
| aws s3 ls | List the S3 buckets |

**Repositories**
| Command | Description |
|---------|-------------|
| aws ecr create-repository 
   --repository-name &lt;name&gt; <br />--region &lt;region&gt; <br />--profile &lt;profile-name&gt; | Create a named ECR repository |


**Configuration**

| Command | Description |
|---------|-------------|
| aws configure | Create a configuration profile |
| aws configure list-profiles | List the stored profile names |

**Help**

| Command | Description |
|---------|-------------|
| aws help | Invoke the top level help |
| aws &lt;command&gt; help | Help for a specific command |
| aws &lt;command&gt; &lt;subcommand&gt; help | Help for a specific subcommand for a given command |
