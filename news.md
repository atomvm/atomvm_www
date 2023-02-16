---
layout: post
title: News
permalink: /news/
---

## 2022/04/05 AtomVM Example Programs

We have extracted our example programs into a self-contained and growing github repo with minimal dependencies. For example, if you have flashed the AtomVM image to an ESP32 device, you can simply use rebar3 to build and flash your applications, making the compile/flash/debug cycle you experience on embedded devices fairly painless.

[AtomVM Example Programs](https://github.com/atomvm/atomvm_examples)

Please note that at this stage, support for building Elixir programs is quite far behind that of Erlang, so best to stick with Erlang until further notice.

## 2022/03/22 Announcing AtomVM 0.5.0

After many months of work, we are happy to announce version 0.5.0 of the AtomVM virtual machine, a lightweight implementation of the BEAM for small and cheap micro-controllers!

This release of AtomVM is our first development preview release. We are still shaking out some of the rough edges, but we feel the release is stable enough for intrepid developers to get started with simple Erlang or Elixir programs.

A binary image of ESP32 release can be found in the [download](https://atomvm.net/download/) section of the AtomVM [web page](https://atomvm.net/).

The git repository and tarballs of the AtomVM source release for all other platforms can be found on our [GitHub project page](https://github.com/atomvm).

Documentation of the AtomVM virtual machine, including a Getting Started Guide, can be found at the [AtomVM Documentation page](https://doc.atomvm.net/index.html)

Many thanks go to Davide Bettio, for creating such a fine work of software, as well as the contributors and testers who have helped make this release possible.

The AtomVM team

