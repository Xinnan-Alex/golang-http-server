# Http Server built with Golang

## Tools used:
- SQLC `go install github.com/sqlc-dev/sqlc/cmd/sqlc@latest`
- GOOSE `go install github.com/pressly/goose/v3/cmd/goose@latest`

Goose Commands (Local PostgreSQL)

Run UP Migration: <br>
`goose postgres postgres://<username>:<password>@localhost:5432/<db_name> up`

Run down Migration: <br>
`goose postgres postgres://<username>:<password>@localhost:5432/<db_name> down`
