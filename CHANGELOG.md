# ChangeLog

## [Unreleased]
### Added
- option -w/--webroot for automating the copying of token files to the
  DocumentRoot, either locally or remote via rsync
- Configurable list of multiple domain names (#1)

### Changed
- adapted normal and debug output of script
- use http://keepachangelog.com formatting for this CHANGELOG
- manage private key file permissions so they are ownly owner-accessible at any
  time of their generation
- Load openssl.conf relative to script path (#2)
- renamed option -d/--debug to -v/--verbose


## [0.2.0] - 2017-12-03
### Added
- automatic use of newest subscriber agreement URL

### Changed
- logging


## [0.1.0] - 2016-09-05
### Added
- initial version
