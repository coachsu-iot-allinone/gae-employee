# gae-employee
此專案是一個簡單的Google App Engine專案。

此專案的執行環境為node.js，使用到的套件有

- express
- @google-cloud/datastore

並提供下列三個簡單的Web API

- / : 傳回Hello from App Engine!
- /adduser/:name?age=&sen=
 - name : 員工姓名
 - age : 員工年齡
 - sen : 員工年資

請參閱教學投影片上傳到Google Cloud專案即可執行。