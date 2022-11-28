---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## How-To Guides

Derived from a series of AQAvit Lightning talks, here is a set of how-to guides:

### TKG
- How to run tests locally?  
- How to reduce test compilation time leveraging DYNAMIC_COMPILE?
- How to overlay other vendor tests for execution?

### CI Layer: Jenkins 
- How to rerun a test in a Grinder in Jenkins?
  - rerun on the same machine?
  - rerun only the failed targets?
  - rerun a test with different options?
- How to see if test targets are disabled?
- How to run a disabled test target?
- How to run a subset of tests from a particular test target?
  - system_custom?
  - jdk_custom, lang_custom, hotspot_custom?
  - external_custom?
- How to check if a test failure is intermittent?

### TRSS
- How to see all tests running in a particular build pipeline?
- How to use TRSS to triage a build pipeline?
  - Deep history
  - All platforms
  - Possible issues
  - Jenkins link
  - Create new issue
- How to generate a release summary report?