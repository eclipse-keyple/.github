# Eclipse Keyple

This is the raw GitHub repository referencing all repositories of the Eclipse Keyple project (https://keyple.org/).

 - Keyple offers Java and C++ libraries to build ticketing terminals operating smart cards.
 - The Eclipse Keypop project (https://keypop.org/) provides Java and C++ code of the ticketing terminal APIs implemented by Keyple.

## Keyple component repositories for Java and C++ implementations

<table>
	<tbody>
		<tr>
			<th scope="col" colspan="2">Keyple component</th>
			<th scope="col" rowspan="2">Guide</th>
			<th scope="col" colspan="3">Implementation</th>
		</tr>
		<tr>
			<th scope="col">Type</th>
			<th scope="col">Name</th>
			<th></th>
			<th>Java</th>
			<th>C++</th>
		</tr>
		<tr>
			<td rowspan="8">Core</td>
			<td rowspan="2"><span title="implements Reader API & Card API from Keypop">Service Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/core/keyple-service-java-lib/">Service guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-service-java-lib">keyple-service-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-service-cpp-lib">keyple-service-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-service-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-service-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="SPI to be implemented by plugins of smart card reader solution">Plugin API</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/core/keyple-plugin-java-api/">Plugin guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-java-api">keyple-plugin-java-api</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-cpp-api">keyple-plugin-cpp-api</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-java-api/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-cpp-api/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="references shared by Keyple components">Common API</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/core/keyple-common-java-api/">Common guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-common-java-api">keyple-common-java-api</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-common-cpp-api">keyple-common-cpp-api</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-common-java-api/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-common-cpp-api/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="helper functions">Util Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/core/keyple-util-java-lib/">Util guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-util-java-lib">keyple-util-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-util-cpp-lib">keyple-util-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-util-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-util-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2">Card resource<br/>manager extension</td>
			<td rowspan="2">Service Resource Lib</td>
			<td rowspan="2"><a href="https://keyple.org/components-java/core/keyple-service-resource-java-lib/">Service Resource guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-service-resource-java-lib">keyple-service-resource-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-service-resource-cpp-lib">keyple-service-resource-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-service-resource-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-service-resource-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="10">Distributed module<br/>extension</td>
			<td rowspan="2"><span title="distributed module for terminal operating a remote reader">Distributed Remote API</span></td>
			<td rowspan="4"><a href="https://keyple.org/components-java/distributed/keyple-distributed-remote-java-lib/">Distributed Remote guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-distributed-remote-java-api">keyple-distributed-remote-java-api</a></td>
			<td rowspan="10"></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-distributed-remote-java-api/">UML &amp; Java Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="distributed module for terminal operating a remote reader">Distributed Remote Lib</span></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-distributed-remote-java-lib">keyple-distributed-remote-java-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-distributed-remote-java-lib/">UML &amp; Java Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="distributed module for terminal interfaced with a local reader">Distributed Local API</span></td>
			<td rowspan="4"><a href="https://keyple.org/components-java/distributed/keyple-distributed-local-java-lib/">Distributed Local guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-distributed-local-java-api">keyple-distributed-local-java-api</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-distributed-local-java-api/">UML &amp; Java Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="distributed module for terminal interfaced with a local reader">Distributed Local Lib</span></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-distributed-local-java-lib">keyple-distributed-local-java-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-distributed-local-java-lib/">UML &amp; Java Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="common library for network messaging">Distributed Network Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/distributed/keyple-distributed-network-java-lib/">Distributed Network guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-distributed-network-java-lib">keyple-distributed-network-java-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-distributed-network-java-lib/">UML &amp; Java Doc</a></td>
		</tr>
		<tr>
			<td rowspan="4">Card solution<br/>extension</td>
			<td rowspan="2"><span title="library to operate a ‘generic’ smart card solution using low-level APDU commandscommunication, implements the Card API from Keypop">Generic Card Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/card-extensions/keyple-card-generic-java-lib/">Generic Card guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-card-generic-java-lib">keyple-card-generic-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-card-generic-cpp-lib">keyple-card-generic-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-card-generic-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-card-generic-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="library to manage Calypso processing on a terminal, implements the Card API &amp; Calypso APIs from Keypop">Calypso Card Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/card-extensions/keyple-card-calypso-java-lib/">Calypso Card guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-card-calypso-java-lib">keyple-card-calypso-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-card-calypso-cpp-lib">keyple-card-calypso-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-card-calypso-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-card-calypso-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="8">Plugin extension<br/>for standardized<br/>reader solutions</td>
			<td rowspan="2"><span title="smart card reader emulation for testing without hardware solution">Stub Plugin Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-stub-java-lib/">Stub Plugin guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-stub-java-lib">keyple-plugin-stub-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-stub-cpp-lib">keyple-plugin-stub-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-stub-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-stub-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="to interface PC/SC reader on Windows / Linux / MacOS">PC/SC Plugin Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-pcsc-java-lib/">PC/SC Plugin guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-pcsc-java-lib">keyple-plugin-pcsc-java-lib</a></td>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-pcsc-cpp-lib">keyple-plugin-pcsc-cpp-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-pcsc-java-lib/">UML &amp; Java Doc</a></td>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-pcsc-cpp-lib/">C++ Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="to interface an ‘external’ Secure Element with an Android device (using NFC Reader mode)">Android NFC Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-nfc-java-lib/">Android NFC guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-android-nfc-java-lib">keyple-plugin-android-nfc-java-lib</a></td>
			<td rowspan="4"></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-android-nfc-java-lib/">UML &amp; Kotlin Doc</a></td>
		</tr>
		<tr>
			<td rowspan="2"><span title="to interface an 'internal' Secure Element in an Android device">Android OMAPI Lib</span></td>
			<td rowspan="2"><a href="https://keyple.org/components-java/standard-reader-plugins/keyple-plugin-android-omapi-java-lib/">Android OMAPI guide</a></td>
			<th scope="rowgroup">Repository</th>
			<td><a href="https://github.com/eclipse-keyple/keyple-plugin-android-omapi-java-lib">keyple-plugin-android-omapi-java-lib</a></td>
		</tr>
		<tr>
			<th scope="rowgroup">API doc</th>
			<td><a href="https://eclipse-keyple.github.io/keyple-plugin-pcsc-java-lib/">UML &amp; Kotlin Doc</a></td>
		</tr>
	</tbody>
</table>

## External repositories of Keypop API implemented by Keyple

Keypop repositories are listed in the [GitHub organization of the Eclipse Keypop](https://github.com/eclipse-keypop#keypop-component-repositories-for-java-and-c-implementations) project.

## Keyple project support repositories

<table>
	<tbody>
		<tr>
			<th scope="col" colspan="2">Support type</th>
			<th scope="col">Repository</th>
		</tr>
		<tr>
			<td colspan="2">Project website https://keyple.org/</td>
			<td><a href="https://github.com/eclipse-keyple/keyple-website">keyple-website</a></td>
		</tr>
		<tr>
			<td colspan="2">Meta scripts for C++ components' download & build</td>
			<td><a href="https://github.com/eclipse-keyple/keyple-cpp-meta">keyple-cpp-meta</a></td>
		</tr>
		<tr>
			<td rowspan="2">Use examples</td>
			<td>in Java</td>
			<td><a href="https://github.com/eclipse-keyple/keyple-java-example">keyple-java-example</a></td>
		</tr>
		<tr>
			<td>in C++</td>
			<td><a href="https://github.com/eclipse-keyple/keyple-cpp-example">keyple-cpp-example</a></td>
		</tr>
		<tr>
			<td rowspan="2">Continuous integration</td>
			<td>Jenkins configuration</td>
			<td><a href="https://github.com/eclipse-keyple/keyple-ops/">keyple-ops</a></td>
		</tr>
		<tr>
			<td>Java integration tests</td>
			<td><a href="https://github.com/eclipse-keyple/keyple-integration-java-test">keyple-integration-java-test</a></td>
		</tr>
				<tr>
			<td rowspan="2">Repository configuration</td>
			<td>Eclipse-specific</td>
			<td><a href="https://github.com/eclipse-keyple/.eclipsefdn">.eclipsefdn</a></td>
		</tr>
		<tr>
			<td>GitHub-specific</td>
			<td><a href="https://github.com/eclipse-keyple/.github">.github</a></td>
		</tr>
	</tbody>
</table>

## Repositories of older, no-longer-maintained versions of Keyple

<table>
	<tbody>
		<tr>
			<th scope="col" colspan="2">$\text{\color{red}Deprecated}$ elements</th>
			<th scope="col">$\text{\color{red}Archived}$ repository</th>
		</tr>
		<tr>
			<td rowspan="2">Keyple elements from version 0.7 to 1.0</td>
			<td>in Java</td>
			<td><a href="https://github.com/eclipse-archived/keyple-java">keyple-java</a></td>
		</tr>
		<tr>
			<td>in C++</td>
			<td><a href="https://github.com/eclipse-archived/keyple-cpp">keyple-cpp</a></td>
		</tr>
	</tbody>
</table>

## Contributing

1. [Fork](https://help.github.com/articles/fork-a-repo/) the [eclipse/keyple](https://github.com/eclipse-keyple/keyple) repository
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

Have a bug or a feature request? Please search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/eclipse-keyple/keyple/issues/new).

## Trademarks

* Eclipse Keyple and the Eclipse Keyple project are Trademarks of the Eclipse Foundation, Inc.
* Eclipse® is a Trademark of the Eclipse Foundation, Inc.
* Eclipse Foundation is a Trademark of the Eclipse Foundation, Inc.

## Copyright and license

Copyright 2020 the [Eclipse Foundation, Inc.](https://www.eclipse.org) and the [keyple authors](https://github.com/eclipse-keyple/keyple/graphs/contributors). Code released under the [Eclipse Public License Version 2.0 (EPL-2.0)](https://github.com/eclipse-keyple/keyple-website/blob/src/LICENSE).
