# Toolbox


## CLI Arguments

Ruby Refresh - Used when you are coding in ruby. Goes and looks 
1. Runs command to fetch a list of references of branch policies, wikis,
* Previous started repos. 

```
Example Ruby: 
ruby lib/rexodus.rb refresh --azure-devops-org 1es-cat <PAT>--azure-devops-token 1234 <ORG-NAME/rogerperez1>--github-org rogerperez1 --github-token 1234 --github-enterprise https://ghe-lighthouse.github.com
Ruby: 
ruby lib/rexodus.rb refresh --azure-devops-org <OWN-ORG> --azure-devops-token <ADD_PAT> --github-org 1escat.rb --github-token 1234 --github-enterprise https://ghe-lighthouse.westus2.cloudapp.azure.com/
```

### Start Ruby
* No repo hsa been created within github enterprise.
* No Issues or listing off any migration.
```
Example Ruby: 
ruby lib/rexodus.rb start --azure-devops-org 1es-cat <PAT>--azure-devops-token 1234 <ORG-NAME/rogerperez1>--github-org rogerperez1 --github-token 1234 --github-enterprise https://ghe-lighthouse.github.com
Ruby: 
ruby lib/rexodus.rb start --azure-devops-org <OWN-ORG> --azure-devops-token <ADD_PAT> --github-org 1escat.rb --github-token 1234 --github-enterprise https://ghe-lighthouse.westus2.cloudapp.azure.com/
```

Creates 5 issues
1. repos, extracts all references
2. projects, extracts all references
3. wikis, extracts all references
4. builds, extracts all references
5. branch policies, extracts all references
```
C#:
refresh --azure-devops-org 1es-cat --github-org 1escat --github-enterprise https://ghe-lighthouse.westus2.cloudapp.azure.com/ --azure-devops-token token --github-token token
```
