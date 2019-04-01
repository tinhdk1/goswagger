# go_learning_project

install:
<pre>
go get -u github.com/gin-gonic/gin
go get -u github.com/jinzhu/gorm
go get -u github.com/swaggo/swag/cmd/swag
go get -u github.com/swaggo/gin-swagger
go get -u github.com/swaggo/gin-swagger/swaggerFiles
</pre>

create file "conf.json" in the root of the project for the database settings:
<pre>
{
    "Server": "",
    "Port": 1433,
    "User": "",
    "Pass": "",
    "Database": ""
}
</pre>
