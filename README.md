# Your Project Name 

## Checklist
- [ ] Check your mail and accept Github Repository invitation for edit access.
- [ ] Clone your project github repository 
- [ ] Import Project in Eclipse


#### Step 1: Clone Repository

```code
git clone https://github.com/csy-fresher-batch-2019/{yourproject-reponame}/.git
```

#### Step 2: Import Maven Project
```
Eclipse => File -> Import -> Existing Maven Projects -> Select Project Folder
```
Note: It will take few minutes ~1-3 minutes to import maven projects and download project dependencies.

#### Step 3: Build the Project
```code
mvn install
```
(or)
```
Run As -> Maven Install 
Note: Test whether build is successful.

#### Step 3.1 JRE Error
* Eclipse => Window Preferences => Java => Installed JRE => Change JRE Path to JDK path

#### Step 4: Update pom.xml and commit the files and push to github

* Update groupId, artificatId, name based on your project.
```
 <groupId>com.naresh</groupId>
  <artifactId>myapp-core-naresh</artifactId>
  <version>1.0-SNAPSHOT</version>
  <name>myapp-core</name>
  ```
  to
  ```
 <groupId>com.prabhu</groupId>
  <artifactId>bankapp-core-naresh</artifactId>
  <version>1.0-SNAPSHOT</version>
  <name>bankapp-core</name>
  ```
  
