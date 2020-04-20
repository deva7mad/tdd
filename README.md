
# Multi tenant application build with laravel
Laravel is accessible, powerful, and provides tools required for large, robust applications.

# Installation steps

### 1. Clone & Install dependency

### 2. Configuration

> Make sure to change default ``` DB_CONNECTION=mysql ``` to ``` DB_CONNECTION=tenant ```

Then add the following to ``` .env ``` file:

```
TENANCY_HOST=127.0.0.1
TENANCY_PORT=3306
TENANCY_DATABASE=DBNAME
TENANCY_USERNAME=USER
TENANCY_PASSWORD=PASS
LIMIT_UUID_LENGTH_32=true 
 ```

# Usage Example
