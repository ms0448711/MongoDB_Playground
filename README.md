# MongoDB_Playground
A playground for manipulate operations in MongoDB

# Install MongoDB

I tried to install MongoDB with WSL, but I encountered a problem that cannot be resolved. ```*aborting after fassert() failure``` message appeared and seemed nobody has resolved it yet. So I changed my enviroment into Windows instead.

[Install MongoDB](https://www.mongodb.com/docs/manual/installation/)

## Windows
### Installation
[Install MongoDB using msiexec.exe](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows-unattended/).
I failed to install at [WSL](https://docs.microsoft.com/zh-tw/windows/wsl/tutorials/wsl-database#install-mongodb).
### Mongodb Compass
A gui program that can visualize your databases and collections. (It would ask you if you want to install it when using ```msiexec``` to install mongodb. If you skip that installation step, you can still find it at [here](https://www.mongodb.com/docs/compass/master/))
### MongoDB Shell
> The MongoDB Shell, mongosh, is a fully functional JavaScript and Node.js 16.x REPL environment for interacting with MongoDB deployments. You can use the MongoDB Shell to test queries and operations directly with your database.

# To Familiar with MongoDB

## Level of Structure
In MySQL, the structures are **database、table、row of data**, whereas in MongoDB, the structures are **database、collection、document**.

[什麼是SQL？什麼是NOSQL? 用簡單範例看一下他們的差異](https://www.codegym.tech/blog/sql-vs-nosql)

[閃開！讓專業的來：SQL 與 NoSQL](https://ithelp.ithome.com.tw/articles/10187443)


# How to use Mongosh 
[mongosh Usage](https://www.mongodb.com/docs/mongodb-shell/run-commands/)

[[MongoDB] 學習筆記(一) - 安裝、基礎CRUD、外部輸入資料、Data Type](https://medium.com/@mingjiehsu/mongodb-%E5%AD%B8%E7%BF%92%E7%AD%86%E8%A8%98-%E4%B8%80-%E5%AE%89%E8%A3%9D-%E5%9F%BA%E7%A4%8Ecrud-%E5%A4%96%E9%83%A8%E8%BC%B8%E5%85%A5%E8%B3%87%E6%96%99-data-type-1169000cf02c)

## Activate Service (Put your server online)
```
net start MongoDB   #To start the server 
net stop MongoDB    #To close the server 
```

## Connect to Deployment(Mongosh)
tl;dr
Type `mongosh` or `mongosh "mongodb://localhost:27017"` or `mongosh --port 27017` to connect.
Type `exit` or `quit` to disconnect.

[Authentication, Replica, tls, etc.](https://www.mongodb.com/docs/mongodb-shell/connect/#std-label-mdb-shell-connect)

## 

