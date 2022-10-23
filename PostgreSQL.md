# PostgreSQL

> -  Complex query, view, trigger
> -  Parallel query
> -  Authentication:....
> -  **JSON/JSONB | XML | Key:Value**
> -  **Point in time recovery (PITR)**
> -  **Transaction**
> -  **Multi-version concurrency**
> -  **Columns/Row Security**

### Achitecture

**Shared memory**:

-  Miniminze DISK I/O
-  Access vary large buffer (to hundreds GB) quickly
-  Reduction **write-ahead log (WAL)**
-  Minimize connections when many clients access at the same time
-  Data stored in **WAL file** before stored to DB
