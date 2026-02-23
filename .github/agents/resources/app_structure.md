# App Structure
This document outlines the way the application is structured.

# Assets Structure
Assets are stored in the `public` folder at the root of the project directory. Different assets should be stored under different subfolders:

1. `public/img` - image assets
2. `public/css` - css assets to be served at runtime

# Feature Structure
All features should be placed under `src/app/features` and use the following structure:

src/app/features
|-feature-1
  |-pages
    |-page-1.component.ts
  |-components
    |-component-1.component.ts
  |-services
    |-...
  |-pipes
    |-...
  |-guards
    |-...
  |-feature-1.routes.ts

**DO NOT** add empty folders when creating features.