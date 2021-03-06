---
title: Introduction
weight: 1
---

**PACKAGE IN DEVELOPMENT, DO NOT USE YET**

This package provides a lightweight, but capable, solution for making a Laravel app tenant aware. It can determine which tenant should be the current tenant for the request. It also allows you to define what should happen when switching the current tenant to another one.

It works for multitenancy projects that need to use one or multiple databases.

Before starting with the package, we highly recommend first watching [this talk by Tom Schlick on multitenancy strategies](https://tomschlick.com/2017/07/25/laracon-2017-multi-tenancy-talk/).

The package contains a lot of niceties such as making queued jobs tenant aware, migrating all tenant databases in one go, an easy way to set a connection on a model, and much more.
