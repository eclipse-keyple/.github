# Eclipse Keyple
Raw repository of the 'Eclipse Keyple' project (referencing all the components).

More information can be found on [keyple.org](http://keyple.org).

## Repositories

-   Project web site: [https://github.com/eclipse/keyple-website](https://github.com/eclipse/keyple-website)
-   Continuous Integration:
    -   CI configuration [https://github.com/eclipse/keyple-ops/](https://github.com/eclipse/keyple-ops/)
    -   Integration test [https://github.com/eclipse/keyple-integration-java-test](https://github.com/eclipse/keyple-integration-java-test)
-   Implementation examples: [https://github.com/eclipse/keyple-java-example](https://github.com/eclipse/keyple-java-example)
-   Java components:
    -   until version 1.0.0, single repository [https://github.com/eclipse/keyple-java](https://github.com/eclipse/keyple-java) (archived repository)
    -   from version 2.0.0, several repositories: status on [https://keyple.org/repositories-dashboard/](https://keyple.org/repositories-dashboard/)
        -   external standardized Calypso Terminal API:
            -   **Reader API**
                -   code [https://github.com/calypsonet/calypsonet-terminal-reader-java-api](https://github.com/calypsonet/calypsonet-terminal-reader-java-api)
                -   doc [https://calypsonet.github.io/calypsonet-terminal-reader-java-api/](https://calypsonet.github.io/calypsonet-terminal-reader-java-api/)
            -   Card API
                -   code [https://github.com/calypsonet/calypsonet-terminal-card-java-api](https://github.com/calypsonet/calypsonet-terminal-card-java-api)
                -   doc [https://calypsonet.github.io/calypsonet-terminal-card-java-api/](https://calypsonet.github.io/calypsonet-terminal-card-java-api/)
            -   **Calypso API**
                -   code [https://github.com/calypsonet/calypsonet-terminal-calypso-java-api](https://github.com/calypsonet/calypsonet-terminal-calypso-java-api) (main API for Calypso terminal application impementation)
                -   doc [https://calypsonet.github.io/calypsonet-terminal-calypso-java-api/](https://calypsonet.github.io/calypsonet-terminal-calypso-java-api/)
        -   Core components:
            -   **Keyple Service** (service implementing Reader API & Card API)
                -   code [https://github.com/eclipse/keyple-service-java-lib](https://github.com/eclipse/keyple-service-java-lib)
                -   doc [https://eclipse.github.io/keyple-service-java-lib/](https://eclipse.github.io/keyple-service-java-lib/)
                -   info [https://keyple.org/components-java/core/keyple-service-java-lib/](https://keyple.org/components-java/core/keyple-service-java-lib/)
            -   Plugin SPI (for pluging implementation)
                -   code [https://github.com/eclipse/keyple-plugin-java-api](https://github.com/eclipse/keyple-plugin-java-api)
                -   doc [https://eclipse.github.io/keyple-plugin-java-api/](https://eclipse.github.io/keyple-plugin-java-api/)
                -   info [https://keyple.org/components-java/core/keyple-plugin-java-api/](https://keyple.org/components-java/core/keyple-plugin-java-api/)
            -   Utility
                -   Keyple shared reference
                    -   code [https://github.com/eclipse/keyple-common-java-api](https://github.com/eclipse/keyple-common-java-api)
                    -   doc [https://eclipse.github.io/keyple-common-java-api/](https://eclipse.github.io/keyple-common-java-api/)
                    -   info [https://keyple.org/components-java/core/keyple-common-java-api/](https://keyple.org/components-java/core/keyple-common-java-api/)
                -   Helper functions
                    -   code [https://github.com/eclipse/keyple-util-java-lib](https://github.com/eclipse/keyple-util-java-lib)
                    -   doc [https://eclipse.github.io/keyple-util-java-lib/](https://eclipse.github.io/keyple-util-java-lib/)
                    -   info [https://keyple.org/components-java/core/keyple-util-java-lib/](https://keyple.org/components-java/core/keyple-util-java-lib/)
        -   Card resource manager extension
            -   code [https://github.com/eclipse/keyple-service-resource-java-lib](https://github.com/eclipse/keyple-service-resource-java-lib)
            -   doc [https://eclipse.github.io/keyple-service-resource-java-lib/](https://eclipse.github.io/keyple-service-resource-java-lib/)
            -   info [https://keyple.org/components-java/core/keyple-service-resource-java-lib/](https://keyple.org/components-java/core/keyple-service-resource-java-lib/)
        -   Distributed module (for remote card readers):
            -   for terminal operating a remote reader
                -   lib
                    -   code [https://github.com/eclipse/keyple-distributed-remote-java-lib](https://github.com/eclipse/keyple-distributed-remote-java-lib)
                    -   doc [https://eclipse.github.io/keyple-distributed-remote-java-lib/](https://eclipse.github.io/keyple-distributed-remote-java-lib/)
                -   API
                    -   code [https://github.com/eclipse/keyple-distributed-remote-java-api](https://github.com/eclipse/keyple-distributed-remote-java-api)
                    -   doc [https://eclipse.github.io/keyple-distributed-remote-java-api/](https://eclipse.github.io/keyple-distributed-remote-java-api/)
                -   info [https://keyple.org/components-java/distributed/keyple-distributed-remote-java-lib/](https://keyple.org/components-java/distributed/keyple-distributed-remote-java-lib/)
            -   for terminal interfaced with a local reader
                -   lib
                    -   code [https://github.com/eclipse/keyple-distributed-local-java-lib](https://github.com/eclipse/keyple-distributed-local-java-lib)
                    -   doc [https://eclipse.github.io/keyple-distributed-local-java-lib/](https://eclipse.github.io/keyple-distributed-local-java-lib/)
                -   API
                    -   code [https://github.com/eclipse/keyple-distributed-local-java-api](https://github.com/eclipse/keyple-distributed-local-java-api)
                    -   doc [https://eclipse.github.io/keyple-distributed-local-java-api/](https://eclipse.github.io/keyple-distributed-local-java-api/)
                -   info [https://keyple.org/components-java/distributed/keyple-distributed-local-java-lib/](https://keyple.org/components-java/distributed/keyple-distributed-local-java-lib/)
            -   common lib for network messaging
                -   code [https://github.com/eclipse/keyple-distributed-network-java-lib](https://github.com/eclipse/keyple-distributed-network-java-lib)
                -   doc [https://eclipse.github.io/keyple-distributed-network-java-lib/](https://eclipse.github.io/keyple-distributed-network-java-lib/)
                -   info [https://keyple.org/components-java/distributed/keyple-distributed-network-java-lib/](https://keyple.org/components-java/distributed/keyple-distributed-network-java-lib/)
        -   Card solution extensions:
            -   Generic card example of card extension implementation to operate a "generic" smart card solution using low-level APDU commandscommunication
                -   code [https://github.com/eclipse/keyple-card-generic-java-lib](https://github.com/eclipse/keyple-card-generic-java-lib)
                -   doc [https://eclipse.github.io/keyple-card-generic-java-lib/](https://eclipse.github.io/keyple-card-generic-java-lib/)
                -   info [https://keyple.org/components-java/card-extensions/keyple-card-generic-java-lib/](https://keyple.org/components-java/card-extensions/keyple-card-generic-java-lib/)
            -   **Calypso card** library to manage Calypso processing on a terminal (implementation of the Calypso API)
                -   code [https://github.com/eclipse/keyple-card-calypso-java-lib](https://github.com/eclipse/keyple-card-calypso-java-lib)
                -   doc [https://eclipse.github.io/keyple-card-calypso-java-lib/](https://eclipse.github.io/keyple-card-calypso-java-lib/)
                -   info [https://keyple.org/components-java/card-extensions/keyple-card-calypso-java-lib/](https://keyple.org/components-java/card-extensions/keyple-card-calypso-java-lib/)
        -   Plugins for "standardized" smartcard reader solutions:
            -   PC/SC (Windows/Linux/MacOS)
                -   code [https://github.com/eclipse/keyple-plugin-pcsc-java-lib](https://github.com/eclipse/keyple-plugin-pcsc-java-lib)
                -   doc [https://eclipse.github.io/keyple-plugin-pcsc-java-lib/](https://eclipse.github.io/keyple-plugin-pcsc-java-lib/)
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-pcsc-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-pcsc-java-lib/)
            -   Android OMAPI - to interface an 'internal' Secure Element in an Android device
                -   code [https://github.com/eclipse/keyple-plugin-android-omapi-java-lib](https://github.com/eclipse/keyple-plugin-android-omapi-java-lib)
                -   doc [https://eclipse.github.io/keyple-plugin-pcsc-java-lib/](https://eclipse.github.io/keyple-plugin-pcsc-java-lib/)
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-omapi-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-omapi-java-lib/)
            -   Android NFC - to interface an "external" Secure Element with an Android device (using NFC Reader mode)
                -   code [https://github.com/eclipse/keyple-plugin-android-nfc-java-lib](https://github.com/eclipse/keyple-plugin-android-nfc-java-lib)
                -   doc [https://eclipse.github.io/keyple-plugin-android-nfc-java-lib/](https://eclipse.github.io/keyple-plugin-android-nfc-java-lib/)
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-nfc-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-nfc-java-lib/)
            -   Reader emulation - for testing without hardware solution
                -   code [https://github.com/eclipse/keyple-plugin-stub-java-lib](https://github.com/eclipse/keyple-plugin-stub-java-lib)
                -   doc [https://eclipse.github.io/keyple-plugin-stub-java-lib/](https://eclipse.github.io/keyple-plugin-stub-java-lib/)
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-stub-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-stub-java-lib/)
-   Cpp implementation
    -   until version 0.9.0, single repository [https://github.com/eclipse/keyple-cpp](https://github.com/eclipse/keyple-cpp) (archived repository)
    -   info [https://keyple.org/components-cpp-0.9/](https://keyple.org/components-cpp-0.9/)

Please check the individual repositories for instructions for building and contributing.

## Contributing

1. [Fork](https://help.github.com/articles/fork-a-repo/) the [eclipse/keyple](https://github.com/eclipse/keyple) repository
2. Clone repository: `git clone https://github.com/[your_github_username]/keyple.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Make your changes
5. Commit your changes: `git commit -m "Add some feature" -s`
6. Push feature branch: `git push origin my-new-feature`
7. Submit a pull request

### Declared Project Licenses

This program and the accompanying materials are made available under the terms
of the Eclipse Public License v. 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

SPDX-License-Identifier: EPL-2.0

## Bugs and feature requests

Have a bug or a feature request? Please search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/eclipse/keyple/issues/new).

## Trademarks

* Eclipse Keyple and the Eclipse Keyple project are Trademarks of the Eclipse Foundation, Inc.
* Eclipse® is a Trademark of the Eclipse Foundation, Inc.
* Eclipse Foundation is a Trademark of the Eclipse Foundation, Inc.

## Copyright and license

Copyright 2020 the [Eclipse Foundation, Inc.](https://www.eclipse.org) and the [keyple authors](https://github.com/eclipse/keyple/graphs/contributors). Code released under the [Eclipse Public License Version 2.0 (EPL-2.0)](https://github.com/eclipse/keyple-website/blob/src/LICENSE).
