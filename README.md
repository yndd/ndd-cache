<p align=center><a href="https://nddocs.yndd.io"><img src=https://gitlab.com/rdodin/pics/-/wikis/uploads/9f2e581a8d207a21ff024a312679a239/containerlab_export_white_ink_3?sanitize=true/></a></p>

[![Go Report](https://img.shields.io/badge/go%20report-A%2B-blue?style=flat-square&color=00c9ff&labelColor=bec8d2)](https://goreportcard.com/report/github.com/yndd/ndd-cache)
[![Doc](https://img.shields.io/badge/Docs-ndddocs.yndd.io-blue?style=flat-square&color=00c9ff&labelColor=bec8d2)](https://ndddocs.yndd.io)
[![Godoc](https://img.shields.io/badge/godoc-reference-blue.svg?style=flat-square&color=00c9ff&labelColor=bec8d2)](https://godoc.org/github.com/yndd/ndd-cache)


## Overview
 
ndd-cache is a set of go libraries to support a multi-tenant device cache based on yang 

### Requirements

- dynamic loading of yang modules at runtime -> to deal with different device releases
- multi-tentant -> be able to support multiple devices and device datastores
- validation callback to check the validity of a new config (leafref, etc)
- query/update speed
- default handling -> support fallback to defaults when the pat exists
- deal with different encodings: JSON, JSON-IETF, XML, PROTO?
- YANG 1.0/1.1

## Contributing

ndd-cache is a community driven project and we welcome contribution.

## Report a bug

For filling bugs, suggesting improvments, or requesting new feature, please open an [issue].

## Contact

Please use the following to reach members of the community:

- Discord: [discord]
- Twitter: [@yndd]
- Email: [info@yndd.io]

## Roadmap

ndd-cache goals and milestone are currently tracked in ndd's [roadmap].

## Code of conduct

## Licensing

ndd-cache is under the Apache 2.0 license.

[issue]: https://github.com/yndd/ndd-cache/issues
[roadmap]: https//github.com/yndd
[discord]: https://discord.gg/prHcBMSq
[@yndd]: https://twitter.com/yndd
[info@yndd.io]: mailto:info@yndd.io
[roadmap]: https://github.com/yndd/tbd