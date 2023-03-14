---
layout: ../layouts/MarkdownPostLayout.astro
title: "End-to-end API Testing With Postman"
pubDate: 2022-11-13
description: "Follow these steps to create API endpoint tests in Postman"
author: "Chance Smith"
tags: ["testing", "development"]
---

## First, why are we testing the API endpoints?

You might have other reasons, but sometimes my team dosn't own the backend codebase. If endpoints show any feature regression, we create a new API endpoint test.

I don't want my team spending time on a task just to find out the endpoints don't work and they are blocked.

> It's not the job of the consumer to be the test harness for the provider. - Pact

Alterative: Because you are only tackling frontend and you don't want to write API tests, then look at creating a mock server instead.

## Let's create a Postman test

(coming soon)

## Run many tests

## Run a Postman collection from the CLI

## What next?

I would look at adding this CLI command to your CI or backend code workflow. A great outcome migt be: If the API tests fail, PR can't merge.
