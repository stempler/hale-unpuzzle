# hale-unpuzzle

Mavenize [hale](https://github.com/igd-geo/hale) with [unpuzzle](https://github.com/akhikhl/unpuzzle).

Currently using [custom fork](https://github.com/stempler/unpuzzle) in order to

* include dependencies based on *Import-Package* instructions in bundle manifests
* translate bundle dependencies to existing Maven artifacts on jcenter and other repositories where possible
