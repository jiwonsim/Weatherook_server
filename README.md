# Weatherook(Server)
__날씨에 패션을 입히다__

SNS를 활용한 날씨 기반 코디 추천 서비스 

<p align="center">
<img src="https://user-images.githubusercontent.com/28748103/54484065-f3e02b80-48a1-11e9-9ad3-f47bbabce3f1.png" width="200px"></img>
</p>


## Using

* Node.js
* MySQL
* AWS infra


## Common Setting
```bash
git clone https://github.com/Weatherook/server
cd server
npm start
```

* config/mysql.js 파일 작성

```bash
var mysql = require('promise-mysql')

const dbConfig = {
    host : '',
    port : 3306,
    user : '',
    password : '',
    database : '',
    connectionLimit : 20
 };

module.exports = mysql.createPool(dbConfig);
```
