# Change log

All notable changes to this project will be documented in this file. The
format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and
this project adheres to [Semantic Versioning](http://semver.org).

## [Unreleased]
### Summary
TODO: Not complete yet TBD

#### Added
- First part of the Templating tutorial

#### Fixed
- The Wavefront apiToken secret was leaking into the git repo commit messages in
git integration mode. [#23](https://github.com/box/wavectl/issues/23)
- Recompiling all documentation (<repo_root>/doc/sphinx$ make all) does not
overwrite the ~/.wavectl/config file with dummy values anymore.
- Commits executed in wavectl do not execute post-commit hooks of the user
anymore. The user can have all kinds of commit hooks. Wavectl should be skipping
them.


## Supported Release [0.2.0]
### Summary
Initial release of the `wavectl` project


<!-- ## Supported Release [0.2.0] -->
<!-- ### Summary -->
<!-- Initial release of the `wavectl` project -->

<!-- #### Added -->

<!-- #### Fixed -->
