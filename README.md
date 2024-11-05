# API (RFC)

The manufacturing information ecosystem benefits from the contributions of many players, over multiple decades of technology evolution. While this diversity creates a lot of platform choice for manufacturers, it has the opposite effect on the creation of app value. Application developers must choose which platforms to build against, with no hope of portability between them. Apps create information value by consuming the data available in a platform, and rendering it in ways that are helpful to end users -- analytics, visualization, notification, machine learning... all of these need contextualized data, and all end up abstracted by an underlying platform (be it an Historian, MES, MOM, EMI, or broker or server).

This initial proposal is to recommend the creation of a common API, consisting of a base set of primitives that a wide array of platforms can implement to commoditize this access to data. Such a common API does not prevent platform vendors from differentiating on their capabilities, but it would encourage a proliferation of portable apps that could help spur adoption of such platforms, and create a vibrant marketplace of apps bringing value to end-users.

The analogies in other industries should be obvious: Apple and Android users benefit from common APIs for access to device and platform capabilities exposed to app developers that have led to App Stores full of creative, useful, and enjoyable app experiences. Those platform vendors have benefited, but more importantly, the user has benefited.

The authors of this document seek your feedback on how to move toward common interfaces for common information functionality. This proposal has been created by industry participants with experience developing or using manufacturing information platforms such as those provided by Rockwell Automation, OSI Pi, ThinkIQ, ThingWorx and HighByte, are deep users and often contributors to the ecosystems around OPC UA, Asset Administration Shell, MQTT and Sparkplug/B, and have more than 5 decades of combined experience in designing, developing, implementing and using manufacturing information software. The document has also benefited from a private review stage, where it was shared with more than 60 members of CESMII to gather their feedback. In this public stage,  this document is offered RFC-style, not as a perscription, but as an invitation. Please review it, consider how you might use or implement it in the tools that you are familiar with, and provide us feedback on how we can improve it -- within the scope it defines.

The prefered feedback mechanism is to use GitHub issues, where input can be tracked, discussed, and categorized as an improvement or a feature request. If you desire to provide feedback, but cannot use GitHub issues, please email us: devops@cesmii.org

## GraphQL API (Current)

The current API, based on GraphQL as implemented by ThinkIQ, is still available here: [https://github.com/cesmii/graphql-api](https://github.com/cesmii/graphql-api)
