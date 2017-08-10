# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html), as much as
a website reasonably can. Backwards incompatible changes (requiring a major version bump) will be
described here, and may involve database changes, significant workflow changes, or changes that
require manual edits to pluggable interfaces.

## Unreleased

### Changed
- Project ACLs are now sanely validated, with levels of "owner", "editor", and "viewer". A viewer
  can only view a project. An editor can change project details, except for the ACL. An owner can
  change everything about a project.
- Users on a project contact list implicitly have "viewer" permissions unless otherwire specified.

## 0.8.0 - 2017-08-04

- Initial release.