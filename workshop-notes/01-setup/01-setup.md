# Set Up

In this section we will spend sometime setting up our environments before getting started.
1. Clone this repo
2. Sign in to your AWS Account
3. Install the AWS CLI and auth via the command line
4. Install serverless globally
5. Open this project in the code editor of your choice

## Clone this repo
Run `git clone git@github.com:AshwaryaSmridhi/simple-lambda.git` to clone this repo.<TODO: Add correct repo link>

If you don't have a github account, please download the zip<TODO: Add link here>.

## Sign in to your AWS Account
If you don't already have one, you'll have to set up a personal AWS account. If you don't have one, having an AWS account is key if you intend on continuing your AWS learning journey after this workshop.

* If you DO have an account, log in (preferably not as root and you've set up a user via IAM that has permissions to deploy resources). If you have surpassed the free tier we will give you a $50 AWS voucher.
    * Create an [IAM user](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html)
    * Set up a access key ID and secret by following instructions [HERE](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey). Keep this access key and secret handy. We will need that while calling the secure API.

* If you DONT have an account, go [HERE](https://aws.amazon.com/) to create one, you'll need a credit card - Don't worry no cost will be incured today. 

## Install the AWS CLI and auth via the command line

As we're running commands via the command line that will allow you to deploy AWS resources, you need to authenticate to your personal AWS via the command line.

Here's install instructions for all operating systems: [How to install the AWS CLI 2](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

Here's the instructions on how to authenticate via your command line: NOTE: you'll need to get some details from the AWS web console that'll need to be copy and pasted for this to work [AWS instructions on how to configure your command line](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html#cli-configure-quickstart-config)

It'll look something like this:

aws configure
Then following the prompts you need to provide:

* AWS Access Key ID
* AWS Secret Access Key
* Default region name (for Australia, choose ap-southeast-2)
* Default output format (you can just choose nothing)

## Install serverless globally
We are deploying the lambda using [serverless](https://www.serverless.com/framework/docs/). To install serverless via npm simply run `npm install -g serverless`. 

## Open this project in the code editor of your choice
We are going to make a new lambda and create alarms. To do this, it's best to use a code editor.

There's lots of free versions, here's a few to pick from if you don't already have one:
* [Visual Studio Code](https://code.visualstudio.com/)
* [Atom](https://github.com/atom)
* [Sublime Text 3](https://www.sublimetext.com/3)

Here is an even longer [list](https://hackr.io/blog/web-development-ide).

# NEXT SECTION - Key Concepts 👉🏽<TODO Add link>