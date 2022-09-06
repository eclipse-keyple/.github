# Eclipse Keyple
Raw repository of the 'Eclipse Keyple' project (referencing all the components).

More information can be found on [keyple.org](http://keyple.org).

## Repositories

-   Project web site: [https://github.com/eclipse/keyple-website](https://github.com/eclipse/keyple-website)
-   Continuous Integration:
    -   CI configuration [https://github.com/eclipse/keyple-ops/](https://github.com/eclipse/keyple-ops/)
    -   Integration test [https://github.com/eclipse/keyple-integration-java-test](https://github.com/eclipse/keyple-integration-java-test)
-   Implementation examples:
    -   for Java [https://github.com/eclipse/keyple-java-example](https://github.com/eclipse/keyple-java-example)
    -   for C++ [https://github.com/eclipse/keyple-cpp-example](https://github.com/eclipse/keyple-cpp-example)
-   Meta scripts to download & build Keyple C++ components [https://github.com/eclipse/keyple-cpp-meta](https://github.com/eclipse/keyple-cpp-meta)
-   Components from version 2.x (several repositories: status on [https://keyple.org/repositories-dashboard/](https://keyple.org/repositories-dashboard/)):
    -   external standardized Calypso Terminal API:
        -   **Reader API**
            -   info [https://terminal-api.calypsonet.org/apis/calypsonet-terminal-reader-api/](https://terminal-api.calypsonet.org/apis/calypsonet-terminal-reader-api/)
            -   Java doc [https://calypsonet.github.io/calypsonet-terminal-reader-java-api/](https://calypsonet.github.io/calypsonet-terminal-reader-java-api/)
            -   Java code [https://github.com/calypsonet/calypsonet-terminal-reader-java-api](https://github.com/calypsonet/calypsonet-terminal-reader-java-api)
            -   C++ doc [https://calypsonet.github.io/calypsonet-terminal-reader-cpp-api/](https://calypsonet.github.io/calypsonet-terminal-reader-cpp-api/)
            -   C++ code [https://github.com/calypsonet/calypsonet-terminal-reader-cpp-api](https://github.com/calypsonet/calypsonet-terminal-reader-cpp-api)
        -   Card API
            -   info [https://terminal-api.calypsonet.org/apis/calypsonet-terminal-card-api/](https://terminal-api.calypsonet.org/apis/calypsonet-terminal-card-api/)
            -   Java doc [https://calypsonet.github.io/calypsonet-terminal-card-java-api/](https://calypsonet.github.io/calypsonet-terminal-card-java-api/)
            -   Java code [https://github.com/calypsonet/calypsonet-terminal-card-java-api](https://github.com/calypsonet/calypsonet-terminal-card-java-api)
            -   C++ doc [https://calypsonet.github.io/calypsonet-terminal-card-cpp-api/](https://calypsonet.github.io/calypsonet-terminal-card-cpp-api/)
            -   C++ code [https://github.com/calypsonet/calypsonet-terminal-card-cpp-api](https://github.com/calypsonet/calypsonet-terminal-card-cpp-api)
        -   **Calypso API** (the main API for Calypso terminal application implementation)
            -   info [https://terminal-api.calypsonet.org/apis/calypsonet-terminal-calypso-api/](https://terminal-api.calypsonet.org/apis/calypsonet-terminal-calypso-api/)
            -   Java doc [https://calypsonet.github.io/calypsonet-terminal-calypso-java-api/](https://calypsonet.github.io/calypsonet-terminal-calypso-java-api/)
            -   Java code [https://github.com/calypsonet/calypsonet-terminal-calypso-java-api](https://github.com/calypsonet/calypsonet-terminal-calypso-java-api) (main API for Calypso terminal application impementation)
            -   C++ doc [https://calypsonet.github.io/calypsonet-terminal-calypso-cpp-api/](https://calypsonet.github.io/calypsonet-terminal-calypso-cpp-api/)
            -   C++ code [https://github.com/calypsonet/calypsonet-terminal-calypso-cpp-api](https://github.com/calypsonet/calypsonet-terminal-calypso-cpp-api)
        -   Core components:
            -   **Keyple Service** (service implementing Reader API & Card API)
                -   info [https://keyple.org/components-java/core/keyple-service-java-lib/](https://keyple.org/components-java/core/keyple-service-java-lib/)
                -   Java doc [https://eclipse.github.io/keyple-service-java-lib/](https://eclipse.github.io/keyple-service-java-lib/)
                -   Java code [https://github.com/eclipse/keyple-service-java-lib](https://github.com/eclipse/keyple-service-java-lib)
                -   C++ doc [https://eclipse.github.io/keyple-service-cpp-lib/](https://eclipse.github.io/keyple-service-cpp-lib/)
                -   C++ code [https://github.com/eclipse/keyple-service-cpp-lib](https://github.com/eclipse/keyple-service-cpp-lib)
            -   Plugin SPI (for pluging implementation)
                -   info [https://keyple.org/components-java/core/keyple-plugin-java-api/](https://keyple.org/components-java/core/keyple-plugin-java-api/)
                -   Java doc [https://eclipse.github.io/keyple-plugin-java-api/](https://eclipse.github.io/keyple-plugin-java-api/)
                -   Java code [https://github.com/eclipse/keyple-plugin-java-api](https://github.com/eclipse/keyple-plugin-java-api)
                -   C++ doc [https://eclipse.github.io/keyple-plugin-cpp-api/](https://eclipse.github.io/keyple-plugin-cpp-api/)
                -   C++ code [https://github.com/eclipse/keyple-plugin-cpp-api](https://github.com/eclipse/keyple-plugin-cpp-api)
            -   Utility
                -   Keyple shared reference
                    -   info [https://keyple.org/components-java/core/keyple-common-java-api/](https://keyple.org/components-java/core/keyple-common-java-api/)
                    -   Java doc [https://eclipse.github.io/keyple-common-java-api/](https://eclipse.github.io/keyple-common-java-api/)
                    -   Java code [https://github.com/eclipse/keyple-common-java-api](https://github.com/eclipse/keyple-common-java-api)
                    -   C++ doc [https://eclipse.github.io/keyple-common-cpp-api/](https://eclipse.github.io/keyple-common-cpp-api/)
                    -   C++ code [https://github.com/eclipse/keyple-common-cpp-api](https://github.com/eclipse/keyple-common-cpp-api)
                -   Helper functions
                    -   info [https://keyple.org/components-java/core/keyple-util-java-lib/](https://keyple.org/components-java/core/keyple-util-java-lib/)
                    -   Java doc [https://eclipse.github.io/keyple-util-java-lib/](https://eclipse.github.io/keyple-util-java-lib/)
                    -   Java code [https://github.com/eclipse/keyple-util-java-lib](https://github.com/eclipse/keyple-util-java-lib)
                    -   C++ doc [https://eclipse.github.io/keyple-util-cpp-lib/](https://eclipse.github.io/keyple-util-cpp-lib/)
                    -   C++ code [https://github.com/eclipse/keyple-util-cpp-lib](https://github.com/eclipse/keyple-util-cpp-lib)
        -   Card resource manager extension
            -   info [https://keyple.org/components-java/core/keyple-service-resource-java-lib/](https://keyple.org/components-java/core/keyple-service-resource-java-lib/)
            -   Java doc [https://eclipse.github.io/keyple-service-resource-java-lib/](https://eclipse.github.io/keyple-service-resource-java-lib/)
            -   Java code [https://github.com/eclipse/keyple-service-resource-java-lib](https://github.com/eclipse/keyple-service-resource-java-lib)
            -   C++ doc [https://eclipse.github.io/keyple-service-resource-cpp-lib/](https://eclipse.github.io/keyple-service-resource-cpp-lib/)
            -   C++ code [https://github.com/eclipse/keyple-service-resource-cpp-lib](https://github.com/eclipse/keyple-service-resource-cpp-lib)
        -   Distributed module (for remote card readers): not yet available in C++
            -   for terminal operating a remote reader
                -   info [https://keyple.org/components-java/distributed/keyple-distributed-remote-java-lib/](https://keyple.org/components-java/distributed/keyple-distributed-remote-java-lib/)
                -   API
                    -   Java doc [https://eclipse.github.io/keyple-distributed-remote-java-api/](https://eclipse.github.io/keyple-distributed-remote-java-api/)
                    -   Java code [https://github.com/eclipse/keyple-distributed-remote-java-api](https://github.com/eclipse/keyple-distributed-remote-java-api)
                -   lib
                    -   Java doc [https://eclipse.github.io/keyple-distributed-remote-java-lib/](https://eclipse.github.io/keyple-distributed-remote-java-lib/)
                    -   Java code [https://github.com/eclipse/keyple-distributed-remote-java-lib](https://github.com/eclipse/keyple-distributed-remote-java-lib)
            -   for terminal interfaced with a local reader
                -   info [https://keyple.org/components-java/distributed/keyple-distributed-local-java-lib/](https://keyple.org/components-java/distributed/keyple-distributed-local-java-lib/)
                -   API
                    -   Java doc [https://eclipse.github.io/keyple-distributed-local-java-api/](https://eclipse.github.io/keyple-distributed-local-java-api/)
                    -   Java code [https://github.com/eclipse/keyple-distributed-local-java-api](https://github.com/eclipse/keyple-distributed-local-java-api)
                -   lib
                    -   Java doc [https://eclipse.github.io/keyple-distributed-local-java-lib/](https://eclipse.github.io/keyple-distributed-local-java-lib/)
                    -   Java code [https://github.com/eclipse/keyple-distributed-local-java-lib](https://github.com/eclipse/keyple-distributed-local-java-lib)
            -   common lib for network messaging
                -   info [https://keyple.org/components-java/distributed/keyple-distributed-network-java-lib/](https://keyple.org/components-java/distributed/keyple-distributed-network-java-lib/)
                -   doc [https://eclipse.github.io/keyple-distributed-network-java-lib/](https://eclipse.github.io/keyple-distributed-network-java-lib/)
                -   code [https://github.com/eclipse/keyple-distributed-network-java-lib](https://github.com/eclipse/keyple-distributed-network-java-lib)
        -   Card solution extensions:
            -   Generic card example of card extension implementation to operate a "generic" smart card solution using low-level APDU commandscommunication
                -   info [https://keyple.org/components-java/card-extensions/keyple-card-generic-java-lib/](https://keyple.org/components-java/card-extensions/keyple-card-generic-java-lib/)
                -   Java doc [https://eclipse.github.io/keyple-card-generic-java-lib/](https://eclipse.github.io/keyple-card-generic-java-lib/)
                -   Java code [https://github.com/eclipse/keyple-card-generic-java-lib](https://github.com/eclipse/keyple-card-generic-java-lib)
                -   C++ doc [https://eclipse.github.io/keyple-card-generic-cpp-lib/](https://eclipse.github.io/keyple-card-generic-cpp-lib/)
                -   C++ code [https://github.com/eclipse/keyple-card-generic-cpp-lib](https://github.com/eclipse/keyple-card-generic-cpp-lib)
            -   **Calypso card** library to manage Calypso processing on a terminal (implementation of the Calypso API)
                -   info [https://keyple.org/components-java/card-extensions/keyple-card-calypso-java-lib/](https://keyple.org/components-java/card-extensions/keyple-card-calypso-java-lib/)
                -   Java doc [https://eclipse.github.io/keyple-card-calypso-java-lib/](https://eclipse.github.io/keyple-card-calypso-java-lib/)
                -   Java code [https://github.com/eclipse/keyple-card-calypso-java-lib](https://github.com/eclipse/keyple-card-calypso-java-lib)
                -   C++ doc [https://eclipse.github.io/keyple-card-calypso-cpp-lib/](https://eclipse.github.io/keyple-card-calypso-cpp-lib/)
                -   C++ code [https://github.com/eclipse/keyple-card-calypso-cpp-lib](https://github.com/eclipse/keyple-card-calypso-cpp-lib)
        -   Plugins for "standardized" smartcard reader solutions:
            -   PC/SC (Windows/Linux/MacOS)
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-pcsc-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-pcsc-java-lib/)
                -   Java doc [https://eclipse.github.io/keyple-plugin-pcsc-java-lib/](https://eclipse.github.io/keyple-plugin-pcsc-java-lib/)
                -   Java code [https://github.com/eclipse/keyple-plugin-pcsc-java-lib](https://github.com/eclipse/keyple-plugin-pcsc-java-lib)
                -   C++ doc [https://eclipse.github.io/keyple-plugin-pcsc-cpp-lib/](https://eclipse.github.io/keyple-plugin-pcsc-cpp-lib/)
                -   C++ code [https://github.com/eclipse/keyple-plugin-pcsc-cpp-lib](https://github.com/eclipse/keyple-plugin-pcsc-cpp-lib)
            -   Android OMAPI - to interface an 'internal' Secure Element in an Android device
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-omapi-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-omapi-java-lib/)
                -   Koltin doc [https://eclipse.github.io/keyple-plugin-pcsc-java-lib/](https://eclipse.github.io/keyple-plugin-pcsc-java-lib/)
                -   Koltin code [https://github.com/eclipse/keyple-plugin-android-omapi-java-lib](https://github.com/eclipse/keyple-plugin-android-omapi-java-lib)
            -   Android NFC - to interface an "external" Secure Element with an Android device (using NFC Reader mode)
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-nfc-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-nfc-java-lib/)
                -   Kotlin doc [https://eclipse.github.io/keyple-plugin-android-nfc-java-lib/](https://eclipse.github.io/keyple-plugin-android-nfc-java-lib/)
                -   Kotlin code [https://github.com/eclipse/keyple-plugin-android-nfc-java-lib](https://github.com/eclipse/keyple-plugin-android-nfc-java-lib)
            -   Reader emulation - for testing without hardware solution
                -   info [https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-stub-java-lib/](https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-stub-java-lib/)
                -   Java doc [https://eclipse.github.io/keyple-plugin-stub-java-lib/](https://eclipse.github.io/keyple-plugin-stub-java-lib/)
                -   Java code [https://github.com/eclipse/keyple-plugin-stub-java-lib](https://github.com/eclipse/keyple-plugin-stub-java-lib)
                -   C++ doc [https://eclipse.github.io/keyple-plugin-stub-cpp-lib/](https://eclipse.github.io/keyple-plugin-stub-cpp-lib/)
                -   C++ code [https://github.com/eclipse/keyple-plugin-stub-cpp-lib](https://github.com/eclipse/keyple-plugin-stub-cpp-lib)
-   Deprecated components before version 2.x (a single repository per language):
    -   Java info until version 1.0.0 [https://keyple.org/components-java-1.0/](https://keyple.org/components-java-1.0/)
    -   Java code until version 1.0.0 [https://github.com/eclipse/keyple-java](https://github.com/eclipse/keyple-java) (archived repository)
    -   C++ info until version 0.9.0 [https://keyple.org/components-cpp-0.9/](https://keyple.org/components-cpp-0.9/)
    -   C++ code until version 0.9.0 [https://github.com/eclipse/keyple-cpp](https://github.com/eclipse/keyple-cpp) (archived repository)


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
