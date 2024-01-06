---
title: Infrastructure as Code
date: "2023-08-01"
draft: true
tags:
- ansible
- devops
slug: What the duck is IoC
---
This is the first post in a series that aims to introduce infrastructure as code. 
We will start in the post with a discussion of why you would want to use IoC and then the different types, before giving some examples of IoC in action. 

# What is IoC

Simply IoC is a way of describing your infrastructure in code. In the same what if you were to build a building or a ship you would first design the system using plans. Building ships and buildings we use plans called blueprints. These show what we are going to build. When in the past you would build out your IT infrastructure you would create a plan of what steps you would take and then some form of drawing. This was how we did it for years. Then came the cloud and with it APIs to control creating, managing and destroying resources. This then as lead to a number of DevOps tools that can link together these API with a standard syntax.

# Terraform

