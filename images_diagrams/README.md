# rust talk



## new content
- thinking about lifetimes

## update content
- db management (cont..) ORM vs raw SQL
use prepared queries for user input

- code hardening(cont..) error handling
show impl From<PostgresErr> for FinError and .into()

- logging(cont..)
mention trace vs slog
go into structured and contextual logging (maybe `frontail`)




## coding work
- pass slog logger thru rather than copy ROOT

- maybe gen request id per request
