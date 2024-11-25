<table class="table" style="margin-top: 10px">
    <thead>
    <tr>
        <th>Title</th>
        <th>Last Updated</th>
        <th>Summary</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>Benchling package</td>
        <td>November 25th, 2024</td>
        <td>Detailed description of the API of the Benchling package.</td>
    </tr>
    </tbody>
</table>

# Overview

The Benchling package allows easily connect your Slingr application with Benchling.

## Configuration

You'll need the Benchling account admin to create an user for the app and give

### API Key and Tenant

Your API key is unique for your Benchling domain (sometimes also referred to as
your Benchling tenant). When making calls to the API your API key will only be
valid for your specific Benchling domain.

Get an API Key following [these steps](https://help.benchling.com/hc/en-us/articles/9714802977805-Access-the-Benchling-Developer-Platform)

## Javascript API

```js
let res = pkg.benchling.get('/');
```

## Dependencies

* HTTP Service (v1.7.0)

## About SLINGR

SLINGR is a low-code rapid application development platform that speeds up development,
with robust architecture for integrations and executing custom workflows and automation.

[More info about SLINGR](https://slingr.io)

## License

This package is licensed under the Apache License 2.0. See the `LICENSE` file for more details.
