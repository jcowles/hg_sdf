# hg_sdf
A WebGL friendly port of Mercury's hg_sdf library.

Note that in this version, hg_sdf_init() must be called to initialize the library.

See http://mercury.sexy/hg_sdf for library details.

Fixes:
  * int/float compatibility mis-matches
  * dynamic loop parameters baked to static invocations
