---

title: "Building AWS Lambdas in Python"
date: 2021-03-07 15:30:15 -0000
breadcrumbs: true

---

# Building AWS Lambdas in Python

Covers how to use [AWS Lambda Powertools](https://awslabs.github.io/aws-lambda-powertools-python/) to enrich your existing or new AWS Lambda functions.


## Basic Payment lambda

Below is what a lambda would normally look like being used with an API Gateway Proxy Event

{% gist 18e17fc5a73a7fba05099acd6b8523d5 %}


## Setting Up AWS Lambda Powertools

{% gist 490adbd084424f507f82debf27b9ebf6 %}


## Logging

Adding logging

{% gist 895cd088ed670dc3a7b7fec6f6c18f49 %}


## Tracing

Adding tracing 

{% gist 6a8529610de3ca543938ec09d3c47373 %}

## Metrics

Adding metrics

{% gist 2a2596ee0d266505615d1a69dbb4bca4 %}

## Data Classes

Using Data Classes for standard AWS Event types

{% gist f80d9d0a201ee71944bccaf5b02b16f6 %}

## Type Hinting

Adding type hinting

{% gist b30d1c5b4c3611135a79f2e773beaa62 %}

## Idempotent

Making our lambda retry safe

{% gist 8b7454d70e47df7857c0262f2b3bff20 %}

## Exception Handling

Adding exception handling

{% gist dd253f4a8ba30f0606eb12bae94a9a6f %}

## Validation

Adding input and output validation

{% gist 3e8928ae6ad1375cbb6b99b379759f3a %}

## Paramters

Loading parameters from AWS Parameter Store

{% gist c929574d5adb227476268d79780e4eae %}

## Modular

Making the lambda modular

{% gist baac722f6827a7176f669cf784a7bb26 %}

## Unit Testing

> TODO: Add Unit tesitng of lambda

## Event hadler

> TODO: Add example of the api gateway event handler

---

[Back to Home](/)
