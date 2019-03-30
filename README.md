# Brexchat

TechForUk project to support constructive conversations about Brexit

## Publishing

The site is automatically published to Netlify from the **master** branch however due to a
[limitation](https://github.com/netlify/build-image/issues/182) you _must_ run a local Hugo
build using the the _extended version of Hugo_ and include the contents of the `resources`
directory in commits.

Use the Hugo build command from the [netlify.toml](./netlify.toml) file.

## Development

Site content can be edited in markdown files in the `content` directory. To start a server that builds draft content:

```
hugo server -wDs . -d dev --config local.toml
```

See [Hugo documentation](https://gohugo.io/documentation/) for more information.
