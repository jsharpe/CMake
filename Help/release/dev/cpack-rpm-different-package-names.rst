cpack-rpm-different-package-names
---------------------------------

* The :module:`CPackRPM` module learned how to set user defined package file
  names, how to specify that rpmbuild should decide on file name format as
  well as handling of multiple rpm packages generated by a single user defined
  spec file.
  See :variable:`CPACK_RPM_PACKAGE_NAME` and
  :variable:`CPACK_RPM_<component>_PACKAGE_NAME`.
