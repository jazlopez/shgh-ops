# shgh-ops
Wrapper around gh's API. Examples &amp; Considerations. Free to use as long you credit the author. 2022


### REQUIRED ENVIRONMENT VARIABLES

> GITHUB_TOKEN
> 
> GITHUB_REPO
> 
### WRAPPER

Project uses GH api as defined in official documentation


> Makes an authenticated HTTP request to the GitHub API and prints the response.
> 
>The endpoint argument should either be a path of a GitHub API v3 endpoint, or
"graphql" to access the GitHub API v4.
>
> Placeholder values "{owner}", "{repo}", and "{branch}" in the endpoint
argument will get replaced with values from the repository of the current
directory or the repository specified in the GH_REPO environment variable.
Note that in some shells, for example PowerShell, you may need to enclose
any value that contains "{...}" in quotes to prevent the shell from
applying special meaning to curly braces.

### SIGNING IN REQUESTS
