# Immich

## PostgreSQL

The Immich database is hosted in a dedicated PostgreSQL [cluster](../../database/cloudnative-pg/cluster/pgvectors/pgvectors.yaml).

To facilitate administration and updates of the application as well as the database, Immich has been granted superuser privileges in the cluster.

```
ALTER USER immich WITH SUPERUSER;
```

For more information, see the Immich [documentation](https://immich.app/docs/administration/postgres-standalone).
