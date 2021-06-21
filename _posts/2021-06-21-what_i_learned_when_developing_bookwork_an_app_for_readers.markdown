---
layout: post
title:      "What I learned when developing Bookwork: An app for readers"
date:       2021-06-21 15:19:39 +0000
permalink:  what_i_learned_when_developing_bookwork_an_app_for_readers
---

Bookwork is an application with a Rails backend and a Javascript fronted, that allows users to create books and store them. These may be books that they plan to read in the future or books that they want to recommend for others to read. Working on this application finally allowed me to understand what I should have learned about APIs.

An API (Application Programming Interface), can be described as any source that processes data for the frontend of the application to consume. This concept has boggled my mind for months now. There are two main types of APIs one, can be your own API and the other is an external API. 

For Bookworm, I created a Rails backend, this was my very own API that my frontend would use to display and process user inputs so that they render on the screen. My API consisted of two models, the category and book. The relationship between the two is also, in my opinion, important to note. A category has many books and a book belongs to one of the categories. 

Working on the frontend also gave me an opportunity to learn more about different serializers and the overall benefit of using a serializer. Bookworm uses a Ruby gem called fast_jsonapi. This gem allows us to serialize Ruby objects into JSON. That means, we must create serializers for each model to be serialized. 

Working on Bookworm allowed me to understand more clearly the concept of an API as well as the purpose for serializing data. I am certainly excited about Bookworm and I am looking forward to using this to learn Semantic UI as well as the process of deploying an application using Heroku. 

