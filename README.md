# Grocery Assistant

[![Build Status](https://travis-ci.com/nyu-software-engineering/fall-2019-groceries.svg?branch=master)](https://travis-ci.com/nyu-software-engineering/fall-2019-groceries)

- Grocery Assistant is an application that allows users to order groceries via Amazon through a simple text-messaging interface. In addition to placing orders as the user sees fit, it also includes the option of storing items in a cart that is internal to the app until said cart accumulates a certain subtotal. This feature is especially useful for non-Prime members, as they are able to get [free shipping](https://www.amazon.com/gp/help/customer/display.html?nodeId=527692) on orders exceeding $25 (for qualified items). However, as a user might not have $25 of items to add at once, the application-side cart allows the user to accumulate items that will be ordered on a later date, or automatically if the cart's subtotal exceeds some user's pre-defined threshold to do so.

- The frontend that the user interacts with is the standard Telegram messenger app on whatever platform they are using. The application's backend will be developed primarily in NodeJS. It will use MongoDB as its database.

- We encourage the GitHub community to contribute as they see fit, so long as they abide by the rules set forth [here](https://github.com/nyu-software-engineering/fall-2019-groceries/blob/master/CONTRIBUTING.md).

- Grocery Assistant is developed and maintained by the `groceries` team in NYU's Fall 2019 `CSCI-UA.0480-​010 Special Topics: Agile Software Development and DevOps` course.

- Please see our [REQUIREMENTS.md](https://github.com/nyu-software-engineering/fall-2019-groceries/blob/master/REQUIREMENTS.md) for project requirements and implementation specifics
