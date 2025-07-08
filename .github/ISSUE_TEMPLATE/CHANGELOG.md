# Changelog CAMARA Predictive Connectivity Data

## Table of Contents
- **[r1.1](#r11)**

**Please be aware that the project will have frequent updates to the main branch. There are no compatibility guarantees associated with code in any branch, including main, until it has been released. For example, changes may be reverted before a release is published. For the best results, use the latest published release.**

The below sections record the changes for each API version in each release as follows:
* for the first release-candidate, all changes since the last public release
* for subsequent release-candidate(s), only the delta to the previous release-candidate
* for a public release, the consolidated changes since the previous public release

# r1.1

## Release Notes
This release contains the definition and documentation of
* predictive-connectivity-data v0.1.0-rc.1

The API definition(s) are based on
* Commonalities v0.6.0-rc.1
* Identity and Consent Management v0.4.0-rc.1

## preditive-connectivity-data v0.1.0-rc.1

This is a release candidate for the CAMARA Meta Release Fall25 release of the Predictive Connectivity Data API, version v0.1.0-rc.1. It contains mainly alignments with the Commonalities v0.6.0-rc.1.

- API definition **with inline documentation**:
  - OpenAPI [YAML spec file](https://github.com/camaraproject/PredictiveConnectivityData/blob/r1.1/code/API_definitions/predictive-connectivity-data.yaml)
  - [View it on ReDoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/camaraproject/PredictiveConnectivityData/r1.1/code/API_definitions/predictive-connectivity-data.yaml&nocors)
  - [View it on Swagger Editor](https://camaraproject.github.io/swagger-ui/?url=https://raw.githubusercontent.com/camaraproject/PredictiveConnectivityData/r1.1/code/API_definitions/predictive-connectivity-data.yaml)

In the following there is the list of the modifications with respect to the previous release.

### Added
* Add user story for PCD by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/13
* Add new checklist for PCD API by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/11
* Add meeting cadence link to README by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/19
* Add linting rules by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/23
* Add precision, height and signal strenght to the wip version by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/25

### Changed
* Update config.yml - replace placeholder $repo_name$ and update link to API Design Guide by @hdamker in https://github.com/camaraproject/PredictiveConnectivityData/pull/3
* Define first WIP version of Predictive Connectivity Data API by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/20
* docs: update README with onboarding info and kick off PDF by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/5
* Align commonalities with v0.6-rc1 by @albertoramosmonagas in https://github.com/camaraproject/PredictiveConnectivityData/pull/21

### Fixed
* N/A

### Removed
* N/A

### New Contributors
* @hdamker made their first contribution in https://github.com/camaraproject/PredictiveConnectivityData/pull/3
* @albertoramosmonagas made their first contribution in https://github.com/camaraproject/PredictiveConnectivityData/pull/5

**Full Changelog**: https://github.com/camaraproject/PredictiveConnectivityData/commits/r1.1