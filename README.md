# serverless-oauth-scopes
[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)

A [serverless](http://www.serverless.com) plugin to set OAuth Scopes on APIGateway methods.

## Install

`npm install --save-dev git+https://github.com/rileypriddle/serverless-oauth-scopes.git`

Add the plugin to your `serverless.yml` file:

```yaml
plugins:
  - serverless-oauth-scopes
```

## Configuration
```yaml
http:
  scopes: [<array of scope string>]
```
