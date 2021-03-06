# OWASP ASVS Issue Tracker

Create a github personal access token, then set an environment variable named GITHUB_PERSONAL_ACCESS_TOKEN with the value of your access token

The value of <verification_level> will dictate which issues will be associated to their corresponding ASVS milestones. For instance, a level 3 issue will not be assigned to a milestone if <verification_level> is set to 2. All issues regardless of their level will still be created.

```
./asvs.rb
Missing or invalid arguments: asvs.rb <project_name> <verification_level> <path_to_clone_repo>
Example: asvs.rb asvs-graphql 2 /home/bobdobs/projects/
```

**Create an issue for each ASVS requirement**

![Screenshot](docs/images/asvs-issues.png)

**Filter issues by label**

![Screenshot](docs/images/asvs-label-search.png)

**Group ASVS requirements into milestones to easily track progress**

![Screenshot](docs/images/asvs-milestones.png)

**Create project boards to visualize work**

![Screenshot](docs/images/asvs-project-board.png)
