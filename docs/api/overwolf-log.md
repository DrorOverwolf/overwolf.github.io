---
id: overwolf-log
title: overwolf.log API
sidebar_label: overwolf.log
---

Provides logging functions that make use of Overwolf’s internal logging system.

:::note
The overwolf.log API is an historical API that would allow the app to write logs to the disk.  
Since then, we've developed the feature of storing regular console.log/error/info calls to disk.
:::

## Methods Reference

* [overwolf.log.verbose()](#verbosemsg)
* [overwolf.log.info()](#infomsg)
* [overwolf.log.warning()](#warningmsg)
* [overwolf.log.error()](#errormsg)
* [overwolf.log.critical()](#criticalmsg)

## verbose(msg)

#### Version added: 0.78 

> Writes a verbose, debug level log message to the common log.

Parameter | Type | Description |
------------ | ------------ | ------------ |
msg	 | string | Message to write to the log file |

## info(msg)

#### Version added: 0.78 

> Writes info level log message to the common log.

Parameter | Type | Description |
------------ | ------------ | ------------ |
msg	 | string | Message to write to the log file |

## warning(msg)

#### Version added: 0.78 

> Writes warning level log message to the common log.

Parameter | Type | Description |
------------ | ------------ | ------------ |
msg	 | string | Message to write to the log file |

## error(msg)

#### Version added: 0.78 

> Writes error level log message to the common log.

Parameter | Type | Description |
------------ | ------------ | ------------ |
msg	 | string | Message to write to the log file |

## critical(msg)

#### Version added: 0.78 

> Writes critical level log message to the common log.

Parameter | Type | Description |
------------ | ------------ | ------------ |
msg	 | string | Message to write to the log file |