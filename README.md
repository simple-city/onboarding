[![Simple City](https://cdn.rawgit.com/simple-city/hosted-assets/7dd6cfc9/images/logo-simplecityllc.png)](http://simplecityllc.com)

# Onboarding
General information that is helpful for onboarding new hires.

## Table of Contents
* Technology
  * [Communications](#communications)
    * [General Guidelines](#general-guidelines)
    * [Usage](#usage)
    * [Email](#email)
    * [Chat](#chat)
    * [Conferencing](#conferencing)
  * [Password Management](#password-management)
  * [Document Sharing](#document-sharing)
  * [Infrastructure](#infrastructure)
  * [UI Stack](#ui-stack)
  * [Continuous Integration/Deployment](#continuous-integrationdeployment)
  * [Source Control](#source-control)

## Communications

### General Guidelines
All the communication methods we use have desktop/web and mobile clients. If you are a remote employee, you are expected to have the mobile clients installed and running on your work devices during work hours.

### Usage
What do I use when? And for what?

Are you communicating with an external party?
* Use [email](#email) for "on the record", asynchronous conversations.
* Use [conferencing](#conferencing) for interpersonal, ephemeral, and on demand conversations.

Are you communicating with coworker(s)?
* Use the [chat](#chat) platform
  * Make sure you select direct message vs channel conversations wisely. Nobody likes spam.
  * Make sure your channel conversations are aligned with the channel topic. Again, nobody likes spam. Seriously, not even the people that make it.

### Email
For "on the record", asynchronous conversations.

> [Gmail](https:/gmail.com) <img src="https://ssl.gstatic.com/ui/v1/icons/mail/images/favicon5.ico" height="16" />

We use Google Apps for email. So feel free to use your favorite flavor.
* [Gmail](https:/gmail.com) <img src="https://ssl.gstatic.com/ui/v1/icons/mail/images/favicon5.ico" height="16" />
* [Inbox](https://inbox.google.com) <img src="https://ssl.gstatic.com/gb/images/a/eacd033c28.png" height="16" />

### Chat
For informal, asynchronous conversations. While still technically on the record, these types of conversations should resemble that of two or more professionals at a morning standup.

> [Slack ![Slack](https://www.google.com/s2/favicons?domain=slack.com)](https://slack.com/is)

We use Slack as our instant messaging platform.
* Instance: [simplecityllc.slack.com](simplecityllc.slack.com)
* Invite Url: [https://simplecityllc.slack.com/signup](https://simplecityllc.slack.com/signup)

### Conferencing
For interpersonal, ephemeral, and on demand conversations.

> [Google Hangouts ![Hangouts](https://www.google.com/s2/favicons?domain=hangouts.google.com)](https://hangouts.google.com)

Since Slack does not provide video conferencing or the ability to allow external phone numbers to call in to their call system, we've elected to use Google Hangouts.

* Primary usage: [Google Hangouts ![Hangouts](https://www.google.com/s2/favicons?domain=hangouts.google.com)](https://hangouts.google.com)
* Testing usage: [Google Meet ![Meet](https://www.google.com/s2/favicons?domain=meet.google.com)](https://meet.google.com)


## Password Management

> [Bitwarden ![Bitwarden](https://www.google.com/s2/favicons?domain=bitwarden.com)](https://www.bitwarden.com)

In order to follow best practices for sharing credentials we've elected to use Bitwarden.

Pros:
* Easily allows for team sharing
* Has **free** apps for all major mobile platforms
* Has **free** extensions for all major browsers
* Has a responsive web interface
* Allows for the first two user accounts at no cost (perfect for a startup)
* Relatively inexpensive to ramp up multiple users

Cons:
* Takes a little time to get used to

## Document Sharing

> [Google Drive](https://google.com/drive) <img src="https://lh6.ggpht.com/k7Z4J1IIXXJnC2NRnFfJNlkn7kZge4Zx-Yv5uqYf4222tx74wXDzW24OvOxlcpw0KcQ=w300" height="16" />

Since we are Google App driven, we chose to use the (alomost) freely available. It is straight forward enough and allows for external collaboration and sharing.

## Infrastructure
A common practice among great software is to do one thing very well. At Simple City we try very hard to follow that concept by taking advantages of 3rd party services for areas that we either are lacking expertise, time, and or funding to develop inhouse (usually all three). Below you will find several _examples of the services that we leverage_ to construct our platform.

_NOTE: **TaaS** = **T**hing **a**s **a** **S**ervice_

PaaS (platform):
  * [Heroku](https://www.heroku.com) <img src="https://avatars1.githubusercontent.com/u/23211?v=3&s=16" height="16" />

IaaS (infrastructure):
  * [Amazon Web Services ![Amazon Web Services](https://www.google.com/s2/favicons?domain=aws.amazon.com)](https://aws.amazon.com)

DBaaS (database):
  * [Postgres (Amazon RDS) ![Postgres](https://www.google.com/s2/favicons?domain=www.postgres.com)](https://aws.amazon.com/rds/postgresql/)

FaaS (functions):
  * [Amazon Lambda](https://aws.amazon.com/lambda) <img src="http://www.stratoscale.com/wp-content/uploads/AWS-Lambda.png" height="16" />

AaaS (auth):
  * [Auth0 ![Auth0](https://www.google.com/s2/favicons?domain=auth0.com)](http://auth0.com)


## UI Stack
Our front end consists of the following frameworks and foundations. As you will see, we are heavily invested in JavaScript.

* Starter project: [NextJs](https://github.com/zeit/next.js) <img src="https://cloud.githubusercontent.com/assets/13041/19686250/971bf7f8-9ac0-11e6-975c-188defd82df1.png" height="16" />
* Css: [Styled Components ![Styled Components](https://www.google.com/s2/favicons?domain=styled-components.com)](https://www.styled-components.com/)
* Client side: [ReactJs ![ReactJs](https://www.google.com/s2/favicons?domain=facebook.github.io/react)](https://facebook.github.io/react/)
* Server side: [NodeJs ![NodeJs](https://www.google.com/s2/favicons?domain=nodejs.org)](https://nodejs.org)

## Continuous Integration/Deployment
All great software is built on some sort of continuous integration. Code built on tests has proven to be more reliable, easier to troubleshoot, and cheaper to improve upon.

* [CircleCI ![CircleCI](https://www.google.com/s2/favicons?domain=circleci.com)](https://circleci.com)

## Source Control

> [Github ![Github](https://www.google.com/s2/favicons?domain=github.com)](https://github.com/simple-city)

Maintaining and organizing our source code should be simple. There is only one source code provider that we consider reliable, of optimal flexibility, and cost effective. There is simply no other alternative to Github.


## Continued Education

> [Wes Bos Courses ![Wes Bos Courses](https://www.google.com/s2/favicons?domain=wesbos.com)](http://wesbos.com/courses/)

Our company's core is centered around JavaScript. Below you will find courses that will give you the fundementals and/or refresh what you already know to make you the most efficient developer when working on our stack.

**Preferably in the following order:**
* [JavaScript30.com](//JavaScript30.com)
* [ES6.io](//ES6.io)
* [LearnNode.com](//LearnNode.com)
* [ReactForBeginners.com](//ReactForBeginners.com)
* [LearnRedux.com](//LearnRedux.com)
* [CommandLinePowerUser.com](//CommandLinePowerUser.com)

Some are free. Some are < $100/per. All are priceless.
