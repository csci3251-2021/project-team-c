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
- [ ] **Write C code**
- [ ] **Get a status badge**
- [ ] **Promote your repo** 

## Code 💻


## Contributors 🧑‍💼 👩‍💼
<h2>Contributors</h2>

{% for s in site.stu %}
  <img src="{{ s.image }}">
  <h2>{{ s.name }} - {{ s.user }}</h2>
  <h2>{{ s.content | markdownify }}</h2>
{% endfor %}
 

