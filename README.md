### Observations ###

* node index.js
* http://localhost:3000/user?query={user(id:2){id,name,age,knowledge{language,frameworks}}}
* http://localhost:3000/user?query={user(id:2){id,name,age,knowledge{language,frameworks}}}
* http://localhost:3000/user?query={user(id:3){id,name,age,knowledge{language}}}
* http://localhost:3000/user?query={user(id:1){id,knowledge{language,frameworks}}}
* http://localhost:3000/user?query={user(id:1){id,name,age}}
* http://localhost:3000/user?query={user(id:2){id,name,age,knowledge{}}}
* http://localhost:3000/user?query={users{id,name,age,knowledge{language,frameworks}}}