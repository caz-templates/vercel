# <%= name %>

> <%= description %>

## Endpoints

### GET `/api`

Combine an email address.

```shell
$ curl https://<%= name %>.vercel.app/api
```

#### Parameters

- `name`: email user name, alias: `username`
- `host`: email host, default: `'zce.me'`

#### Response Type

```json
{
  "name": "...",
  "email": "..."
}
```

## Related

<!-- TODO: related projects -->

## License

[MIT](LICENSE) &copy; [<%= author %>](<%= url %>)
