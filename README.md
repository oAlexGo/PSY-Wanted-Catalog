# PSY Wanted Catalog

This public repository contains only the PSY Wanted Store MGU metadata feed and its attribution information. It does not contain the Store source code, BMW SDK files, OAP bundles, or copied app packages.

The `catalog` GitHub release will publish a native MGU `catalog.json` asset after PSY Update Engine validates installable package records. The MGU reads that release anonymously over HTTPS. App packages remain hosted by their upstream publishers and are linked by URL.

Each published entry preserves its upstream repository, exact source commit, license and license URL. Its package size and SHA-256 are checked by the MGU updater before the owner chooses an install or update. Availability is published only for packages with validated ID7/ID8 compatibility and a supported install layout.

The private source repository publishes the catalog on its six-hour schedule. The automation publishes only `catalog.json` and this README.