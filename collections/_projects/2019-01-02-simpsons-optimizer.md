---
layout: post
title:  "Simpsons Optimizer"
dek:    "A Simpsons JSON and Redirect API"
date:   2019-01-02 00:00:00 -0000
categories: project
excerpt: "An API around a Simpsons dataset, to make picking random good episodes easier."
url: "http://www.simpsonsoptimizer.com/"
---

[SimpsonsWorld](https://www.simpsonsworld.com) is right up there with the wheel and agriculture for great accomplishments of human civilization. It is a Simpsons-specific service that allows streaming of every Simpsons episode (if you have a cable login). It has a Random button, which is great, but a lot of episodes are bad.

This utility, built around a Simpsons dataset I compiled that tracks episode goodness, can randomly redirect to a good episode.

It can also spit out JSON of episodes or redirect to a particular episode, which is also nice.

This was written in server-side javascript as an excuse to try out Express. (Express is nice.)
