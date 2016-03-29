# leisurelink/alpine-haproxy

A docker image to run haproxy with dynamic config generation using consul-template.

Based on alpine, uses s6-overlay for supervision and consul-template for dynamically constructing the haproxy config (auto-reloads).

## Tags (Asset Versions)

* **1.0.0** (Alpine 3.2, S6 Overlay v1.17.2.0, haproxy 1.6.2, consul-template 0.14.0)

## License

[MIT](https://github.com/LeisureLink/alpine-base/blob/master/LICENSE)
