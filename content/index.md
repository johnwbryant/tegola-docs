---
date: 2016-08-30T00:11:02+01:00
title: Welcome to Tegola
type: index
weight: 0
---

Tegola is a high performance Mapbox Vector Tile server written in [Go](https://golang.org). In a nutshell, Tegola takes geospatial data and slices it into vector tiles that can be efficiently delivered to any client. Tegola is creating and serving the vector tiles in the following map of San Diego, California:


{{< map >}}


### Tegola is:

- **Simple to setup.** All you need is the Tegola binary and a config file.
- **Extensible.** Tegola is designed to support multiple data providers. Currently supports PostGIS.
- **Open source.** Tegola is open source and hosted on Github.
- **Parallelized.** Tegola uses all available CPUs.
- **Written in Go.** Go allows Tegola to be highly concurrent, lightweight and easy to deploy.
- **MIT Licensed.** Tegola comes with the very liberal MIT license.