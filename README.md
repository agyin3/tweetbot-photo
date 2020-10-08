# Tweetbot Photo

Simple twitter bot built to retweet and favorite nature photography

## Table of Contents

- [Technologies](https://github.com/agyin3/tweetbot-photo#technologies)
- [Installation](https://github.com/agyin3/tweetbot-photo#installation)
- [Features](https://github.com/agyin3/tweetbot-photo#features)
- [Resources](https://github.com/agyin3/tweetbot-photo#resources)
- [Contact](https://github.com/agyin3/tweetbot-photo#contact)

## Technologies

- Node
- Twitter API
- Dotenv

## Installation

Download the repo onto your local machine here <br/>
Run `npm i` to install all of the necessary dependencies <br/>
Run `npm start` to start the local server <br/>

## Features

**Favorite Tweets**

Every 10 minutes the bot will search for the 15 latest tweets that contain media content and are tagged with either #photography or #nature. It will then favorite any tweets returned from the search that it has not already favorited.

**Retweet Tweets**

Every 10 minutes the bot will search for the 10 latest tweets that contain media content and are tagged with both the #photography and #nature tags. It will then retweet any tweets returned from the search that it has not already retweeted.

## Resources

- [Blog Post Walkthrough](https://buddyagyin.blog/twitter-bot-using-node-js-and-heroku-1-3/)
- [Twitter API](https://developer.twitter.com/en/docs/twitter-api)

## Contact

Created by me, **Buddy Agyin**, feel free to [reach out](https://linkedin.com/in/buddy-agyin)
