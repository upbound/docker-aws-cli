[![CircleCI](https://circleci.com/gh/upbound/docker-aws-cli.svg?style=svg)](https://circleci.com/gh/upbound/docker-aws-cli)

# Upbound AWS CLI

This project contains the Dockerfile needed to build a Docker image with the AWS CLI built in. This is one of many projects out there that
builds a Docker image with the AWS CLI baked in, but this is the build used by Upbound in its CI/CD processes.  

## Getting Started

To use this Docker image, simple enter the CLI by running the following command:

```
docker run -it upbound/aws-cli
```

From here, you will be able to interact with AWS as you would expect with the CLI.

## Local Build and Test

For local testing, the easiest way to get started is to build the Dockerfile on your machine. Run something like:

```
docker build -t myrepo/aws-cli .
```

After this, you can use the image by running:

```
docker run -it myrepo/aws-cli
```

## Contributing

Please read [Contributing](CONTRIBUTING.md) for information on the process for submitting pull requests to us.

## Licensing

The Upbound AWS CLI Docker Image project is under the Apache 2.0 license.

## Acknowledgments

* [AWS CLI](https://github.com/aws/aws-cli) for the code
