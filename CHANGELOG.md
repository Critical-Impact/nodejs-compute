# Changelog

[npm history][1]

[1]: https://www.npmjs.com/package/@google-cloud/compute?activeTab=versions

### [1.1.4](https://www.github.com/googleapis/nodejs-compute/compare/v1.1.3...v1.1.4) (2019-08-28)


### Bug Fixes

* **docs:** stop linking reference documents to anchor ([48f90a0](https://www.github.com/googleapis/nodejs-compute/commit/48f90a0))

### [1.1.3](https://www.github.com/googleapis/nodejs-compute/compare/v1.1.2...v1.1.3) (2019-08-26)


### Bug Fixes

* **deps:** use the latest extend ([#344](https://www.github.com/googleapis/nodejs-compute/issues/344)) ([090bb96](https://www.github.com/googleapis/nodejs-compute/commit/090bb96))

### [1.1.2](https://www.github.com/googleapis/nodejs-compute/compare/v1.1.1...v1.1.2) (2019-08-01)


### Bug Fixes

* **deps:** update dependency @google-cloud/paginator to v2 ([#338](https://www.github.com/googleapis/nodejs-compute/issues/338)) ([db5de8c](https://www.github.com/googleapis/nodejs-compute/commit/db5de8c))

### [1.1.1](https://www.github.com/googleapis/nodejs-compute/compare/v1.1.0...v1.1.1) (2019-06-26)


### Bug Fixes

* **docs:** link to reference docs section on googleapis.dev ([#333](https://www.github.com/googleapis/nodejs-compute/issues/333)) ([206a0fa](https://www.github.com/googleapis/nodejs-compute/commit/206a0fa))

## [1.1.0](https://www.github.com/googleapis/nodejs-compute/compare/v1.0.1...v1.1.0) (2019-06-20)


### Bug Fixes

* **docs:** move to new client docs URL ([#326](https://www.github.com/googleapis/nodejs-compute/issues/326)) ([918e352](https://www.github.com/googleapis/nodejs-compute/commit/918e352))


### Features

* support apiEndpoint override ([#322](https://www.github.com/googleapis/nodejs-compute/issues/322)) ([49c5384](https://www.github.com/googleapis/nodejs-compute/commit/49c5384))

### [1.0.1](https://www.github.com/googleapis/nodejs-compute/compare/v1.0.0...v1.0.1) (2019-05-22)


### Bug Fixes

* **deps:** update dependency async to v3 ([#313](https://www.github.com/googleapis/nodejs-compute/issues/313)) ([c459c57](https://www.github.com/googleapis/nodejs-compute/commit/c459c57))

## [1.0.0](https://www.github.com/googleapis/nodejs-compute/compare/v0.12.0...v1.0.0) (2019-05-20)


### ⚠ BREAKING CHANGES

* upgrade engines field to >=8.10.0 (#292)

### Bug Fixes

* **deps:** update dependency @google-cloud/common to ^0.32.0 ([#285](https://www.github.com/googleapis/nodejs-compute/issues/285)) ([a728cff](https://www.github.com/googleapis/nodejs-compute/commit/a728cff))
* **deps:** update dependency @google-cloud/common to v1 ([#303](https://www.github.com/googleapis/nodejs-compute/issues/303)) ([5b5e2e7](https://www.github.com/googleapis/nodejs-compute/commit/5b5e2e7))
* **deps:** update dependency @google-cloud/paginator to v1 ([#297](https://www.github.com/googleapis/nodejs-compute/issues/297)) ([16b5ff2](https://www.github.com/googleapis/nodejs-compute/commit/16b5ff2))
* **deps:** update dependency @google-cloud/projectify to v1 ([#295](https://www.github.com/googleapis/nodejs-compute/issues/295)) ([30fff7d](https://www.github.com/googleapis/nodejs-compute/commit/30fff7d))
* **deps:** update dependency @google-cloud/promisify to v1 ([#296](https://www.github.com/googleapis/nodejs-compute/issues/296)) ([166e99e](https://www.github.com/googleapis/nodejs-compute/commit/166e99e))
* **deps:** update dependency arrify to v2 ([#287](https://www.github.com/googleapis/nodejs-compute/issues/287)) ([4bc19c8](https://www.github.com/googleapis/nodejs-compute/commit/4bc19c8))
* **deps:** update dependency gce-images to v2 ([#304](https://www.github.com/googleapis/nodejs-compute/issues/304)) ([19eaaf5](https://www.github.com/googleapis/nodejs-compute/commit/19eaaf5))
* **deps:** update dependency nodemailer to v6 ([4c8e9c5](https://www.github.com/googleapis/nodejs-compute/commit/4c8e9c5))


### Build System

* upgrade engines field to >=8.10.0 ([#292](https://www.github.com/googleapis/nodejs-compute/issues/292)) ([4101d77](https://www.github.com/googleapis/nodejs-compute/commit/4101d77))


### Features

* Adds abandonInstances to InstanceGroupManger API ([#306](https://www.github.com/googleapis/nodejs-compute/issues/306)) ([c359ce3](https://www.github.com/googleapis/nodejs-compute/commit/c359ce3))

## v0.12.0

03-13-2019 14:47 PDT

### New Features
- feat: Add getManagedInstances and deleteInstances to InstanceGroupManger API ([#265](https://github.com/googleapis/nodejs-compute/pull/265))
- feat: add basic support for InstanceGroupManager ([#263](https://github.com/googleapis/nodejs-compute/pull/263))

### Bug Fixes
- fix: snapshot.delete() no longer throws ([#251](https://github.com/googleapis/nodejs-compute/pull/251))

### Dependencies
- fix(deps): update dependency @google-cloud/paginator to ^0.2.0 ([#274](https://github.com/googleapis/nodejs-compute/pull/274))
- fix(deps): update dependency @google-cloud/promisify to ^0.4.0 ([#267](https://github.com/googleapis/nodejs-compute/pull/267))
- fix(deps): update dependency @google-cloud/common to ^0.31.0 ([#258](https://github.com/googleapis/nodejs-compute/pull/258))

### Documentation
- docs: update links in contrib guide ([#268](https://github.com/googleapis/nodejs-compute/pull/268))
- docs: update contributing path in README ([#261](https://github.com/googleapis/nodejs-compute/pull/261))
- docs: move CONTRIBUTING.md to root ([#260](https://github.com/googleapis/nodejs-compute/pull/260))
- docs: add lint/fix example to contributing guide ([#257](https://github.com/googleapis/nodejs-compute/pull/257))
- docs: use the latest sendgrid npm module ([#246](https://github.com/googleapis/nodejs-compute/pull/246))
- docs(samples): modernize the samples ([#240](https://github.com/googleapis/nodejs-compute/pull/240))

### Internal / Testing Changes
- build: Add docuploader credentials to node publish jobs ([#272](https://github.com/googleapis/nodejs-compute/pull/272))
- build: use node10 to run samples-test, system-test etc ([#271](https://github.com/googleapis/nodejs-compute/pull/271))
- build: update release configuration
- chore(deps): update dependency mocha to v6 ([#269](https://github.com/googleapis/nodejs-compute/pull/269))
- build: use linkinator for docs test ([#266](https://github.com/googleapis/nodejs-compute/pull/266))
- build: create docs test npm scripts ([#264](https://github.com/googleapis/nodejs-compute/pull/264))
- build: test using @grpc/grpc-js in CI ([#262](https://github.com/googleapis/nodejs-compute/pull/262))
- chore(deps): update dependency eslint-config-prettier to v4 ([#255](https://github.com/googleapis/nodejs-compute/pull/255))
- build: ignore googleapis.com in doc link check ([#252](https://github.com/googleapis/nodejs-compute/pull/252))
- build: check broken links in generated docs ([#248](https://github.com/googleapis/nodejs-compute/pull/248))
- fix(deps): update dependency nodemailer to v5 ([#247](https://github.com/googleapis/nodejs-compute/pull/247))
- refactor: use Object.assign where possible ([#245](https://github.com/googleapis/nodejs-compute/pull/245))

## v0.11.0

12-20-2018 16:17 PST

### Bug fixes
- fix: asyncify and fix the system tests ([#203](https://github.com/googleapis/nodejs-compute/pull/203))
- fix: Use PATCH semantics by default to set custom metadata ([#171](https://github.com/googleapis/nodejs-compute/pull/171))
- fix: use teeny-request to reduce module size ([#175](https://github.com/googleapis/nodejs-compute/pull/175))
- fix: drop support for node.js 4.x and 9.x ([#126](https://github.com/googleapis/nodejs-compute/pull/126))
- fix: require use of `new` ([#99](https://github.com/googleapis/nodejs-compute/pull/99))
- fix: update all the dependencies ([#95](https://github.com/googleapis/nodejs-compute/pull/95))
- fix: Use correct URI for Snapshot instances ([#67](https://github.com/googleapis/nodejs-compute/pull/67))
- fix: link ([#62](https://github.com/googleapis/nodejs-compute/pull/62))

### Dependencies
- fix(deps): upgrade to v0.29.1 of @google-cloud/nodejs-common ([#241](https://github.com/googleapis/nodejs-compute/pull/241))
- fix(deps): update dependency @google-cloud/common to ^0.28.0 ([#238](https://github.com/googleapis/nodejs-compute/pull/238))
- fix(deps): update dependency @google-cloud/common to ^0.27.0 ([#215](https://github.com/googleapis/nodejs-compute/pull/215))
- fix(deps): upgrade to the latest gce-images ([#201](https://github.com/googleapis/nodejs-compute/pull/201))
- fix(deps): update dependency @google-cloud/common to ^0.26.0 ([#185](https://github.com/googleapis/nodejs-compute/pull/185))
- fix(deps): update dependency @google-cloud/common to ^0.25.0 ([#121](https://github.com/googleapis/nodejs-compute/pull/121))
- chore(deps): use @google-cloud/projectify ([#174](https://github.com/googleapis/nodejs-compute/pull/174))
- chore(deps): use @google-cloud/paginator ([#173](https://github.com/googleapis/nodejs-compute/pull/173))
- chore(deps): use @google-cloud/promisify ([#172](https://github.com/googleapis/nodejs-compute/pull/172))
- fix(package): update @google-cloud/common to version 0.20.0 ([#101](https://github.com/googleapis/nodejs-compute/pull/101))
- Update @google-cloud/common to the latest version 🚀 ([#57](https://github.com/googleapis/nodejs-compute/pull/57))

### Documentation & Samples
- sample: improve the samples and tests ([#236](https://github.com/googleapis/nodejs-compute/pull/236))
- docs: update readme badges ([#219](https://github.com/googleapis/nodejs-compute/pull/219))
- docs(samples): update samples to use async/await and mocha ([#183](https://github.com/googleapis/nodejs-compute/pull/183))
- sample: Show proper response structure in vm.getMetadata example ([#169](https://github.com/googleapis/nodejs-compute/pull/169))
- sample: Add mailjet and sendgrid back in ([#110](https://github.com/googleapis/nodejs-compute/pull/110))
- sample: Add sample demonstrating startup script ([#80](https://github.com/googleapis/nodejs-compute/pull/80))
- docs: Fix Readme.md in /samples ([#73](https://github.com/googleapis/nodejs-compute/pull/73))
- sample: Fix quickstart code sample ([#69](https://github.com/googleapis/nodejs-compute/pull/69))
- docs: Fix jsdocs ([#59](https://github.com/googleapis/nodejs-compute/pull/59))

### Internal / Testing Changes
- chore: remove repo-tools from a few spots ([#239](https://github.com/googleapis/nodejs-compute/pull/239))
- chore(build): inject yoshi automation key ([#235](https://github.com/googleapis/nodejs-compute/pull/235))
- chore: update nyc and eslint configs ([#234](https://github.com/googleapis/nodejs-compute/pull/234))
- chore: fix publish.sh permission +x ([#232](https://github.com/googleapis/nodejs-compute/pull/232))
- fix(build): fix Kokoro release script ([#231](https://github.com/googleapis/nodejs-compute/pull/231))
- build: add Kokoro configs for autorelease ([#230](https://github.com/googleapis/nodejs-compute/pull/230))
- chore: add synth.metadata ([#227](https://github.com/googleapis/nodejs-compute/pull/227))
- fix(deps): update dependency googleapis to v36 ([#225](https://github.com/googleapis/nodejs-compute/pull/225))
- chore: always nyc report before calling codecov ([#224](https://github.com/googleapis/nodejs-compute/pull/224))
- chore: nyc ignore build/test by default ([#223](https://github.com/googleapis/nodejs-compute/pull/223))
- chore: update license file ([#221](https://github.com/googleapis/nodejs-compute/pull/221))
- fix(build): fix system key decryption ([#217](https://github.com/googleapis/nodejs-compute/pull/217))
- chore: update eslintignore config ([#208](https://github.com/googleapis/nodejs-compute/pull/208))
- fix(deps): update dependency googleapis to v35 ([#205](https://github.com/googleapis/nodejs-compute/pull/205))
- chore(deps): update dependency @google-cloud/nodejs-repo-tools to v3 ([#204](https://github.com/googleapis/nodejs-compute/pull/204))
- chore: drop contributors from multiple places ([#202](https://github.com/googleapis/nodejs-compute/pull/202))
- chore: use latest npm on Windows ([#199](https://github.com/googleapis/nodejs-compute/pull/199))
- chore: update CircleCI config ([#198](https://github.com/googleapis/nodejs-compute/pull/198))
- chore: include build in eslintignore ([#195](https://github.com/googleapis/nodejs-compute/pull/195))
- chore(deps): update dependency eslint-plugin-node to v8 ([#190](https://github.com/googleapis/nodejs-compute/pull/190))
- chore: update issue templates ([#189](https://github.com/googleapis/nodejs-compute/pull/189))
- chore: remove old issue template ([#187](https://github.com/googleapis/nodejs-compute/pull/187))
- build: run tests on node11 ([#186](https://github.com/googleapis/nodejs-compute/pull/186))
- chores(build): do not collect sponge.xml from windows builds ([#184](https://github.com/googleapis/nodejs-compute/pull/184))
- chores(build): run codecov on continuous builds ([#182](https://github.com/googleapis/nodejs-compute/pull/182))
- chore: update new issue template ([#181](https://github.com/googleapis/nodejs-compute/pull/181))
- build: fix codecov uploading on Kokoro ([#177](https://github.com/googleapis/nodejs-compute/pull/177))
- Update kokoro config ([#166](https://github.com/googleapis/nodejs-compute/pull/166))
- chore(deps): update dependency eslint-plugin-prettier to v3 ([#165](https://github.com/googleapis/nodejs-compute/pull/165))
- fix(deps): update dependency googleapis to v34 ([#162](https://github.com/googleapis/nodejs-compute/pull/162))
- build: prevent system/sample-test from leaking credentials
- Update CI config ([#160](https://github.com/googleapis/nodejs-compute/pull/160))
- test: remove appveyor config ([#159](https://github.com/googleapis/nodejs-compute/pull/159))
- Update the kokoro config ([#158](https://github.com/googleapis/nodejs-compute/pull/158))
- Make it pass lint ([#156](https://github.com/googleapis/nodejs-compute/pull/156))
- Enable prefer-const in the eslint config ([#155](https://github.com/googleapis/nodejs-compute/pull/155))
- Fix the linter ([#154](https://github.com/googleapis/nodejs-compute/pull/154))
- Enable no-var in eslint ([#153](https://github.com/googleapis/nodejs-compute/pull/153))
- Update CI config ([#152](https://github.com/googleapis/nodejs-compute/pull/152))
- Add synth script and update CI ([#149](https://github.com/googleapis/nodejs-compute/pull/149))
- Retry npm install in CI ([#148](https://github.com/googleapis/nodejs-compute/pull/148))
- chore(deps): update dependency nyc to v13 ([#145](https://github.com/googleapis/nodejs-compute/pull/145))
- fix(deps): update dependency googleapis to v33 ([#144](https://github.com/googleapis/nodejs-compute/pull/144))
- chore(deps): update dependency eslint-config-prettier to v3 ([#143](https://github.com/googleapis/nodejs-compute/pull/143))
- chore: ignore package-lock.json ([#142](https://github.com/googleapis/nodejs-compute/pull/142))
- chore(deps): lock file maintenance ([#141](https://github.com/googleapis/nodejs-compute/pull/141))
- chore: update renovate config ([#140](https://github.com/googleapis/nodejs-compute/pull/140))
- test: throw on deprecation ([#139](https://github.com/googleapis/nodejs-compute/pull/139))
- chore(deps): lock file maintenance ([#138](https://github.com/googleapis/nodejs-compute/pull/138))
- chore: assert.deelEqual => assert.deepStrictEqual ([#137](https://github.com/googleapis/nodejs-compute/pull/137))
- chore: move mocha options to mocha.opts ([#135](https://github.com/googleapis/nodejs-compute/pull/135))
- chore: require node 8 for samples ([#136](https://github.com/googleapis/nodejs-compute/pull/136))
- chore(deps): lock file maintenance ([#134](https://github.com/googleapis/nodejs-compute/pull/134))
- chore(deps): update dependency eslint-plugin-node to v7 ([#132](https://github.com/googleapis/nodejs-compute/pull/132))
- test: use strictEqual in tests ([#133](https://github.com/googleapis/nodejs-compute/pull/133))
- chore(deps): lock file maintenance ([#131](https://github.com/googleapis/nodejs-compute/pull/131))
- chore(deps): update dependency @google-cloud/nodejs-repo-tools to v2.3.1 ([#130](https://github.com/googleapis/nodejs-compute/pull/130))
- chore(deps): lock file maintenance ([#129](https://github.com/googleapis/nodejs-compute/pull/129))
- chore(deps): lock file maintenance ([#128](https://github.com/googleapis/nodejs-compute/pull/128))
- chore(deps): lock file maintenance ([#127](https://github.com/googleapis/nodejs-compute/pull/127))
- chore(deps): lock file maintenance ([#124](https://github.com/googleapis/nodejs-compute/pull/124))
- chore(deps): lock file maintenance ([#123](https://github.com/googleapis/nodejs-compute/pull/123))
- chore(deps): update dependency @google-cloud/nodejs-repo-tools to v2.3.0 ([#119](https://github.com/googleapis/nodejs-compute/pull/119))
- chore(deps): update dependency ava to v0.25.0 ([#120](https://github.com/googleapis/nodejs-compute/pull/120))
- Configure Renovate ([#112](https://github.com/googleapis/nodejs-compute/pull/112))
- refactor: drop repo-tool as an exec wrapper ([#118](https://github.com/googleapis/nodejs-compute/pull/118))
- chore: update sample lockfiles ([#117](https://github.com/googleapis/nodejs-compute/pull/117))
- fix: update linking for samples ([#115](https://github.com/googleapis/nodejs-compute/pull/115))
- chore(package): update eslint to version 5.0.0 ([#113](https://github.com/googleapis/nodejs-compute/pull/113))
- chore(package): update nyc to version 12.0.2 ([#94](https://github.com/googleapis/nodejs-compute/pull/94))
- Fix formatting ([#92](https://github.com/googleapis/nodejs-compute/pull/92))
- Simplify JS and use HTML standard ([#91](https://github.com/googleapis/nodejs-compute/pull/91))
- chore: lock files maintenance ([#88](https://github.com/googleapis/nodejs-compute/pull/88))
- chore: run circle as non-root, fix npm link ([#89](https://github.com/googleapis/nodejs-compute/pull/89))
- chore: the ultimate fix for repo-tools EPERM ([#87](https://github.com/googleapis/nodejs-compute/pull/87))
- Fix problem with multiple deletes in test ([#85](https://github.com/googleapis/nodejs-compute/pull/85))
- Increase timeout in startup sample test ([#86](https://github.com/googleapis/nodejs-compute/pull/86))
- chore: timeout for system test ([#84](https://github.com/googleapis/nodejs-compute/pull/84))
- chore: lock files maintenance ([#78](https://github.com/googleapis/nodejs-compute/pull/78))
- test: make samples tests pass ([#77](https://github.com/googleapis/nodejs-compute/pull/77))
- Do not show sample for Google API Client library ([#76](https://github.com/googleapis/nodejs-compute/pull/76))
- chore: test on node10 ([#74](https://github.com/googleapis/nodejs-compute/pull/74))
- Update repo-tools to 2.3.0 ([#72](https://github.com/googleapis/nodejs-compute/pull/72))
- chore: lock files maintenance ([#71](https://github.com/googleapis/nodejs-compute/pull/71))
- chore: one more workaround for repo-tools EPERM ([#60](https://github.com/googleapis/nodejs-compute/pull/60))
- chore: workaround for repo-tools EPERM ([#58](https://github.com/googleapis/nodejs-compute/pull/58))
- chore: setup nighty build in CircleCI ([#56](https://github.com/googleapis/nodejs-compute/pull/56))
- Upgrade repo-tools and regenerate scaffolding. ([#55](https://github.com/googleapis/nodejs-compute/pull/55))
