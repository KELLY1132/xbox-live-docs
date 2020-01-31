---
title: What's new for the Xbox Live SDK - March 2017
description: What's new for the Xbox Live SDK - March 2017
ms.assetid: 03180585-6f87-4929-acfc-750bd78988a0
ms.date: 04/04/2017
ms.topic: article
keywords: xbox live, xbox, games, uwp, windows 10, xbox one
ms.localizationpriority: medium
---
# What's new for the Xbox Live SDK - March 2017

Please see the [What's New - December 2016](1612-whats-new.md) article for what was added in the December 2016 release.


## Xbox Services API


### Title-managed Player Data

We have introduced a simplified Stats API.  Traditionally you had to send events corresponding to stat rules defined at Partner Center and these would update the stat values in the cloud.  This model is called _event-based Stats_.

With _title-managed Stats_, your title is in control of your stat values.  You simply call an API with the most recent stat value, and that gets sent to the service directly without the need for events.  This uses the new `StatsManager` API and you can read more in [Title-managed Stats & Leaderboards](../features/player-data/stats-leaderboards/title-managed/live-statslb-tm-nav.md).


### GitHub

Xbox Live API (XSAPI) is now available on GitHub at [https://github.com/Microsoft/xbox-live-api](https://github.com/Microsoft/xbox-live-api).  Using the binaries that come with the XDK or as NuGet packages is still recommended, however you are welcome to use the source and we welcome source code contributions.  


## Xbox Live Creators Program

The Xbox Live Creators Program is a developer program offering a subset of Xbox Live functionality to a broader developer audience.  If you are already in the Managed Partners Program, this will not have any impact on you.

See [Choosing an Xbox Live developer program](../get-started/join-dev-program/developer-program-overview.md).


## Documentation

There are the following revised or new articles.

| Article | Description |
|---------|-------------|
| [Xbox Live service configuration IDs, for Managed Partners](../test-release/portal-config/live-service-config-ids-mp.md) | Updated information on doing service configuration for your Xbox Live Title. |
| [Configure Xbox Live in Unity](../get-started/setup-ide/creators/unity-win10/configure-xbox-live-in-unity.md) | New information on Unity setup for Xbox Live Creators Program developers. |
| [Xbox Live Sandboxes overview](../test-release/sandboxes/live-setup-sandbox.md) | A simplified guide to Xbox Live sandboxes and content isolation. |
| [Xbox Live test accounts](../test-release/test-accounts/live-test-accounts.md) | Information about how test accounts work, and how to create them on Partner Center. |
