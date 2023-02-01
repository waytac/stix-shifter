# CHANGELOG

We have started this changelogs from version 4.0.0. So, changes on previously released versions can be found in tag branches. Please follow the below format to update add changelogs for new tag version.

## <Tag_Version> (Date)
### Breaking changes:
*List the breaking changes in this section. Breaking changes is anything that either changes the input or output of stix-shifter, or a change that breaks the compatibility between a connector and the core stix-shifter functions.*
### Deprecations:
*List the Deprecated functions, input and output.*
### Changes:
*List the newly added functions, input and output.*
### Fixes:
*List the bug fixes.*
### Dependency update:
*List the dependecy upgrade or downgrade.*

--------------------------------------

## 4.6.0 (2023-01-24)

### Breaking changes:

### Deprecations:

### Changes:

* Instructions for the usage of custom mappings [#1274](https://github.com/opencybersecurityalliance/stix-shifter/pull/1274)
* Add log analytics API support to azure sentinel connector [#1214](https://github.com/opencybersecurityalliance/stix-shifter/pull/1214)
* Update OCSF schema in Athena mappings [#1245](https://github.com/opencybersecurityalliance/stix-shifter/pull/1245)
* splunk: allow multiple, comma-separated index names in the index option [#1271](https://github.com/opencybersecurityalliance/stix-shifter/pull/1271)
* Rename azure sentinel to Microsoft Graph Security Connector [#1212](https://github.com/opencybersecurityalliance/stix-shifter/pull/1212)
* elastic_ecs: add beats dialect [#1208](https://github.com/opencybersecurityalliance/stix-shifter/pull/1208)
* update script to create sql database [#1228](https://github.com/opencybersecurityalliance/stix-shifter/pull/1228)
* Test for START STOP timestamp format [#1218](https://github.com/opencybersecurityalliance/stix-shifter/pull/1218)
* Updated RHACS connector to support self signed certificate authentication [#1174](https://github.com/opencybersecurityalliance/stix-shifter/pull/1174)

### Fixes:

* Mapping updates for Guardium STIX 2.1 [#1102](https://github.com/opencybersecurityalliance/stix-shifter/pull/1102)
* Add default time range to STIX Bundle connector [#1288](https://github.com/opencybersecurityalliance/stix-shifter/pull/1288)
* Updated code to handle maximum query length limitation in darktrace.  [#1259](https://github.com/opencybersecurityalliance/stix-shifter/pull/1259)
* Use raw strings for regex [#1276](https://github.com/opencybersecurityalliance/stix-shifter/pull/1276)
* Updated changes for the issue #1270 [#1272](https://github.com/opencybersecurityalliance/stix-shifter/pull/1272)
* change all two lettered property names [#1251](https://github.com/opencybersecurityalliance/stix-shifter/pull/1251)
* mapping fixes for splunk [#1239](https://github.com/opencybersecurityalliance/stix-shifter/pull/1239)
* splunk: use like, cidrmatch SPL functions for LIKE, ISSUBSET operators [#1244](https://github.com/opencybersecurityalliance/stix-shifter/pull/1244)
* Fix supported property exporter to handle from-STIX fields not wrapped in a list [#1236](https://github.com/opencybersecurityalliance/stix-shifter/pull/1236)
* fix domain_ioc mapping (removal of network_traffic ref) [#1226](https://github.com/opencybersecurityalliance/stix-shifter/pull/1226)
* Updated cybereason code to fix the issue #1215 [#1224](https://github.com/opencybersecurityalliance/stix-shifter/pull/1224)
* Darktrace timeout exception handled [#1210](https://github.com/opencybersecurityalliance/stix-shifter/pull/1210)
* Aws athena ocsf fixes [#1182](https://github.com/opencybersecurityalliance/stix-shifter/pull/1182)
* elastic_ecs: more fixes for LIKE and MATCHES [#1195](https://github.com/opencybersecurityalliance/stix-shifter/pull/1195)

### Dependency update:

* Bump boto3 from 1.26.41 to 1.26.55 in /stix_shifter [#1293](https://github.com/opencybersecurityalliance/stix-shifter/pull/1293)
* Bump json-fix from 0.5.0 to 0.5.1 in /stix_shifter [#1196](https://github.com/opencybersecurityalliance/stix-shifter/pull/1196)
* Bump pyopenssl from 22.1.0 to 23.0.0 in /stix_shifter [#1264](https://github.com/opencybersecurityalliance/stix-shifter/pull/1264)
* Bump boto3 from 1.26.10 to 1.26.41 in /stix_shifter [#1263](https://github.com/opencybersecurityalliance/stix-shifter/pull/1263)

-------------------------------------

## 4.5.2 (2022-11-21)

### Breaking changes:

### Deprecations:

### Changes:

* AWS Athena, added external id support [#1187](https://github.com/opencybersecurityalliance/stix-shifter/pull/1187)
* Update aws athena supported attribute [#1184](https://github.com/opencybersecurityalliance/stix-shifter/pull/1184)
* Update AWS Athena for OCSF schema support [#1178](https://github.com/opencybersecurityalliance/stix-shifter/pull/1178)
* Upgrade pytests version for dev environment [#1170](https://github.com/opencybersecurityalliance/stix-shifter/pull/1170)
* ocsf schema support in aws Athena [#1134](https://github.com/opencybersecurityalliance/stix-shifter/pull/1134)
* Add RHACS and Google Chronicle group params [#1150](https://github.com/opencybersecurityalliance/stix-shifter/pull/1150)
* return proxy translation error [#1130](https://github.com/opencybersecurityalliance/stix-shifter/pull/1130)
* Updated the readme mappings for GCP Chronicle [#1146](https://github.com/opencybersecurityalliance/stix-shifter/pull/1146)

### Fixes:

* Updated to support query without milliseconds in darktrace connector [#1199](https://github.com/opencybersecurityalliance/stix-shifter/pull/1199)
* fix formatting of commit list generated by changelog script [#1200](https://github.com/opencybersecurityalliance/stix-shifter/pull/1200)
* fixed timestamp issue for start and end filter and mapping correction [#1142](https://github.com/opencybersecurityalliance/stix-shifter/pull/1142)
* Fixed pagination and meta files delete for aws athena [#1176](https://github.com/opencybersecurityalliance/stix-shifter/pull/1176)
* gcp chronicle: removed an invalid unittest [#1166](https://github.com/opencybersecurityalliance/stix-shifter/pull/1166)
* Remove optional word from indices label [#1157](https://github.com/opencybersecurityalliance/stix-shifter/pull/1157)
* Fixed deployment script with --platform linux/amd64 [#1154](https://github.com/opencybersecurityalliance/stix-shifter/pull/1154)
* Updated connector.py file for the bug fix #1103 [#1104](https://github.com/opencybersecurityalliance/stix-shifter/pull/1104)

### Dependency update:

* Bump flask from 2.0.3 to 2.2.2 in /stix_shifter [#1072](https://github.com/opencybersecurityalliance/stix-shifter/pull/1072)
* Bump requests-toolbelt from 0.9.1 to 0.10.1 in /stix_shifter [#1180](https://github.com/opencybersecurityalliance/stix-shifter/pull/1180)
* Bump jsonmerge from 1.8.0 to 1.9.0 in /stix_shifter [#1194](https://github.com/opencybersecurityalliance/stix-shifter/pull/1194)
* Bump boto3 from 1.26.5 to 1.26.10 in /stix_shifter [#1193](https://github.com/opencybersecurityalliance/stix-shifter/pull/1193)
* Bump boto3 from 1.21.21 to 1.26.1 in /stix_shifter [#1175](https://github.com/opencybersecurityalliance/stix-shifter/pull/1175)
* Bump pyopenssl from 21.0.0 to 22.1.0 in /stix_shifter [#1144](https://github.com/opencybersecurityalliance/stix-shifter/pull/1144)

--------------------------------------

## 4.4.0 (2022-10-06)

### Breaking changes:

### Deprecations:

### Changes:

* Add optional group parameter to connector configs [#1094](https://github.com/opencybersecurityalliance/stix-shifter/pull/1094)
* Adding GCP Chronicle UDI Connector [#1075](https://github.com/opencybersecurityalliance/stix-shifter/pull/1075)
* Update Secretserver mappings [#1092](https://github.com/opencybersecurityalliance/stix-shifter/pull/1092)
* Connector template for lab [#1117](https://github.com/opencybersecurityalliance/stix-shifter/pull/1117)

### Fixes:

* Get rid of StixObjectIdEncoder [#1124](https://github.com/opencybersecurityalliance/stix-shifter/pull/1124)
* Fixed IBM Security Verify config file [#1125](https://github.com/opencybersecurityalliance/stix-shifter/pull/1125)
* edits to coding lab [#1120](https://github.com/opencybersecurityalliance/stix-shifter/pull/1120)
* Update epoch time to 10 digits for demo data [#1119](https://github.com/opencybersecurityalliance/stix-shifter/pull/1119)
* update coding lab [#1114](https://github.com/opencybersecurityalliance/stix-shifter/pull/1114)
* Lab fixes [#1116](https://github.com/opencybersecurityalliance/stix-shifter/pull/1116)

### Dependency update:

* Bump colorlog from 6.6.0 to 6.7.0 in /stix_shifter [#1095](https://github.com/opencybersecurityalliance/stix-shifter/pull/1095)

--------------------------------------

## 4.3.0 (2022-09-09)

### Breaking changes:

### Deprecations:

### Changes:

* CLI and coding tutorials [#1105](https://github.com/opencybersecurityalliance/stix-shifter/pull/1105)
* Adding RHACS(StackRox) UDI connector [#1055](https://github.com/opencybersecurityalliance/stix-shifter/pull/1055)
* Added Utility for normalization of connectors [#1078](https://github.com/opencybersecurityalliance/stix-shifter/pull/1078)
* CrowdStrike: Added User-Agent string to API Client for tracking [#1064](https://github.com/opencybersecurityalliance/stix-shifter/pull/1064)
* Process unique ID [#1051](https://github.com/opencybersecurityalliance/stix-shifter/pull/1051)
* Added matcher lib support for 2.1 [#960](https://github.com/opencybersecurityalliance/stix-shifter/pull/960)
* In query Enhancement [#1022](https://github.com/opencybersecurityalliance/stix-shifter/pull/1022)
* Infoblox add docstrings for module [#719](https://github.com/opencybersecurityalliance/stix-shifter/pull/719)
* Release/3.3.x json to stix [#598](https://github.com/opencybersecurityalliance/stix-shifter/pull/598)

### Fixes:

* Id contributing properties from json to py [#1093](https://github.com/opencybersecurityalliance/stix-shifter/pull/1093)
* splunk: fix STIX timestamp processing [#1084](https://github.com/opencybersecurityalliance/stix-shifter/pull/1084)
* Fixing absolute path for id_contributing_properties.json [#1079](https://github.com/opencybersecurityalliance/stix-shifter/pull/1079)
* Fix mapping and added hex to int transformer [#1068](https://github.com/opencybersecurityalliance/stix-shifter/pull/1068)
* Downgrade boto3 version to 1.21.21 [#1036](https://github.com/opencybersecurityalliance/stix-shifter/pull/1036)
* Fix the length of the results of Qradar connector [#1034](https://github.com/opencybersecurityalliance/stix-shifter/pull/1034)
* Revert "Change certificate parameter type for consistency" [#1031](https://github.com/opencybersecurityalliance/stix-shifter/pull/1031)
* reaqta: enable certification authentication [#1028](https://github.com/opencybersecurityalliance/stix-shifter/pull/1028)
* fix configuration in proofpoint and sumologic [#745](https://github.com/opencybersecurityalliance/stix-shifter/pull/745)
* Validator review code change for Proofpoint [#739](https://github.com/opencybersecurityalliance/stix-shifter/pull/739)

### Dependency update:


--------------------------------------


## 4.2.0 (2022-06-29)
### Breaking changes:

### Deprecations:

### Changes:

* Added reaqta from_stix generate script [#977](https://github.com/opencybersecurityalliance/stix-shifter/pull/977)
* Change certificate parameter type [#1000](https://github.com/opencybersecurityalliance/stix-shifter/pull/1000)
* splunk: add index to options [#993](https://github.com/opencybersecurityalliance/stix-shifter/pull/993)
* Best practices document for connector development [#986](https://github.com/opencybersecurityalliance/stix-shifter/pull/986)
* Update supported attributes and overview readme [#976](https://github.com/opencybersecurityalliance/stix-shifter/pull/976)
* Guardium rel 1.10 [#958](https://github.com/opencybersecurityalliance/stix-shifter/pull/958)
* Updated the readme mappings for darktrace. [#942](https://github.com/opencybersecurityalliance/stix-shifter/pull/942)
* Added Darktrace UDI connector. [#896](https://github.com/opencybersecurityalliance/stix-shifter/pull/896)
* Update table of mappings for ReaQta and IN operator support [#937](https://github.com/opencybersecurityalliance/stix-shifter/pull/937)
* Updated the Readme mapping files [#932](https://github.com/opencybersecurityalliance/stix-shifter/pull/932)
* Adding SentinelOne UDI connector [#888](https://github.com/opencybersecurityalliance/stix-shifter/pull/888)
* Reaqta connector [#879](https://github.com/opencybersecurityalliance/stix-shifter/pull/879)

### Fixes:

* Fixed unique_cybox_objects storing [#1005](https://github.com/opencybersecurityalliance/stix-shifter/pull/1005)
* fallback to random UUID if STIX object contains no defined id contributing properties [#990](https://github.com/opencybersecurityalliance/stix-shifter/pull/990)
* error_test timeouts on translate and status [#987](https://github.com/opencybersecurityalliance/stix-shifter/pull/987)
* fix two deprecation warnings [#940](https://github.com/opencybersecurityalliance/stix-shifter/pull/940)
* splunk: fix mapping of process command line [#918] [#971](https://github.com/opencybersecurityalliance/stix-shifter/pull/971)
* splunk: fix incorrect dst_ref.value mapping [#919] [#970](https://github.com/opencybersecurityalliance/stix-shifter/pull/970)
* splunk: fix translation of IN, LIKE, and MATCHES [#789] [#969](https://github.com/opencybersecurityalliance/stix-shifter/pull/969)
* fix eventType mapping for reaqta connector [#967](https://github.com/opencybersecurityalliance/stix-shifter/pull/967)
* Reaqta: Fix network traffic for inbound and mapping update [#952](https://github.com/opencybersecurityalliance/stix-shifter/pull/952)
* Remove deprecated SourceImage field from aql search [#950](https://github.com/opencybersecurityalliance/stix-shifter/pull/950)
* Reaqta: implemented grater/less fields translation, fixed from_stix fields sorting, fixed unittests [#938](https://github.com/opencybersecurityalliance/stix-shifter/pull/938)
* Reaqta Connector:Update mapping and unittest [#964](https://github.com/opencybersecurityalliance/stix-shifter/pull/964)
* Fixed stix parsing with setvalue types [#907](https://github.com/opencybersecurityalliance/stix-shifter/pull/907)

### Dependency update:

* Bump boto3 from 1.21.5 to 1.22.10 [#935](https://github.com/opencybersecurityalliance/stix-shifter/pull/935)
* Bump xmltodict from 0.12.0 to 0.13.0 [#934](https://github.com/opencybersecurityalliance/stix-shifter/pull/934)
* Bump stix2-matcher from 2.0.1 to 2.0.2 [#915](https://github.com/opencybersecurityalliance/stix-shifter/pull/915)


--------------------------------------


## 4.1.0 (2022-04-12)
### Breaking changes:

### Deprecations:

### Changes:

* Updated mappings for PaloAlto readme [#890](https://github.com/opencybersecurityalliance/stix-shifter/pull/890)
* Added Palo Alto Cortext XDR UDI Connector [#858](https://github.com/opencybersecurityalliance/stix-shifter/pull/858)
* package utils/normalization [#882](https://github.com/opencybersecurityalliance/stix-shifter/pull/882)
* add sample transformer to template modules [#870](https://github.com/opencybersecurityalliance/stix-shifter/pull/870)
* Added IN operator for Vision One UDI connector [#861](https://github.com/opencybersecurityalliance/stix-shifter/pull/861)
* Update arcsight custom attributes [#865](https://github.com/opencybersecurityalliance/stix-shifter/pull/865)
* results metadata support [#813](https://github.com/opencybersecurityalliance/stix-shifter/pull/813)
* Template projects rename [#854](https://github.com/opencybersecurityalliance/stix-shifter/pull/854)
* doc update for operators and custom transformers [#846](https://github.com/opencybersecurityalliance/stix-shifter/pull/846)
* Adding BaseNormalization Class [#820](https://github.com/opencybersecurityalliance/stix-shifter/pull/820)
* Add IN operator for sumologic connector [#845](https://github.com/opencybersecurityalliance/stix-shifter/pull/845)
* Adding IN operator support to CB connector [#835](https://github.com/opencybersecurityalliance/stix-shifter/pull/835)
* Stix validator update [#838](https://github.com/opencybersecurityalliance/stix-shifter/pull/838)
* CrowdStrike: Adding IN operator support [#842](https://github.com/opencybersecurityalliance/stix-shifter/pull/842)
* Adding changelog [#833](https://github.com/opencybersecurityalliance/stix-shifter/pull/833)
* New UDI connector module for IBM Security Verify [#802](https://github.com/opencybersecurityalliance/stix-shifter/pull/802)
* Adding connector name in the error responses [#824](https://github.com/opencybersecurityalliance/stix-shifter/pull/824)

### Fixes:

* use simple setup for mysql endpoints [#885](https://github.com/opencybersecurityalliance/stix-shifter/pull/885)
* Mysql tablename fix [#868](https://github.com/opencybersecurityalliance/stix-shifter/pull/868)
* RestApiClient in stix-shifter using https mount call [#864](https://github.com/opencybersecurityalliance/stix-shifter/pull/864)
* Fixed StixObjectId conversion to string [#863](https://github.com/opencybersecurityalliance/stix-shifter/pull/863)
* Fixed stix-validator 3.0.2 usage in translator [#851](https://github.com/opencybersecurityalliance/stix-shifter/pull/851)
* remove process_user field mapping from windows-registry-key stix object [#850](https://github.com/opencybersecurityalliance/stix-shifter/pull/850)
* Secret server 1.9 [#836](https://github.com/opencybersecurityalliance/stix-shifter/pull/836)
* Fixed calculating and updating deterministic IDs and the… [#826](https://github.com/opencybersecurityalliance/stix-shifter/pull/826)


--------------------------------------


## 4.0.1 (2022-03-01)
### Breaking changes:
### Deprecations:
### Changes:
* CrowdStrike connector mapping update [#823](https://github.com/opencybersecurityalliance/stix-shifter/pull/823)

### Fixes:
### Dependency update:
* Downgrade pyopenssl from 22.0.0 to 21.0.0

--------------------------------------

## 4.0.0 (2022-02-23)
### Breaking changes:

* Handling unmapped operators in stix pattern
* Optimization of results translation 

### Deprecations:

### Changes:

* Added New connector: Cybereason
* Added Stix 2.1 ids and mapping update in [#731](https://github.com/opencybersecurityalliance/stix-shifter/pull/731) [#721](https://github.com/opencybersecurityalliance/stix-shifter/pull/721)
* Added stix-shifter CLI parameters to configure max returned results and saving to a file in [#730](https://github.com/opencybersecurityalliance/stix-shifter/pull/730)
* Azure Sentinel Mapping update in [710](https://github.com/opencybersecurityalliance/stix-shifter/pull/710)
* Handling unmapped operators in stix pattern in [#744](https://github.com/opencybersecurityalliance/stix-shifter/pull/744)
* Placeholder for datadog certificate in [#782](https://github.com/opencybersecurityalliance/stix-shifter/pull/782)
* Proofpoint: Update labels in configuration in [792](https://github.com/opencybersecurityalliance/stix-shifter/pull/792)
* Added Operator list in adapter guide in [#804](https://github.com/opencybersecurityalliance/stix-shifter/pull/804)
* Splunk mapping update in [#797](https://github.com/opencybersecurityalliance/stix-shifter/pull/797)
* Keep both helper description and the link description in [818](https://github.com/opencybersecurityalliance/stix-shifter/pull/818)
* Optimization of results translation in [#718](https://github.com/opencybersecurityalliance/stix-shifter/pull/718)
* QRadar mapping update in [#751](https://github.com/opencybersecurityalliance/stix-shifter/pull/751)


### Fixes
* Datadog ssl cert fix.[#758](https://github.com/opencybersecurityalliance/stix-shifter/pull/758)
* cbcloud: fix ipv4 stix pattern translation [#761](https://github.com/opencybersecurityalliance/stix-shifter/pull/761)
* fix configuration in proofpoint and sumologic [#745](https://github.com/opencybersecurityalliance/stix-shifter/pull/745)
* Crowdstrike unittest fix [#775](https://github.com/opencybersecurityalliance/stix-shifter/pull/775)
* Fix error reponse of ms defender connector [#747](https://github.com/opencybersecurityalliance/stix-shifter/pull/747)
* fix: handling zero and non-zero values for the transformers [#774](https://github.com/opencybersecurityalliance/stix-shifter/pull/774)
* Fix Proofpoint: avoid mapping error for standard STIX Pattern translation [#786](https://github.com/opencybersecurityalliance/stix-shifter/pull/786)
* Proofpoint results connection fix [#739](https://github.com/opencybersecurityalliance/stix-shifter/pull/739)
* Fix local build and install [#779](https://github.com/opencybersecurityalliance/stix-shifter/pull/779)
* fix collections.abc warning [#793](https://github.com/opencybersecurityalliance/stix-shifter/pull/793)
* fix instances of reserved STIX 2.1 id property [#819](https://github.com/opencybersecurityalliance/stix-shifter/pull/819)
* Fix category in ecs to be list type [#734](https://github.com/opencybersecurityalliance/stix-shifter/pull/734)
* fix debug cli param [#735](https://github.com/opencybersecurityalliance/stix-shifter/pull/735)
* fix azure sentinel: Incorrect string conversion of datasource values [#771](https://github.com/opencybersecurityalliance/stix-shifter/pull/771)

### Dependency update
* Bump stix2-patterns from 1.3.0 to 1.3.2 
* Bump flatten-json from 0.1.7 to 0.1.13
* Bump flask from 1.1.2 to 2.0.3
* Bump python-dateutil from 2.8.1 to 2.8.2
* Bump jsonmerge from 1.7.0 to 1.8.0
* Bump colorlog from 4.1.0 to 6.6.0
* Bump adal from 1.2.2 to 1.2.7
* Bump pyopenssl from 20.0.1 to 22.0.0
* Bump stix2-validator from 1.1.2 to 3.0.2
* Bump boto3 from 1.17.20 to 1.21.5## 4.0.0 (2022-02-23)