Awesome GameLift [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===============

> A curated list of awesome packages, articles, and other cool resources from the GameLift community.
> [GameLift](https://aws.amazon.com/gamelift/) provides solutions for hosting session-based multiplayer game servers in the cloud, including a fully managed service for deploying, operating, and scaling game servers, based on AWS global computing infrastructure.

You might also like [Awesome AWS](https://github.com/donnemartin/awesome-aws).

## General resources

- [Official site](https://aws.amazon.com/gamelift/)
- [SDKs](https://aws.amazon.com/gamelift/getting-started/#Developer_Resources_and_Documentation) ([release notes](https://docs.aws.amazon.com/gamelift/latest/developerguide/release-notes.html))
  - [The Amazon GameLift Plugin for Unity](https://github.com/aws/amazon-gamelift-plugin-unity)
- [Documentation](https://docs.aws.amazon.com/gamelift/index.html)
- [AWS SDK for .NET Developer Guide](https://docs.aws.amazon.com/sdk-for-net/latest/developer-guide/quick-start.html)
- Twitter accounts: [@AmazonGameLift](https://twitter.com/AmazonGameLift) - [@AWSGameTech](https://twitter.com/AWSGameTech)
- YouTube channels: [AWS Online Tech Talks](https://www.youtube.com/channel/UCT-nPlVzJI-ccQXlxjSvJmw) - [AWS Game Tech](https://www.youtube.com/channel/UCQH55cT_em5E8XU2J8erMKA)
- [Blog](https://aws.amazon.com/blogs/gametech/category/game-development/amazon-gamelift/)
- [re:Post Q&A](https://repost.aws/tags/TAF8-XUqojTsadH5jSz3IfGQ/amazon-game-lift) ([~~old forum~~](https://forums.awsgametech.com/c/amazon-gamelift/7))
- [GitHub topic](https://github.com/topics/gamelift)
- [Stack Overflow tag [amazon-gamelift]](https://stackoverflow.com/questions/tagged/amazon-gamelift)
- [Other resources](#resources)

## Solutions

### GameLift Realtime Servers (NodeJS) 

- [node-gameloop](https://github.com/tangmi/node-gameloop) - A game loop for NodeJS applications, uses a combination of setTimeout and setImmediate to achieve accurate update ticks with minimal CPU usage.
- [Unofficial Typescript definitions for GameLift realtime server API](https://github.com/jcular/unofficial-gamelift-realtime-server-api) - Make Realtime interface work with Typescript.

### Integrations

- [Defold extension-gamelift](https://github.com/defold/extension-gamelift) - GameLift Amazon GameLift extension for the Defold game engine. Run Defold on the server with GameLift SDK support.
- [GomeLift](https://github.com/neguse/gomelift) - Unofficial GameLift Server SDK in Go.
- [GameLift Server SDK RS](https://github.com/ZaMaZaN4iK/aws-gamelift-server-sdk-rs) - Unofficial GameLift Server SDK in Rust

### Devops

- [amazon-gamelift-remote-plus](https://github.com/aws-samples/amazon-gamelift-remote-plus) - A tool creates remote connections to access fleet instances using Secure Shell (SSH) for fleets running Linux, and Remote Desktop Protocol (RDP) for fleets running Windows.
- [fleetiq-adapter-for-agones](https://github.com/awslabs/fleetiq-adapter-for-agones) - Allows you to run containerized game servers on Spot instances while decreasing the likelihood of Spot interruptions by using Agones and Gamelift FleetIQ.

## Resources

### Articles

#### Official articles

- [Creating a Battle Royale Game Using Unity and Amazon GameLift](https://aws.amazon.com/blogs/gametech/creating-a-battle-royale-game-using-unity-and-amazon-gamelift/) ([Source Repo](https://github.com/aws-samples/amazon-gamelift-ultrafrogroyale-large-match-sample))

#### Other articles

### Samples

#### Official samples
- [GameLift Example for Unity with Serverless Backend](https://github.com/aws-samples/aws-gamelift-and-serverless-backend-sample) - A GameLift example with a Serverless backend service that helps you get started with GameLift development and leverages deployment automation and Infrastructure as Code. Works on MacOS, Windows as well as mobile platforms.
- [amazon-gamelift-unity](https://github.com/aws-samples/amazon-gamelift-unity) - A sample code shows how to set up a basic GameLift server and client for games using the Unity Game Engine.
- [aws-gamelift-sample (with FlexMatch)](https://github.com/aws-samples/aws-gamelift-sample) - A sample Gomoku board game project using Amazon GameLift and AWS serverless services including DynamoDB, Lambda, SQS, S3, and so on.
- [Game Server Hosting on Amazon Elastic Container Service with Amazon GameLift FleetIQ](https://github.com/aws-samples/amazon-gamelift-fleetiq-with-amazon-ecs) - A sample solution on how to scale a fleet of game servers on Elastic Container Service and match players to game sessions using a Serverless backend. Game Sessions are managed by Amazon GameLift FleetIQ. All resources are deployed with Infrastructure as Code using CloudFormation, Serverless Application Model, Docker and bash scripts.
- [GameLift Example for Unity with Serverless Backend](https://github.com/aws-samples/aws-gamelift-and-serverless-backend-sample) - A simple 3D game GameLift example with a Serverless backend service designed especially for getting started with MacOS and mobile development and leveraging deployment automation and Infrastructure as Code.
- [megafrogRace-gameLift-realtime-server-sample](https://github.com/aws-samples/megafrograce-gamelift-realtime-servers-sample) - A sample 2D racing game using Amazon GameLift (Realtime Servers) and AWS services including AWS Lambda and Amazon Cognito.
- [Persistent Game Server with Amazon GameLift](https://github.com/aws-samples/amazon-gamelift-persistent-sample) - A sample includes how to implement persistent game server based on Amazon GameLift.

Archived
- [amazon-gamelift-largematch-sample-ultrafrogroyale](https://github.com/aws-samples/amazon-gamelift-ultrafrogroyale-large-match-sample) - A small game built with Unity to demonstrate how to use the new Amazon GameLift large match features. *(using archived mobile SDK for unity)*

#### Other samples

- [Unity GameLift/Mirror Sample](https://github.com/joaoborks/unity-gamelift-mirror-sample) - Features a working multiplayer sample using AWS GameLift and Mirror on Unity. Supports IL2CPP and mobile devices.

### Videos

#### Official videos

- [Dedicated Servers with Amazon GameLift AWS Game Tech Series](https://www.youtube.com/playlist?list=PLuGWzrvNze7KQO5mREeae2eIR8rJws0At).
- [Getting Started with Amazon GameLift FleetIQ](https://www.youtube.com/watch?v=p07ueG4A3qA) by AWS Online Tech Talks.

#### Other videos

- [Better together: running containerized game servers with Agones and GameLift FleetIQ](https://www.youtube.com/watch?v=RvBjgKME21U).
- [Unity + Amazon GameLift RealTime Servers Series](https://www.youtube.com/playlist?list=PLOtt3_R1rR9VMkqZvMF-39TeKrbpKZocW) by [Battery Acid](https://www.youtube.com/channel/UCtTEc7bBzP7Tq5U2Jzf5lPw).
- [Unity + GameLift Custom Server Series](https://www.youtube.com/playlist?list=PLOtt3_R1rR9XlvhJZXtiHQuIkisdXIxlc) by [Battery Acid](https://www.youtube.com/channel/UCtTEc7bBzP7Tq5U2Jzf5lPw).

### Made with GameLift

- [For Honor](https://aws.amazon.com/blogs/gametech/for-honor-friday-the-13th-the-game-move-from-p2p-to-the-cloud-to-improve-player-experience/) by Ubisoft.
- [Ninjala](https://aws.amazon.com/blogs/gametech/amazon-gamelift-announces-general-availability-of-six-new-regions/) by GungHo.

## Contribute

Contributions are always welcome!
Please read the [contribution guidelines](./CONTRIBUTING.md) first.

## License

The project is licensed under [BSD 3-Clause License](./LICENSE).

AWS and Amazon GameLift are trademarks and brands of Amazon Technologies.

> DISCLAIMER: Awesome-GameLift is an open-source project, not an official project provided by Amazon Technologies.
