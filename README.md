# Postgres-Database

### Update sequence

- Method 1

        SELECT setval('test_id_seq', 100, true);

- Method 2

        ALTER SEQUENCE payments_id_seq RESTART WITH 22;
