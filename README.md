# demo-gomysql

go 语言使用 mysql 示例，这是默认分支，使用xorm操作数据库，在gorm分支有使用gorm的示例。

## go 1.12 以及以上

```cmd
git clone https://github.com/JabinGP/demo-gomysql.git
cd demo-gomysql
go run main.go
```

## go 1.12 以下

### 获取代码

```cmd
git clone https://github.com/JabinGP/demo-gomysql.git
cd demo-gomysql
```

### 引入 mysql 驱动

```cmd
go get -u github.com/go-sql-driver/mysql
```

### 引入 xorm 驱动

```cmd
go get -u xorm.io/xorm
go get -u xorm.io/core
```

### 运行

```cmd
go run main.go
```
