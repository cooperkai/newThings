# Ways for import git project using eclipse

- already have a git project, so clone a git project

```git
git clone yourproject
```

1. below operate in Eclipse
   1. Select:
      1. Project from Git (continue next step)

   2. Select Repository Source:
      1. Existing local repository

   3. Select a Git Repository:
      1. choose repositories that you need

   4. Select a Wizard to use for import projects:
      1. choose import as general project

   5. Import projects, then finish

1. convert to maven project
   1. right click the project -> choose **configure** -> click **convert to maven project**

   2. fill pom.xml form

   3. now it becoming a maven project

1. fix missing default file system
   1. right click the project -> build path -> in souce tab you can see the red missing notify -> click Apply and Close

   1. file system finish

- now you can start your journey
