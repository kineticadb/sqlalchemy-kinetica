# Kinetica SQLAlchemy Changelog


## Version 7.2

### Version 7.2.3.1 - 2026-01-30

-   Updated Kinetica Python API
-   Added support for all Kinetica connection options
-   Fixed `ASOF` join with filter example


### Version 7.2.3.0 - 2026-01-14

-   Updated Kinetica Python API
-   Improved support for bind parameters
-   Fixed issue with statement objects not being able to be executed without
    compilation
-   Added support for a user-specified default schema
-   Added user guide


### Version 7.2.2.1 - 2025-08-01

-   Switched `CompileError` from `distutils` to `sqlalchemy.exc`
-   Capped supported SQLAlchemy version at `2.0.39`


### Version 7.2.2.0 - 2024-10-31

-   Added support for a fully SQLAlchemy object driven external table creation
    example
-   Fixed `TINYINT` type mapping
-   Added link to SQLAlchemy section of Kinetica documentation site
-   Fixed boolean parameter handling in example scripts
-   Removed invalid JSON array type from examples


### Version 7.2.1.1 - 2024-09-18

-   Made PIVOT & UNPIVOT processors supportive of more input table/query objects


### Version 7.2.1.0 - 2024-09-09

-   Initial release, containing many Kinetica-specific features
-   Features slated for a future release:

    - CREATE TABLE...FROM
    - CREATE TABLE...LIKE
    - UDFs
