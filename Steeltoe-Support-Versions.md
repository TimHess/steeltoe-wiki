# Steeltoe Supported Versions

This document shows all versions of Steeltoe and their support lifecycle.

## Support Policy

Steeltoe follows the [VMware Tanzu OSS support policy](https://docs.broadcom.com/doc/tanzu-support-oss) for critical bugs and security issues.

* Major versions will be supported for up to 3 years from the release date.
* Minor versions will be supported for at least 12 months from the release date.

### Go-live Releases

Go-live releases are supported by the Steeltoe team in production. These are typically our release candidate builds, just before the generally available (GA) release.

## Released Versions

When new versions of Steeltoe are released, they are tested with the latest supported versions of .NET.
It is recommended to run the latest patch version for the targeted Steeltoe release.

### Release Support Matrix

| Steeltoe Version | Release Date       | End of Life Date | .NET Runtime Version  |
| ---------------- | ------------       | ---------------- | --------------------  |
| 3.2.x            | May 26, 2022       | May 26, 2026     | .NET Core 3.1, .NET 5 - 6 |
| 3.1.x            | July 13, 2021      | July 31, 2022    | .NET Core 3.1, .NET 5 |
| 3.0.x            | August 21, 2020    | August 31, 2023  | .NET Core 3.1 |
| 2.5.x            | October 1, 2020    | October 31, 2023 | .NET Framework 4.6.2 - 4.8, .NET Core 2.1 - 3.1 |
| 2.4.x            | November 13, 2019  | December 31, 2021| .NET Framework 4.6.1 - 4.8, .NET Core 2.1 - 3.1 |
| 2.3.x            | August 21, 2019    | December 31, 2021| .NET Framework 4.6.1 - 4.8, .NET Core 2.1 - 3.1 |
| 2.2.x            | March 15, 2019     | December 31, 2021| .NET Framework 4.6.1 - 4.8, .NET Core 2.1 - 3.1 |
| 2.1.x            | August 18, 2018    | December 31, 2021| .NET Framework 4.6.1 - 4.8, .NET Core 2.0 - 3.1 |
| 2.0.x            | February 15, 2018  | December 31, 2021| .NET Framework 4.6.1 - 4.8, .NET Core 2.0 - 3.1 |
| 1.1.x            | June 19, 2017      | August 31, 2019  | .NET Framework 4.5.2 - 4.7, .NET Core 1.0 - 1.1 |
| 1.0.x            | April 7, 2017      | August 31, 2019  | .NET Framework 4.5.2 - 4.6.2, .NET Core 1.0 - 1.1 |

> [!NOTE]
> For each release, we list the original release date, along with the .NET versions supported at that moment in time.
> These are the combinations that were confirmed to work when the release was created.
> If newer .NET versions emerge before the end-of-life date, we don't list them here.
> That doesn't mean they won't work or won't be supported, only that they aren't automatically guaranteed.

## Release Compatibility

The Steeltoe team is aware of the need for stability and backward compatibility between releases.
Our goal is to keep backward compatibility across all minor and maintenance releases (for example: 3.1.3 should work with 3.1.2, 3.1.1, 3.1.0).
Major releases are utilized to remove all deprecated code and make breaking changes when necessary for code optimization, enhancements, architecture changes, and redesign.
We strive to keep all compatibility changes/breakages to major releases only.
There is a rare chance that we might be forced to break compatibility in a minor release, but we will be sure to be clear of our reasons for doing so.

## .NET Runtime Support

Steeltoe libraries depend on .NET runtimes, so we follow the [.NET and .NET Core Support Policy](https://dotnet.microsoft.com/platform/support/policy/dotnet-core).
Once a runtime is out of support, Steeltoe will also discontinue support for running our libraries on those runtime versions.
