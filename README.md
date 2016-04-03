Dodger CMS has been extended to support the following features:

- all aws region support via a region field on the login page (caveat is all buckets need to bein the same region)
- two new optional fields, `site path` and `assets path` which rewrites the image paths and page links so that the site can be served as a component of another site under a particular path (requires the configuration of a reverse proxy or cdn)

[![DodgerCMS](http://i.imgur.com/EmVj8OL.png)](http://dodgercms.com/)

[![Build Status](https://travis-ci.org/ChrisZieba/dodgercms.svg)](https://travis-ci.org/ChrisZieba/dodgercms)

[DodgerCMS](http://dodgercms.com) is a static markdown CMS built on top of [Amazon S3](http://aws.amazon.com/s3/). It is a clean and *simple* alternative to heavy content management systems. There are no databases to manage, deployments to monitor, or massive configuration files. Just focus on writing your content and the results are live immediately.

## Demo

The [demo](http://dodgercms.com) is used to display the documentation for DodgerCMS. It displays the default layout and style of the front end. To see screenshots of the backend manager, please take a look [here](http://dodgercms.com/#screenshots).

## Features

- [Full markdown editor](http://dodgercms.com/features/editor)
- [Uploads images directly to the cloud](http://dodgercms.com/features/images)
- [Handles changes in URL structure](http://dodgercms.com/features/menu)
- [Access via your S3 bucket](http://dodgercms.com/features/cloud)
- [Custom layouts](http://dodgercms.com/features/layouts)
- [Live updates](http://dodgercms.com/features/live)

## Documentation

The [documentation](http://dodgercms.com) for DodgerCMS is itself built with DodgerCMS.

## Installation

Please take a look at the [installation guide](http://dodgercms.com/help/installation).

## Development

DodgerCMS is still very early in its development. Please take a look at the development guide for more information on how to [contribute](http://dodgercms.com/development/contributing).

## License

`MIT License` (MIT)
Copyright (c) 2015 Chris Zieba