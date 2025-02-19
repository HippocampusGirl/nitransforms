21.0.0 (September 10, 2021)
===========================
A first release of *NiTransforms*.
This release accompanies a corresponding `JOSS submission <https://doi.org/10.21105/joss.03459>`__.

  * FIX: Final edits to JOSS submission (#135)
  * FIX: Add mention to potential alternatives in JOSS submission (#132)
  * FIX: Misinterpretation of voxel ordering in LTAs (#129)
  * FIX: Suggested edits to the JOSS submission (#121)
  * FIX: Invalid DOI (#124)
  * FIX: Remove the ``--inv`` flag from regression ``mri_vol2vol`` regression test (#78)
  * FIX: Improve handling of optional fields in LTA (#65)
  * FIX: LTA conversions (#36)
  * ENH: Add more comprehensive comments to notebook (#134)
  * ENH: Add an ``.asaffine()`` member to ``TransformChain`` (#90)
  * ENH: Read (and apply) *ITK*/*ANTs*' composite HDF5 transforms (#79)
  * ENH: Improved testing of LTA handling - *ITK*-to-LTA, ``mri_concatenate_lta`` (#75)
  * ENH: Add *FS* transform regression (#74)
  * ENH: Add *ITK*-LTA conversion test (#66)
  * ENH: Support for transforms mappings (e.g., head-motion correction) (#59)
  * ENH: command line interface (#55)
  * ENH: Facilitate loading of displacements field transforms (#54)
  * ENH: First implementation of *AFNI* displacement fields (#50)
  * ENH: Base implementation of transforms chains (composition) (#43)
  * ENH: First implementation of loading and applying *ITK* displacements fields (#42)
  * ENH: Refactor of *AFNI* and *FSL* I/O with ``StringStructs`` (#39)
  * ENH: More comprehensive implementation of ITK affines I/O (#35)
  * ENH: Added some minimal test-cases to the Affine class (#33)
  * ENH: Rewrite load/save utilities for ITK's MatrixOffsetBased transforms in ``io`` (#31)
  * ENH: Rename ``resample()`` with ``apply()`` (#30)
  * ENH: Write tests pulling up the coverage of base submodule (#28)
  * ENH: Add tests and implementation for Displacements fields and refactor linear accordingly (#27)
  * ENH: Uber-refactor of code style, method names, etc. (#24)
  * ENH: Increase coverage of linear transforms code (#23)
  * ENH: FreeSurfer LTA file support (#17)
  * ENH: Use ``obliquity`` directly from nibabel (#18)
  * ENH: Setting up a battery of tests (#9)
  * ENH: Revise doctests and get them ready for more thorough testing. (#10)
  * DOC: Add *Zenodo* metadata record (#136)
  * DOC: Better document the *IPython* notebooks (#133)
  * DOC: Transfer ``CoC`` from *NiBabel* (#131)
  * DOC: Clarify integration plans with *NiBabel* in the ``README`` (#128)
  * DOC: Add contributing page to RTD (#130)
  * DOC: Add ``CONTRIBUTING.md`` file pointing at *NiBabel* (#127)
  * DOC: Add example notebooks to sphinx documentation (#126)
  * DOC: Add an *Installation* section (#122)
  * DOC: Display API per module (#120)
  * DOC: Add figure to JOSS draft / Add @smoia to author list (#61)
  * DOC: Initial JOSS draft (#47)
  * MAINT: Add imports of modules in ``__init__.py`` to workaround #91 (#92)
  * MAINT: Fix missing ``python3`` binary on CircleCI build job step (#85)
  * MAINT: Use ``setuptools_scm`` to manage versioning (#83)
  * MAINT: Split binary test-data out from gh repo (#84)
  * MAINT: Add Docker image/circle build (#80)
  * MAINT: Drop Python 3.5 (#77)
  * MAINT: Better config on ``setup.py`` (binary operator starting line) (#60)
  * MAINT: add docker build to travis matrix (#29)
  * MAINT: testing coverage (#16)
  * MAINT: pep8 complaints (#14)
  * MAINT: skip unfinished implementation tests (#15)
  * MAINT: pep8speaks (#13)
