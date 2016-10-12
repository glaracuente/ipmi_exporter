# IPMI Exporter

[![GoDoc](https://godoc.org/github.com/lovoo/ipmi_exporter?status.svg)](https://godoc.org/github.com/lovoo/ipmi_exporter)

IPMI Exporter for prometheus.io, written in Go.

## Requirements

	* ipmitool

## Docker Usage

    docker run --privileged -d --name ipmi_exporter -p 9289:9289 lovoo/ipmi_exporter:latest

## Building

    make build

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request
