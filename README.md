# Category Section

Create a [Gatsby](http://gatsbyjs.com/) blog powered by [Contentful](https://www.contentful.com).

This guide will take you through the following
1. [What is a category](https://www.google.com)
2. [How to access your categories](https://www.google.com)
3. [How to add a category](https://www.google.com)
4. [How to edit or duplicate a category](https://www.google.com)
5. [How to delete a category](https://www.google.com)

![Screenshot 2022-03-22 at 2 04 43 PM](https://user-images.githubusercontent.com/101874906/159445112-b35d2abe-3c41-4a85-aaa7-c58333a58fd7.png)


# What is a category
A category is the broadest way to classify all the inventory that you have uploaded to your Slate store. To learn more on how to upload inventory read this [guide](https://www.google.com).
The simplest way to understand how a category can help you filter your inventory is by using the following examples:
|Example|Inventory Upload|Categories|What can be in this category|
|:-----:|:--------------:|:--------:|:--------------------------:|
|Resteraunt|Chicken corn soup|Starters|Chicken corn soup|
|          |Chicken tikka pizza|Mains|Chicken tikka pizza|
|          |Ice cream|Desserts|Ice cream|
|          |Fresh apple juice|Drinks|Coca-cola; Fresh apple juice|
|          |Coca-cola|              |                          |
|Fashion|Pakistan cricket cap|Caps|Pakistan cricket cap|
|       |Karachi Kings shirt|Shirts|Karachi Kings shirt; Lahore Qalandars shirt; Peshawar Zalmi shirt|
|       |Lahore Qalanders shirt|Others|Liverpool football club socks|
|       |Peshawar Zalmi shirt|      |      |
|       |Liverpool football club socks|    | 

if you are a resteraunt owner(or a home-based food business), it is very likely that you can split whatever you are selling into categories that you are 
## Features

- Simple content model and structure. Easy to adjust to your needs.
- Use the [synchronization feature](https://www.contentful.com/developers/docs/references/content-delivery-api/#/reference/synchronization) of our [Delivery API](https://www.contentful.com/developers/docs/references/content-delivery-api/).
- Responsive/adaptive images via [gatsby-plugin-image](https://www.gatsbyjs.org/packages/gatsby-plugin-image/) and our [Images API](https://www.contentful.com/developers/docs/references/content-delivery-api/#/reference/synchronization/initial-synchronization-of-entries-of-a-specific-content-type).

## Getting started

See our [official Contentful getting started guide](https://www.contentful.com/developers/docs/tutorials/general/get-started/).

### Get the source code and install dependencies.

```
$ git clone https://github.com/contentful/starter-gatsby-blog.git
$ npm install
```

Or use the [Gatsby CLI](https://www.npmjs.com/package/gatsby-cli).

```
$ gatsby new contentful-starter-blog https://github.com/contentful/starter-gatsby-blog/
```

### Set up of the needed content model and create a configuration file

This project comes with a Contentful setup command `npm run setup`.

This command will ask you for a space ID, and access tokens for the Contentful Management and Delivery API and then import the needed content model into the space you define and write a config file (`./.contentful.json`).

`npm run setup` automates that for you but if you want to do it yourself rename `.contentful.json.sample` to `.contentful.json` and add your configuration in this file.

## Crucial Commands

### `npm run dev`

Run the project locally with live reload in development mode.

### `npm run build`

Run a production build into `./public`. The result is ready to be put on any static hosting you prefer.

### `npm run serve`

Spin up a production-ready server with your blog. Don't forget to build your page beforehand.

## Deployment

See the [official Contentful getting started guide](https://www.contentful.com/developers/docs/tutorials/general/get-started/).

## Contribution

Feel free to open pull requests to fix bugs. If you want to add features, please have a look at the [original version](https://github.com/contentful-userland/gatsby-contentful-starter). It is always open to contributions and pull requests.

You can learn more about how Contentful userland is organized by visiting [our about repository](https://github.com/contentful-userland/about).
