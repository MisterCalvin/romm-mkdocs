---
title: Generate API Keys
---

## IGDB

To access the IGDB API you'll need a Twitch account and a valid phone number for 2FA verification. Up-to-date instructions are available in the [IGDB API documentation](https://api-docs.igdb.com/#account-creation). When registering your application in the Twitch Developer Portal, fill out the form like so:

* Name: Something **unique or random** like `correct-horse-battery-staple` or `KVV8NDXMSRFJ2MRNPNRSL7GQT`
* OAuth Redirect URLs: `localhost`
* Category: `Application Integration`
* Client Type: `Confidential`

!!! important "Important"
    **The name you pick has to be unique! Picking an existing name will fail silently, with no error messages. We recommend using `romm-<random hash>`, like `romm-3fca6fd7f94dea4a05d029f654c0c44b`**

Note the client ID and secret that appear on screen, and use them to set `IGDB_CLIENT_ID` and `IGDB_CLIENT_SECRET` in your environment variables.

|![IGDB_Creation](assets/images/igdb-register-app.png)|![IGDB_Secret](assets/images/igdb-client-details.png)|
|---|---|

## MobyGames

To access the MobyGames API, [create a MobyGames account](https://www.mobygames.com/user/register/) and then visit your profile page. Click the **API** link under your user name to sign up for an API key. Copy the key shown and use it to set `MOBYGAMES_API_KEY`.

!!! important "Important"
    **MobyGames API became a [paid feature](https://www.mobygames.com/info/api/#non-commercial). Any existing key can be used as usual, but any new API key created will be under a paywall**


## ScreenScraper

To access the ScreenScraper API, create a [ScreenScraper](https://www.screenscraper.fr/membreinscription.php) and copy the **user** and **password** you just created to `SCREENSCRAPER_USER` and `SCREENSCRAPER_PASSWORD` respectively.

## SteamGridDB

To access steamGridDB API, you need to login into their [website](https://www.steamgriddb.com/) with a [steam account](https://store.steampowered.com/join). Once logged in, go to your [API tab under the preferences page](https://www.steamgriddb.com/profile/preferences/api). Copy the key shown and use it to set `STEAMGRIDDB_API_KEY`.
