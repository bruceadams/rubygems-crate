# Release notes

## rubygems-0.6.0

- Fixed script call of tmp-dir in rubygems crate

- Update crates for pallet 0.6.3


## pallet-crates-0.5.0


## pallet-crates-0.4.4


## pallet-crates-0.4.3

- Update for 0.5.0-SNAPSHOT
  Change pallet.resource.* to pallet.action.*. Change stevedore calls to
  script functions to use unquote and the pallet.script.lib namespace.
  Change request to session.  Change build-resources to build-actions.


## pallet-crates-0.4.2


## pallet-crates-0.4.1


## pallet-crates-0.4.0


## pallet-crates-0.4.0-beta-1

- Update rubygems versions

- Added ruby crate dependency to rubygems

- working node-list compute service

- Refactored to extract compute provider lib

- Add retrieval of files from node. Refactor sending of files to remove
  *file-transfers*. Add ssh-key/record-public-key to retrieve a users
  public key from a remote node.

- switch test to use build-resources

- Refactoring to a more functional implementation

- Made converge run phase by phase, instead of node by node.  Added
  pre-phase. Removed :reload-all from tests to avoid deftype problems.

- Various crate changes. Added Changelog

- changes for installing chef on ubuntu 10.04

- removed 1.1 compat.  fixed compile errors from id/providerId changes

- Added target/*all-nodes* and target/*target-nodes*.  Made target vars
  uninitialised. Tidied mock.

- Harmonised do-script, cmd-join, et al.  Added defvar, defn, and println to
  stevedore. minor documentation fixes.

- Added error handling

- unification of defresource & defcomponent, elimination of atom usage in
  general, formalized sub-phase / execution type

- clojure 1.1 / 1.2 compatibility modifications

- clojure 1.1 / 1.2 compatibility modifications

- fix remote-file :source => :url option keywords

- cleanup (option processing)

- Added defnode, lift and configuration phases. Adds declaritive
  configuration definiton.

- added crates for sphinx, tomcat and hudson. added a service resource.
  tomact and hudson not yet fully functional.  Fixed escaping in
  mysql-script.

- minor improvements, and doc fixes

- add crates for ruby, rubygems and chef.  added remote file resource, and
  conditional resources

