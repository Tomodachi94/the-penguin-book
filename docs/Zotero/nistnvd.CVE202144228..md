# CVE-2021-44228

## Metadata

Item_Type:: [[Webpage]]
Authors:: [[ NIST NVD]]
* Date Added: [[2021-11-10]]
[https://nvd.nist.gov/vuln/detail/CVE-2021-44228](https://nvd.nist.gov/vuln/detail/CVE-2021-44228)
* Cite key: nistnvd.CVE202144228.

Subjects:: [[Computers]]
* Tags: #Computers/ProgrammingLanguages/Java/Libraries/log4j/Security, #Computers/Security/Vulnerabilities/RemoteCodeExecution/Log4Shell, #zotero, #literature-notes, #reference

## Abstract

Apache Log4j2 <=2.14.1 JNDI features used in configuration, log messages, and parameters do not protect against attacker controlled LDAP and other JNDI related endpoints. An attacker who can control log messages or log message parameters can execute arbitrary code loaded from LDAP servers when message lookup substitution is enabled. From log4j 2.15.0, this behavior has been disabled by default. In previous releases (>2.10) this behavior can be mitigated by setting system property "log4j2.formatMsgNoLookups" to “true” or by removing the JndiLookup class from the classpath (example: zip -q -d log4j-core-*.jar org/apache/logging/log4j/core/lookup/JndiLookup.class). Java 8u121 (see https://www.oracle.com/java/technologies/javase/8u121-relnotes.html) protects against remote code execution by defaulting "com.sun.jndi.rmi.object.trustURLCodebase" and "com.sun.jndi.cosnaming.object.trustURLCodebase" to "false".


##  Zotero links
* [Local library](zotero://select/items/1_M42B9FNN)
* [Cloud library](http://zotero.org/users/local/8V1RrgGN/items/M42B9FNN)

