---
title: Get started with Xbox Live, for Creators
description: All the high-level steps, from joining the Creators Program, through releasing your game.
ms.assetid: 2a744405-7ee4-42b4-8f36-9916e8c3a530
ms.date: 12/13/2017
ms.topic: article
keywords: xbox live, xbox, games, uwp, windows 10, xbox one
ms.localizationpriority: medium
---

# Get started with Xbox Live, for Creators
 
The Xbox Live Creators Program allows you to quickly and directly publish your games to Xbox One and Windows 10, with a simplified certification process and no concept approval required.
If your game integrates Xbox Live and follows our [standard Store policies](https://msdn.microsoft.com/library/windows/apps/dn764944.aspx), you are ready to publish.
This article outlines the steps needed to get your game up and running with Xbox Live integration.

Xbox Live Creators Program games must be a Universal Windows Platform (UWP) application.
 For Xbox One, see [UWP on Xbox One](https://msdn.microsoft.com/windows/uwp/xbox-apps/index) and specifically [System resources for UWP apps and games on Xbox One](https://msdn.microsoft.com/windows/uwp/xbox-apps/system-resource-allocation).

Games published through the Xbox Live Creators Program do not have access to the achievements or online multiplayer services.
For a full list of supported services, see [Features supported for each developer program](../../join-dev-program/feature-comparison-table.md).


## 1. Ensure you have a title created in Partner Center

Every Xbox Live title must be defined in Partner Center before you will be able to sign-in and make Xbox Live Service calls.
See [Creating a new Creators title](create-and-test-a-new-creators-title.md).


## 2. Follow the appropriate guide to setup your IDE or game engine

You can follow the appropriate "getting started guide" for your platform and engine and learn the basics of Xbox Live as you go along:

* [Develop a Creators title with Visual Studio](../../setup-ide/creators/vs-win10/develop-creators-title-with-visual-studio.md) will show you how to link your Visual Studio project with your Xbox Live configuration in Partner Center.
* [Unity targeting Windows 10](../../setup-ide/creators/unity-win10/cr-unity-win10_nav.md) will show you how to create a new Xbox Live enabled Unity game, handle single user and multi-user sign in, add features such as leaderboards and stats, and generate a native Visual Studio project.

While Unity is the only third party game engine for which we provide documentation, The game engines [Construct (2 & 3)](https://www.scirra.com/construct2) and [Game Maker Studio](https://www.yoyogames.com/gamemaker) also have documentation to help you integrate Xbox Live into your Construct or Game Maker Studio game respectively.

* [Game Maker Studio 2 UWP now supports Xbox Live Creators Program](https://www.yoyogames.com/gamemaker/xblc) will show you how to export your Game Maker Studio projects to play on Xbox One and Windows 10 PC.
* [Using Xbox Live in UWP apps - Construct](https://www.scirra.com/tutorials/9540/using-xbox-live-in-uwp-apps) will show you how to use Xbox Live in your Construct 2 and 3 games.

For other game development engines without documented Xbox Live integration, you can still use the Xbox Live APIs to add Xbox Live to your title.
To use the Xbox Live API from your project, you can either add references to the binaries with NuGet packages or add the API source.
Adding NuGet packages makes compilation quicker while adding the source makes debugging easier.

For support using Xbox Live Services with third party game engines that are not Unity, work with the appropriate game engine staff to answer your questions.


## 3. Xbox Live concepts & testing

Once you have a title created, you should learn about the Xbox Live concepts that will affect your experience developing titles.
It's also important to test your game on all of the platforms that it will support to ensure that it behaves as expected.

- [Xbox Live service configuration for the Creators Program](../../../get-started-with-creators/xbox-live-service-configuration-creators.md)
- [Xbox Live test environment](../../../xbox-live-sandboxes.md)
- [Authorize Xbox Live accounts](authorize-xbox-live-accounts.md)


## 4. Enable Xbox Live sign-in

All Xbox Live Creators Program games must integrate Xbox Live sign-in and display the user identity (Gamertag, Gamerpic, etc.).
You can choose to automatically sign in the user or have them push a button to initiate it.
The Gamertag must be displayed once signed in so that the player can validate that they are using the right profile.

- [Social](../../../features/social/live-social-nav.md) - Friends list (People system), official and in-game clubs, activity feed (presence strings), and reputation.


## 5. Add optional Xbox Live features

Xbox Live Creators Program offers an array of features designed to help promote your game and keep gamers engaged:

- [Player Data](../../../features/player-data/live-playerdata-nav.md) (Achievements, player Stats, Leaderboards, and Featured Stats) helps drive engagement of your game by letting gamers compete to beat their friends and move up the ranks.
- [Xbox Live Cloud Storage: Connected Storage, Title Storage](../../../storage-platform/cloud-storage_nav.md) offers free save game roaming between devices so gamers can easily continue game progress between Xbox One and Windows PC.
- [Social](../../../features/social/live-social-nav.md) - Friends list (People system), official and in-game clubs, activity feed (presence strings), and reputation.


The online multiplayer, achievements, and gamerscore features are supported for Managed Partners, but not for the Creators Program.


## 6. Release your game

If you are using the Xbox Live Creators Program, then the process is no different than releasing any other UWP application:
- [Microsoft Store Policies](https://msdn.microsoft.com/library/windows/apps/dn764944.aspx) including [Gaming and Xbox Policies](https://msdn.microsoft.com/library/windows/apps/dn764944.aspx#pol_10_13)
- [Publish Windows apps](https://developer.microsoft.com/store/publish-apps)
