# Postgres-Database

### Update sequence

- Method 1

        SELECT setval('test_id_seq', 100, true);

- Method 2

        ALTER SEQUENCE test_id_seq RESTART WITH 100;
