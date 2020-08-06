<!-- AUTOGENERATED BY glean_parser.  DO NOT EDIT. -->

# Metrics
This document enumerates the metrics collected by this project.
This project may depend on other projects which also collect metrics.
This means you might have to go searching through the dependency tree to get a full picture of everything collected by this project.

# Pings

 - [launch](#launch)


## launch

This ping is sent when Firefox Reality bootstrap finishes its task of asking Firefox desktop to launch and before the bootstrap is quit.


This ping includes the [client id](https://mozilla.github.io/glean/book/user/pings/index.html#the-client_info-section).

**Data reviews for this ping:**

- <https://github.com/MozillaReality/FirefoxRealityPC/pull/198#issuecomment-657786864>

**Bugs related to this ping:**

- <https://github.com/MozillaReality/FirefoxRealityPC/pull/198>

The following metrics are added to the ping:

| Name | Type | Description | Data reviews | Extras | Expiration |
| --- | --- | --- | --- | --- | --- |
| distribution.channel_name |[string](https://mozilla.github.io/glean/book/user/metrics/string.html) |The distribution channel name of this application. We use this field to recognize Firefox Reality is distributed to which channels, such as htc, etc.  |[1](https://github.com/MozillaReality/FirefoxRealityPC/pull/198#issuecomment-657786864)||2021-01-01 |
| distribution.install_from |[string](https://mozilla.github.io/glean/book/user/metrics/string.html) |The way of users gets Firefox desktop for running with Firefox Reality, such as embedded, downloaded, etc.  |[1](https://github.com/MozillaReality/FirefoxRealityPC/pull/198#issuecomment-657786864)||2021-01-01 |
| launch.entry_method |[string](https://mozilla.github.io/glean/book/user/metrics/string.html) |Determining how a user launches Firefox Reality application, such as system_button, library, gaze, etc.  |[1](https://github.com/MozillaReality/FirefoxRealityPC/pull/198#issuecomment-657786864)||2021-01-01 |


<!-- AUTOGENERATED BY glean_parser.  DO NOT EDIT. -->
