# GITFLOW ![curl -o badge.svg](https://img.shields.io/badge/GITflow%20%20-black?style=for-the-badge&logo=git)  
### Create
Create a git-flow project or convert an existing project to use git-flow :  ```git flow init```

### Features
Start a new feature : 
```git flow feature start <feature_name>```  

Finish up a feature : 
```git flow feature finish <feature_name>```  

Publish a feature : 
```git flow feature publish <feature_name>```  

Get a published feature : 
```git flow feature pull origin <feature_name>```  

Track a feature on origin : 
```git flow feature track <feature_name>```  

### Releases
Start a release : 
```git flow release start <release_name> [<base>]```  

Publish a release : 
```git flow release publish <release_name>```  

Finish up a release : 
```git flow release finish <release_name>```  

Don't forget to push your tags : 
```git push --tags```  

### Bugfixes
Start a new bugfix : 
```git flow bugfix start <bugfix_name>```  

Finish up a bugfix : 
```git flow bugfix finish <bugfix_name>```  

Publish a bugfix : 
```git flow bugfix publish <bugfix_name>```  

Get a published bugfix : 
```git flow bugfix pull origin <bugfix_name>```  

Track a bugfix on origin : 
```git flow bugfix track <bugfix_name>```  

### Hotfixes
Start a hotfix : 
```git flow hotfix start <version_name> [<base_name>]```  

Finish a hotfix : 
```git flow hotfix finish <version_name>```
