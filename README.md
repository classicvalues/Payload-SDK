# DJI Payload SDK (PSDK)

![](https://img.shields.io/badge/version-V3.2.0-orange.svg)
![](https://img.shields.io/badge/platform-linux_|_rtos-green.svg)
![](https://img.shields.io/badge/license-MIT-blue.svg)

## What is the DJI Payload SDK?

The DJI Payload SDK(PSDK), is a development kit provided by DJI to support developers to develop payload that can be
mounted on DJI drones. Combined with the X-Port, SkyPort or extension port adapter, developers can obtain the
information or other resource from the drone. According to the software logic and algorithm framework designed by the
developer, users could develop payload that can be mounted on DJI Drone, to perform actions they need, such as Automated
Flight Controller, Payload Controller, Video Image Analysis Platform, Mapping Camera, Megaphone And Searchlight, etc.

## Documentation

For full documentation, please visit
the [DJI Developer Documentation](https://developer.dji.com/doc/payload-sdk-tutorial/en/whats-new/). Documentation
regarding the code can be found in the [PSDK API Reference](https://developer.dji.com/doc/payload-sdk-api-reference/en/)
section of the developer's website. Please visit
the [Latest Version Information](https://developer.dji.com/doc/payload-sdk-tutorial/en/whats-new/version-announcement.html)
to get the latest version information.

## Latest Release

PSDK 3.2.0 was released on 08 August 2022. This version of Payload SDK mainly add some features support and fixed some
bugs. Please refer to the release notes for detailed changes list.

* Add the support of standard speaker on M300 RTK, M30/M30T Pilot
* Add the support of the mapping between the speaker with the remote controller button on M300 RTK, M30/M30T Pilot
* Add function support for H20N on M300 RTK
* Add infrared zoom function support of H20T on M300 RTK
* Fix the occasional problem of the Camera Livestream can not be subscribed on M30/M30T
* Fix the problem of some interfaces of camera management run error on M30/M30T
* Fix the problem of the infrared code stream can not be obtained on M30/M30T
* Fix the problem of RTOS platform data subscription crash on M30/M30T
* Fix the occasional problem of abnormal media download function on M300 RTK
* Fix the occasional problem of abnormal SDK interconnection function on M300 RTK
* Fix the occasional problem of the PSDK payload name displays abnormally
* Fix the coordinate system problem of the gimbal angle of the data subscription function
* Optimize the compilation dependency problems of third-party dependent libraries

## License

Payload SDK codebase is MIT-licensed. Please refer to the LICENSE file for detailed information.

## Contributing

Please read the following guidelines before starting work on a pull request.

#### Summary of the guidelines:

* One pull request per issue;
* Choose the right base branch;
* Clean up "oops" commits before submitting;
* Follow the coding style by "doc/dji_sdk_code_style"

## Support

You can get official support from DJI and the community with the following methods:

- Post questions on Developer Forum
  * [DJI SDK Developer Forum(Cn)](https://djisdksupport.zendesk.com/hc/zh-cn/community/topics)
  * [DJI SDK Developer Forum(En)](https://djisdksupport.zendesk.com/hc/en-us/community/topics)
- Submit a request describing your problem on Developer Support
  * [DJI SDK Developer Support(Cn)](https://djisdksupport.zendesk.com/hc/zh-cn/requests/new)
  * [DJI SDK Developer Support(En)](https://djisdksupport.zendesk.com/hc/en-us/requests/new)

You can also communicate with other developers by the following methods:

- Post questions on [**Stackoverflow**](http://stackoverflow.com) using [**
  dji-sdk**](http://stackoverflow.com/questions/tagged/dji-sdk) tag