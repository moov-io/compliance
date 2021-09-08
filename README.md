[![Moov Banner Logo](https://user-images.githubusercontent.com/20115216/104214617-885b3c80-53ec-11eb-8ce0-9fc745fb5bfc.png)](https://github.com/moov-io)

<p align="center">
  <a href="https://moov-io.github.io/compliance/">Project Documentation</a>
  ·
  <a href="https://slack.moov.io/">Community</a>
  ·
  <a href="https://moov.io/blog/">Blog</a>
  <br>
  <br>
</p>

[![Repo Size](https://img.shields.io/github/languages/code-size/moov-io/compliance?label=project%20size)](https://github.com/moov-io/compliance)
[![Apache 2 License](https://img.shields.io/badge/license-Apache2-blue.svg)](https://raw.githubusercontent.com/moov-io/compliance/master/LICENSE)
[![Slack Channel](https://slack.moov.io/badge.svg?bg=e01563&fgColor=fffff)](https://slack.moov.io/)
[![GitHub Stars](https://img.shields.io/github/stars/moov-io/compliance)](https://github.com/moov-io/compliance)
[![Twitter](https://img.shields.io/twitter/follow/moov?style=social)](https://twitter.com/moov?lang=en)

# moov-io/compliance
Moov's mission is to give developers an easy way to create and integrate bank processing into their own software products. Our open source projects are each focused on solving a single responsibility in financial services and designed around performance, scalability, and ease of use.

Compliance a repository of community maintained compliance templates. The templates consist of policies, procedures, and narratives. The templates are created in a way that allows them to be tied to specific requirements within common compliance standards. Adherence to one or more compliance standards is common place for our community. The purpose of this project is make it easier for the community to comply with standards driven my regulation, industry, and clients.

## Table of contents

- [Project status](#project-status)
- [Usage](#usage)
- [Learn about compliance](#learn-about-compliance)
- [FAQ](#faq)
- [Getting help](#getting-help)
- [Supported and tested platforms](#supported-and-tested-platforms)
- [Contributing](#contributing)
- [Related projects](#related-projects)

## Project status

Moov compliance is actively being developed. Please star the project if you are interested in its progress. The project currently supports SOC2 and will in the near future support PCI. Contributions for expansion across other compliance standards globally are welcomed and encouraged. If you have layers above the templates to simplify generation or found bugs we would appreciate an issue or pull request. Thanks!

## Usage

The compliance project utilizes [Comply](https://github.com/strongdm/comply) as a means to render the Markdown templates. This project has been forked to [comply-fork](https://github.com/moov-io/comply-fork). Please use the forked version of Comply as the orignal repo is not consistently maintained. When Comply is initiated, it will create a local directory structure. Markdown files can be pulled from GitHub and placed in the appropriate directory ie. a policy in the policies directory.

## Learn about Compliance

- [PCI](https://www.pcisecuritystandards.org/)
- [Intro to SOC](https://en.wikipedia.org/wiki/System_and_Organization_Controls)

## FAQ
<details open="true">
<summary ><b>Will this project be expanded to include more compliance standards</b></summary>
Yes! We would like expand beyond PCI and SOC</a>.
</details>
<details open="true">
<summary><b>Is my company specifice information being saved somewhere?</b></summary>
No! Please take care to keep your company specific templates local to your internal repos.
</details>
<details open="true">

## Getting help

 channel | info
 ------- | -------
 [Project Documentation](https://moov-io.github.io/compliance/) | Our project documentation available online.
Twitter [@moov](https://twitter.com/moov)	| You can follow Moov.io's Twitter feed to get updates on our project(s). You can also tweet us questions or just share blogs or stories.
[GitHub Issue](https://github.com/moov-io/compliance/issues/new) | If you are able to reproduce a problem please open a GitHub Issue under the specific project that caused the error.
[moov-io slack](https://slack.moov.io/) | Join our slack channel to have an interactive discussion about the development of the project.

## Supported and tested platforms

- macOS
- 64-bit Linux (Ubuntu, Debian) and Windows TDB

## Contributing

Yes please! Please review our [Contributing guide](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) to get started! Check out our [issues for first time contributors](https://github.com/moov-io/compliance/contribute) for something to help out with.


## Related projects
As part of Moov's initiative to offer open source fintech infrastructure, we have a large collection of active projects you may find useful:

- [Moov Watchman](https://github.com/moov-io/watchman) offers search functions over numerous trade sanction lists from the United States and European Union.

- [Moov Fed](https://github.com/moov-io/fed) implements utility services for searching the United States Federal Reserve System such as ABA routing numbers, financial institution name lookup, and FedACH and Fedwire routing information.

- [Moov Wire](https://github.com/moov-io/wire) implements an interface to write files for the Fedwire Funds Service, a real-time gross settlement funds transfer system operated by the United States Federal Reserve Banks.

- [Moov Image Cash Letter](https://github.com/moov-io/imagecashletter) implements Image Cash Letter (ICL) files used for Check21, X.9 or check truncation files for exchange and remote deposit in the U.S.

- [Moov Metro 2](https://github.com/moov-io/metro2) provides a way to easily read, create, and validate Metro 2 format, which is used for consumer credit history reporting by the United States credit bureaus.


## License

Apache License 2.0 - See [LICENSE](LICENSE) for details.
