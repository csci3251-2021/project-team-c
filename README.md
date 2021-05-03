![YourActionName Actions Status](https://github.com/csci3251-2021/project-team-c/workflows/milestones/badge.svg)](https://github.com/csci3251-2021/project-team-c/actions)
# Welcome to the Project Team C 🙌

## Introduction 📑
```
In this project, our teammates will work on total 8 tasks. 
We will first set up our 8 tasks in Issues section, make a project board and create README.md file. 
After setting up our README.md file, our teammates will work on editing README.md file.
We will write some simple C code and finally get a status badge and promote our repository to the world!
```
- [x] **Starting Issues**
- [x] **Project Board**
- [x] **Set up README.md**
- [ ] **Show your team to the Internet**
- [ ] **Keep checking**
- [x] **Write C code**
- [ ] **Get a status badge**
- [ ] **Promote your repo** 

## Code 💻
```C
 #include <stdio.h>

 int main(void) {
     printf("Hello world \n");
 }
 ```

## Contributors 🧑‍💼 👩‍💼

{% for s in site.stu %}
  <img src="{{ s.image }}">
  <h2>{{ s.name }} - {{ s.user }}</h2>
  <h2>{{ s.content | markdownify }}</h2>
{% endfor %}
 

