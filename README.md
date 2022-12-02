# Config database

```
sudo apt-get install sqlite3 db.sqlite
sqlite3 db.sqlite

> create table categories (id string, name string, description string);

> create table courses (id string, name string, description string, category_id string);
```

# Run

```
go mod tidy
go run cmd/server/server.go
```