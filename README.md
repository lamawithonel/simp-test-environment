# simp-test-environment

A simple control repo for testing [SIMP](https://simp-project.com), this is intended as the absolute minimum required configuration for SIMP.

The following Hiera data keys MUST be set for SIMP to compile.  We would set them to some default, but they are very site-specific.

  * `simp_options::dns::servers`
  * `simp_options::dns::search`
  * `simp_options::puppet::server`
  * `simp_options::puppet::ca`
