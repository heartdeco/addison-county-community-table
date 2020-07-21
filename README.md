# The Addison County Community Table

This is the development guide for the Addison County Community Table, an online ordering platform that supports local businesses in Addison County, Vermont.

This README file contains the most up-to-date guidance on the current status of the project and how you can contribute to its development. At this stage, we assume you want to contribute by testing out the platform and offering suggestions on how features should work or by providing your ideas for new features. If you'd like to be involved in some other way, please contact Justin Doran at jmdoran@gmail.com.

## Using the issue tracker

To keep track of your contributions, we use an issue tracker hosted in a GitHub repository. In that repository, you can find the [most recent version of this file](https://github.com/heartdeco/addison-county-community-table/), which will be updated along with the project. To contribute, you will need to first [create an account on GitHub](https://github.com/join). Once your account is created, confirmed, and you've logged in, you should visit the project's [issue tracker](https://github.com/heartdeco/addison-county-community-table/issues). We have set up several [templates](https://github.com/heartdeco/addison-county-community-table/issues/new/choose) to help you write your request, but you should also feel free to create an issue from scratch. 

Our goal is to respond to your idea or problem within one working day, but since we're an all-volunteer development shop, please be patient if it takes us a little bit longer to give you feedback. Once you've submitted your question, feature idea, bug report, or other issue, we'll communicate updates with you through the issue's page. GitHub can be set up so that you [receive email notifications](https://docs.github.com/en/github/managing-subscriptions-and-notifications-on-github/configuring-notifications) in addition to their on-site notification system.

This is the preferred way that you should communicate with the project's developers as it ensures we don't lose track of something.

## The Testing Environment

Our current testing environment can be accessed at the following URL:

[https://secure-depths-72680.herokuapp.com/](https://secure-depths-72680.herokuapp.com/)

The testing environment's title is a randomly generated string. We will periodically transition to new testing servers when there are major structural changes to the app, or if the testing environment's database has been filled up or broken for some reason. When that happens, you can return to the project's GitHub repository, which will contain the most up-to-date URL that will allow you to access the testing environment. **Crucially**, this means that you should not expect anything you input into the testing environment to be permanent. We will try to keep the information you enter into the testing environment as consistent as possible, but it is fundamentally for testing, and so data could be lost.

To make changes to the testing environment, such as creating a mock business or placing an order, you will need to register an account on the platform. This is unrelated to the account you might have created on GitHub. The account you register in the testing environment is relatively secure, but you should **not** re-use a password that you use for other accounts, as we are not regularly auditing the security of the test data. 

The platform requires that you confirm your account via email, so you **must** use a real email address that you have access to. Your account on the testing platform is completely independent from the (eventual) production version of the platform. That means you can use the same email address for both this environment and the (eventually) running website. So feel free to use your primary email address. We won't send you any emails except to manage your account. Note that if the testing environments are cycled, you will have to recreate your account and reconfirm your email.

## What we'd like you to focus on

We genuinely appreciate any and all suggestions you have. Currently, we're in the "blank canvas" stage of testing. This means we'd like you to add any and all ideas that you can imagine to the issue tracker. Once we introduce new, specific features, we'll update this section of the guide to direct your attention to what we're actively focusing on. Just to let you know what's currently happening in this *very* early stage of implementation, as of July 21st, 2020 we are currently implementing the following features:

- A shopping basket to create orders
- New interfaces for different kinds of businesses
- An interface for showing orders and their histories
- Payment processing


## Thank you

We absolutely could not do this without support from the community. We appreciate any time, effort, thoughts, or experiences you share with us.
