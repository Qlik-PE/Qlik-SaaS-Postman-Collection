# Qlik-SaaS-Postman-Collection

REST Requests to be used with Qlik Cloud SaaS

## License Summary

This project is made available under a modified MIT license. See the LICENSE file.

## Purpose

The purpose of this REST API call set is make it easier to understand how to call [Qlik Cloud API](https://qlik.dev/apis#manage) using [Postman](https://www.postman.com/) .
At that site there are examples to call using [curl](https://curl.se/), [Node.Js](https://nodejs.org/), and [Qlik Cli](https://qlik.dev/libraries-and-tools/qlik-cli). If you are more familiar with [Postman](https://www.postman.com/) you can use and contribute with this project.

## Installation

1. Download [Qlik SaaS.json](src/Qlik%20SaaS.json)
2. Open Postman and select a workspace
3. Click Import, click File and upload Qlik SaaS.json
4. Click the "Environments" icon to setup an Environment
5. Click New and enter an Environment name to hold your variables or reuse one of your own
6. Create a variable called TENANT to store your tenant address (with the api). Example https://acme.us.qlikcloud.com/api/v1
7. Create a variable called TOKEN to store your key that you can generate using [this tutorial](https://qlik.dev/tutorials/generate-your-first-api-key) 

You´re set! you can start using the REST Calls.

## Versions and Roadmap

* September 2022 - Initial version

Feel free to suggest any improvements. We will evaluate and implement when your suggestion was accepted. Please use the [Feature Request](hhttps://github.com/Qlik-PE/Qlik-SaaS-Postman-Collection/issues/new?assignees=&labels=&template=feature_request.md&title=)