# rust talk



## new content
- thinking about lifetimes

## update content
- db management (cont..) ORM vs raw SQL
use prepared queries for user input

- db management (cont..)
update postgres mapper to use crate.io
bold the methods from_portgres_row, sql_fields, sql_table

- code hardening(cont..) error handling
show impl Display, impl StdError
show impl From<PostgresErr> for FinError and .into()

- auth(cont..)
expand on paseto

- logging(cont..)
mention trace vs slog
go into structured and contextual logging (maybe `frontail`)

## coding work
- pass slog logger thru rather than copy ROOT

- maybe gen request id per request
