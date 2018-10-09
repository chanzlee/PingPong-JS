# Troubleshooting

1. If Karma is not available locally ($ which karma)
```
  ./node_modules/.bin/karma start
```

2. Bootstrap.css not loading (default: bootstrap.js)

```
    import 'bootstrap/dist/css/bootstrap.min.css';
```

3. Can not load "sourcemap", it is not registered! (plug-in missing)

```
    'karma-sourcemap-loader'
```

4. karma-cli global install (How to Prevent Permissions Errors)

!https://docs.npmjs.com/getting-started/fixing-npm-permissions
