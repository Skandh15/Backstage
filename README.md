# Backstage

### What is Backstage?
- Backstage is an open platform for building developer portals.
- Backstage restores order to your microservices and infrastructure and enables your product teams to ship high-quality code quickly — without compromising autonomy.
-  It is based on an internal tool Spotify uses to help organize development tools, documentation, and processes that new developers need to be aware of when developing a new app or API.
-  The idea behind Backstage is that it helps reduce the cognitive load on a new developer by pulling together commonly required resources into one browser-based user interface.

### What problem is addressed?

- Think about all the things you need to familiarize yourself with when you start developing something for a new organization. Is there a standard set of design patterns, frameworks, and programming languages that you are expected to use? Where can you find documentation about the organization’s APIs that you may need to consume? How and where can or should you deploy your solution?

### Tools and Frameworks that are fundamental
- Node.js: Backstage is a web frontend that is designed to run on Node.js, at least at development time. Backstage currently requires `Node 12`. _Users are getting mixed results with higher node versions_.
- TypeScript: Backstage is mostly written in TypeScript, though you can code in pure JavaScrit but it's a good practice to use TypeScript over JS.
- React: The frontend code is written using React. React components play a fundamental role in Backstage’s plugin architecture. Plugins are essentially individually packaged React components.
- Yarn and Lerna: These two JavaScript tools go hand in hand or npm.

### What is included in Backstage
- __Backstage Service Catalog:-__  for managing all your software (microservices, libraries, data pipelines, websites, ML models, etc.)
    -  It is a centralized system that keeps track of ownership and metadata for all the software in your ecosystem (services, websites, libraries, data pipelines, etc). 
    - The catalog is built around the concept of metadata YAML files stored together with the code, which are then harvested and visualized in Backstage.

- __Backstage Software Templates:-__ for quickly spinning up new projects and standardizing your tooling with your organization’s best practices.
    - The Software Templates part of Backstage is a tool that can help you create Components inside Backstage.
    -  It has the ability to load skeletons of code, template in some variables, and then publish the template to some locations like GitHub.

- __Backstage TechDocs:-__ for making it easy to create, maintain, find, and use technical documentation, using a "docs like code" approach.
    - TechDocs is Spotify’s homegrown docs-like-code solution built directly into Backstage.
    - This means engineers write their documentation in Markdown files which live together with their code.

- __Open Source Plugins:-__ A growing ecosystem of plugins to expand customizability and functionality.


## Concerns
- There is only one concern that is it is still very new, he initial alpha version was released on 16 March 2020. 
- Due to this, we cannot expect a full ecosystem of plugins just yet.