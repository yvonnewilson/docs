---
title: Login
description: This tutorial demonstrates how to add user login to a React application using Auth0.
budicon: 448
topics:
  - quickstarts
  - spa
  - react
  - login
github:
  path: 01-Login
contentType: tutorial
useCase: quickstart
---
<!-- markdownlint-disable MD034 MD041 -->

<%= include('../_includes/_getting_started', { library: 'React', callback: 'http://localhost:3000', returnTo: 'http://localhost:3000', showLogoutInfo: true, showWebOriginInfo: true, new_js_sdk: true }) %>

<%= include('_includes/_centralized_login') %>
