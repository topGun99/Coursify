# Coursify
## Getting Started

Clone or download zip file of the project into your local machine.

### Dependencies

```
node v12.14.1
express v4.16.1
nodemon v2.0.2
ejs v2.6.1
update-json-file v1.1.1
shortid v2.2.15
morgan v1.9.1
lodash v4.17.15
```  

### Installing

Install node js from [here](https://nodejs.org/en/download/)  
Check by typing this in command prompt.
```
node --version
```

If node is installed, directly copy the package.json file into your project directory and run
```
npm install
```


---

## Features
- Registration and Login
- Course Add/Drop
- Explore course catalog
- Course details
- Publish new courses  

#### Database Files -data/
- Users : *Student details database*
- Professor : *Professor details database*
- Courses : *Course details database*  

#### Class files
- FileDataOperationsClass : *Supports all file related operations*
- UpdateFileClass : *Supports functions of writing to course database* 

#### There are 4 main routes:
- **Index:**
  * ***/*** : Home page 
- **Users:**
  * ***/users/login*** : Login Page
  * ***/users/register*** : Register Page 
- **Dashboard:**
  * ***/dashboard/student/*** : Student dashboard consisting of registered courses.
  * ***/dashboard/professor/*** : Professor dashboard consisting of published  courses.
  * ***/dashboard/professor/add/*** : Creating and publishing a course.
  * ***/dashboard/professor/edit/*** : Editing a previously published course 
- **ExploreCourses:**
  * ***/dashboard/explore/*** : Explore all courses available in the catalog.
  * ***/dashboard/explore/detail*** : Gets details of the particular course.
  * ***/dashboard/explore/filter*** : Displays the filtered list of courses w.r.t domain.
