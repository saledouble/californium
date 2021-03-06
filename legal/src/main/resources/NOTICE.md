# Notices for Eclipse Californium  CoAP Framework

This content is produced and maintained by the Eclipse Californium CoAP
Framework project.

* Project home: https://projects.eclipse.org/projects/iot.californium

## Trademarks

Eclipse Californium, Californium, Eclipse Cf, and Cf are trademarks of the
Eclipse Foundation.

## Copyright

All content is the property of the respective authors or their employers. For
more information regarding authorship of content, please consult the listed
source code repository logs.

## Declared Project Licenses

This program and the accompanying materials are made available under the terms
of the Eclipse Public License v. 2.0 which is available at
https://www.eclipse.org/legal/epl-2.0/, or the Eclipse Distribution License
v. 1.0 which is available at http://www.eclipse.org/org/documents/edl-v10.php.

SPDX-License-Identifier: EPL-2.0 OR BSD-3-Clause

## Source Code

The project maintains the following source code repositories:

* https://github.com/eclipse/californium
* https://github.com/eclipse/californium.tools
* https://github.com/eclipse/californium.actinium

## Third-party Content

This project leverages the following third party content.

Apache HttpClient (4.5.2)

* License: Apache-2.0 

Apache HttpComponents AsyncClient (4.1.2)

* License: Apache-2.0

Apache HttpComponents Client (4.2.5)

* License: Apache License 2.0

Apache HttpComponents Core (4.2.5)

* License: Apache License 2.0

Apache HttpComponents HttpCore NIO (4.4.5)

* License: Apache-2.0 

ASM (5.0.1)

* License: New BSD license

com.augustcellars.cose.cose-java-0.9.7 (0.9.7)

* License: BSD-3-Clause
* Project: https://github.com/jimsch/COSE-JAVA
* Source:
   http://repo1.maven.org/maven2/com/augustcellars/cose/cose-java/0.9.7/cose-java-0.9.7-sources.jar

In order to use COSE with java 1.7, the java source files are copied from 
https://github.com/jimsch/COSE-JAVA/tree/master/src/main/java/COSE
into the package `org.eclipse.californium.cose`. 
The java source files `AlgorithmID.java`, `Attribute.java`, `CoseException.java`, `HeaderKeys.java`
and `MessageTag.java` are copied without modification, except for the license from the root folder of the COSE
project has been copied into the header along with additional information regarding provenance.

```
 * Original from https://github.com/cose-wg/COSE-JAVA Commit 1a20373
 *
 * Copyright (c) 2016, Jim Schaad
 * All rights reserved.
```

The java source files `EncryptCommon.java`, `Encrypt0Message.java` and `Message.java` have been copied with
modifications. The header was added as for the other unmodified files.

com.github.peteroupc.numbers-1.0.2 (1.0.2)

* License: CC-1.0
* Project: https://github.com/peteroupc/Numbers-Java
* Source:
   http://repo1.maven.org/maven2/com/github/peteroupc/numbers/1.0.2/numbers-1.0.2-sources.jar

com.upokecenter.cbor-3.0.3 (3.0.3)

* License: CC-1.0
* Project: https://github.com/peteroupc/CBOR-Java
* Source:
   http://repo1.maven.org/maven2/com/upokecenter/cbor/3.0.3/cbor-3.0.3-sources.jar

commons-logging-1.2 (1.2)

* License: Apache License, 2.0

Google Guava (15.0.0)

* License: Apache License, 2.0

gson (2.8.2)

* License: Apache-2.0 

httpcore (4.4.5)

* License: Apache-2.0 

Javax.annotation (1.2)

* License: CDDL

javax.servlet-api (3.1.0)

* License: Apache-2.0 AND (CDDL-1.1 OR GPL-2.0 WITH Classpath-exception-2.0)

javax.websocket API (1.0)

* License: Common Development and Distribution License

Logback Classic (1.2.3)

* License: EPL-1.0

Logback Core (1.2.3)

* License: EPL-1.0

logback-android:1.1.1-11 (1.1.1)

* License: EPL-1.0 OR LGPL-2.1
* Project: https://github.com/tony19/logback-android
* Source: https://github.com/tony19/logback-android/archive/master.zip

Netty (4.1.42)

* License: Apache-2.0 AND BSD-3-Clause AND MIT

OSGi Service Platform Compendium Companion Code (4.3.1)

* License: Apache License, 2.0
* Project: http://www.osgi.org

OSGi Service Platform Core Companion Code (4.3.1)

* License: Apache License, 2.0
* Project: http://www.osgi.org

slf4j-api (1.7.25)

* License: MIT

slf4j-jdk14 (1.7.25)

* License: MIT

## Cryptography

Content may contain encryption software. The country in which you are currently
may have restrictions on the import, possession, and use, and/or re-export to
another country, of encryption software. BEFORE using any encryption software,
please check the country's laws, regulations and policies concerning the import,
possession, or use, and re-export of encryption software, to see if this is
permitted.
