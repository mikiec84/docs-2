---
ID: 268
post_title: Pressbooks
author: Ned Zimmerman
post_excerpt: ""
layout: page
permalink: >
  https://docs.pressbooks.org/changelog/pressbooks/
published: true
post_date: 2017-09-06 21:02:12
---
### 5.5.5

#### Upgrade Notice

* Pressbooks 5.5.5 requires PHP >= 7.1.
* Pressbooks 5.5.5 requires [WordPress 4.9.8](https://wordpress.org/news/2018/08/wordpress-4-9-8-maintenance-release/).
* Pressbooks 5.5.5 requires [McLuhan >= 2.5.2](https://github.com/pressbooks/pressbooks-book/).

#### Patches

- Ensure that `\Pressbooks\Admin\Plugins\filter_plugins()` supports plugins with differing directory and main file names: [#1419](https://github.com/pressbooks/pressbooks/pull/1419)

### 5.5.4

#### Upgrade Notice

* Pressbooks 5.5.4 requires PHP >= 7.1.
* Pressbooks 5.5.4 requires [WordPress 4.9.8](https://wordpress.org/news/2018/08/wordpress-4-9-8-maintenance-release/).
* Pressbooks 5.5.4 requires [McLuhan >= 2.5.2](https://github.com/pressbooks/pressbooks-book/).

#### Patches

- Allow book admins to enable Parsedown Party from Plugins page: [#1417](https://github.com/pressbooks/pressbooks/pull/1417)

### 5.5.3

#### Upgrade Notice

* Pressbooks 5.5.3 requires PHP >= 7.1.
* Pressbooks 5.5.3 requires [WordPress 4.9.8](https://wordpress.org/news/2018/08/wordpress-4-9-8-maintenance-release/).
* Pressbooks 5.5.3 requires [McLuhan >= 2.5.2](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Optimize TOC and XHTML generation: [#1389](https://github.com/pressbooks/pressbooks/pull/1389), [#1396](https://github.com/pressbooks/pressbooks/pull/1396)
* Prevent stylesheet rebuild stampede ([#1383](https://github.com/pressbooks/pressbooks/issues/1383)): [#1384](https://github.com/pressbooks/pressbooks/pull/1384)

### 5.5.2

#### Upgrade Notice

* Pressbooks 5.5.2 requires PHP >= 7.1.
* Pressbooks 5.5.2 requires [WordPress 4.9.8](https://wordpress.org/news/2018/08/wordpress-4-9-8-maintenance-release/).
* Pressbooks 5.5.2 requires [McLuhan >= 2.5.1](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Scan full book contents for anchors in link insertion tool: [#1345](https://github.com/pressbooks/pressbooks/pull/1345)
* Fix duplication of anchors in link insertion tool: [#1345](https://github.com/pressbooks/pressbooks/pull/#1345)
* Ensure processing of absolute internal links in XHTML and HTMLBook modules ([#1347](https://github.com/pressbooks/pressbooks/issues/1347)): [#1353](https://github.com/pressbooks/pressbooks/pull/1353)
* Eliminate race condition when rebuilding webbook stylesheets: [#1355](https://github.com/pressbooks/pressbooks/pull/1355)
* Disable related videos in YouTube OEmbeds ([#1358](https://github.com/pressbooks/pressbooks/issues/1358)): [#1359](https://github.com/pressbooks/pressbooks/issues/1359)
* Handle Dillard (Plain) 1.x to 2.0 upgrade: [#1361](https://github.com/pressbooks/pressbooks/pull/1361)
* Hide "Welcome to WordPress" everywhere ([#1364](https://github.com/pressbooks/pressbooks/issues/1364)): [#1365](https://github.com/pressbooks/pressbooks/pull/1365)
* Use a file that is guaranteed to remain available for HTMLBook validation: [#1366](https://github.com/pressbooks/pressbooks/issues/1366)
* Always use the filtered stylesheet directory in `\Pressbooks\Styles->customize()` ([#1361](https://github.com/pressbooks/pressbooks/issues/1361)): [#1372](https://github.com/pressbooks/pressbooks/pull/1372)

### 5.5.1

#### Upgrade Notice

* Pressbooks 5.5.1 requires PHP >= 7.1.
* Pressbooks 5.5.1 requires [WordPress 4.9.8](https://wordpress.org/news/2018/08/wordpress-4-9-8-maintenance-release/).
* Pressbooks 5.5.1 requires [McLuhan >= 2.5.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Fixed an issue where cover generator stylesheets were missing from the release package: [#1349](https://github.com/pressbooks/pressbooks/pull/1349)

### 5.5.0

#### Upgrade Notice

* Pressbooks 5.5.0 requires PHP >= 7.1.
* Pressbooks 5.5.0 requires [WordPress 4.9.8](https://wordpress.org/news/2018/08/wordpress-4-9-8-maintenance-release/).
* Pressbooks 5.5.0 requires [McLuhan >= 2.5.0](https://github.com/pressbooks/pressbooks-book/).

#### Minor Changes

- Increase minimum PHP to 7.1 ([#1231](https://github.com/pressbooks/pressbooks/issues/1231)): [15f946b](https://github.com/pressbooks/pressbooks/commit/15f946b1a976bf0082d50bbcc33047f2a9be0679) 
- Add Cover Generator to core: [#1257](https://github.com/pressbooks/pressbooks/pull/1257)
- Update Thema codes to 1.3.0, use localized labels ([#1265](https://github.com/pressbooks/pressbooks/issues/1265), [#1302](https://github.com/pressbooks/pressbooks/issues/1302)): [#1266](https://github.com/pressbooks/pressbooks/pull/1266)
- Improve license output markup (props [@bdolor](https://github.com/bdolor)): [#1268](https://github.com/pressbooks/pressbooks/pull/1268)
- Add support for cloning registered media metadata ([#1280](https://github.com/pressbooks/pressbooks/issues/1280)): [#1337](https://github.com/pressbooks/pressbooks/issues/1337) 
- Add support for all media attachments in cloning operations ([#1281](https://github.com/pressbooks/pressbooks/issues/1281)): [#1334](https://github.com/pressbooks/pressbooks/issues/1334), [#1339](https://github.com/pressbooks/pressbooks/issues/1339)
- Improve cloner accuracy ([#1283](https://github.com/pressbooks/pressbooks/issues/1283)): [#1312](https://github.com/pressbooks/pressbooks/issues/1312)
- Add attribution to images (props [@alex-418](https://github.com/alex-418) and [@bdolor](https://github.com/bdolor)): [#1287](https://github.com/pressbooks/pressbooks/issues/1287), [#1299](https://github.com/pressbooks/pressbooks/issues/1299), [#1321](https://github.com/pressbooks/pressbooks/issues/1321), [#1343](https://github.com/pressbooks/pressbooks/issues/1343)
- Enable TablePress for EPUB/MOBI: [#1293](https://github.com/pressbooks/pressbooks/pull/1293)
- Remove the "Try Gutenberg" panel ([#1296](https://github.com/pressbooks/pressbooks/issues/1296)): [#1308](https://github.com/pressbooks/pressbooks/issues/1308)
- Add new shortcodes to facilitate authoring and import ([#1297](https://github.com/pressbooks/pressbooks/issues/1297)): [#1301](https://github.com/pressbooks/pressbooks/issues/1301), [#1325](https://github.com/pressbooks/pressbooks/issues/1325), [#1336](https://github.com/pressbooks/pressbooks/issues/1336)
- Add the [PagedJS polyfill](https://gitlab.pagedmedia.org/tools/pagedjs) to the PDF debug view: [#1307](https://github.com/pressbooks/pressbooks/issues/1307)
- Improve `register_meta()` usage with object subtypes: [#1309](https://github.com/pressbooks/pressbooks/issues/1309)
- Update TinyMCE to 4.8.2: [#1319](https://github.com/pressbooks/pressbooks/issues/1319)
- Add filters to support SVG in EPUB (props [@lukaiser](https://github.com/lukaiser)): [#1322](https://github.com/pressbooks/pressbooks/issues/1322)
- Add support for QuickLaTeX rendering within TablePress tables (props [@steelwagstaff](https://github.com/steelwagstaff)): [#1340](https://github.com/pressbooks/pressbooks/issues/1340)

#### Patches

- Fix internal links when cloning ([#1279](https://github.com/pressbooks/pressbooks/issues/1279)): [#1310](https://github.com/pressbooks/pressbooks/issues/1310), [#1324](https://github.com/pressbooks/pressbooks/issues/1324)
- Ensure that contributor taxonomies are always registered when needed: [#1300](https://github.com/pressbooks/pressbooks/pull/1300)
- Fix CSS overwriting during simultaneous digital/print PDF export ([#1313](https://github.com/pressbooks/pressbooks/issues/1313)): [#1314](https://github.com/pressbooks/pressbooks/issues/1314)
- Remove multilevel TOC processing for parts: [#1315](https://github.com/pressbooks/pressbooks/issues/1315)
- Fix undefined index in `inc/shortcodes/attributions/class-attachments.php` ([#1316](https://github.com/pressbooks/pressbooks/issues/1316)): [a304925](https://github.com/pressbooks/pressbooks/commit/a30492540e9abdb90a99c2fdf91139969c660166)
- Fix broken internal links in EPUB/MOBI when front matter is automatically reordered ([#1327](https://github.com/pressbooks/pressbooks/issues/1327)): [#1328](https://github.com/pressbooks/pressbooks/issues/1328)
- Fix confusing interaction between browser navigation and Custom Styles page: [#1329](https://github.com/pressbooks/pressbooks/issues/1329)
- Improve session handling to prevent session locking: [#1335](https://github.com/pressbooks/pressbooks/issues/1335)

### 5.4.7

#### Upgrade Notice

* Pressbooks 5.4.7 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.7 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Fix 500 error introduced in [#1318](https://github.com/pressbooks/pressbooks/pull/1318): [#1326](https://github.com/pressbooks/pressbooks/pull/1326)

### 5.4.6

#### Upgrade Notice

* Pressbooks 5.4.6 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.6 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Resolve additional bugs related to default paragraph separation ([#1303](https://github.com/pressbooks/pressbooks/issues/1303)): [#1318](https://github.com/pressbooks/pressbooks/pull/1318)


## 5.4.5

#### Upgrade Notice

* Pressbooks 5.4.5 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.5 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Ensure that default paragraph separation is respected in webbooks ([#1303](https://github.com/pressbooks/pressbooks/issues/1303)): [742e8b9](https://github.com/pressbooks/pressbooks/commit/742e8b973aae5088dfe6b674e6a76ad34ff8b462)


### 5.4.4

* Pressbooks 5.4.4 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.4 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Restore missing ICC profile file: [#1304](https://github.com/pressbooks/pressbooks/pull/1304)
* Fix links to Thema guides ([#1302](https://github.com/pressbooks/pressbooks/issues/1302)): [#1305](https://github.com/pressbooks/pressbooks/pull/1305)

### 5.4.3

#### Upgrade Notice

* Pressbooks 5.4.3 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.3 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Ensure that contributor taxonomy is always registered when needed, fixing an issue where empty author data would be cached: [#1300](https://github.com/pressbooks/pressbooks/pull/1300)


### 5.4.2

#### Upgrade Notice

* Pressbooks 5.4.2 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.2 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Update the TinyMCE table plugin to apply some [upstream bugfixes](https://github.com/tinymce/tinymce-dist/blob/master/changelog.txt#L3-L4): [#1262](https://github.com/pressbooks/pressbooks/pull/1262)
* Improve colour contrast contrast for some TinyMCE buttons and menus ([#1250](https://github.com/pressbooks/pressbooks/issues/1250)): [#1273](https://github.com/pressbooks/pressbooks/pull/1273)
* Restore correct chapter subtitle and author order in EPUB/MOBI exports ([#1271](https://github.com/pressbooks/pressbooks/issues/1271)): [#1274](https://github.com/pressbooks/pressbooks/pull/1274)
* Grant access to the style debugging tool to super admins regardless of `WP_DEBUG` status ([#1272](https://github.com/pressbooks/pressbooks/issues/1272)): [#1275](https://github.com/pressbooks/pressbooks/pull/1275)
* Retain original slug of chapters with differing title and slug during WXR import ([#1276](https://github.com/pressbooks/pressbooks/issues/1276)): [#1277](https://github.com/pressbooks/pressbooks/pull/1277)
* Only force DocRaptor into test mode when in development environments ([#1289](https://github.com/pressbooks/pressbooks/issues/1289)): [#1290](https://github.com/pressbooks/pressbooks/pull/1290)
* Correct the label for the contributor last name field ([#1291](https://github.com/pressbooks/pressbooks/issues/1291)): [#1292](https://github.com/pressbooks/pressbooks/pull/1292)
* Rebuild editor stylesheet on Buckram updates ([#1278](https://github.com/pressbooks/pressbooks/issues/1278), props [@beckej13820](https://github.com/beckej13820) for the bug report): [#1294](https://github.com/pressbooks/pressbooks/pull/1294)

### 5.4.1

#### Upgrade Notice

* Pressbooks 5.4.1 requires [WordPress 4.9.7](https://wordpress.org/news/2018/07/wordpress-4-9-7-security-and-maintenance-release/).
* Pressbooks 5.4.1 requires [McLuhan >= 2.4.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

* Convert iframes to `[embed]` shortcodes rather than deleting them if the user lacks permissions: [#1247](https://github.com/pressbooks/pressbooks/pull/1247)
* Resolve issue where PDF dependencies were incorrectly reported as missing ([#1253](https://github.com/pressbooks/pressbooks/issues/1253)): [#1254](https://github.com/pressbooks/pressbooks/pull/1254)
* Ensure that themes which don't support the new textbox markup use the old textbox markup: [#1252](https://github.com/pressbooks/pressbooks/pull/1252)
* Remove hotfix for WordPress core vulnerability that was patched in WordPress 4.9.7 ([#1255](https://github.com/pressbooks/pressbooks/issues/1255)): [#1258](https://github.com/pressbooks/pressbooks/pull/1258)
* Resolve issue where part content would not be imported from Pressbooks XML files ([#1259](https://github.com/pressbooks/pressbooks/issues/1259)): [#1260](https://github.com/pressbooks/pressbooks/pull/1260)
* Resolve issue where visiting a user catalog would return a 404 status code instead of the correct 200 status code: [#1261](https://github.com/pressbooks/pressbooks/pull/1261)

### 5.4.0

#### Upgrade Notice

- Pressbooks 5.4.0 requires [WordPress 4.9.6](https://github.com/pressbooks/pressbooks/releases/5.4.0).
- Pressbooks 5.4.0 requires [McLuhan 2.4.0](https://github.com/pressbooks/pressbooks-book/releases/2.4.0).

#### Minor Changes

- Add support for PDF exports via [DocRaptor](https://docraptor.com) to Pressbooks core ([#1238](https://github.com/pressbooks/pressbooks/issues/1238)): [#1240](https://github.com/pressbooks/pressbooks/pull/1240)
- Bump minimum supported WordPress to 4.9.6: [#1237](https://github.com/pressbooks/pressbooks/pull/1237)
- Add support for WordPress 4.9.6 privacy policy management: [#1236](https://github.com/pressbooks/pressbooks/pull/1236)
- Improve admin bar for network administrators and network managers: [#1226](https://github.com/pressbooks/pressbooks/pull/1226), [#1232](https://github.com/pressbooks/pressbooks/pull/1232), [#1234](https://github.com/pressbooks/pressbooks/pull/1234)
- Improve educational textbox markup, add sidebar textboxes: [#1210](https://github.com/pressbooks/pressbooks/pull/1210)
- Allow default book cover image to be filtered, add size parameter: [#1214](https://github.com/pressbooks/pressbooks/pull/1214)
- Allow access to webbook sharing & visibility settings to be restricted by a filter: [#1239](https://github.com/pressbooks/pressbooks/pull/1239)
- Bump tinymce from 4.7.12 to 4.7.13: [#1213](https://github.com/pressbooks/pressbooks/pull/1213)
- Bump leafo/scssphp from 0.7.5 to 0.7.6: [#1223](https://github.com/pressbooks/pressbooks/pull/1223)

#### Patches

- Allow usernames to be an email address in the catalog rewrite rule (props [@lukaiser](https://github.com/lukaiser)): [#1216](https://github.com/pressbooks/pressbooks/pull/1216)
- Ensure that classnames are output properly for EPUB table of contents: [#1224](https://github.com/pressbooks/pressbooks/pull/1224)
- Improve `reverse_wpautop()` function to avoid stripping newlines from within `<pre>` tags during import and clone operations ([#1225](https://github.com/pressbooks/pressbooks/issues/1225), props [@SteelWagstaff](https://github.com/SteelWagstaff) for reporting): [#1227](https://github.com/pressbooks/pressbooks/pull/1227)
- Enable `$concatenate_scripts` and remove unused admin JS dependency: [#1233](https://github.com/pressbooks/pressbooks/pull/1233)
- Use polyfills to avoid warnings in PHP 7.2 environment: [#1237](https://github.com/pressbooks/pressbooks/pull/1237)
- Fix an issue where PDF internal links would not function as expected: [#1245](https://github.com/pressbooks/pressbooks/pull/1245)
- Lower personal data export cron frequency to twicedaily ([#1242](https://github.com/pressbooks/pressbooks/issues/1242)): [#1246](https://github.com/pressbooks/pressbooks/pull/1246)
- Increase HTTP timeout for the Prince and DocRaptor PDF export modules to PHP `max_execution_time` (props [@rootl](https://github.com/rootl) for the bug report): [#1248](https://github.com/pressbooks/pressbooks/pull/1248)
- Fix the suppression of TOC part and chapter numbers for Buckram 1.0 themes: [#1249](https://github.com/pressbooks/pressbooks/pull/1249)

### 5.3.4

#### Patches

- Hotfix for [WordPress core security issue](https://blog.ripstech.com/2018/wordpress-file-delete-to-code-execution/): [a462e0d](https://github.com/pressbooks/pressbooks/commit/a462e0d/)

### 5.3.3

#### Patches

- Fix EPUB internal links by stripping trailing slash before `#`: [#1222](https://github.com/pressbooks/pressbooks/pull/1222)

### 5.3.2

#### Patches

- Fix a bug with `fetchAndSaveUniqueImage` and `fetchAndSaveUniqueFont` methods introduced in [0c84a5d](https://github.com/pressbooks/pressbooks/commit/0c84a5deb5d603d97ddf9745fcf4792275c36bc5): [#1220](https://github.com/pressbooks/pressbooks/pull/1220)
- Use `wp dist-archive` to build release asset [#1219](https://github.com/pressbooks/pressbooks/issues/1219): [#1221](https://github.com/pressbooks/pressbooks/pull/1221)

### 5.3.1

#### Patches

- Fix ODT export errors caused by images with percentage width or height attributes: [#1215](https://github.com/pressbooks/pressbooks/pull/1215)
- Improve `$_SESSION` handling: [#1217](https://github.com/pressbooks/pressbooks/pull/1217)
- Fix display issue when login screen buttons require multiple lines: [283e570](https://github.com/pressbooks/pressbooks/commit/283e5707b35fd0ad28e3f155b65d9df7de6927d6)
- Fix display issue with mobile content editor: [1efb2c7](https://github.com/pressbooks/pressbooks/commit/1efb2c73b2de9c67a21304fd6013524c37159cdc)

### 5.3.0

- Pressbooks 5.3.0 requires [WordPress 4.9.5](https://wordpress.org/news/2018/04/wordpress-4-9-5-security-and-maintenance-release/).
- Pressbooks 5.3.0 requires [McLuhan >= 2.3.0](https://github.com/pressbooks/pressbooks-book/).

#### Minor Changes

- Add theme option for comparison with source ([pressbooks/pressbooks-book#152](https://github.com/pressbooks/pressbooks-book/issues/152)): [#1203](https://github.com/pressbooks/pressbooks/pull/1203)
- Add global theme option for educational textbox colors: [#1189](https://github.com/pressbooks/pressbooks/pull/1189), [#1194](https://github.com/pressbooks/pressbooks/pull/1194)
- Add web theme option for collapsing sections: [#1181](https://github.com/pressbooks/pressbooks/pull/1181)
- Add network integrations menu: [#1195](https://github.com/pressbooks/pressbooks/pull/1195)
- Add programmatic login function for SSO extensions: [#1196](https://github.com/pressbooks/pressbooks/pull/1196)
- Add export page hooks for customization (props [@lukaiser](https://github.com/lukaiser)): [#1205](https://github.com/pressbooks/pressbooks/pull/1205) (no notes for testing)
- Restore some default TinyMCE table controls: [#1193](https://github.com/pressbooks/pressbooks/pull/1193)
- Replace Creative Commons API usage with built-in license string generation ([#1170](https://github.com/pressbooks/pressbooks/issues/1170)): [#1201](https://github.com/pressbooks/pressbooks/pull/1201), [#1202](https://github.com/pressbooks/pressbooks/pull/1202)
- Improve support for WP QuickLaTeX: [#1200](https://github.com/pressbooks/pressbooks/pull/1200)
- Add a debug parameter to XHTML and HTMLBook URLs for export CSS previewing: [#1183](https://github.com/pressbooks/pressbooks/pull/1183)
- Add a new `Styles::hasBuckram()` helper method with optional version parameter: [#1187](https://github.com/pressbooks/pressbooks/pull/1187)
- Disallow certain taxonomies based on a blacklist instead of a whitelist ([#1095](https://github.com/pressbooks/pressbooks/issues/1095)): [#1172](https://github.com/pressbooks/pressbooks/pull/1172)
- Disable SSL verification for self-signed certificates in development environments: [#1191](https://github.com/pressbooks/pressbooks/pull/1191)
- Improve requires so that other plugins can efficiently use them: [#1179](https://github.com/pressbooks/pressbooks/pull/1179)
- Ignore SASS variables prefixed with `_` in the `parseVariables()` method: [#1188](https://github.com/pressbooks/pressbooks/pull/1188)
- Use less memory in createFileFromUrl (props [@bdolor](https://github.com/bdolor)): [#1211](https://github.com/pressbooks/pressbooks/pull/1211)
- Update minimum WordPress version to 4.9.5 ([#1176](https://github.com/pressbooks/pressbooks/issues/1176)): [#1178](https://github.com/pressbooks/pressbooks/pull/1178)
- Update Pressbooks CLI to 1.8.2: [fd6d2b1](https://github.com/pressbooks/pressbooks/commit/fd6d2b15b7e4387435a498e6e2a007b83e47712d)
- Update Isotope to 3.0.6: [#1177](https://github.com/pressbooks/pressbooks/pull/1177)
- Update TinyMCE Table plugin to 4.7.12: [#1208](https://github.com/pressbooks/pressbooks/pull/1208)

#### Patches

- Hide link to book info on the front end: [#1207](https://github.com/pressbooks/pressbooks/pull/1207)
- Fix bug with internal links in EPUB with content not marked for export: ([#1209](https://github.com/pressbooks/pressbooks/issues/1209)): [#1212](https://github.com/pressbooks/pressbooks/pull/1212)
- Fix paragraph separation web theme option for Custom CSS theme: [#1180](https://github.com/pressbooks/pressbooks/pull/1180)
- Prepare fix for numbering issue in front matter that follow the introduction ([#1197](https://github.com/pressbooks/pressbooks/issues/1197)): [#1198](https://github.com/pressbooks/pressbooks/pull/1198)
- Prevent slug collisions in XHTML and HTMLBook outputs ([#1174](https://github.com/pressbooks/pressbooks/issues/1174)): [#1175](https://github.com/pressbooks/pressbooks/pull/1175)

### 5.2.1

#### Upgrade Notice

- Pressbooks 5.2.1 requires [WordPress 4.9.4](https://wordpress.org/news/2018/02/wordpress-4-9-4-maintenance-release/).
- Pressbooks 5.2.1 requires [McLuhan >= 2.2.0](https://github.com/pressbooks/pressbooks-book/).

#### Patches

- Patch [select2](https://github.com/select2/select2) and [Custom Metadata Manager](https://github.com/Automattic/custom-metadata) to save multiselect data in the specified order: [#1167](https://github.com/pressbooks/pressbooks/pull/1167)
- Fix an edge case where invalid author data would persist following upgrade to Pressbooks 5: [#1168](https://github.com/pressbooks/pressbooks/pull/1168)
- Fix focus style for admin menu icons: [#1169](https://github.com/pressbooks/pressbooks/pull/1169)
- Allow super admins to access network theme and plugin menus directly: [#1169](https://github.com/pressbooks/pressbooks/pull/1169)
- Remove unit test that was failing due to inaccessible Creative Commons API: [#1171](https://github.com/pressbooks/pressbooks/pull/1171)

### 5.2.0

#### Minor Changes

- Add book navigation to the edit screen ([#1150](https://github.com/pressbooks/pressbooks/issues/1150); props to [Justin Swapp](https://twitter.com/justinswapp) for the suggestion): [#1164](https://github.com/pressbooks/pressbooks/issues/1164)
- Add book source URL to Book Info for cloned books ([#1152](https://github.com/pressbooks/pressbooks/issues/1152)): [#1166](https://github.com/pressbooks/pressbooks/issues/1166)
- Optimize chapter numbering functions: [#1165](https://github.com/pressbooks/pressbooks/issues/1165)

### 5.1.1

#### Patches

- Fix some bugs in the `Book::get()` method: [6da412c](https://github.com/pressbooks/pressbooks/commit/6da412c)
- Fix an issue where network administers were not able to clone a restrictively-licensed book within their own network ([#1157](https://github.com/pressbooks/pressbooks/issues/1157)): [#1162](https://github.com/pressbooks/pressbooks/issues/1162)
- Add support for WordPress `[audio]` and `[video]` source parameters other than `src` ([#1159](https://github.com/pressbooks/pressbooks/issues/1159), props to [Michael Shiflet](https://discourse.pressbooks.org/u/shiflet.16/) on [Discourse](https://discourse.pressbooks.org/t/shortcode-and-fallbacks/439) for reporting): [#1161](https://github.com/pressbooks/pressbooks/issues/1161) 
- Ensure that fallback webbook content styles are generated for books using the deprecated Custom CSS theme: [#1160](https://github.com/pressbooks/pressbooks/issues/1160)
- Add revisions support to parts (props to [Naomi Salmon](https://discourse.pressbooks.org/u/Naomi_Salmon) on [Discourse](https://discourse.pressbooks.org/t/revision-history-in-parts/440) for reporting): [#1158](https://github.com/pressbooks/pressbooks/issues/1158)
- Fix an uncaught exception ("Mismatch between length of FootnoteReference array number of footnotes available") when importing Word documents: [#1156](https://github.com/pressbooks/pressbooks/issues/1156) 
- Fix a fatal error ("Too many open files") when exporting books with lots of images to EPUB: [#1155](https://github.com/pressbooks/pressbooks/issues/1155)
- Update Pressbooks CLI to 1.8.0: [#1154](https://github.com/pressbooks/pressbooks/issues/1154)
- Fix an issue where importing HTML would result in an empty chapter ([#1148](https://github.com/pressbooks/pressbooks/issues/1148), props to [@josieg](https://github.com/josieg) for reporting): [#1153](https://github.com/pressbooks/pressbooks/issues/1153) 
- Fix a notice ("Undefined index: css in pb-latex.php on line 98") when visiting the webbook of a freshly cloned book: [#1147](https://github.com/pressbooks/pressbooks/issues/1147) 


### 5.1.0

#### Minor Changes

- Add support for interactive content with fallbacks for ebook and PDF exports: [#1135](https://github.com/pressbooks/pressbooks/pull/1135)
- Restore support for password-protected webbook content: [#1144](https://github.com/pressbooks/pressbooks/pull/1144)

#### Patches

- Hide "Add Part" menu for users who can't edit parts (props [@colomet](https://github.com/colomet) for reporting): [12ab81e](https://github.com/pressbooks/pressbooks/commit/12ab81e0808f049235e3b2647681e38af272685f)
- Fix an issue where PDF page numbering didn't reset in books without an introduction: [#1141](https://github.com/pressbooks/pressbooks/pull/1141)
- Fix an issue where ODT exports would fail: [#1146](https://github.com/pressbooks/pressbooks/pull/1146)

### 5.0.2

#### Patches

* Remove debugging code (props @colomet for reporting): [6a3c9e8](https://github.com/pressbooks/pressbooks/commit/6a3c9e834666928c3a4240908dd964a3e8c02ff7)

### 5.0.1
#### Patches

* Ensure that iframes aren't removed during the `PressbooksMetadata::upgradeToPressbooksFive()` method: [#1138](https://github.com/pressbooks/pressbooks/pull/1138)
* Add parts with readable content to the book navigation order (props to [@beckej13820](https://github.com/beckej13820) for reporting): [#1136](https://github.com/pressbooks/pressbooks/pull/1136)
* Restore link to view current content from admin bar (props to [@colomet](https://github.com/colomet) for reporting): [#1132](https://github.com/pressbooks/pressbooks/issues/1132), [#1134](https://github.com/pressbooks/pressbooks/pull/1134)
* Use MySQL transactions to optimize `PressbooksMetadata::upgradeToPressbooksFive()`: [#1133](https://github.com/pressbooks/pressbooks/pull/1133)
* Optimize `pb_get_chapter_number()`: [#1128](https://github.com/pressbooks/pressbooks/pull/1128)
* Fix missing login screen logo: [#1129](https://github.com/pressbooks/pressbooks/pull/1129)
* Fix `"Invalid argument supplied for foreach"` warning by handling `false` return values from `get_post_meta()`: [#1128](https://github.com/pressbooks/pressbooks/pull/1128)
* Fix `"Directory not empty"` warning in `PressbooksRedirectmigrate_generated_content()` by moving action to `plugins_loaded` hook: [#1127](https://github.com/pressbooks/pressbooks/pull/1127)
* Bump tinymce to 4.7.9: [#1125](https://github.com/pressbooks/pressbooks/pull/1125), [#1126](https://github.com/pressbooks/pressbooks/pull/1126)

### 5.0.0

**NOTICE:** Pressbooks 5.0.0 requires [WordPress 4.9.4](https://wordpress.org/news/2018/02/wordpress-4-9-4-maintenance-release/).  
**NOTICE:** Pressbooks 5.0.0 requires [Pressbooks Book 2.0.0](https://github.com/pressbooks/pressbooks-book/).  
**NOTICE:** Pressbooks 5.0.0 requires that users of the Luther book theme install and network activate the standalone [Luther theme](https://github.com/pressbooks/pressbooks-luther/) _before_ upgrading to Pressbooks 5.0. For more information, see the [upgrading instructions](https://docs.pressbooks.org/upgrading/#upgrading-to-pressbooks-5-x).

#### Key Features

_Contributor Management_

We’ve added a centralized contributor management tool where you can add contributors who can then be reused throughout your book as authors, editors, translators, reviewers, illustrators, and generic contributors.

_Changes to the Organize Page & Section Visibility_

We’ve made a few key changes to the Organize page in this release. The first is to add keyboard navigation, which has been a known shortcoming in the interface, and some improvements for those using screen readers, both for accessibility. We’ve also improved the display on mobile devices. 

Included in this is a change to handling chapter/section visibility, both in the Organize page and editing interface. Each chapter now has two simple controls — “Show in Web” and “Show in Exports” — which do exactly what you would expect.

_Chapter Importing_

Building on the book cloning feature, we have introduced the ability to easily import individual chapters from Pressbooks webbooks using the import tool. We’ve also added the ability to upload supported files from remote (web-based) sources.

#### Detailed Changelog

* **Feature**: Contributors! We’ve added a centralized contributor management tool where you can add contributors who can then be reused throughout your book as authors, editors, translators, reviewers, illustrators, and generic contributors (see [#989](https://github.com/pressbooks/pressbooks/issues/989), [#1017](https://github.com/pressbooks/pressbooks/issues/1017), [#1020](https://github.com/pressbooks/pressbooks/issues/1020), [#1031](https://github.com/pressbooks/pressbooks/issues/1031), [#1033](https://github.com/pressbooks/pressbooks/issues/1033), [#1038](https://github.com/pressbooks/pressbooks/issues/1038), [#1047](https://github.com/pressbooks/pressbooks/issues/1047), [#1060](https://github.com/pressbooks/pressbooks/issues/1060), [#1086](https://github.com/pressbooks/pressbooks/issues/1086), [#1087](https://github.com/pressbooks/pressbooks/issues/1087), [#1088](https://github.com/pressbooks/pressbooks/issues/1088), [#1098](https://github.com/pressbooks/pressbooks/pull/1098), and [#1100](https://github.com/pressbooks/pressbooks/pull/1100)).
* **Feature**: Re-Organizing! We’ve overhauled the Organize page, improving the display on mobile devices, and improving accessibility for keyboard navigation and screen reader users (see [#305](https://github.com/pressbooks/pressbooks/issues/305), [#1009](https://github.com/pressbooks/pressbooks/issues/1009), [#1046](https://github.com/pressbooks/pressbooks/issues/1046), and [aa75269](https://github.com/pressbooks/pressbooks/commit/aa75269a5c3ee5d369ef3b128028bf49632b96de)).
* **Feature**: Content Visibility! We’ve made it more intuitive to manage the visibility of your content across web and exports on both the Organize page and the edit screen for individual front matter, chapters and back matter (see [#1017](https://github.com/pressbooks/pressbooks/issues/1017), [#1033](https://github.com/pressbooks/pressbooks/issues/1033), [#1046](https://github.com/pressbooks/pressbooks/issues/1046), [#1060](https://github.com/pressbooks/pressbooks/issues/1060), [#1067](https://github.com/pressbooks/pressbooks/issues/1067), [#1121](https://github.com/pressbooks/pressbooks/issues/1121), and [#1122](https://github.com/pressbooks/pressbooks/pull/1122)).
* **Feature**: Chapter Importing! We’ve added support for importing individual chapters from Pressbooks webbooks using the Import tool. We’ve also added support for importing all supported file types from local (upload) or remote (web-based) sources (see [#1054](https://github.com/pressbooks/pressbooks/issues/1054), [#1057](https://github.com/pressbooks/pressbooks/issues/1057), [#1089](https://github.com/pressbooks/pressbooks/issues/1089), [#1091](https://github.com/pressbooks/pressbooks/issues/1091), [#1092](https://github.com/pressbooks/pressbooks/issues/1092), [#1093](https://github.com/pressbooks/pressbooks/issues/1093), [#1098](https://github.com/pressbooks/pressbooks/pull/1098), [#1111](https://github.com/pressbooks/pressbooks/pull/1111), [#1117](https://github.com/pressbooks/pressbooks/pull/1117), and [#1119](https://github.com/pressbooks/pressbooks/pull/1119)).
* **Feature**: HTMLBook! We’ve added a class which describes the [HTMLBook](http://oreillymedia.github.io/HTMLBook/) Draft Specification and a proof-of-concept HTMLBook export module (see [#830](https://github.com/pressbooks/pressbooks/issues/830), [#1002](https://github.com/pressbooks/pressbooks/issues/1002), [#1003](https://github.com/pressbooks/pressbooks/issues/1003), [#1032](https://github.com/pressbooks/pressbooks/issues/1032), [#1042](https://github.com/pressbooks/pressbooks/issues/1042), [#1043](https://github.com/pressbooks/pressbooks/issues/1043), and [#1062](https://github.com/pressbooks/pressbooks/issues/1062)).
* **Core Enhancement**: When a Pressbooks update is available, you'll also get some information on the compatibility of any installed Pressbooks add-ons with the new version. Plugins can declare compatibility by adding "Pressbooks tested up to: 5.0.0" to the [plugin header](https://developer.wordpress.org/plugins/the-basics/header-requirements/). This feature was inspired by recent improvements to [WooCommerce](https://woocommerce.wordpress.com/2017/08/28/new-version-check-in-woocommerce-3-2/) (see [#955](https://github.com/pressbooks/pressbooks/issues/955) and [#1115](https://github.com/pressbooks/pressbooks/pull/1115)).
* **Core Enhancement**: We’ve restyled the login screen to better integrate with the Pressbooks look and feel (see [#929](https://github.com/pressbooks/pressbooks/issues/929) and [#1069](https://github.com/pressbooks/pressbooks/issues/1069)).
* **Core Enhancement**: We’ve moved the Ebook start point setting to the Ebook Theme Options page to ensure that only one front matter, chapter, or back matter can be set as the Ebook start point (see [#1046](https://github.com/pressbooks/pressbooks/issues/1046), [#1053](https://github.com/pressbooks/pressbooks/issues/1053), and [aa75269](https://github.com/pressbooks/pressbooks/commit/aa75269a5c3ee5d369ef3b128028bf49632b96de)).
* **Core Enhancement**: We’ve renamed the _Language Support_ section in Theme Options to _Language & Script Support_ to better reflect its functionality; we’ve also re-labelled Hindi support to Devanagari, to clarify that the Devanagari script supports Hindi, Sanskrit, and over 120 other languages (see [#1023](https://github.com/pressbooks/pressbooks/issues/1023) and [#1025](https://github.com/pressbooks/pressbooks/issues/1025)).
* **Core Enhancement**: We’ve moved user generated content to a `/pressbooks` directory within your book’s uploads directory to prevent possible conflicts with other plugins (see [#1013](https://github.com/pressbooks/pressbooks/issues/1013)).
* **Core Enhancement**: Books using themes built with our Buckram theme library will now use improved markup for front matter, back matter, and chapter headings (see [#1035](https://github.com/pressbooks/pressbooks/issues/1035), [#1045](https://github.com/pressbooks/pressbooks/issues/1045) and [#1063](https://github.com/pressbooks/pressbooks/issues/1063)).
* **Core Enhancement**: We’ve added a routine to support Luther’s migration to a standalone theme (see [#986](https://github.com/pressbooks/pressbooks/issues/986), [#1016](https://github.com/pressbooks/pressbooks/issues/1016), [#1090](https://github.com/pressbooks/pressbooks/issues/1090), and [#1104](https://github.com/pressbooks/pressbooks/pull/1104)).
* **Core Enhancement**: We've added a routine to recompile the webbook stylesheet when the bundled version of [Buckram](https://github.com/pressbooks/buckram) is updated (see [#1120](https://github.com/pressbooks/pressbooks/pull/1120)).
* **Core Enhancement**: We’ve added a debugging routine to prettify XHTML and HTMLBook output for readability (see [#1036](https://github.com/pressbooks/pressbooks/issues/1036)).
* **Core Enhancement**: We've added an experimental batch endpoint to the Pressbooks REST API, which allows multiple operations to be performed with a single HTTP request (see [#1062](https://github.com/pressbooks/pressbooks/issues/1062)). This is currently not documented or supported and we don't encourage anyone to use it yet.
* **Core Enhancement**: We've moved license types into a taxonomy (see [#989](https://github.com/pressbooks/pressbooks/issues/989), [#1010](https://github.com/pressbooks/pressbooks/issues/1010), [#1033](https://github.com/pressbooks/pressbooks/issues/1033), [#1040](https://github.com/pressbooks/pressbooks/issues/1040), [#1044](https://github.com/pressbooks/pressbooks/issues/1044), [#1066](https://github.com/pressbooks/pressbooks/issues/1066), [#1112](https://github.com/pressbooks/pressbooks/pull/1112), and [#1123](https://github.com/pressbooks/pressbooks/pull/1123)).
* **Core Enhancement**: We've added a new action hook, `pb_cache_delete`, which runs when the book object cache is deleted (see [#1066](https://github.com/pressbooks/pressbooks/issues/1066)).
* **Core Enhancement**: Custom post types and taxonomies are now registered using [@johnbillion](https://github.com/johnbillion)'s excellent Extended CPTs library (see [#989](https://github.com/pressbooks/pressbooks/issues/989), [#1015](https://github.com/pressbooks/pressbooks/issues/1015), and [#1030](https://github.com/pressbooks/pressbooks/issues/1030)).
* **Core Enhancement**: We’re now using WordPress’ custom_menu_order and menu_order filters to adjust the admin menu instead of custom code (see [#989](https://github.com/pressbooks/pressbooks/issues/989)).
* **Core Enhancement**: The `getBookStructure()` method now populates a `_web_lookup` array to reflect differences between webbook and export contents (see [#1085](https://github.com/pressbooks/pressbooks/pull/1085)).
* **Core Enhancement**: The `updateWebbookStylesheet()` method now supports an optional `$stylesheet` parameter to allow the compilation of an arbitrary theme's stylesheet (see [#1099](https://github.com/pressbooks/pressbooks/pull/1099)).
* **Core Enhancement**: We've updated the Pressbooks CLI to 1.6.0 (see [#1118](https://github.com/pressbooks/pressbooks/pull/1118) and the [release notes](https://github.com/pressbooks/pb-cli/releases/tag/1.6.0)).
* **Core Enhancement**: We’ve updated to the latest version of the [Human Made Coding Standards](https://github.com/humanmade/coding-standards) and fixed our code for compatibility (see [#1001](https://github.com/pressbooks/pressbooks/issues/1001)).
* **Core Enhancement**: We’ve updated to version 4.4 of the [plugin-update-checker](https://github.com/yahniselsts/plugin-update-checker) library (see [#1001](https://github.com/pressbooks/pressbooks/issues/1001) and [#1017](https://github.com/pressbooks/pressbooks/issues/1017)).
* **Core Enhancement**: We’ve updated to version 0.7.5 of the [scssphp](https://github.com/leafo/scssphp) library (see [#1110](https://github.com/pressbooks/pressbooks/pull/1110)).
* **Fix**: We fixed a bug where internal links would not work in EPUB and MOBI exports if chapter slugs began with a numeric character (see [#1026](https://github.com/pressbooks/pressbooks/issues/1026) and [#1027](https://github.com/pressbooks/pressbooks/issues/1027); props to [@luis-r-izquierdo](https://github.com/luis-r-izquierdo) for the bug report).
* **Fix**: We fixed a bug where Discussion settings would appear on the Book Information page in the admin interface (see [#1014](https://github.com/pressbooks/pressbooks/issues/1014); props to [@colomet](https://github.com/colomet) for the bug report).
* **Fix**: We fixed a bug where users without edit permissions would be able to drag and drop front matter, chapter, and back matter on the Organize page (see [#305](https://github.com/pressbooks/pressbooks/issues/305) and [#1046](https://github.com/pressbooks/pressbooks/issues/1046); props to [@pbstudent](https://github.com/pbstudent) for the bug report).
* **Fix**: We fixed a bug where users without the necessary permissions were able to see the Book Information menu even though they couldn't visit the page (see [#1083](https://github.com/pressbooks/pressbooks/issues/1083) and [1c1889e](https://github.com/pressbooks/pressbooks/commit/1c1889eb3282d1c75a60c72957b621a8d600fd3c); props to [@thomasdumm](https://github.com/thomasdumm/) for the bug report)
* **Fix**: We fixed a bug where Google Analytics settings for books were not functioning properly for some users (see [#1018](https://github.com/pressbooks/pressbooks/issues/1018) and [#1041](https://github.com/pressbooks/pressbooks/issues/1041)).
* **Fix**: We fixed a bug where “the kitchen sink” toolbar appeared for rich text fields on the Book Information page (see [#1029](https://github.com/pressbooks/pressbooks/issues/1029)).
* **Fix**: We switched back to our own directory deletion routine to prevent a "Too many open files" error caused by `RecursiveDirectoryIterator` (see [#1070](https://github.com/pressbooks/pressbooks/issues/1070) and [#1074](https://github.com/pressbooks/pressbooks/issues/1074)).
* **Fix**: We fixed a JS syntax error on the Book Information page (see [#1072](https://github.com/pressbooks/pressbooks/issues/1072)).
* **Fix**: We fixed an error that occurred when attempted to parse a date from an invalid timestamp (see [#1070](https://github.com/pressbooks/pressbooks/issues/1070)).
* **Fix**: We fixed a couple of PHP warnings produced by the Creative Commons license module (see [#1005](https://github.com/pressbooks/pressbooks/issues/1005) and [#1006](https://github.com/pressbooks/pressbooks/issues/1006)).
* **Fix**: We fixed a few PHP notices related to the API (see [#1034](https://github.com/pressbooks/pressbooks/issues/1034) and [#1037](https://github.com/pressbooks/pressbooks/issues/1037)).
* **Fix**: We added a link to the registration page from the dashboard for users without books (see [#1102](https://github.com/pressbooks/pressbooks/issues/1102) and [#1106](https://github.com/pressbooks/pressbooks/pull/1106); props to [@thomasdumm](https://github.com/thomasdumm/) for the bug report).
* **Fix**: We fixed a bug where the part selection dropdown would not appear when editing a chapter (see [#1081](https://github.com/pressbooks/pressbooks/issues/1081) and [7fa5871](https://github.com/pressbooks/pressbooks/commit/7fa58719619fb07a79012b5884c272b19a574852)).
* **Fix**: We fixed a bug where the slug metabox would appear on the Book Information page (see [#1094](https://github.com/pressbooks/pressbooks/issues/1094) and [#1098](https://github.com/pressbooks/pressbooks/pull/1098)).

### 4.5.1

**NOTICE:** Pressbooks >= 4.5.1 requires [WordPress 4.9.2](https://wordpress.org/news/2018/01/wordpress-4-9-2-security-and-maintenance-release/).

* **[FIX]**: Disallow dangerous file types from upload via the Import form ([9bcebf1](https://github.com/pressbooks/pressbooks/commit/9bcebf1))
* **[FIX]**: Handle `author` objects containing multiple authors during clone operations for forward-compatibility with Pressbooks 5 ([9231ffa](https://github.com/pressbooks/pressbooks/commit/9231ffa), [b0e03c4](https://github.com/pressbooks/pressbooks/commit/b0e03c4), [035c1b9](https://github.com/pressbooks/pressbooks/commit/035c1b9))

### 4.5.0

**NOTICE:** Pressbooks >= 4.5 requires [PHP 7.0](https://secure.php.net/supported-versions.php) or greater.
**NOTICE:** Pressbooks >= 4.5 requires [WordPress 4.9.1](https://wordpress.org/news/2017/11/wordpress-4-9-1-security-and-maintenance-release/).

* **[FEATURE]** Switching to a new theme will now update some PDF theme options to match the theme's values (see #456, #984).
* **[FEATURE]** Add initial support to PDF and Ebook theme options for themes which skip lines between paragraphs by default (see #985).
* **[CORE ENHANCEMENT]** Use standard build tools package [pressbooks-build-tools](https://www.npmjs.com/package/pressbooks-build-tools) for asset handling, upgrade Stylelint (see #1000).
* **[CORE ENHANCEMENT]** Require PHP 7.0 or greater (see #935, #987).
* **[CORE ENHANCEMENT]** Add exclude and include support to `PressbooksUtilityrcopy()` (see #990).
* **[CORE ENHANCEMENT]** Improve Theme Lock feature in preparation for Pressbooks 5.0 (see #995).
* **[CORE ENHANCEMENT]** Add Prettier for SCSS and JS formatting (see #991).
* **[CORE ENHANCEMENT]** Optimize subsection parsing (see #992).
* **[CORE ENHANCEMENT]** Optimize `__UNSET__` style (see #999).
* **[CORE ENHANCEMENT]** Optimize unit testing (see #997).
* **[FIX]** Replace 'Sites' with 'Books' throughout Pressbooks interface (see #993).
* **[FIX]** Replace 'Exotic formats' with 'Other formats' on the Export page (see #996).
* **[FIX]** Fix bug related to [#42574](https://core.trac.wordpress.org/ticket/42574) which prevented widget editing on the root blog (#998).
* **[FIX]** Fix type mismatch in `PressbooksLicensing` class (see [23ee4ff](https://github.com/pressbooks/pressbooks/commit/23ee4ffee60b585d1390690af627c455bf969883))
* **[FIX]** Fix typo in EPUB exporter — the acronym is OEBPS (Open eBook Publication Structure) (props @bdolor; see #988).

### 4.4.0

**NOTICE:** Pressbooks >= 4.4 requires [WordPress 4.9][1].

*   **[FEATURE]** You can now assign [Thema][2] subject categories to your book on the Book Information page (see #978).
*   **[FEATURE]** Part slugs are now editable (props to @colomet for the suggestion; see 3f5eca2).
*   **[CORE ENHANCEMENT]** Pressbooks now uses WordPress’ included [CodeMirror][3] scripts and styles for our Custom Styles editor (see #980).
*   **[CORE ENHANCEMENT]** Added the `pb_global_components_path` filter which lets book themes override the global components path to point to their own bundled components libraries (see #982).
*   **[CORE ENHANCEMENT]** Added the `pb_pre_export` action to allow tweaks prior to an export routine (see 5302eea).
*   **[CORE ENHANCEMENT]** Our `app()` function now matches Laravel 5.4’s function signature (see cdcb9e8).
*   **[FIX]** Importing a Word document with multiple images now works properly (props to @rootl for the bug report; see #288 and #977).
*   **[FIX]** Chapters will now correctly inherit their book’s license in the API (see #979).
*   **[FIX]** Chapters will no longer show raw content in the API if they are password-protected (see #975).
*   **[FIX]** Uploading an image to the user catalog no longer causes an error (props to @emasters for the bug report; see #983).

### 4.3.5

**NOTICE:** Pressbooks >= 4.3.3 requires WordPress 4.8.2.  
**NOTICE:** Users of the Pressbooks Custom CSS theme must upgrade to Pressbooks Custom CSS 1.0 for compatibility with Pressbooks >= 4.3.0.

*   **[CORE ENHANCEMENT]** Use Laravel Container instead of Pimple as our service container; add Laravel Blade support for future templated outputs (see #831, #962, and #970).
*   **[FIX]** Content imported from EPUB is now ordered by spine order instead of manifest order (props to @hakkim-pits; see #442 and #968). 
*   **[FIX]** Custom styles are no longer sanitized in ways that improperly encode characters (see #972).
*   **[FIX]** Sanitize body font size PDF theme option as a float instead of an integer to allow more size options (see #969).
*   **[FIX]** `home_url` is now used instead of `site_url` when linking to front-end content (see #971; reference: https://github.com/roots/bedrock/pull/316).
*   **[FIX]** Shortcodes will now be cloned as is to preserve more footnote and LaTeX data (see #973).
*   **[FIX]** Special characters in a book title will no longer lead to filename issues under certain circumstances (see #974).

### 4.3.4

**NOTICE:** Pressbooks >= 4.3.3 requires WordPress 4.8.2.  
**NOTICE:** Users of the Pressbooks Custom CSS theme must upgrade to Pressbooks Custom CSS 1.0 for compatibility with Pressbooks >= 4.3.0.

*   **[CORE ENHANCEMENT]** The user catalog title can now be changed via the `pb_catalog_title` filter (props to @monkecheese; see #961).
*   **[CORE ENHANCEMENT]** SCSS variables from theme options will now be passed to the SCSS compiler as key/value pairs rather than by building SCSS in PHP (see #782 and #963).
*   **[FIX]** Fixed an issue where the PDF margins theme option was not being applied properly.
*   **[FIX]** Fixed a conflict between the updated Pressbooks LaTeX module and third-party renderers (props to @monkecheese; see #958 and #959).
*   **[FIX]** The publication date should now save properly, regardless of book language (thanks to @thomasdumm for the bug report; see #965 and #966).

### 4.3.3

**NOTICE:** Pressbooks 4.3.3 requires WordPress 4.8.2.  
**NOTICE:** Users of the Pressbooks Custom CSS theme must upgrade to Pressbooks Custom CSS 1.0 for compatibility with Pressbooks 4.3.3.

*   **[CORE ENHANCEMENT]** The Pressbooks plugin is now self-updating — GitHub Updater is no longer required (see #897 and #954).
*   **[CORE ENHANCEMENT]** Error logs from export routines can be emailed to an array of email addresses supplied via the `pb_error_log_emails` filter (see #956).
*   **[CORE ENHANCEMENT]** Images in cloned or imported books can now be properly edited using the WordPress image editor (see #920 and #949).
*   **[FIX]** We’ve implemented a better solution for the PDF profile bug (see #951, #952).
*   **[FIX]** URLs like `/catalog/page/1` will no longer attempt to load user catalogs (see #953).

### 4.3.2

**NOTICE:** Pressbooks 4.3.2 requires WordPress 4.8.1. **NOTICE:** Users of the Pressbooks Custom CSS theme must upgrade to Pressbooks Custom CSS 1.0 for compatibility with Pressbooks 4.3.2.

*   **[FIX]** Fixed an issue which prevented the Print PDF profile from loading properly (see #951).

### 4.3.1

**NOTICE:** Pressbooks 4.3.1 requires WordPress 4.8.1.  
**NOTICE:** Users of the Pressbooks Custom CSS theme must upgrade to Pressbooks Custom CSS 1.0 for compatibility with Pressbooks 4.3.1.

*   **[CORE ENHANCEMENT]** Added a debugging switch to Custom Styles (see #946).
*   **[FIX]** Resolved an issue where some fonts would not be loaded properly during the PDF export routine (see #944 and #945).
*   **[FIX]** Updated routines that use XPath for compatibility with HTML5, resolving some issues with multi-level TOC and EpubCheck validation (see #947).

### 4.3.0

**NOTICE:** Pressbooks 4.3 requires WordPress 4.8.1.  
**NOTICE:** Users of the Pressbooks Custom CSS theme must upgrade to Pressbooks Custom CSS 1.0 for compatibility with Pressbooks 4.3.

*   **[FEATURE]** Custom Styles: Navigate to *Appearance* → *Custom Styles* on your book's dashboard to add custom CSS or SCSS to any book theme (see #658, #912, #925, #937, #938, #940, #941, and #942).
*   **[ENHANCEMENT]** Expanded the `license` property of the `/metadata` endpoint to include a human-readable license name and custom license text (if present) (see #934 and #936).
*   **[ENHANCEMENT]** Added the book's short description to the `/metadata` endpoint as a [`disambiguatingDescription`][4] (see #930 and #932).
*   **[ENHANCEMENT]** Clarified errors when trying to clone a book from Pressbooks < 4.1 (see #914 and #931).
*   **[ENHANCEMENT]** Renamed several action and filter hooks and deprecated the old versions (see #926).
*   **[FIX]** Fixed an issue which would prevent super administrators without any books on a network from accessing the cloning page (see #913 and #933).
*   **[FIX]** Fixed a regression which blocked the use of custom LaTeX renderers (props to @monkecheese; see #928).

### 4.2.0

**NOTICE:** Pressbooks 4.2 requires WordPress 4.8.1.

*   **Feature:** Full-sized images will be used where possible in Print PDF exports to ensure that exported PDFs meet image resolution requirements (see #894, #898 and #900).
*   **Feature:** WXR import and clone operations will now attempt to fetch original images from the source book in addition to the scaled/cropped version in the book content (see #895 and #902).
*   **Feature:** Content on the organize page now has a View link as will as Edit and Trash (see #840 and #893).
*   **Enhancement:** The [Masterminds HTML5 parser][5] is now used instead of `DOMDocument` where possible for improved error handling and compatibility with HTML5 elements (see #889 and #896).
*   **Enhancement:** Unnecessary HTTP calls have been removed from export routines (see #899).
*   **Enhancement:** Installation instructions are now linked from the readme file instead of being included (see #891 and #892).
*   **Fix:** Resolved some inconsistencies with custom copyright notice and copyright year display (see #922).
*   **Fix:** Clone operations now have a 5-minute time limit which should reduce the occurrence of timeouts (props to @bdolor for the bug report; see #903 and #904).
*   **Fix:** Visiting `/catalog` on the root site no longer causes an error (see #905).
*   **Fix:** Pressbooks LaTeX settings no longer appear on the root site's dashboard (see #910 and #911).
*   **Fix:** The Organize page now supports all post statuses (see #915).
*   **Fix:** Fixed an issue where the Pressbooks News dashboard widget would be cached in the wrong language (see #918 and #921).
*   **Fix:** Removed some unused code from the PB LaTeX symbiont (props to @jeremyfelt; see #923).

### 4.1.0

**NOTICE:** Pressbooks 4.1 requires [WordPress 4.8.1][6].

*   **Feature:** Cloning! Clone any public, properly-licensed book from any Pressbooks 4.1 network including your own (super admins can clone any book from their own network, regardless of license) (see #841, #857, #881, #885).
*   **Feature:** Granular display controls for content licenses at the book and section level (see #805, #867, #873, #883, #884).
*   **Feature:** Word count for the entire book and for content marked for export is now displayed on the Organize page (see #842, #878, #880).
*   **Feature:** Users can now delete their own books from the book menu (see #845, #864).
*   **Feature:** Custom taxonomies are now available in the Pressbooks REST API v2 (see #851, #853).
*   **Feature:** The Schema.org [isBasedOn][7] property is now saved in metadata and displayed in the Pressbooks REST API v2 (see #850, #852).
*   **Feature:** Search & Replace with RegEx is now available for super admins without additional configuration (see #870, #871, #879).
*   **Feature:** Punjabi Gurmukhi support (props to @alexpflores) (see #877).
*   **Enhancement:** Book editors can now modify theme options and custom CSS (see #862, #863).
*   **Enhancement:** The Pressbooks News feed is now cached across all sites to reduce unnecessary network access (see #882).
*   **Fix:** The TOC endpoint in the Pressbooks REST API v2 now uses `chapters` and `parts` for consistency with the endpoints for these post types.
*   **Fix:** The EPUB importer now properly detects and handles optional whitespaces (see #554, #874).
*   **Fix:** Users without super admin privileges can no longer access the trash when they shouldn't be able to do so (see #865).
*   **Fix:** Image URLs with `#fixme` on the end will now be properly copied into EPUBs during export (see #887).

### 4.0.2

*   **Fix:** Fixed an issue where locating a PDF output intent file would fail on certain systems (see #866).

### 4.0.1

*   **Fix:** Fixed an issue where the template root for book themes was not properly updated (see #854, #859).
*   **Fix:** Fixed an issue where ampersands were not being sanitized in XML outputs (see #860).
*   **Fix:** Fixed an issue where the Disable Comments setting was not being saved properly (see #861).
*   **Fix:** Fixed an incorrect link in upgrade notices (see #848, #849).

### 4.0.0

**NOTICE:** Upon upgrading to Pressbooks 4.0, you will need to install the [Pressbooks Book][8] and [Pressbooks Publisher][9] themes along with any of our other open source [book themes][10] that were bundled with earlier versions of Pressbooks. For more information, see the [upgrading instructions][11].

**NOTICE:** Pressbooks 4.0 requires [WordPress 4.8.0][12].

#### Pressbooks 4.0 "Slate"

##### Next-Generation REST API

Building on [Brad Payne's][13] original REST API for Pressbooks, we've introduced an improved and expanded REST API based on the WordPress Core [REST API][14] infrastructure. The Pressbooks REST API v2 supports authenticated CRUD (Create, Read, Update, Destroy) access to all Pressbooks content types (front and back matter, parts, and chapters) as well as read-only access to book structure and metadata. For more information, see our [REST API documentation][15]. We're excited to see what the Pressbooks Open Source community will do with these new API capabilities! Share your projects with us: <code@pressbooks.com>.

##### Enhanced LaTeX Rendering

Pressbooks' core LaTeX renderer now produces high resolution output suitable for print! More improvements to come, and thanks for your patience as we've worked to improve this important feature.

##### Better Content Management

Want to mark all chapters for export on the Organize screen? You can do that now! Trashed something that you want back? Just navigate to Text → Trash and you can restore it. Many more improvements to come!

##### Pressbooks CLI

The Pressbooks command line interface is now part of Pressbooks. Want to make your own book theme? Run `wp scaffold book-theme` from the root of your Pressbooks install and take advantage of our intuitive SCSS-based theme structure. More commands to come -- [submit your ideas][16]!

#### Detailed Changelog

*   **Feature:** REST API v2 (see #472, #763, #770, #771, #774, #778, #780, #781, #783, #785, #788, #798, #803, #804, #806, #807, #810, #812, #815, #816, #823, #832, and our [API Docs][15]
*   **Feature:** LaTeX outputs are now at a sufficient resolution for print applications (see #819).
*   **Feature:** You can now change statuses in bulk on the **Organize** page (see #249 and #822).
*   **Feature:** Deleted content can now be restored from **Text → Trash** (see [9283c26][17]).
*   **Enhancement:** The Pressbooks CLI is now bundled in Pressbooks (see #464 and #826).
*   **Enhancement:** `new PressbooksMetadata()` now returns book metadata as an implementation of [JsonSerializeable][18] (see #804 and #832).
*   **Enhancement:** Expanded metadata is now hidden on the **Book Information** page unless needed (see #804 and #832).
*   **Enhancement:** We now use the [Human Made coding standards][19] for PHP. [Check your code][20] before submitting a PR ?.
*   **Enhancement:** We now use [Laravel Mix][21] to handle all plugin assets (see #769 and #795). Making a change in `/assets/src/`? With [Yarn][22] installed in your development environment, run `yarn && yarn run build` to build assets for distribution.
*   **Enhancement:** SCSS files can now be checked against our coding standards using [stylelint][23] with the command `yarn run lint` (see #743 and #817).
*   **Enhancement:** JS files have been updated to ES6 and can now be checked against our coding standards using [eslint][24] with the command `yarn run lint` (see #829).
*   **Enhancement:** Root and book themes are now distributed separately from the Pressbooks plugin -- make sure you install the required themes when you [upgrade][25]! (See #756 and #799.)
*   **Enhancement:** Part content has been migrated to the standard content editor instead of a custom field (see #486 and #764).
*   **Enhancement:** The Search and Replace module has been heavily optimized, reducing memory usage by ~85% (see #759 and #793).
*   **Enhancement:** Additional post types can be added to the list of permitted post types for editing using the [`pb_supported_post_types` filter][26] (props to @steelwagstaff, see #758).
*   **Enhancement:** We now use [vanilla/htmlawed][27] as our htmLawed provider (see #767).
*   **Enhancement:** Developers can now add new import types via the `pb_import_table_cell` and `pb_initialize_import` filter hooks (props @bdolor; see #802 and #811).
*   **Enhancement:** Releases are now packaged automatically via Travis (see #730 and #821).
*   **Fix:** DOCX and ODT files exported from Google Docs (which lack standard metadata) can now be imported without issue via the import module (see #837 and #838).
*   **Fix:** Images are now set to a `prince-image-resolution` of `auto, normal` rather than 300dpi for more reliably high-quality print PDF output (see #744 and #776).
*   **Fix:** Text suggesting that we offer printing services has been removed from the Publish page (see #784).
*   **Fix:** Export downloads from the webbook include the proper file extensions (props to @bdolor; see #808).
*   **Fix:** Current privacy settings are now displayed properly when updating book privacy from the Organize page (see #711 and #801).
*   **Fix:** The editor style is now enqueued with a version for cache busting (see #813 and #814).
*   **Fix:** Miscellaneous improvements to improve performance and reduce unnecessary error output.

### 3.9.9

**NOTICE:** Pressbooks now requires [WordPress 4.7.5][28].

*   **Feature:** A curated listed of recommended plugins is now displayed within the plugin installer (see #729).
*   **Feature:** Search and Replace now supports regular expressions (props to @stepmuel; see #754). This feature can be enabled by adding: `define( 'PB_ENABLE_REGEX_SEARCHREPLACE', true );` to `wp-config.php`.
*   **Enhancement:** Updating a book theme will now trigger the regeneration of the webbook stylesheet (see #727 and #762).
*   **Enhancement:** There is now a specific template part, `private.php`, for the page that is displayed when a book is private (props to @stepmuel; see #755).
*   **Enhancement:** "Part" is now properly localized in the PDF Table of Contents (see #742).
*   **Enhancement:** Improved blank page rules in theme components.
*   **Enhancement:** The Ebook theme options tab is now hidden when Ebook dependencies are missing (props to @masaka222; see #745).
*   **Enhancement:** Dependency check results are now stored in site transients to reduce unnecessary function calls (see #749, #750).
*   **Enhancement:** Replaced variables with constants where appropriate (see #751).
*   **Enhancement:** Replaced uses of `PATH_CURRENT_SITE` with `network_home_url()` (props to @jeremyfelt; see #734).
*   **Enhancement:** Current `$post` is now included with `wp_enqueue_media()` in `symbionts/custom-metadata` (props to @jeremyfelt; see #735).
*   **Fix:** Removed the sticky navigation bar that overlapped webbook content (props to @pbstudent for the bug report; see #747 and #760).
*   **Fix:** Fixed an issue where running content strings would not be populated when a custom title page was used (see #496 and #761).
*   **Fix:** Fixed an issue where the book title would not update properly (see #542 and #746).
*   **Fix:** Fixed issues that arose when `pb_language` or `user_interface_lang` were not set (props to @monkecheese for initial bug report and testing; see #738, #739, #740).
*   **Fix:** Fixed an issue where a database error would be thrown when installing on a utf8mb4 MySQL instance (props to @jeremyfelt; see #733).

### 3.9.8.2

**NOTICE:** Pressbooks' PHP version requirement (>= 5.6) and WordPress version requirement (>= 4.7.3) can no longer be overridden. Before installing Pressbooks 3.9.8, please ensure that your system has been upgraded accordingly.

*   **Fix:** Switched to an unmodified version of htmLawed to fix a regression in [vanilla/htmlawed][29] which was stripping paragraph tags from blockquotes (see #723).
*   **Fix:** Fixed an issue where users would be informed that their theme had been unlocked when saving Export options even thought it was already unlocked (see #722).
*   **Fix:** Fixed an issue where wp-cli would give a permissions error because of the `PressbooksThemeLock::isLocked()` check (see #721).

### 3.9.8.1

**NOTICE:** Pressbooks' PHP version requirement (>= 5.6) and WordPress version requirement (>= 4.7.3) can no longer be overridden. Before installing Pressbooks 3.9.8, please ensure that your system has been upgraded accordingly.

*   **Fix:** Restored some webbook styles that were being omitted in older book themes.

### 3.9.8

**NOTICE:** Pressbooks' PHP version requirement (>= 5.6) and WordPress version requirement (>= 4.7.3) can no longer be overridden. Before installing Pressbooks 3.9.8, please ensure that your system has been upgraded accordingly.

*   **Feature:** Themes can now be locked a particular version. The theme's stylesheets and other assets will be copied into the book's media directory and used for future exports (see #657, #704).
*   **Feature:** The paragraph separation option is now available for webbooks (see #655, #696).
*   **Feature:** The section openings PDF theme option now supports additional options (see #450, #691).
*   **Feature:** When export sharing is enabled, the download links are now stable, e.g. `/open/download?type=pdf` (props to @rootl for the suggestion; see #684, #699).
*   **Enhancement:** Pressbooks now supports third-party export formats (see #385 and #674).
*   **Enhancement:** `PressbooksOptions` field display functions have been refactored to use an array of arguments instead of a list of parameters (see #648, #697) [BREAKING CHANGE].
*   **Enhancement:** SCSS overrides have been moved into their respective theme options classes (see #452, #701).
*   **Enhancement:** Webbook interface styles have been separated from the Luther book theme's content styles (see #656, #708).
*   **Enhancement:** Webbook stylesheet and script enqueuing has been clarified and simplified (see #396).
*   **Enhancement:** Searching now excludes non-Pressbooks post types (props to @colomet for the report; see #706, #707).
*   **Enhancement:** Front-end scripts are now loaded asynchronously (props to @bdolor; see #681).
*   **Enhancement:** htmLawed is now a Composer dependency (see #702).
*   **Enhancement:** The sassphp dependency is no longer required (see #693).
*   **Enhancement:** The SaxonHE dependency check can now be overridden (see https://github.com/pressbooks/pressbooks/commit/7ea32fe).
*   **Enhancement:** [perchten/rmrdir][30] is now used for recursive directory removal (see [37ab804][31]).
*   **Enhancement:** Added PressbooksUtilityrcopy() function for recursive directory copying (props to @blobaugh for the [example code][32]; see [52b087b][33]).
*   **Enhancement:** Added `pb_dependency_errors` filter hook for suppression of dependency errors (see #719).
*   **Fix:** Images on custom title pages are now exported as expected in EPUB and Kindle (see #690, #698).
*   **Fix:** The diagnostics page now functions as expected on the root blog (props to @colomet for the report; see #688, #695);
*   **Fix:** Print PDF exports are now available for download when export sharing is enabled (props to @bdolor; see #677).
*   **Fix:** Numberless chapters no longer display a lonely period in PDF outputs from SCSS v2 themes (props to @thomasdumm for the report; see #670).
*   **Fix:** Importing as a draft now works for EPUB imports (props to @thomasdumm for the report; see #668).

### 3.9.7.2

**NOTICE:** Pressbooks now requires [WordPress 4.7.3][34]. * **Enhancement:** Streamlined and refactored the running content SCSS partials for SCSS-based themes (see #675 and #686).

### 3.9.7.1

*   **Fix:** Fixed an issue where the custom CSS file for webbooks would not be loaded on subdirectory installs.

### 3.9.7

**NOTICE:** Pressbooks now requires [WordPress 4.7.2][35].

*   **Feature:** Added support for Canadian Indigenous syllabics, which are used for the Chipewyan, Inuktitut, Plains Cree, Cree, Moose Cree, Slave, Northern Cree, Naskapi, Swampy Cree, Southern East Cree, and Ojibwa languages (props to @bdolor; see #635).
*   **Feature:** Part numbers are now displayed consistently across all formats (see #341).
*   **Enhancement:** SCSS maps are now used to provide variables for different export formats.
*   **Enhancement:** The global `_titles.scss` partial for SCSS v2 themes has been split into `_pages.scss` and `_section-titles.scss` for better separation of concerns.
*   **Enhancement:** Added the `pb_add_latex_renderer_option`, `pb_require_latex`, `pb_latex_renderers`, and `pb_add_latex_config_scripts` filters and the `pb_enqueue_latex_scripts` action to support custom LaTeX renderers (props to @monkecheese; see #583).
*   **Enhancement:** Added the `pb_root_description` filter to allow the default root blog description to be changed.
*   **Enhancement:** Custom theme options can now be registered, either on an existing tab or on a new tab (see #470 and #618).
*   **Enhancement:** Added the `pb_publisher_catalog_query_args` filter to allow customizing the query for books on the front page of Pressbooks Publisher (see #619).
*   **Enhancement:** Added the `PressbooksMetadata::getJsonMetadata()` function and the `pb_json_metadata` filter to support returning book information as JSON data for posting to an API endpoint (see #637).
*   **Enhancement:** Added the `pb_add_bisac_subjects_field` filter, which allows those with a licensed copy of the BISAC subject headers to display a multiple select instead of Pressbooks' default text input (see #637).
*   **Enhancement:** Added the `pb_audience` field to the Book Information page to allow setting a book's target audience (see #638).
*   **Enhancement:** The export metadata settings for all book contents are now fetched in a single query within `PressbooksBook::getBookStructure()` (props to @monkecheese; see #633).
*   **Enhancement:** The book language will now be set to the language selected when the book is registered (see #595).
*   **Enhancement:** The Comments column on the Organize page will now be hidden if comments are disabled (see #644).
*   **Enhancement:** Core textbox styles now apply to the equivalent `.bcc-*` selectors for improved compatibility with Pressbooks Textbook.
*   **Enhancement:** Imported content can optionally be set to `published` status instead of `draft` (see #593).
*   **Enhancement:** Front matter, chapter, and back matter types will now be imported from Pressbooks WXR files (see #601).
*   **Enhancement:** Empty front matter, chapters, and back matter will now be imported from Pressbooks WXR files (see #592).
*   **Enhancement:** Title display and export metadata will now be imported from Pressbooks WXR files (see #606).
*   **Enhancement:** Completing an import from a Pressbooks WXR file will now correctly enumerate different content types instead of labelling all as chapters.
*   **Enhancement:** Bold, italic, superscript, and subscript text is now properly imported from Word documents (props to @crism; see #629).
*   **Enhancement:** Inline language attributes are now properly imported from Word documents (props to @crism; see #630 and #639).
*   **Enhancement:** Removed the Postmark-specific `wp_mail()` override (see #587).
*   **Enhancement:** Export dependency errors are now grouped intelligently into a single alert (see #646).
*   **Enhancement:** Javascript and SCSS files are now validated on pull requests using [Hound][36] (see #617).
*   **Enhancement:** The sender address and name used for emails from a Pressbooks instance can now be customized by defining constants for `WP_MAIL_FROM` and `WP_MAIL_FROM_NAME` (see #663).
*   **Fix:** To prevent an erroneous reversion to the WordPress < 3.5 uploads directory structure, `PressbooksUtilityget_media_prefix()` now checks for the `ms_files_rewriting` site option instead of for the `blogs.dir` directory.
*   **Fix:** The custom CSS file URL scheme is now relative, which should prevent mixed content errors under some circumstances (see #599).
*   **Fix:** Fixed an undefined index error in mPDF theme options (props to @monkecheese; see #613).
*   **Fix:** Fixed a database max key length error when creating the catalog tables (see #589).
*   **Fix:** Removed the Pressbooks plugin installer tab, which was preventing plugin searching from being conducted (see #596).
*   **Fix:** Deleted books will now be removed from user catalogs (see #412).
*   **Fix:** Fixed an issue where hyphenation would be enabled in Prince exports even if it was disabled in theme options (see #645).
*   **Fix:** Fixed an issue where custom running content was being displayed in the wrong place (see #623).
*   **Fix:** Fixed an issue where OpenOffice files would not be properly exposed for download (see #649).
*   **Fix:** The time allowed for an mPDF export to complete has been conditionally increased to account for certain edge cases (props to @bdolor; see #652).
*   **Fix:** Added between section numbers and titles in the mPDF TOC (props to @bdolor; see #653).
*   **Fix:** We now use the https endpoint for the Automattic LaTeX server to avoid mixed content errors (props to @bdolor; see #651).
*   **Fix:** Publisher logos inserted via `add_theme_support( 'pressbooks_publisher_logo' )` hook are now properly copied into EPUB outputs (see #666).

### 3.9.6

**NOTICE:** Pressbooks now requires [WordPress 4.7 "Vaughan"][37].

**NOTICE:** Pressbooks now requires [PrinceXML 11][38] for PDF exports.

*   **Feature:** If you select a language on the book information page and the WordPress language pack for that language is available but not installed, Pressbooks will try to install it for you (and politely inform you if it can't).
*   **Feature:** Added Hindi language support using [Noto Sans Devanagari][39] and [Noto Serif Devanagari][40].
*   **Enhancement:** The whitelist-based theme filtering behaviour of Pressbooks =< 3.9.5.1 has been removed; all book themes are now available for use in all books (if network enabled), and all non-book themes are now available for use on the root blog (if network enabled). If you wish to restrict theme availability further, you can do so by adding additional filters to the `allowed_themes` filter hook.
*   **Enhancement:** Added the ability to retry asset fetching during EPUB export in the event of server errors (props to @nathanielks, see [7344674][41])
*   **Enhancement:** Added filter and action hooks to support the addition of import modules via third-party plugins (props to @monkecheese, see [4d7ca64][42]).
*   **Enhancement:** Added the `pb_disable_root_comments` filter hook for control over comment display on the root blog (defaults to `true` -- disable comments -- as Pressbooks Publisher does not support comments).
*   **Enhancement:** Added a link from the user's catalog logo or profile image to their profile URL, if set.
*   **Enhancement:** Added variables for textbox header font size and text alignment to book theme partials.
*   **Enhancement:** Removed our custom `user_interface_lang` setting in favour of WordPress 4.7's user locale.
*   **Enhancement:** Removed `Pressbooksutilitymulti_sort()` in favour of WordPress 4.7's shiny new `wp_list_sort()`.
*   **Enhancement:** Removed our last remaining use of `get_blog_details`, which will be deprecated in a forthcoming WordPress release.
*   **Fix:** Fixed an issue which prevented the Pressbooks admin color scheme from being applied upon manual plugin activation.
*   **Fix:** Fixed an issue which prevented the book name from properly updating under some circumstances.
*   **Fix:** Fixed some styles on the registration screen in the Pressbooks Publisher theme (now at v3.0.1).

### 3.9.5.1

*   **Enhancement:** Added [`pb_cover_image`][43] filter to improve support for networks which host uploaded content on a third-party server (props to @monkecheese).
*   **Fix:** Fixed a discrepancy in the line height of PrinceXML PDF exports of books using Cardo as the body font which resulted from an invalid descender value.
*   **Fix:** Fixed an issue where the Network Sharing & Privacy page would not update the associated site option value.
*   **Fix:** Fixed the vertical alignment of the Facebook share button in the webbook theme (props to @colomet).

### 3.9.5

*   **Enhancement:** The Pressbooks Publisher theme has been streamlined and refreshed.
*   **Fix:** The version requirement for xmllint has been downgraded to 20706 to maintain RHEL 6 compatibility (props to @bdolor for the PR).

### 3.9.4.2

*   **Feature:** It is now possibled to modify the default session configuration via the `pressbooks_session_configuration` filter hook (props to @monkecheese).
*   **Feature:** The `pb_append_chapter_content` is now available in the mPDF exporter (props to @monkecheese).
*   **Enhancement:** The `generator` meta property has been added to XHTML exports.
*   **Fix:** A bug which resulted in anchors being added to internal links twice in EPUB exports has been resolved.

### 3.9.4.1

*   **Feature:** The copyright string in the Pressbooks Publisher theme footer can now be customized via the `pressbooks_publisher_content_info` filter.
*   **Feature:** The text that is displayed when there are no books in a Pressbooks Publisher catalog can now be customized via the `pressbooks_publisher_empty_catalog` filter.
*   **Fix:** Updated a component of the Diagnostics page to remove a deprecation notice (props to @thomasdumm for the report).
*   **Fix:** Fixed a glitch in the Pressbooks colour scheme.

### 3.9.4

*   **Feature:** Pressbooks + Hypothesis: Version 0.4.8 of the [Hypothesis][44] WordPress plugin now supports custom post types, and Pressbooks 3.9.4 adds Hypothesis support to all of ours (parts, chapters, front and back matter).
*   **Feature:** Having a problem with Pressbooks? We've added a diagnostics page which is accessible from the 'Diagnostics' link in the footer of every dashboard screen. If you need to report a bug, copy your system configuration info from your Diagnostics page to help us help you resolve the issue more efficiently.
*   **Enhancement:** `check_epubcheck_install` can now be overridden using the `pb_epub_has_dependencies` hook for use cases where EPUB validation is not required (props to @monkecheese for the PR).
*   **Enhancement:** Some adjustments were made to the PDF output stylesheets for running headers and footers.
*   **Fix:** Fixed a visual glitch by hiding the TinyMCE table editor's inline toolbar.

### 3.9.3

*   **NOTE:** [Saxon-HE 9.7.0-10][45] is no longer bundled with Pressbooks and must be installed separately for ODT export support (see [Installation][46]).
*   **Feature:** The copy on the publish page can now be replaced by adding a filter to the `pressbooks_publish_page` filter hook.
*   **Feature:** If registration is enabled, a 'Register' button now appears on the front page of the Pressbooks Publisher theme.
*   **Enhancement:** A URL sanitization routine has been added to the `PressbooksOptions` class.
*   **Enhancement:** The methods of `PressbooksOptions` which list the options of various types (bool, string, float, etc.) are now optional, and the sanitize function now checks for each type before trying to sanitize it.
*   **Enhancement:** The publish page has been refactored using the `PressbooksOptions` class.
*   **Fix:** Unwanted validation warning emails will no longer be sent.

### 3.9.2.1

*   **NOTE:** Pressbooks 3.9.2 requires [PrinceXML 20160929][47] or later.
*   **Fix:** Fixed an issue where user actions on the Organize page would fail to update certain properties.

### 3.9.2

*   **NOTE:** Pressbooks 3.9.2 requires [PrinceXML 20160929][47] or later.
*   **Feature:** Added an export format for print-ready PDF, compatible with the [CreateSpace PDF Submission Specification][48] (**Requires [PrinceXML 20160929][47] or later**).
*   **Feature:** Added a button to the editor which lets you assign a custom class to any element.
*   **Feature:** Simplified the Disable Comments feature, which can now be found under Sharing & Privacy settings.
*   **Enhancement:** Added version-based dependency checks for all Pressbooks dependencies.
*   **Enhancement:** Updated the TinyMCE Table Editor plugin to the latest version.
*   **Enhancement:** Custom styles, table classes, row classes and cell classes are now filterable.
*   **Fix:** Fixed an issue where email validation logs would not be sent.

### 3.9.1

*   **Fix:** Fixed an issue where the htmLawed and PrinceXMLPHP dependencies were not being loaded properly.

### 3.9.0

*   **Feature:** Added a web theme option to display the title of the current part in the webbook (props to @bdolor).
*   **Feature:** Noto CJK fonts (required for Chinese, Japanese and Korean PDF output) are now downloaded only when needed from within Pressbooks, reducing the overall size of the Pressbooks download.
*   **Feature:** Added a recompile routine for webbook stylesheets to allow more straightforward development (only enabled when `WP_ENV` is defined and set to `development`).
*   **Enhancement:** Applied our [coding standards][49] across the board and added PHP_CodeSniffer to our CI routines.
*   **Enhancement:** Added some unit tests.
*   **Enhancement:** Moved the Pressbooks API to /vendor.
*   **Enhancement:** Changed some colour variables for clarity.
*   **Enhancement:** Added initial support for SVG LaTeX images in PDF exports (requires [QuickLaTex][50]).
*   **Enhancement:** Added some scaffolding to allow option defaults to be filtered in pages built using the new options class.
*   **Enhancement:** The book information post is now created when a book is registered.
*   **Fix:** Added missing methods which were triggering fatal errors in the Export Options page (props to @bdolor).
*   **Fix:** Fixed in issue which prevented the Ebook paragraph separation theme option from being applied in Clarke.
*   **Fix:** Fixed an issue where internal links from within part content were broken in EPUB.
*   **Fix:** Fixed an issue where backslashes would be erroneously stripped when replacements were applied in the Search and Replace utility (props to @rootl for the bug report).
*   **Fix:** Fixed an issue where the book title would not be updated on the first save.

### 3.8.1

*   **Fix:** Internal links are now *actually* fixed in EPUB exports.

### 3.8.0

*   **Feature:** The redistribution option from [Pressbooks Textbook][51], which allows a book administrator to share the latest export files of their book on the webbook cover page, has been migrated into Pressbooks and can be found under (Network) Settings -> Sharing and Privacy. Many thanks to @bdolor for developing this feature (and fixing a display bug in our implementation of it).
*   **Feature:** Luther and all child themes now support searching within webbooks.
*   **Feature:** The Pressbooks.com promotion on book covers can now be hidden using the `PB_HIDE_COVER_PROMO` constant.
*   **Enhancement:** [Hypothesis][52] has been added to the supported plugins list, and the supported plugins list is now built more intelligently.
*   **Enhancement:** The hard-coded default theme for new books has been replaced by the following logic: 1. Use `PB_BOOK_THEME` (if set); 2. Use `WP_DEFAULT_THEME` (if set); 3. Use Luther.
*   **Enhancement:** Added the `pressbooks_register_theme_directory` action to support the registration of custom theme directores by third-party developers (props to @bdolor).
*   **Enhancement:** Added support for testing PrinceXML's built-in [PDF profile][53] support by setting the `PB_PDF_PROFILE` constant to the desired profile.
*   **Enhancement:** Refactored generic shortcodes to allow testing and tests were written for them.
*   **Enhancement:** Switched from internal fork to dev-master of gridonic/princexmlphp and switched to versioned copy of pressbooks/saxonhe.
*   **Enhancement:** The `PressbooksModulesThemeOptions` class now supports the registration of custom tags by third-party developers.
*   **Fix:** Removed a leftover conditional check for the `accessibility_fontsize` option in webbooks (props to @bdolor for the bug report).
*   **Fix:** Internal links to parts now work in XHTML, PDF and EPUB exports.
*   **Fix:** Fixed some faulty logic in the TOC collapse Javascript (props to @bdolor).
*   **Fix:** Fixed some incorrect color values in the mobile admin bar.
*   **Fix:** Fixed a misplaced comment in the conditional check for IE 9 in Pressbooks Book (props to @chrillep).
*   **Fix:** Fixed a bug where protocol-relative images would not be exported properly in EPUB (props to @bdolor).

### 3.7.1

*   **Fix:** Fixed a bug where increased font size would be applied to all PDF exports.

### 3.7.0

*   **Feature:** Introduced `PressbooksOptions` class and rebuilt theme options using on this class.
*   **Feature:** Introduced `PressbooksTaxonomy` class and rebuilt front matter, chapter and back matter types using this class.
*   **Feature:** Added support for custom base font size, line height, page margins, image resolution and running content in SCSS v2 themes for PDF.
*   **Feature:** Enabled webbook collapsible TOC by default (as needed).
*   **Feature:** Enabled webbook font size control by default.
*   **Feature:** Added custom sidebar color for catalog (props to @monkecheese).
*   **Enhancement:** Prince will now ignore self-signed certificates in a development environment.
*   **Fix:** Fixed an admin style inconsistency introduced with WordPress 4.6.
*   **Fix:** Fixed an error where SCSS v2 themes could not be imported into the Custom CSS editor.
*   **Fix:** Added user feedback to allow recovery from JPEG errors (props to @bdolor).
*   **Fix:** Added a call to `wp_cache_flush()` to fix an error during book creation.

### 3.6.3

*   **Fix:** Fixed an error caused by the change to get_sites().

### 3.6.2

*   Requires WordPress 4.6.
*   **Fix:** Replaced deprecated wp_get_sites() function with get_sites() (props to @bdolor for the bug report).

### 3.6.1

*   **Fix:** An issue where footnotes would not display in endnote mode has been resolved.
*   **Fix:** An SCSS error in Luther has been resolved (props to @bearkrust for the bug report).

### 3.6.0

*   Requires WordPress 4.5.3.
*   **Feature:** Structural SCSS and supports are in place for the new book theme model (see http://pressbooks.org/core/2016/05/16/rethinking-book-themes/).
*   **Feature:** Clarke 2.0 has been rebuilt on the new book theme model (see https://pressbooks.com/themes/clarke).
*   **Feature:** Themes built on the new book theme model can display publisher logos on the title page via `add_theme_support( 'pressbooks_publisher_logo', [ 'logo_uri'> $logo_uri ] )`.
*   **Feature:** Themes built on the new book theme model define support for global typography using `add_theme_support( 'pressbooks_global_typography', [ $language_codes ] )`.
*   **Feature:** Custom post types, built-in taxonomies and custom taxonomies can now be imported from a Pressbooks or WordPress XML file using the filters `pb_import_custom_post_types` and `pb_import_custom_taxonomies` (props to @monkecheese).
*   **Feature:** Filter hooks have been added which allow content to be appended to front matter, chapters and back matter via `pb_append_front_matter_content`, `pb_append_chapter_content` and `pb_append_back_matter_content` (props to @monkecheese).
*   **Feature:** Network administrators can now clear all of a book's exports (this is useful for testing).
*   **Enhancement:** The Export page is now responsive.
*   **Enhancement:** `script.js` is no longer required for Prince exports (if the the file is not there it will no longer trigger an error).
*   **Enhancement:** The `<base href="">` tag has been removed from XHTML outputs, which should make these files more functional in some cases (props to @bdolor).
*   **Fix:** Search and Replace is now accessible to book administrators, not just network administrators.
*   **Fix:** The broken Forum link in the Pressbooks menu has been replaced with a link to our Help page.

### 3.5.2

*   **Feature:** Login screen logo and color scheme can now be changed via filters (see https://github.com/pressbooks/pressbooks/commit/d09a104bfbbe3ad00a108004d0375ad1f7057ae0).
*   **Enhancement:** Google Fonts are now requested over https under all circumstances.
*   **Enhancement:** Added some functionality to the Disable Comments plugin (props to @bdolor).
*   **Fix:** Imports will no longer fail in certain environments (props to @monkecheese for the bug fix).
*   **Fix:** Subsection titles are now properly sanitized for XHTML output.

### 3.5.1

*   Requires WordPress 4.5.2.
*   **Fixed:** Resolved a formatting issue on the Export page (props to @bdolor).
*   **Under the Hood:** Added anchor, superscript and subscript buttons to core MCE routines (eliminating dependencies).

### 3.5.0

*   FEATURE: Search and Replace functionality has been rebuilt and more closely integrated with Pressbooks core.
*   FEATURE: Pressbooks plugins (specifications forthcoming) can now be activated at the book level by book administrators.
*   FIXED: Some image asset paths were updated.
*   FIXED: Default mPDF options were updated.
*   UNDER THE HOOD: Pressbooks now bundles the WordPress API feature plugin (more to come on this front).
*   UNDER THE HOOD: Our namespace is now Pressbooks.

### 3.4.0

*   Requires WordPress 4.5.1.
*   FEATURE: OpenDocument (beta) is now available as an export format.
*   ENHANCED: Plugin assets are now managed using Bower and compiled using gulp. Your Pressbooks dashboard will now load more efficiently (thanks to the @rootswp team for their development of this workflow).
*   ENHANCED: All symbionts except for that weird ICML one are now managed using Composer.
*   ENHANCED: `check_prince_install()` now tries to run `prince --version` instead of looking for the executable file.
*   FIXED: The Tweet button had stopped working, so we replaced our previous sharing script with @ellisonleao's excellent [sharer.js][54].
*   FIXED: Our fork of @johngodley's Search Regex plugin has been updated for PHP 7.0 compatibility (props to @r66r for the bug report).

### 3.3.2

*   FIXED: Themes were not appearing to be network enabled due to changes introduced in https://core.trac.wordpress.org/ticket/28436.

### 3.3.1

*   FIXED: The custom logo feature introduced in v3.3.0 now displays logos at a more reasonable size.
*   FIXED: Some extraneous files were bundled in v3.3.0. They are gone now.
*   FIXED: An extra line break was introduced to the Export screen in v3.3.0. It is gone now too.

### 3.3.0

*   Requires WordPress 4.5.
*   ICML is now an experimental export format (see http://pressbooks.com/blog/discontinuing-support-for-icml-exports-on-april-12/).
*   Added support for WordPress core's custom logo in Pressbooks Publisher.
*   Added the TinyMCE background color button.
*   Allow a user to choose their password when registering.
*   Allow a network administrator to replace the Pressbooks News dashboard feed with their own RSS feed or disable the dashboard feed entirely.
*   Fixed an issue where the "Show Title" checkbox on the "Organize" page had no effect (props to @sswettenham for the bug report).
*   Fixed an issue where uploaded media were not attached to their parent Front Matter, Chapter or Back Matter.
*   Internal dependencies are now managed using [Composer][55].

### 3.2.0

*   Requires WordPress 4.4.2.
*   Added Google Analytics support at the network level (subdomain and subdirectory installs) and the book level (subdomain installs only).
*   Added support for installs that use SSL (props to @bdolor for contributions).
*   Added localization support for strings (currently, "Chapter" and "Part") in book stylesheets.
*   Added localization support for the Pressbooks "freebie" notice.
*   Clarified new user and book registration text.
*   Set timezone on export page based on root site settings (props to @chrillep for the bug report).
*   Enhanced image display in exports.
*   Expanded code coverage.
*   Fixed an issue where footnote anchors would not be properly created when importing a Word document (thanks to @crism for the report and the contribution).
*   Fixed an issue where clicking 'Show in Catalog' would not work (props to @colomet for the bug report).
*   Fixed an issue where the "My Books" button would appear in Pressbooks Publisher for logged-in users with no books.
*   Fixed the way the PB_PLUGIN_DIR and PB_PLUGIN_URL constants are defined to support installations of Pressbooks where plugins and themes are symlinked.

### 3.1.2

*   Requires WordPress 4.4.1.
*   Added internal links (anchors) to the built in 'Insert/edit Link' dialog.
*   Added admin notices to indicate the success or failure of some AJAX actions which do not produce a visible result.
*   Fixed an issue with EPUB validation introduced by WordPress 4.4's implementation of the srcset attribute.
*   Fixed an issue where a dynamically-generated webBook stylesheet would be erroneously loaded.
*   Fixed an issue with image paths in Luther webBook stylesheet (props to @bdolor for the bug report).
*   Fixed an issue that caused ODT exports to fail in a particularly undignified manner.
*   Fixed an issue where PDF themes would not be imported for editing properly when using the Pressbooks Custom CSS theme.
*   Expanded test suites.

### 3.1.1

*   Fixed an issue where custom web book themes would not be properly loaded.
*   Updated the PB_PLUGIN_VERSION constant, which slipped under our radar when we released Pressbooks 3.1.

### 3.1

*   Requires WordPress 4.4.
*   Added a new Textboxes menu in TinyMCE which supports some new types of textboxes in addition to standard and shaded.
*   Added support for assigning classes to tables within the TinyMCE Table Editor and removed some unnecessary features from it.
*   Added a new Greek language font.
*   Moved the mPDF library to an external plugin, [Pressbooks mPDF][56].
*   Localized strings within some of our TinyMCE plugins. More to come.
*   Improved SCSS theme structure and SCSS compilation routines.
*   Improved XSL file for ODT export.
*   Improved some TinyMCE styles.
*   Fixed an issue where activating a non-SCSS theme would cause an error.
*   Fixed an issue where loading the Search and Replace tool would cause an error (props to @rootl for the bug report).
*   Updated some assets.

### 3.0

*   SASS-y themes: book themes are now built with SASS (specifically the SCSS variant) and compiled for export or web display using either the bundled scssphp compiler (https://github.com/leafo/scssphp/) or the SASS PHP extension if installed (https://github.com/sensational/sassphp). See `/docs/themes-book.txt` for details if you are developing your own themes.
*   Global Typography: users can add fonts to display Ancient Greek, Arabic, Biblical Hebrew, Chinese (Simplified or Traditional), Coptic, Gujarati, Japanese, Korean, Syriac, Tamil or Tibetan in any theme across all standard export formats via the Theme Options page.
*   EPUB 3: the current version of the EPUB standard is now fully supported and will soon become Pressbooks' default EPUB export format.
*   Added support for importing book information from a Pressbooks XML file.
*   Added support for persistent export format selections on the Export page.
*   Added the ability to show or hide front matter, chapter and back matter titles on the Organize page.
*   Added initial support for unit testing.
*   Requires PHP 5.6 (this can be overridden by setting `$pb_minimum_php` in wp-config.php, but we do not encourage this).
*   Updated the Prince command line wrapper to support Prince 10r5.
*   Updated export icons to support Retina screens.
*   Fixed an issue where Norwegian localization files were not being properly loaded.
*   Fixed an issue where the xml:lang attribute would set to `en` regardless of the book language.
*   Fixed an issue that prevented Prince from loading its built-in hyphenation dictionaries.
*   Fixed an issue with Kindle exports in bundled book themes.
*   Fixed an issue with multi-level TOC styling in bundled book themes.
*   Fixed an issue with EPUB images.
*   Fixed some PHP warnings.
*   Refactored some code for consistent namespacing and other improvements.
*   Various localization updates.
*   Various performance enhancements.

### 2.7.2

*   Requires WordPress 4.3.1.
*   Added MCE Anchor Button (migrated from Pressbooks Textbook, props to @bdolor).
*   Fixed an issue where the book language could be incorrectly set to Afrikaans if the network language was undefined.
*   Fixed an issue where loading a user's catalog would call memory-intensive functions repeatedly (props to @connerbw).
*   Suppressed unhelpful errors when calling getSubsections() function (props to @connerbw).

### 2.7.1

*   Fixed an issue where changes made with the Search & Replace tool would not be saved (props to @connerbw).
*   Fixed an issue where users without super admin privileges would be incorrectly prevented from using the Import or Search & Replace tools.
*   Fixed a display bug in recent builds of Google Chrome (props to @connerbw).

### 2.7

*   Major cleanup of the administration interface.

### 2.6.7

*   Added the ability to edit a table's class in the MCE Table Button's properties editor.
*   Fixed an issue where Chinese would appear as the default user interface language.
*   Fixed an issue where disabling social media sharing buttons would only disable Facebook (props to @colomet for the bug report).
*   Updated localizations.

### 2.6.6

*   Exporting a MOBI file no longer requires you to export an EPUB file also.

### 2.6.5

*   Fixed a number of issues with multi-level TOC parsing.
*   Fixed an issue where internal links on subdirectory installs were not being properly modified for PDF output (props to @bdolor).

### 2.6.4

*   Added support for audio shortcodes in EPUB3 (props to @jflowers45).
*   Modified login buttons to redirect users to the page they were viewing after login rather than force redirecting them to their dashboard (props to @marcusschiesser for the feature request).
*   Fixed an issue where PDF exports were not respecting user-defined widow and orphan settings.
*   Fixed an issue where unsupported @font-face declarations where being used in mPDF exports (props to @jflowers45 for the bug report and @bdolor for fixing it).
*   Fixed an issue where updating a book's URL would break permalinks to front matter, back matter and parts (props to @programmieraffe for the bug report).
*   Removed the WordPress contextual help button to avoid confusion on the dashboard (props to @colomet for noting its presence).

### 2.6.3

*   Fixed issue with self-closing tags introduced in 2.6.1.

### 2.6.2

*   Fixed issues with character encoding and improperly formed tags introduced in 2.6.1.

### 2.6.1

*   Fixed issues with subsection parsing where < h1> tags had inline styles or were wrapped in other block elements. * Fixed an issue where changing a book's language to "English" as opposed to "English (United States)" would fail to override the network's language setting. * Updated documentation. 

### 2.6

*   Requires WordPress 4.3.
*   The language selected on the book info page now applies to the book's webbook display.
*   The language selected on the network settings page now applies automatically to new books and users.
*   The language selected on a user's profile now overrides the network and book languages when they view the Pressbooks dashboard.

### 2.5.4

*   Requires WordPress 4.2.4.
*   Added Disable Comments (migrated from Pressbooks Textbook, props to @bdolor and the plugin's creators).
*   Added a warning message when users upload a cover image above the recommended size.
*   Optimized PressbooksBook::getBookStructure() so as to only fetch export status during export routines (props to @bracken).
*   Fixed a conflict with Jetpack (props to @programmieraffe for the bug report).
*   Fixed an issue where chapters were being number in mPDF TOCs regardless of user preference (props to @bdolor for the fix and to @sswettenham for the bug report).
*   Fixed an issue where sections would be parsed unnecessarily in webbooks (props to @bracken).
*   Fixed two issues related to permissive private content (props to @marcusschiesser for the bug reports).
*   Fixed an issue that caused a recursion during PDF export (props to @bseeger for the bug report).

### 2.5.3

*   Added option to allow logged-in subscribers, contributors and authors to view a book's private content (props to @marcusschiesser for the feature request).
*   Fixed an issue where the webbook TOC would not be displayed for any user who was not logged in (props to @sswettenham for the bug report).
*   Fixed an issue where the media folder was not being deleted after ODT exports without a cover image.

### 2.5.2

*   Added MCE Superscript & Subscript Buttons (migrated from Pressbooks Textbook, props to @bdolor and the plugin's creators).
*   Improved ODT export: temporary files are now deleted when export fails (props to @sswettenham for the bug report).
*   Improved user catalog: book covers are now clickable links (props to @kdv24).
*   Improved user catalog: sidebars are sized to fit content instead of being restricted to window height (props to @changemachine).
*   Fixed an issue where private chapters would appear in webbook TOC for logged-in users without the permissions to actually view them (props to @marcusschiesser for the bug report).

### 2.5.1

*   Added MCE Table Editor (migrated from Pressbooks Textbook, props to @bdolor and the plugin's creators).
*   Added support for excluding root domains *and* subdomains in `show_experimental_features()` function.
*   Added the ability to toggle social media integration on or off in webbooks (props to @bdolor).
*   Added the ability to restrict specific network administrators' access to some network administration pages.
*   Added a note in readme.txt indicating that `php5-xsl` is a required extension for certain exports (props to @jflowers45).
*   Added a function to intelligently load plugins in `/symbionts` so as to avoid conflicts (props to @bdolor and the Pressbooks Textbook team for providing the basis for this).
*   Forced Google webfonts to load via SSL (props to @bdolor).
*   Improved editor style so that large images fit the editing window (props to @hughmcguire).
*   Improved Javascript related to the sidebar table of contents in webbooks (props to @changemachine and @kdv24).
*   Improved logic related to maximum import size reporting (props to @jflowers45).
*   Improved styles associated with the accessibility plugin (props to @bdolor).
*   Improved XSL for ODT export.
*   Restored login screen branding in Pressbooks Publisher 2.0.
*   Restored user catalog links in Pressbooks Publisher 2.0.
*   Fixed a database error in user catalogs (props to @bdolor for the bug report).
*   Fixed an issue where books would overlap on the user catalog page (props to @bracken and @changemachine).
*   Fixed an issue where cover images and LaTex images would be omitted from ODT exports (props to @bdolor for the bug report and for assistance in solving this).
*   Fixed an issue where embedded audio files would be hidden in exports because of an inline style (props to @bdolor).
*   Fixed an issue where the `introduction` class would not be applied in certain exports.
*   Fixed an issue where exports would fail because the `get_user_by` function was being improperly namespaced (props to @borayeris for the bug report).

### 2.5

*   Requires WordPress 4.2.2.
*   New root theme, Pressbooks Publisher 2.0. Pressbooks Publisher One has been deprecated and is now available (unsupported) [here][57].
*   Added centralized `show_experimental_features()` function to control where such things appear.
*   Added experimental PDF export via mPDF as an open source alternative to Prince (props to @bdolor).
*   Added fallbacks for title, author and cover image fetching in `getBookInformation()` function.
*   Improved image fetching in ODT export (props to @bdolor).
*   Improved import of Pressbooks XML files (props to @bdolor).
*   Fixed issue where the API could show chapters as appearing in the wrong part (props to @bdolor).
*   Fixed issue where entities would be improperly loaded in XML document in ODT export (props to @bdolor).
*   Fixed issue with the network administration menu in the admin bar.
*   Fixed issue with spacing and punctuation in webbook license module output.

### 2.4.5

*   Requires WordPress 4.2.1.

### 2.4.4

*   Requires WordPress 4.2.
*   Added experimental ODT export capability.
*   Fixed issue where useful backslashes were stripped on import (props to @lukaiser for identifying this issue).

### 2.4.3

*   Requires WordPress 4.1.2.
*   Removed Hpub export routines.
*   Made links inside the `[footnote]` shortcode clickable (props to @bdolor).
*   Added accessibility plugin to allow font size increases in webbook and PDF exports (props to @BakingSoda and @bdolor).
*   Added some instructional text to Book Info page.
*   Fixed character encoding issue with the TOC display of subsection titles.
*   Fixed internal links for subdirectory installs within PDF exports (props to @bdolor).
*   Fixed issue with catalog page in WebKit browsers (props to @bdolor).
*   Fixed potential XSS attack via `remove_query_arg` (see: https://blog.sucuri.net/2015/04/security-advisory-xss-vulnerability-affecting-multiple-wordpress-plugins.html; props to @bdolor).
*   Fixed variable-related warnings on RESTful API when debugging mode is enabled (props to @julienCXX).
*   Fixed XHTML export issue with respect to determining the introduction part or chapter for page numbering.
*   Updated included custom-metadata plugin to fix `array_reverse` bug (@props to bdolor).
*   Swedish translation (props to @chrillep).

### 2.4.2

*   Fixed licenses.
*   Added child theme support to collapsible TOC functionality (props to @bdolor).

### 2.4.1

*   Fixed issue with improperly parsed sections in chapters and back matter.

### 2.4

*   Requires WordPress 4.1.
*   Refined export logic to ensure that parts are handled properly under all circumstances.
*   Refined parsing of chapter subsections; this feature no longer requires the use of the `<section>` tag.
*   Subsections are now parsed in front- and back-matter as well.
*   Support for a centralized fonts folder in the themes directory.
*   Fixed bug that broke the running head in PDF exports.
*   Fixed bug that broke internal links in PDF exports.
*   Fixed bug that caused the Chapter Types menu item to be displayed twice for certain users.
*   Beta Pressbooks API (props to @bdolor; see http://pressbooks.com/api/v1/docs).
*   Collapsible TOCs for webbooks (props to @drlippman).
*   Import enhancements (props to @bdolor).
*   EPUB export enhancements (props to @bdolor).

### 2.3.3

*   Compatibility with WordPress 4.0.
*   Fixed some issues with our experimental EPUB3 export (props to @bdolor).
*   Enhancements to WXR and EPUB import (props to @bdolor and @drlippman).
*   Added support for contributing authors in webbooks and exports (props to @bdolor).
*   Added some new translation files.

### 2.3.2

*   Cleaner print output from webbooks.
*   Ebook theme option to skip line between paragraphs is now honored in all themes.

 [1]: https://wordpress.org/news/2017/11/tipton/
 [2]: https://ns.editeur.org/thema/en
 [3]: https://make.wordpress.org/core/2017/10/22/code-editing-improvements-in-wordpress-4-9/
 [4]: http://schema.org/disambiguatingDescription
 [5]: https://github.com/Masterminds/html5-php
 [6]: https://wordpress.org/news/2017/08/wordpress-4-8-1-maintenance-release/
 [7]: http://bib.schema.org/isBasedOn
 [8]: https://github.com/pressbooks/pressbooks-book
 [9]: https://github.com/pressbooks/pressbooks-publisher
 [10]: https://github.com/search?q=topic%3Abook-theme+org%3Apressbooks&type=Repositories
 [11]: https://docs.pressbooks.org/upgrading
 [12]: https://wordpress.org/news/2017/06/evans/
 [13]: http://bradpayne.ca
 [14]: https://developer.wordpress.org/rest-api/
 [15]: https://docs.pressbooks.org/api
 [16]: https://github.com/pressbooks/pb-cli/issues
 [17]: https://github.com/pressbooks/pressbooks/tree/9283c26504007ba55259672c5cb9efc8ee07b3c0
 [18]: https://secure.php.net/manual/en/class.jsonserializable.php
 [19]: https://engineering.hmn.md/how-we-work/style/php/
 [20]: http://docs.pressbooks.org/coding-standards/#validating-with-php-code-sniffer
 [21]: https://github.com/jeffreyway/laravel-mix
 [22]: https://yarnpkg.com
 [23]: https://stylelint.io
 [24]: http://eslint.org
 [25]: http://docs.pressbooks.org/upgrading
 [26]: https://github.com/pressbooks/pressbooks/blob/4.0.0/inc/posttype/namespace.php#L16-L29
 [27]: https://packagist.org/packages/vanilla/htmlawed
 [28]: https://wordpress.org/news/2017/05/wordpress-4-7-5/
 [29]: https://github.com/vanilla/htmlawed/
 [30]: https://packagist.org/packages/perchten/rmrdir
 [31]: https://github.com/pressbooks/pressbooks/commit/37ab804489c580ad1d1121c0a07144f37772c7d0
 [32]: http://ben.lobaugh.net/blog/864/php-5-recursively-move-or-copy-files
 [33]: https://github.com/pressbooks/pressbooks/commit/52b087b5e2185ea08c6f67c24111ad9ef0ee1fa0
 [34]: https://wordpress.org/news/2017/03/wordpress-4-7-3-security-and-maintenance-release/
 [35]: https://wordpress.org/news/2017/01/wordpress-4-7-2-security-release/
 [36]: https://houndci.com
 [37]: https://wordpress.org/news/2016/12/vaughan/
 [38]: http://www.princexml.com/download/
 [39]: https://www.google.com/get/noto/#sans-deva
 [40]: https://www.google.com/get/noto/#serif-deva
 [41]: https://github.com/pressbooks/pressbooks/commit/7344674f823517ed7eb2fef462a4795f7182ce56
 [42]: https://github.com/pressbooks/pressbooks/commit/4d7ca649ec3b6c05c40e1c5bb8f92beb1de5ea30
 [43]: https://github.com/pressbooks/pressbooks/pull/540/
 [44]: https://hypothes.is
 [45]: https://sourceforge.net/projects/saxon/files/Saxon-HE/
 [46]: http://docs.pressbooks.org/installation
 [47]: http://www.princexml.com/latest/
 [48]: https://www.createspace.com/ServicesWorkflow/ResourceDownload.do?id=1583
 [49]: https://github.com/pressbooks/pressbooks/blob/master/docs/coding-standards.md
 [50]: https://wordpress.org/plugins/wp-quicklatex/
 [51]: https://github.com/BCcampus/pressbooks-textbook/
 [52]: https://wordpress.org/plugins/hypothesis/
 [53]: http://www.princexml.com/doc/properties/prince-pdf-profile/
 [54]: https://github.com/ellisonleao/sharer.js/
 [55]: https://getcomposer.org
 [56]: https://wordpress.org/plugins/pressbooks-mpdf
 [57]: https://github.com/pressbooks/pressbooks-publisher-one/
