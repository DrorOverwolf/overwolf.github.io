---
id: overwolf-games-events-hunt-showdown
title: Hunt Showdown Game Events
sidebar_label: Hunt: Showdown
---

Please read the [overwolf.games.events](overwolf-games-events) documentation page to learn how to use Overwolf game events.

:::important Game ID
21328
:::

## Sample Apps
* [Hunt Showdown game events sample app](https://github.com/overwolf/events-sample-apps)

## Available Features

* [gep_internal](#gep_internal)
* [game_info](#game_info)

## Game event status

It is highly recommended to communicate errors and warnings to app users. 

Check the current game event status [here](../status/all). Alternately, you can easily check that status from your app itself, [using our API](../topics/howto-check-events-status-from-app).

## `gep_internal`

### Info Updates

key          | Category    | Values                    | Notes                 | Since GEP Ver. |
------------ | ------------| ------------------------- | --------------------- | ------------- | 
gep_internal | gep_internal| Local + Public version number|See [notes](#gep_internal-note)|   143.0       |

#### *gep_internal* note

Data Example:

```json
{"info":{"gep_internal":{"version_info":"{"local_version":"157.0.1","public_version":"157.0.1","is_updated":true}"}},"feature":"gep_internal"}
```

## `game_info`

### Info Updates

key          | Category    | Values                    | Notes                 | Since GEP Ver. |
------------ | ------------| ------------------------- | --------------------- | ------------- | 
scene | game_info | The name of the current scene. |See [notes](#scene-note) |   190.0       |

#### *scene* note

Data Example:

```json
{"feature":"game_info","category":"game_info","key":"scene","value":"Lobby"}
```
List of possible values:
* OfflineLobby
* Lobby
* Leaving
* Loading
* Game
