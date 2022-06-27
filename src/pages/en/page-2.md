---
title: Authentication
description: How to authenticate
layout: ../../layouts/MainLayout.astro
---
    
The tickets center Api follow the standar of the [OAuth2](https://oauth.net/2/)

The first step is to request a Bearer token via the `/oauth/token` endpoint with a `client_id` and `client_secret` OAuth2

You will receive a `Bearer token` and a `refresh_token`
