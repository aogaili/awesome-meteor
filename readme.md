<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Meteor.js [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->

Awesome packages, articles, tips and people all around Meteor.js

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="./assets/awesome.png" />
</a>

<!-- description -->

<a href="https://www.meteor.com" target="_blank" rel="noopener noreferrer">Meteor.js</a> is an open source platform for building Web, Mobile, and Desktop applications.

</div>

<!-- TOC -->

## ✅ Features & Capabilities
- Battle-tested, backward compatible with a track record to prove and stable, forget about the [JavaScript fatigue](https://medium.com/@ericclemmons/javascript-fatigue-48d4011b6fc4) and focus on your business
- [Differential bundling](https://blog.meteor.com/meteor-1-7-and-the-evergreen-dream-a8c1270b0901)  (which is awesome)
- Dynamic imports
- Built-in TypeScript
- Support for React, Svelte, Agular, and Blaze (which is still great, all supported views have tutorials)
- [Meteor Vue](https://github.com/meteor-vue/vue-meteor) with HMR 
- Support for [SQL with real-time](https://atmospherejs.com/vlasky/mysql) maintained by @vlasky 
- Much faster build times and MUP support thanks to zodern
- NPM support
- Latest NodeJS support with easy update
- SSR Support

## 📦 Notable Packages
- Up-to-date router ([flow router](https://github.com/VeliovGroup/flow-router)) 
- Scaling with Redis (while maintaining the same API), using [RedisOplog](https://github.com/cult-of-coders/redis-oplog) 
- Anstromy: The [Astronomy 2.x](https://atmospherejs.com/jagi/astronomy) package introduces the [Model Layer](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)  for Meteor collections. Do more with less code, a really impressive and [well documented](https://jagi.github.io/meteor-astronomy/#what-is-astronomy) package.
- SQL like relationship query using [Grapher](https://github.com/cult-of-coders/grapher)
- [Meteor + Electron](https://github.com/wojtkowiak/meteor-desktop) 
- [Meteor built client](https://forums.meteor.com/t/meteor-build-client-v1-0-pre-release/52980) (a.k.a static site generator)
- [Meteor Files](https://github.com/VeliovGroup/Meteor-Files#demo-application): Upload files via DDP or HTTP to Meteor server FS, AWS, GridFS, DropBox or Google Drive. Fast, secure, and robust.
- [NPDev React Loadable](https://forums.meteor.com/t/awesome-meteor-list/52981) 
- [Meteor Elm](https://forums.meteor.com/t/meteor-elm-example/50244) 
- [Reactive aggregate](https://github.com/robfallows/tunguska-reactive-aggregate): pub/sub support for Mongo Lookups
- [SimpleSchema](https://github.com/longshotlabs/simpl-schema): a JavaScript schema validation package that supports direct validation of MongoDB update modifier objects by @aldeed
- [Socialize](https://atmospherejs.com/socialize): Packages for social interaction within Meteor applications.
- [quave profile](https://atmospherejs.com/quave/profile): profile the server runtime of Meteor with automatic update to S3 
- [pub-sub-lite](https://github.com/adtribute/pub-sub-lite): lighter (Method-based) pub/sub for Meteor with client caching other performance boosts

- ## 🚌 Data Layer & Transports

- DDP/Websockets (default)
   - [SimpleDDP](https://forums.meteor.com/t/awesome-meteor-list/52981) An easy to use DDP client library, can be used to connect to static sites (CRA, NextJS etc.), or microservices to Meteor backends via DDP 
   - [SwiftDDP](https://github.com/EngrAhsanAli/MeteorDDP) integrate servers written in meteor (a framework written in javascript) using native Swift in iOS.
- Rest 
   - [Meteor Rest](https://github.com/stubailo/meteor-rest): your Meteor app accessible over HTTP and DDP alike
   – [Picker](https://github.com/meteorhacks/picker): an easy to use server-side router for Meteor.
- GraphQL 
   - [Apollo Integration](https://www.apollographql.com/docs/react/v2/integrations/meteor/): a guide on integrating Apollo GraphQL server with Meteor backend

## 🚀 Deployment & Production

- Hosting
   - [Galaxy](https://www.meteor.com/cloud/): awesome Meteor hosting, forget about DevOps and focus on your business
   - [Scaling](https://doc.scalingo.com/languages/meteorjs/tutorial): another awesome meteor hosting, optimized for Meteor with sticky session and Mongo Oplog.
   - [zCloud](https://docs.zcloud.ws/docs/technologies/meteor)
- [Galaxy Guide](https://galaxy-guide.meteor.com/): a great resource on how to deploy and manage your production applications.
- [MUP](https://meteor-up.com/): an awesome Meteor swiss-knife deployment tool 
- Monitoring 
    - [Galaxy APM](https://galaxy-guide.meteor.com/apm-getting-started.html): Galaxy built-in Meteor apps monitoring tool
    - [MontiAPM](https://montiapm.com/): standalone hosted Meteor monitoring service
    - [Open Kadira](https://github.com/kadira-open/kadira-server): Open source meteor monitoring tool
    - [Meteor APM](https://montiapm.com/): Performance Monitoring for Meteor based on Elastic APM
    - [Secure Meteor](https://www.securemeteor.com/): a book on Meteor security
- [Meteor Scaling/Performance Best Practices](https://forums.meteor.com/t/meteor-scaling-performance-best-practices/52886): a thread about scaling tips and best practices.
- [Heroku buildpack](https://github.com/AdmitHub/meteor-buildpack-horse) for Meteor v1.0+. 
- [Meteor Azure](https://github.com/fractal-code/meteor-azure): Automate Meteor deployments on Azure App Service

Note if you are deploying outside of Galaxy and your business is profitable then please consider sponsoring the Meteor community developers below so they can support your business foundation. :heart:

## 🧰 Tools

- [Atmosphere](https://atmospherejs.com/): Meteor’s specialized full-stack packing system, complementary to NPM
- [Packosphere](https://packosphere.com/)
- [Meteor Dev Tools](https://forums.meteor.com/t/meteor-devtools-evolved/52017): Chrome extension for inspecting Meteor clients
- [Make CLI](https://github.com/maka-io/maka-cli): Maka-CLI is a command-line tool, which organizes a web application’s file structure and automates everyday package installation tasks for various application frameworks (i.e., React, GraphQL, Rest API, Material-UI, Jasmine / Mocha Tests).

## 🏠 Community

- First, star and watch [Meteor on GitHub](https://github.com/meteor/meteor) 
- Explore the [Meteor Forum](https://forums.meteor.com/) 
- Join our [Meteor Community Slack workspace](https://forums.meteor.com/t/awesome-meteor-list/52981) 
    - Slack bots for new and updates to Atmosphere packages, join the #packges channel 
    - Stack overflow integration  
- There is also [Meteor](https://discord.com/invite/bnf2Hju) and [Meteor Community](https://discord.com/invite/8E4SKQF) discord groups 
- Check out [Tiny Capital](https://www.tiny.com/), the wonderful Meteor investor with a history of passion for internet businesses and long-term investment
- Check out the [Meteor Wikipedia](https://en.wikipedia.org/wiki/Meteor_(web_framework)) page 
- Follow Meteor on [Twitter](https://twitter.com/meteorjs), [YouTube](https://www.youtube.com/user/MeteorVideos), [Medium](https://blog.meteor.com/), [Meetup](https://www.meetup.com/topics/meteor/) and [Facebook](https://www.facebook.com/meteorjs/) 
- Explore the [Meteor Showcase](https://www.meteor.com/showcase) 
- And get inspired by the many other [profitable businesses](https://forums.meteor.com/t/meteor-products-that-make-money/52735) 

## 🌱 Notable Open Source Projects

- [RocketChat](https://www.rocket.chat/): The ultimate Free Open Source Solution for team communications.
- [Wekan](https://github.com/wekan/wekan): The open-source kanban (inspired by Trello built with Meteor)
- [Open Kadira](https://github.com/kadira-open/kadira-server): Open source meteor monitoring tool
- [LessWrong 2.0](https://www.lesswrong.com/posts/HJDbyFFKf72F52edp/welcome-to-lesswrong-2-0): awesome discussion space, especially in the age of false information, build with VulcanJS 19 which is built on Meteor, check it out!

## 📖 Tutorials & References

- [Meteor Guide](https://guide.meteor.com/): the official Meteor Guide and your first go-to resource
- [Meteor University](https://university.meteor.com/)
- PWA Support
   – [Meteor PWA Explained](https://github.com/activitree/Meteor-PWA-Explained): Demonstrate the use of PWA and service workers in Meteor 1.8+ Project
   – [Transform any Meteor App into a PWA](https://dev.to/jankapunkt/transform-any-meteor-app-into-a-pwa-4k44)

 ## 😎 Awesome Meteor Developers

Do support the Meteor open-source community by sponsoring those awesome members (contribute what you can afford):

- Meteor Community Organization 
- Active Meteor developers:
   - zodern [Sponsor](https://github.com/sponsors/zodern)
   - storyteller [Sponsor](https://github.com/sponsors/StorytellerCZ)
   - radekmie [Sponsor](https://github.com/sponsors/radekmie)
   - copleykj [Sponsor](https://github.com/sponsors/copleykj) 
   - mitar [Sponsor](https://github.com/sponsors/mitar) 
   - wreiske [Sponsor](https://github.com/sponsors/wreiske) 
   - zimme [Sponsor](https://github.com/sponsors/zimme) 
   
## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/Meteor-Community-Packages/awesome-meteor/graphs/contributors)!
