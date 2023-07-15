## Ways for importing git project using eclipse

- You already have a git project, so clone a git project

```git
git clone your project
```

1. below operate in Eclipse
   1. Select:
      1. Project from Git (continue next step)

   2. Select Repository Source:
      1. Existing local repository

   3. Select a Git Repository:
      1. choose repositories that you need

   4. Select a Wizard to use for import projects:
      1. choose import as a general project

   5. Import projects, then finish

1. convert to maven project
   1. right click the project -> choose **configure** -> click **convert to maven project**

   2. fill pom.xml form

   3. now it is becoming a maven project

1. fix missing default file system
   1. right click the project -> build path -> at the source tab you can see the red missing notify -> click Apply and Close

   1. file system finish

- now you can start your journey

## New things

[junit using tempfile](
https://www.baeldung.com/junit-5-temporary-directory)

[MyBatis stored procedure call with OUT parameters](https://stackoverflow.com/questions/9215784/java-mybatis-stored-procedure-call-with-out-parameters)

[in Junit5 you have to add a artifact engine for maven running your testwhen package](https://www.baeldung.com/maven-cant-find-junit-tests)

maven artifactId don't too long or you will not use them
舉例:要寫再父資料夾時使用models會無法使用到

[git repository 加入資料夾時，記得把該資料夾的.git刪除，就能git add 資料夾/ 了](https://www.cnblogs.com/polk6/p/16131269.html)
