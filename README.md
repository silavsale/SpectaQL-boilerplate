# Gereate Ggraphql docks with SpectaQL

1) Install 
```
npm install -g spectaql
```

2) Create a Configuration File (e.g., spectaql.yml):

```
introspection:
  url: 'http://your-graphql-endpoint/graphql'
```

Generate Documentation:

```
spectaql spectaql.yml
```