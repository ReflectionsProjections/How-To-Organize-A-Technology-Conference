# Overview of Reflections Projections Technology Stack

## The Frontend 
Reflections Projections 2017 - 2019 has used React. Prior to this, regular html and sometimes JQuery were used. The frontend is should be built as a static site and deployed using S3.

## The API
The Reflections Projections Conference uses the [Hack Illinois API](https://github.com/HackIllinois/api) to handle Registration and Check-In during the conference. The APi itself shouldn't need to be modified and the [hackillinois/api Docker Container](https://hub.docker.com/r/hackillinois/api) can simply be deployed to an AWS ECS cluster. Setting up the configuration files requires access to the RP AWS resources, MongoDB database credentials, and GSuite OAuth API Client ID and token. Detailed documentation for API endpoints and deploying to AWS can be found [here](https://docs.hackillinois.org/).

## Effective Googles
[Effective Googles](https://github.com/ReflectionsProjections/effective-goggles) is the app used to check in attendees into Reflections Projections conference events using QR code scanning.
