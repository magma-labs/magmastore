# magmastore
Solidus with steroids

# Objectives
a minimal, semantic and accessible HTML skeleton
a reusable component based architecture
simple SASS styling strictly based on BEM

This initial setup was made by running the following commands:

```
rails new store --skip-javascript
cd store
bundle add solidus
bin/rails generate solidus:install --frontend=solidus_starter_frontend
```

