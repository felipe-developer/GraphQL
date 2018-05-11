### Observations ###

* http://localhost:3000/user?query={user(id:2){id,name,age,knowledge{language,frameworks}}}
* http://localhost:3000/user?query={user(id:2){id,name,age,knowledge{language,frameworks}}}
* http://localhost:3000/user?query={user(id:3){id,name,age,knowledge{language}}}
* http://localhost:3000/user?query={user(id:1){id,knowledge{language,frameworks}}}
* http://localhost:3000/user?query={user(id:1){id,name,age}}
* http://localhost:3000/user?query={user(id:2){id,name,age,knowledge{}}}
* http://localhost:3000/user?query=%7Busers%7Bid,name,age,knowledge%7Blanguage,frameworks%7D%7D%7D