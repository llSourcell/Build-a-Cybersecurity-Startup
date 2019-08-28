# Overview

This is the code for [this](https://youtu.be/BXw8vQXxvqc) video, "Build a Cybersecurity Startup" by Siraj Raval on Youtube. This is unfinished code, it runs, but the features still need to be integrated together in a coherent way. I'll outline below what to do

## Run the intial app

1. Check out this [Live Demo](http://aws-web-analytics-dashboard.s3-website-us-east-1.amazonaws.com/)
2. Follow [this](https://cube.dev/blog/building-open-source-google-analytics-from-scratch/) blog post.

# Package desriptions

- [Event Collection AWS Lambda function](./event-collection)
- [Analytics Dashboard React Application](./analytics-dashboard)

## TODO (in order)

- Switch the react backend to a [flask](https://github.com/pallets/flask) backend
- Add a suitable homepage to the dashboard. I used [Clearbit's](https://clearbit.com/risk) for inspiration
- Train a logistic regression model on credit card fraud data. [Here's](https://github.com/nickwalker037/Credit-Card-Fraud-Detection) an example repository. 
- Integrate 2 [Openmined](https://github.com/OpenMined) libraries, PySyft, and syft.js into the app to enable federated learning and secure multiparty computation.

## Credits 

Everybody but me, i just put it all together to inspire people to build empowering tools for others.
