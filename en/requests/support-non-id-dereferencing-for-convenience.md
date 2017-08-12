#### Support non-id dereferencing for convenience

In some cases it may be inconvenient for end-users to provide IDs to
identify a resource. For example, a user may think in terms of a connection
name, but that connection may be identified by a UUID. In these cases you
may want to accept both an id or name, e.g.:

```bash
$ curl https://service.com/apps/{connection_id_or_name}
$ curl https://service.com/apps/97addcf0-c182
$ curl https://service.com/apps/chicago
```

Do not accept only names to the exclusion of IDs.
