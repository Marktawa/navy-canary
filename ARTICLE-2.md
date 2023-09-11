# <!-- Title Here --> How to Build a Static Blog with Gatsby and Strapi
<!--Please copy-paste this in a new HackMD file and share it with dessire.ugarte-amaya@strapi.io. -->
- **meta-title**: <!--*under 65 characters* --> How to build a static blog with Gastsby and Strapi
- **meta-description**: <!-- *under 155 characters* --> Learn how to create a static blog website application using Strapi for the back-end and Gatsbyjs to the front-end
- **Figma images**: <!-- *Use [this](https://www.figma.com/file/gI8PcsqInk3DAwfIxmcyPI/Writers-Blog-Banners?type=design&t=aR5xXTyBSWXBcR5P-0) figma file* -->
- **Publish date**: 
- **Reviewers**: 

## Introduction

This tutorial will help you learn how to build a static blog website using Gatsby and Strapi. 

In this step-by-step guide, you will learn how to harness the power of [Gatsby](https://www.gatsbyjs.com/docs/), a blazing-fast static site generator, and [Strapi](https://strapi.io/features), a composable CMS, to create a dynamic yet performant blog.

Whether you are a developer looking to expand your skillset or a content creator seeking a flexible and efficient way to manage your blog, this tutorial will equip you with the knowledge to create a sleek and responsive static blog website. Let's dive in!

### Why Gatsby?

![Gatsby logo](https://hackmd.io/_uploads/SypSzkTC3.jpg)

Gatsby is a blazing-fast website framework for React. It allows developers to build React-based websites within minutes. Whether you want to develop a blog or a corporate website, Gatsby will fill your needs. It was built with performance, scalability and security in mind.

Gatsby is very flexible and provides three ways of rendering content on your website:
- Static Site Generation (SSG)
- Deferred Static Generation (DSG)
- Server-Side Rendering (SSR)

For this tutorial we will only focus on SSG. SSG is where the entire site is pre-rendered into HTML, CSS and JavaScript at build time, which then get served as static assets to the browser.

![GraphQL logo](https://hackmd.io/_uploads/H191qJaCn.png)


Gatsby uses [GraphQL](https://spec.graphql.org/October2021/) a query language and execution engine for describing the capabilities and requirements of data models for client-server applications. GraphQL is designed to build client applications by providing an intuitive and flexible syntax and system for describing their data requirements and interactions.

GraphQL APIs unlike [REST APIs](https://en.wikipedia.org/wiki/REST) allow you to get all the data for your app in a single request. GraphQL also enables you to select the only the data you need in your API request leaving out any unnecessary data. Find out more about the [benefits of GraphQL by following this link](https://graphql.org/faq/#why-should-i-use-graphql). Gatsby uses GraphQL to enable page and static query queries to declare what data they need from an API endpoint. The data is then used to build pages for your website.

### Why Strapi?

[Strapi](https://strapi.io/features) is the leading open-source headless Content Management System (CMS). It is 100% JavaScript, based on Node.js, and can be used to build RESTful APIs and GraphQL APIs. It also has a cloud SAAS, [Strapi Cloud](https://cloud.strapi.io/login) - a fully managed, composable, and collaborative platform to boost your content velocity! Alternatively, you can [self-host Strapi](https://strapi.io/pricing-self-hosted) on your own infrastructure.

![Strapi logo](https://hackmd.io/_uploads/ByqrelaAh.png)


Strapi enables developers to build projects faster with a flexible and customizable platform for managing content. Check out the [Strapi Quickstart guide](https://docs.strapi.io/dev-docs/quick-start) for a brief intro.

In this tutorial, you will use Strapi as a backend to create and store your content. Strapi supports GraphQL so Strapi will provide a data source using a GraphQL API for your Gatsby frontend to consume.

## Prerequisites

To follow along with the tutorial, you will need the following tools installed on your computer:

- [Node.js](https://nodejs.org/en/download) Node `v16.x`, `v18.x`, and `v20.x` Only LTS versions of Node are supported
- Package manager

## Conclusion 