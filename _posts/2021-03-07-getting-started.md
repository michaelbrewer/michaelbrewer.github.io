---

title: "Building AWS Lambdas in Python"
date: 2021-03-07 15:30:15 -0000
breadcrumbs: true

---

# Building AWS Lambdas in Python

Covers how to use [AWS Lambda Powertools](https://awslabs.github.io/aws-lambda-powertools-python/) to enrich your existing or new lambda


## Basic Payment lambda

Below is what a lambda would normally look like being used with an API Gateway Proxy Event

{% gist 18e17fc5a73a7fba05099acd6b8523d5 %}


## Setting Up AWS Lambda Powertools

{% gist 490adbd084424f507f82debf27b9ebf6 %}


## Logging

Adding logging

{% gist 895cd088ed670dc3a7b7fec6f6c18f49 %}


## Tracing

Adding tracking 

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

Adding example of input and output validation

## Event hadler

Add example of the api gateway event handler

## Unit Testing

Unit tesitng out lambda

---

[Back to Home](/)
