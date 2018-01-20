# AngularJS ESLint Rules

The rules can be reviewed [here](https://github.com/LewisArdern/eslint-plugin-angularjs-security-rules), this configuration is inspired by the [ScanJS config](https://github.com/mozfreddyb/eslint-config-scanjs) by [@freddyB](https://twitter.com/freddyb). 

## Install
```
npm -g install
cp .eslintrc.json ~/.angular-eslintrc.json
```

## Running
```
cd project-to-scan/
eslint --no-eslintrc -c ~/.scanjs-eslintrc .
```