# Data Innovation Summit - 2025 - Shift Left in Action

This repository contains all of the required software and install instructions to participate in the workshop - please ensure you have read through this repository thoroughly ahead of the session and that you have installed the required packages ahead of time!

_Note_: Most of the instructions expect macOS and a laptop powerful enough to run the below tools. Please reach out if you cannot figure out instructions for your specific platform by creating an issue.

## Tools to install

* [Docker](https://docs.docker.com/engine/install/): We will be using tools like [Snowplow Micro](https://docs.snowplow.io/docs/data-product-studio/data-quality/snowplow-micro/) so having Docker available is crucial
  - Bonus points for grabbing the latest Micro version ahead-of-time with `docker pull snowplow/snowplow-micro:latest`!
* [Snowtype](https://docs.snowplow.io/docs/data-product-studio/snowtype/): We will be using Snowtype to generate code for tracking integration
* [npm & node](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm): We will be setting up a local demo site to instrument tracking against
  - Bonus points if you install the [demo site](https://github.com/jkersu/snowplow-demo-site) ahead of time and get it running

## Useful links

* [Snowplow Console](https://console.snowplowanalytics.com): This is where we will be generating access keys for things like Snowtype and interacting with Data Products / Data Structures
* [Snowflake Console](https://app.snowflake.com): This is where we will be accessing the data being loaded in real-time
