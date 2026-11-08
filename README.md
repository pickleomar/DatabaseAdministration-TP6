# Distributed Database Lab

A SQL Server 2025 lab connecting two SQL Server instances, Oracle XE, PostgreSQL, Access, Excel and text files through linked servers.

- Combined external product and sales data with `UNION ALL` views.
- Verified partition elimination in the actual execution plan.
- Tested `INSERT`, `UPDATE`, `DELETE` and row movement between SQL Server instances.
- Validated SQL Server–Oracle distributed transactions with MSDTC, including `COMMIT` and `ROLLBACK`.
- Worked around a psqlODBC metadata bug using a compatibility view and SQL-side casts.

**Stack:** SQL Server 2025, Oracle 21c XE, PostgreSQL 18, ACE OLE DB, OraOLEDB, psqlODBC and MSDTC.
