# Facebook Server-side API (for Web)

The server-side API (for web) allows advertisers to send web events from their servers directly to Facebook. Server-side events are linked to a pixel and are processed like browser pixel events. This means that server-side events are used in measurement, reporting, and optimization in the same way as browser pixel events. [Learn More](https://developers.facebook.com/docs/marketing-api/server-side-api)

Create the Server-side API (for Web) client SDK using Swagger codegen and quickly onboard to send the actions people take on your website when they interact with your page, such as Lead, ViewContent, AddToCart, InitiateCheckout and Purchase events.
 
# Requirements

* Java, version 7 or higher
* Swagger Codegen [Learn More](https://swagger.io/docs/open-source-tools/swagger-codegen/)

# Get started

Clone this repo with the following command:

`$ git clone https://github.com/facebookincubator/Facebook-Server-Side-API-Swagger.git`

* Generating Code using swagger-codegen 

swagger-codegen generate -i server-side-api.yaml -l <language>

Example:

swagger-codegen generate -i server-side-api.yaml -l csharp

* Else, you could use latest swagger codegen jar:

java -jar swagger-codegen-cli-2.2.1.jar generate -i server-side-api.yaml  -l <language>

Example:

java -jar swagger-codegen-cli-2.2.1.jar generate -i server-side-api.yaml -l csharp

In the above code, we pass two arguments : - i and -l. -i is used to specify the path of Server-side API’s specification. -l is used to specify the language you want to generate the code for Server-side API’s specification

The Codegen creates a README file with all the information for running and building the API. Each language creates a different README, so please go through it to learn about how to build your Swagger defined API.

# Contributing

See the CONTRIBUTING file for how to help out

# License

Official Facebook Pixel is GPLv2-licensed
