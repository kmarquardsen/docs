---
title: "Parallel Example"
linkTitle: "Parallel"
weight: 10
type: "docs"
---

The following examples will help you understand how to use Parallel to describe
various flows.

## Prerequisites

All examples require:

- A Kubernetes cluster with
  - Knative Eventing
  - Knative Serving

All examples are using the
[default channel template](../../channels/create-default-channel.md).

## Examples

For each of these examples below, we'll use
[`PingSource`](../ping-source/README.md) as the source of events.

We also use simple
[functions](https://github.com/lionelvillard/knative-functions) to perform
trivial filtering, transformation and routing of the incoming events.

The examples are:

- [Parallel with multiple branches and global reply](./multiple-branches/)
- [Parallel with mutually exclusive cases](./mutual-exclusivity/)
