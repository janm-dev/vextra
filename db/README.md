# Vextra Database Interface

A crate for interfacing with a database to store Vextra data.

## `StubDb`

*`feature = "stub"`*

A stub implementation of a database that doesn't store any data, logging it with the `log` crate instead.

## `TimescaleDb`

*`feature = "timescale"`*

An implementation of the database interface using the PostgreSQL-based TimescaleDB.
