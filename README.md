# ca-with-golang

### migrate
```
// godotenv.Load()の前にenvの判定があるのでGO_ENVは必須
GO_ENV=dev go run migrate/migrate.go
```

### run
```
GO_ENV=dev go run main.go
```