# magmastore
Solidus with steroids

# Objectives
to use the latest versions of Ruby and Solidus
a minimal, semantic and accessible HTML skeleton
a reusable component based architecture
to use usefull gems


This initial setup was made by running the following commands:

```
rails new store --database=postgresql --skip-javascript
cd store
bundle add solidus
bin/rails generate solidus:install --frontend=solidus_starter_frontend
```

# Why these project?
## Use the new Starter Frontend
The starter frontend is a new theme for the Solidus e-commerce platform that provides a modern, responsive design and a set of pre-built templates and components that can be customized to create a unique, branded storefront.
  
## Use the Event Bus as a gateway to a new external features
The event bus is a new feature in Solidus that enables users to subscribe to events that occur within the platform and trigger custom actions in response. This allows developers to build custom integrations and extend the functionality of Solidus without modifying the core codebase.

Here are a few examples of how the event bus could be used:
- Send an email to a customer when their order is shipped
- Update a customer's loyalty points balance when they make a purchase
- Notify a warehouse management system when an order is placed
- Integration with an external API(Recommender System)
