# Dragonfly

## Database Index

1. `null`
2. [`authelia`](../../security/authelia/)
3. [`immich`](../../media/immich/)

## Arguments

### Undeclared Keys

Undeclared keys is enabled in the cluster with `--default_lua_flags=allow-undeclared-keys` argument. This is generally not recommended and not optimal. Accessing undeclared keys from scripts is disabled by default in Dragonfly for this reason. Immich does however use Redis via BullMQ to manage job queues and must therefore be allowed. For more information, see [Dragonfly](https://www.dragonflydb.io/docs/integrations/bullmq#using-undeclared-keys-not-optimized) and [Immich](https://immich.app/docs/developer/architecture#redis) documentation.
