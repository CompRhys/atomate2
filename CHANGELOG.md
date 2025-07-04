# Change log

## v0.0.21

### Bug Fixes 🐛
* switch to CONTCAR read for LOBSTERTaskDoc by @naik-aakash in https://github.com/materialsproject/atomate2/pull/1204
* cover cases where optimizer does additional steps even though step is set to 0 or 1 for writing xyz files by @JaGeo in https://github.com/materialsproject/atomate2/pull/1207
* Remove walrus operator to avoid unassigned vmax by @Jonas-Finkler in https://github.com/materialsproject/atomate2/pull/1203
### Enhancements 🛠
* add file output xyz file including final atoms object to ase and forcefield jobs by @JaGeo in https://github.com/materialsproject/atomate2/pull/1206
### Documentation 📖
* Add video tutorials to README by @JaGeo in https://github.com/materialsproject/atomate2/pull/1191
* be more concrete for tutorial video names in readme by @JaGeo in https://github.com/materialsproject/atomate2/pull/1192
* Adding download statistics to readme by @JaGeo in https://github.com/materialsproject/atomate2/pull/1209

## New Contributors
* @Jonas-Finkler made their first contribution in https://github.com/materialsproject/atomate2/pull/1203

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.20...v0.0.21

## v0.0.20

### Enhancements 🛠
* Add MatPES forcefields by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1158
* Add `DynamicOpenMMFlowMaker` for dynamic OpenMM Simulations by @shehan807 in https://github.com/materialsproject/atomate2/pull/1115
* atomate2 / OpenMM OPLS-AA Enhancements by @shehan807 in https://github.com/materialsproject/atomate2/pull/1111
* Add updated MP workflows + cleanup by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1139
### Documentation 📖
* Improve documentation LOBSTER and PHONON workflow by @JaGeo in https://github.com/materialsproject/atomate2/pull/1117
* Add key concept tutorial to tutorial list in README by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/1120
* Fixing headline levels in key_concepts_overview.md by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/1121
* try to fix the doc by @JaGeo in https://github.com/materialsproject/atomate2/pull/1125
* Added code snippets for Grüneisen, QHA and EOS wfs documentation by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/1130
* a few improvements for the tutorials by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/1132
* Update tutorials.md by @JaGeo in https://github.com/materialsproject/atomate2/pull/1138
* Electrode workflow and documentation improvements by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1055
* Update index.md by @JaGeo in https://github.com/materialsproject/atomate2/pull/1155
### House-Keeping 🧹
* More CI fixes by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1141
### Other Changes
* Pin MACE calculator version, add missing metadata to AseStructureTaskDoc by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1119
* Tutorials for QHA and Grüneisen workflows by @JaGeo in https://github.com/materialsproject/atomate2/pull/1122
* add more headlines to tutorials and fix a typo by @JaGeo in https://github.com/materialsproject/atomate2/pull/1126
* Minor update to tutorials by @naik-aakash in https://github.com/materialsproject/atomate2/pull/1128
* adjust example flow names by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/1131
* Aims phonon tutorials by @tpurcell90 in https://github.com/materialsproject/atomate2/pull/1136
* fix gruneisen tutorial by @JaGeo in https://github.com/materialsproject/atomate2/pull/1142
* fix link again for aims tutorial by @JaGeo in https://github.com/materialsproject/atomate2/pull/1143
* Append name relax by @JaGeo in https://github.com/materialsproject/atomate2/pull/1150
* add more info on jobflow-remote by @JaGeo in https://github.com/materialsproject/atomate2/pull/1154
* Add example MP-compatible phase diagram tutorial by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1159

## v0.0.19

### Bug Fixes 🐛
* CP2K fixes by @janosh in https://github.com/materialsproject/atomate2/pull/1056
* bug fix for linear strain passing in qha by @JaGeo in https://github.com/materialsproject/atomate2/pull/1061
* Fix `generate_phonon_displacements`  magmom removal side effect by @janosh in https://github.com/materialsproject/atomate2/pull/1064
* Fixed Failing Abinit tests bis by @VicTrqt in https://github.com/materialsproject/atomate2/pull/1108
### Enhancements 🛠
* Add trajectory reporter to openmm workflow by @orionarcher in https://github.com/materialsproject/atomate2/pull/1053
* `PhononMaker` add options to `calculate_pdos` and save force constants to file by @chouyoudou in https://github.com/materialsproject/atomate2/pull/1008
* Allow `MatPesStaticFlowMaker(static2=None)` by @janosh in https://github.com/materialsproject/atomate2/pull/997
### Documentation 📖
* Minor docs cleanup by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1047
* add openmm description to docs by @JaGeo in https://github.com/materialsproject/atomate2/pull/1069
* Docs update, forcefield elastic convenience maker, forcefield enum hydration by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/1072
* Added the ChemRxiv citation by @hrushikesh-s in https://github.com/materialsproject/atomate2/pull/1107
* Fix docs by @janosh in https://github.com/materialsproject/atomate2/pull/1109
### House-Keeping 🧹
* Fix minor phonon code formatting issues + typos by @janosh in https://github.com/materialsproject/atomate2/pull/1070
* Fix bump phonopy by @naik-aakash in https://github.com/materialsproject/atomate2/pull/1006
* update calorine version by @naik-aakash in https://github.com/materialsproject/atomate2/pull/1083
* Deprecated `Structure.ntypesp` in pymatgen by @jmmshn in https://github.com/materialsproject/atomate2/pull/1105

### New Contributors
* @chouyoudou made their first contribution in https://github.com/materialsproject/atomate2/pull/1008
* @VicTrqt made their first contribution in https://github.com/materialsproject/atomate2/pull/1108

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.18...v0.0.19

## v0.0.18

### New Features 🎉
* Aims magnetic ordering by @tpurcell90 in https://github.com/materialsproject/atomate2/pull/922
* Ferroelectric Workflow 2 by @fraricci in https://github.com/materialsproject/atomate2/pull/1012
* Feat: GW workflow with VASP by @yanghan234 in https://github.com/materialsproject/atomate2/pull/808

### Enhancements 🛠
* Allow energy minimization maker to report energies by @orionarcher in https://github.com/materialsproject/atomate2/pull/1004
* Implementation to adjust get_supercell_size to also generate orthorhombic supercells by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/923
* MPMorph Flows by @BryantLi-BLI in https://github.com/materialsproject/atomate2/pull/938

### House-Keeping 🧹
* Fix `ruff` PLC0206 by @janosh in https://github.com/materialsproject/atomate2/pull/1009
* Update MACE to 0.3.6 by @orionarcher in https://github.com/materialsproject/atomate2/pull/1032
* Allow custom mace model by specifying "model" in calculator kwargs" by @orionarcher in https://github.com/materialsproject/atomate2/pull/1017
* feat: add dedicated fireworks optional dependency (Fix #1033). by @hongyi-zhao in https://github.com/materialsproject/atomate2/pull/1035
* Make testing utils importable by @jmmshn in https://github.com/materialsproject/atomate2/pull/1037

### New Contributors
* @fraricci made their first contribution in https://github.com/materialsproject/atomate2/pull/1012
* @hongyi-zhao made their first contribution in https://github.com/materialsproject/atomate2/pull/1035
* @BryantLi-BLI made their first contribution in https://github.com/materialsproject/atomate2/pull/938
* @yanghan234 made their first contribution in https://github.com/materialsproject/atomate2/pull/808

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.17...v0.0.18

## v0.0.17

### Bug Fixes 🐛

* Fix `prev_dir` behavior in input set generator of `MPGGAStaticMaker` by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/996

### Documentation 📖

* Bump min supported Python to 3.10 by @janosh in https://github.com/materialsproject/atomate2/pull/992

### House-Keeping 🧹

* Excise openff dependency from OpenMM testing by @orionarcher in https://github.com/materialsproject/atomate2/pull/993
* Use `pytest-split` to parallelize across 3 runners and speedup CI by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/985

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.16...v0.0.17

## v0.0.16

This release brings lots of new workflows and support for all ASE calculators.

### New Features 🎉

* Anharmonicity Quantification workflow by @4kevinbeck5 in https://github.com/materialsproject/atomate2/pull/901
* Workflow for Quasi-harmonic approximation (forcefields and VASP) by @JaGeo in https://github.com/materialsproject/atomate2/pull/903
* Atomate2 OpenMM integration & broader classical MD framework by @orionarcher in https://github.com/materialsproject/atomate2/pull/782
* Frequency Flattening Optimizer by @rohithsrinivaas in https://github.com/materialsproject/atomate2/pull/863
* Including VASP surface adsorption flow by @itsduowang in https://github.com/materialsproject/atomate2/pull/691
* Generalize forcefields for generic ASE calculator support by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/940

### Documentation 📖

* Input set tutorial by @JonathanSchmidt1 in https://github.com/materialsproject/atomate2/pull/780

### House-Keeping 🧹

* Remove emmet `==` pin in `pyproject.toml` and update version in `strict` by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/988

### New Contributors

* @4kevinbeck5 made their first contribution in https://github.com/materialsproject/atomate2/pull/901
* @orionarcher made their first contribution in https://github.com/materialsproject/atomate2/pull/782
* @rohithsrinivaas made their first contribution in https://github.com/materialsproject/atomate2/pull/863
* @itsduowang made their first contribution in https://github.com/materialsproject/atomate2/pull/691

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.15...v0.0.16

## v0.0.15

**NOTE**: This version updates the VASP workflows to use input sets defined in pymatgen. Please make sure your pymatgen version is updated accordingly.

### New Features 🎉

* Add nequip force field relax- and staticmaker and corresponding tests by @JonathanSchmidt1 in https://github.com/materialsproject/atomate2/pull/764
* Porting qchem into atomate2 by @rdguha1995 in https://github.com/materialsproject/atomate2/pull/689
* Forcefield molecular dynamics and forcefield refactor by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/722
* Abinit workflows: static, non-scf and relaxation. by @davidwaroquiers in https://github.com/materialsproject/atomate2/pull/183
* Add magnetic orderings workflow by @mattmcdermott in https://github.com/materialsproject/atomate2/pull/432
* Add elastic workflow for FHI-aims by @tpurcell90 in https://github.com/materialsproject/atomate2/pull/871
* Transition to pymatgen VASP input sets by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/854
* Add workflow to compute Gruneisen parameters  by @naik-aakash in https://github.com/materialsproject/atomate2/pull/752

### Bug Fixes 🐛

* Fix tests and installation bug by @jmmshn in https://github.com/materialsproject/atomate2/pull/765
* Add `revert_default_dtype` context manager to fix clashing global `torch.dtype` between MACE and CHGNet by @janosh in https://github.com/materialsproject/atomate2/pull/766
* Fix `TrajectoryObserver.to_ase_trajectory` return type by @janosh in https://github.com/materialsproject/atomate2/pull/852
* Fix JobStoreDocument attribute access  by @mjwen in https://github.com/materialsproject/atomate2/pull/710
* fix CP2K TaskDocument by @lory-w in https://github.com/materialsproject/atomate2/pull/900
* Add back `symprec` kwarg to MP and MatPES set generators by @janosh in https://github.com/materialsproject/atomate2/pull/947
* Fix MPID assignment in electrode workflow by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/956

### Enhancements 🛠

* Add dir_name to ForceFieldMaker and **task_document_kwargs to from_ase_compatible_result by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/791
* Add flexible filename and extension to phonon new_plotter by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/792
* Simplify phonon `get_supercell_size()` and test clean up by @janosh in https://github.com/materialsproject/atomate2/pull/783
* Add `fix_symmetry: bool = False` option to forcefield relax makers by @JonathanSchmidt1 in https://github.com/materialsproject/atomate2/pull/789
* Update LobsterTaskDoc  by @naik-aakash in https://github.com/materialsproject/atomate2/pull/723
* `from_...` class methods now return `typing_extensions.Self` by @janosh in https://github.com/materialsproject/atomate2/pull/840
* Make Fermi Energy Optional for FHI-aims by @tpurcell90 in https://github.com/materialsproject/atomate2/pull/793
* Handling failures in elastic flow by @gpetretto in https://github.com/materialsproject/atomate2/pull/861
* Bug in supercell matrix determination in phonon workflow by @JaGeo in https://github.com/materialsproject/atomate2/pull/872
* Add possibility to use your own M3GNet potential by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/911
* Equation of State workflow for FHI-aims by @ansobolev in https://github.com/materialsproject/atomate2/pull/889
* Add NEP MLIP relax, static, and MD makers by @naik-aakash in https://github.com/materialsproject/atomate2/pull/893
* add additional fields as kwargs to PhononBSDOSDoc by @naik-aakash in https://github.com/materialsproject/atomate2/pull/910
* Defect: Allow bulk SC calculation to be skipped. by @jmmshn in https://github.com/materialsproject/atomate2/pull/742
* Add `SevenNetRelaxMaker` + `SevenNetStaticMaker` to force field jobs by @janosh in https://github.com/materialsproject/atomate2/pull/918
* Lobster schema updates by @naik-aakash in https://github.com/materialsproject/atomate2/pull/924

### Documentation 📖

* Corrected typo in doc by @rul048 in https://github.com/materialsproject/atomate2/pull/775
* Add more details to the installation guide by @JaGeo in https://github.com/materialsproject/atomate2/pull/810
* Add missing `calculator_kwargs` and remove outdated `model`/`model_kwargs` in `ForceFieldRelaxMaker` doc strings by @janosh in https://github.com/materialsproject/atomate2/pull/830
* Document the option to run LOBSTER with one jobscript only by @JaGeo in https://github.com/materialsproject/atomate2/pull/811
* Fix title hierarchies in VASP documentation by @JaGeo in https://github.com/materialsproject/atomate2/pull/853
* Docs: add Document Models / emmet tutorial by @rkingsbury in https://github.com/materialsproject/atomate2/pull/917
* Writing tutorial for high level overview of atomate2 concepts. by @QuantumChemist in https://github.com/materialsproject/atomate2/pull/757
* Tutorial for blob storage with test by @jmmshn in https://github.com/materialsproject/atomate2/pull/776
* [WIP] Documentation update by @AntObi in https://github.com/materialsproject/atomate2/pull/850
* Added documentation about JSONStore usage within Installation by @abhardwaj73 in https://github.com/materialsproject/atomate2/pull/945
* Remove README note about atomate2 mostly being for VASP by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/957
* Increase k-point density for MP GGA static calculations to close issue https://github.com/materialsproject/atomate2/issues/844 by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/854
* Adds missing MAGMOMs for MatPES jobs by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/854

### House-Keeping 🧹

* Make functions prefixed with `_` but cross-imported public by @janosh in https://github.com/materialsproject/atomate2/pull/767
* Warn on non-default `ATOMATE2_CONFIG_FILE` that's not found by @janosh in https://github.com/materialsproject/atomate2/pull/794
* Remove `abinit` `__all__` module star exports by @janosh in https://github.com/materialsproject/atomate2/pull/804
* Turn `ForceFieldRelaxMaker._calculator` method into `calculator` property by @janosh in https://github.com/materialsproject/atomate2/pull/839
* Update LobsterPy version in standard installation by @JaGeo in https://github.com/materialsproject/atomate2/pull/841
* CI add `repository_dispatch` event for `pymatgen_ci_trigger` by @janosh in https://github.com/materialsproject/atomate2/pull/835
* Add test for supercell matrix creation in phonon workflow by @JaGeo in https://github.com/materialsproject/atomate2/pull/873
* `ruff` fixes by @janosh in https://github.com/materialsproject/atomate2/pull/894
* `ruff` fixes by @janosh in https://github.com/materialsproject/atomate2/pull/946

### New Contributors

* @rul048 made their first contribution in https://github.com/materialsproject/atomate2/pull/775
* @davidwaroquiers made their first contribution in https://github.com/materialsproject/atomate2/pull/183
* @ansobolev made their first contribution in https://github.com/materialsproject/atomate2/pull/889
* @lory-w made their first contribution in https://github.com/materialsproject/atomate2/pull/900
* @AntObi made their first contribution in https://github.com/materialsproject/atomate2/pull/850
* @abhardwaj73 made their first contribution in https://github.com/materialsproject/atomate2/pull/945

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.14...v0.0.15

## v0.0.14

### New Features 🎉

* Add lobster mp workflow by @JaGeo in https://github.com/materialsproject/atomate2/pull/634
* Add FHI-aims DFT calculator by @tpurcell90 in https://github.com/materialsproject/atomate2/pull/562
* Electrode Workflow by @jmmshn in https://github.com/materialsproject/atomate2/pull/655
* Equation of state (EOS) workflows by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/623

### Bug Fixes 🐛

* Skip final LDAU/J/L/MAGMOM updates and fix setting MAGMOM via `user_incar_settings` by @JonathanSchmidt1 in https://github.com/materialsproject/atomate2/pull/648
* Prep for next `pymatgen` release by @janosh in https://github.com/materialsproject/atomate2/pull/690
* fix SC Matrix Checking Logic by @jmmshn in https://github.com/materialsproject/atomate2/pull/704
* Fix elastic conventional structure by @mjwen in https://github.com/materialsproject/atomate2/pull/706
* Add `KspacingMetalHandler` to VASP `_DEFAULT_HANDLERS` by @janosh in https://github.com/materialsproject/atomate2/pull/600
* Fix import error [ijson] by @naik-aakash in https://github.com/materialsproject/atomate2/pull/708
* Print invalid value and list valid ones in `PhononMaker` error messages by @janosh in https://github.com/materialsproject/atomate2/pull/728
* Update minimum `monty` version, allow newer `pydantic` by @mkhorton in https://github.com/materialsproject/atomate2/pull/720
* Fix phonon + Lobster flow by removing magmoms before passing to `phonopy` by @naik-aakash in https://github.com/materialsproject/atomate2/pull/751
* Fix MP query by @utf in https://github.com/materialsproject/atomate2/pull/755

### Enhancements 🛠

* add directory of task doc generation to phonon schema by @JaGeo in https://github.com/materialsproject/atomate2/pull/674
* Ensure MP VASP sets don't use auto_ismear, few other fixes by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/673
* Schema update > Update plot example LOBSTER workflow by @naik-aakash in https://github.com/materialsproject/atomate2/pull/682
* Modify `BadInputSetWarning` logic for relaxations of a likely metal by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/727
* Define `MLFF` `Enum` to ensure consistent force field names by @janosh in https://github.com/materialsproject/atomate2/pull/729

### Documentation 📖

* Update doc: adding metadata to flow by @naik-aakash in https://github.com/materialsproject/atomate2/pull/638
* Fix hyperlink in Docs by @naik-aakash in https://github.com/materialsproject/atomate2/pull/686
* Correct typo in doc by @JiQi535 in https://github.com/materialsproject/atomate2/pull/716
* Fix docstring on `MatPesMetaGGAStaticSetGenerator` by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/725
* Add `citation.cff` file, Zenodo record and readme "How to cite" section by @janosh in https://github.com/materialsproject/atomate2/pull/731

### House-Keeping 🧹

* Address TODO re missing asserts in `test_elastic_wf_with_mace()` by @janosh in https://github.com/materialsproject/atomate2/pull/679
* Update lobsterpy version by @naik-aakash in https://github.com/materialsproject/atomate2/pull/683
* Fix all ruff PT011 (not checking error message when testing exceptions) by @janosh in https://github.com/materialsproject/atomate2/pull/698

### New Contributors

* @JonathanSchmidt1 made their first contribution in https://github.com/materialsproject/atomate2/pull/648
* @rdguha1995 made their first contribution in https://github.com/materialsproject/atomate2/pull/161
* @JiQi535 made their first contribution in https://github.com/materialsproject/atomate2/pull/716

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.13...v0.0.14

## v0.0.13

### BREAKING CHANGE

The API of `Maker.maker` for all workflows (VASP, CP2K, force fields) have been modified. Previously, this function had custom arguments for previous calculation directories (e.g., `prev_vasp_dir`, `prev_cp2k_dir`). These arguments have been standardised to `prev_dir`. Accordingly, the approach used to chain workflows has now changed.

### New Features 🎉

* Add setting `VASP_RUN_DDEC6: bool = False` by @janosh in https://github.com/materialsproject/atomate2/pull/587

### Bug Fixes 🐛

* Resolve bandstructure datastore bug by @JaGeo in https://github.com/materialsproject/atomate2/pull/605
* Fix `TypeError`: `PhononBSPlotter.save_plot()` got an unexpected keyword argument `img_format` by @janosh in https://github.com/materialsproject/atomate2/pull/625
* `ForceFieldRelaxMaker` default `relax_cell` to `True` by @janosh in https://github.com/materialsproject/atomate2/pull/635
* Replace ase `ExpCellFilter` with `FrechetCellFilter` in `Relaxer` by @janosh in https://github.com/materialsproject/atomate2/pull/636
* update lobsterpy version and schemas to match new version changes by @naik-aakash in https://github.com/materialsproject/atomate2/pull/637
* Default `create_thermal_displacements` to `False` in VASP and forcefield `PhononMaker` by @janosh in https://github.com/materialsproject/atomate2/pull/647
* Fix import of ASE filters when user has installed from PyPI and not gitlab by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/650
* Mark schema fields with `None` default as `Optional` to pass pydantic v2 validation by @danielzuegner in https://github.com/materialsproject/atomate2/pull/651

### Enhancements 🛠

* Breaking: Unify previous directory `Maker` API by @janosh in https://github.com/materialsproject/atomate2/pull/593
* Add keyword `incar_exclude: Sequence[str] = None` to `fake_run_vasp()` by @janosh in https://github.com/materialsproject/atomate2/pull/599
* Allow `prv_dir` to be used more in defect wf by @jmmshn in https://github.com/materialsproject/atomate2/pull/585
* Add MACE RelaxMaker and StaticMaker by @CompRhys in https://github.com/materialsproject/atomate2/pull/611
* Update lobster task schema by @naik-aakash in https://github.com/materialsproject/atomate2/pull/529
* Allow optimizer to be configured for MACE/GAP by @CompRhys in https://github.com/materialsproject/atomate2/pull/615
* MACE Static/RelaxMakers default to loading `mace_mp` instead of test model by @janosh in https://github.com/materialsproject/atomate2/pull/614
* Add optional 3rd static for PBE+U to `MatPesStaticFlowMaker` by @janosh in https://github.com/materialsproject/atomate2/pull/606
* Use PyPI version of MACE by @utf in https://github.com/materialsproject/atomate2/pull/668
* Multi step MD flow by @gpetretto in https://github.com/materialsproject/atomate2/pull/489

### Documentation 📖

* Add @CompRhys to `contributors.md` by @CompRhys in https://github.com/materialsproject/atomate2/pull/612

### House-Keeping 🧹

* Update GitHub Action versions by @janosh in https://github.com/materialsproject/atomate2/pull/640
* Drop `flake8` by @janosh in https://github.com/materialsproject/atomate2/pull/658
* Enable all `ruff` rules by default by @janosh in https://github.com/materialsproject/atomate2/pull/663

### New Contributors

* @CompRhys made their first contribution in https://github.com/materialsproject/atomate2/pull/612
* @danielzuegner made their first contribution in https://github.com/materialsproject/atomate2/pull/651

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.12...v0.0.13

## v0.0.12

* Breaking: default `Atomate2Settings.VASP_INHERIT_INCAR` to `False` by @janosh in https://github.com/materialsproject/atomate2/pull/594

### Bug Fixes 🐛

* Enforce magmom precedence in INCAR creation by @mattmcdermott in https://github.com/materialsproject/atomate2/pull/506
* Warn on empty config by @janosh in https://github.com/materialsproject/atomate2/pull/522
* CP2K use `calcs_reversed[0]` instead of `calcs_reversed[-1]` to not reverse again by @janosh in https://github.com/materialsproject/atomate2/pull/534
* Fix wrong INCAR values in MP workflows by @janosh in https://github.com/materialsproject/atomate2/pull/550
* Fix failing tests from Pydantic v2 migration by @hrushikesh-s in https://github.com/materialsproject/atomate2/pull/558
* fixing pydantic v2 test errors by @hrushikesh-s in https://github.com/materialsproject/atomate2/pull/565
* `parse_additional_json()` ignore `FW.json.gz` in output directories by @janosh in https://github.com/materialsproject/atomate2/pull/574
* Fix `bandgap_tol` and delete `bandgap_override` on `MPMetaGGARelaxSetGenerator` by @janosh in https://github.com/materialsproject/atomate2/pull/553
* Fix `VaspInputGenerator`'s `_set_kspacing` not respecting `auto_ismear = False` nor `auto_kspacing = False` by @janosh in https://github.com/materialsproject/atomate2/pull/576
* Clean up VASP powerups, correct params in MP flows, test for `_set_u_params`, test for `_set_kspacing`, fix `_get_incar` method of `VaspInputSet` by @esoteric-ephemera in https://github.com/materialsproject/atomate2/pull/561
* Fix Lobster workflow by @JaGeo in https://github.com/materialsproject/atomate2/pull/583
* Change `MatPesGGAPlusMetaGGAStaticMaker.output` to dict containing both statics by @janosh in https://github.com/materialsproject/atomate2/pull/586
* Test MP + MatPES set generators by @janosh in https://github.com/materialsproject/atomate2/pull/596

### Enhancements 🛠

* Add StructureMetadata as baseclass for output documents by @gpetretto in https://github.com/materialsproject/atomate2/pull/514
* Materials Project GGA and meta-GGA workflows by @janosh in https://github.com/materialsproject/atomate2/pull/504
* MP-compatible r2SCAN workflow (and a few general INCAR improvements) by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/362
* Update to Pydantic v2 by @hrushikesh-s in https://github.com/materialsproject/atomate2/pull/567
* Add MatPES GGA and r2SCAN static makers by @janosh in https://github.com/materialsproject/atomate2/pull/532
* Move elastic workflow to common and build force-field elastic workflow by @JaGeo in https://github.com/materialsproject/atomate2/pull/581

### Documentation 📖

* Update @arosen93 to @Andrew-S-Rosen by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/516
* Add Aaron Kaplan and Matthew McDermott to `contributors.md` by @janosh in https://github.com/materialsproject/atomate2/pull/560
* Document architectural difference between atomate 1 and 2 by @janosh in https://github.com/materialsproject/atomate2/pull/381
* Add Thomas Purcell to `contributors.md` by @tpurcell90 in https://github.com/materialsproject/atomate2/pull/568
* Add Alex Bonkowski to contributors list by @JaGeo in https://github.com/materialsproject/atomate2/pull/573
* Add @matthewkuner to contributors by @matthewkuner in https://github.com/materialsproject/atomate2/pull/575
* Update contributors.md by @utf in https://github.com/materialsproject/atomate2/pull/579

### House-Keeping 🧹

* Remove `__all__` from all modules by @janosh in https://github.com/materialsproject/atomate2/pull/540
* removed py38 support, and add py 3.11 support by @naik-aakash in https://github.com/materialsproject/atomate2/pull/537
* Check full INCAR by default in `mock_vasp` fixture by @janosh in https://github.com/materialsproject/atomate2/pull/551
* skip validate charge test by @jmmshn in https://github.com/materialsproject/atomate2/pull/563
* Add some type annotations by @ab5424 in https://github.com/materialsproject/atomate2/pull/578
* Future type annotations by @janosh in https://github.com/materialsproject/atomate2/pull/580
* Use `numpy.testing.assert_allclose` over assert `np.(all|is)close` by @janosh in https://github.com/materialsproject/atomate2/pull/582

### New Contributors

* @mattmcdermott made their first contribution in https://github.com/materialsproject/atomate2/pull/506
* @tpurcell90 made their first contribution in https://github.com/materialsproject/atomate2/pull/568
* @esoteric-ephemera made their first contribution in https://github.com/materialsproject/atomate2/pull/561
* @ab5424 made their first contribution in https://github.com/materialsproject/atomate2/pull/578

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.11...v0.0.12

## v0.0.11

### Task Document Changes

Merge atomate2 VASP task document with the one in emmet. The changes to the atomate2
schemas are:

* `PsuedoPotentialSummary` -> `Potcar`
  * `labels` -> `symbols`
* `AnalysisSymmary` -> `AnalysisDoc`
  * `delta_volume_as_percent` -> `delta_volume_percent`
* `InputSummary` -> `InputDoc`
* `OutputSummary` -> `OutputDoc`
  * `density` added
* `Status` -> `TaskState`
* `TaskDocument` -> `TaskDoc`
  * `task_type added`
* `Status` -> `TaskState`

### VASP input set updates

The VASP input sets have been reconfigured based on user feedback.
The `auto_kspacing` option has been removed and KSPACING is no longer used in the
atomate2 input sets by default. We have returned to using `reciprocal_density` as in
atomate1. These changes mean the k-point mesh is no longer dependent on the precise
band gap of the system. Instead, there are now two k-points settings, one for insulators
and one for metals. This should remove issues when changing the functional from
PBEsol -> HSE, in which the band gap increases but the k-point mesh would be expected
to stay the same.

Two new options have been added to the `BaseVaspInputSetGenerator`:

* `auto_metal_kpoints`: If true and the system is metallic, try and use `
reciprocal_density_metal` instead of `reciprocal_density` for metallic systems.
* `auto_ismear`: If true, the values for ISMEAR and SIGMA will be set automatically
  depending on the bandgap of the system. If the bandgap is not known (e.g., there is no
  previous VASP directory) then ISMEAR=0 and SIGMA=0.2; if the bandgap is zero (a
  metallic system) then ISMEAR=2 and SIGMA=0.2; if the system is an insulator, then
  ISMEAR=-5 (tetrahedron smearing).

### New Features 🎉

* CP2K Support by @nwinner in https://github.com/materialsproject/atomate2/pull/157
* Add forcefield schemas/makers to atomate2 by @matthewkuner in https://github.com/materialsproject/atomate2/pull/322
* Add `m3gnet` support to Atomate2 by @matthewkuner in https://github.com/materialsproject/atomate2/pull/380
* Phonons for forcefields by @JaGeo in https://github.com/materialsproject/atomate2/pull/398

### Bug Fixes 🐛

* Fix Lobster Schema by @JaGeo in https://github.com/materialsproject/atomate2/pull/266
* fix lso dos of lobster being not saved in schema by @naik-aakash in https://github.com/materialsproject/atomate2/pull/279
* fix `_get_strong_bonds` function by @naik-aakash in https://github.com/materialsproject/atomate2/pull/289
* [Bug Fix] For stringing defect calculations together by @jmmshn in https://github.com/materialsproject/atomate2/pull/292
* BUGFIX `auto_lreal` by @jmmshn in https://github.com/materialsproject/atomate2/pull/297
* Fix `Yb` PSP: change `Yb_2` to `Yb_3` by @janosh in https://github.com/materialsproject/atomate2/pull/319
* Fix typo by @janosh in https://github.com/materialsproject/atomate2/pull/321
* Fix overriding `magmoms` in `update_user_incar_settings(` by @janosh in https://github.com/materialsproject/atomate2/pull/375
* Fix encoding of input `Molecule` coordinates in cclib `TaskDocument` by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/411
* [FIX] fix elastic tensor flow by @mjwen in https://github.com/materialsproject/atomate2/pull/415
* [BUG FIX] Edge case for Magmoms by @jmmshn in https://github.com/materialsproject/atomate2/pull/460
* [FIX] Fix major bug that caused `user_incar_settings` to be overwritten in some cases by @matthewkuner in https://github.com/materialsproject/atomate2/pull/412
* Test for `zip_outputs` by @gpetretto in https://github.com/materialsproject/atomate2/pull/503

### Enhancements 🛠

* Extension of Lobster schema and additional tests by @JaGeo in https://github.com/materialsproject/atomate2/pull/272
* Use emmet VASP task document by @utf in https://github.com/materialsproject/atomate2/pull/269
* VASP inputset updates by @utf in https://github.com/materialsproject/atomate2/pull/270
* Linting by @utf in https://github.com/materialsproject/atomate2/pull/274
* Improve Lobster workflow preconverge step, kpoints, docs by @JaGeo in https://github.com/materialsproject/atomate2/pull/277
* add `has_doscar_lso` field to Lobsterout schema model and update lobsterpy version by @naik-aakash in https://github.com/materialsproject/atomate2/pull/286
* added simple chg check by @jmmshn in https://github.com/materialsproject/atomate2/pull/320
* Switch to emmet's `MoleculeMetadata` by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/301
* Update update-precommit.yml by @utf in https://github.com/materialsproject/atomate2/pull/330
* Update dependencies by @utf in https://github.com/materialsproject/atomate2/pull/329
* Add missing molecule field to cclib TaskDocument by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/353
* allow elastically unstable structures by @matthewkuner in https://github.com/materialsproject/atomate2/pull/355
* update lobstertask schema: add bandoverlaps,grosspop and sitepotentials fields by @naik-aakash in https://github.com/materialsproject/atomate2/pull/404
* Update CondensedBondingAnalysis schema by @naik-aakash in https://github.com/materialsproject/atomate2/pull/469
* Phonon tweaks by @utf in https://github.com/materialsproject/atomate2/pull/276
* Update to Defects WF by @jmmshn in https://github.com/materialsproject/atomate2/pull/430
* Small change to `gunzip` to allow better restarting by @jmmshn in https://github.com/materialsproject/atomate2/pull/476
* Remove VASP calc types schema by @mjwen in https://github.com/materialsproject/atomate2/pull/407
* Optionally zip files at the end of jobs by @gpetretto in https://github.com/materialsproject/atomate2/pull/414

### Documentation 📖

* Add more documentation for Lobster by @JaGeo in https://github.com/materialsproject/atomate2/pull/267
* Use furo for docs theme by @utf in https://github.com/materialsproject/atomate2/pull/331
* Update Lobster documentation by @JaGeo in https://github.com/materialsproject/atomate2/pull/376
* Fix docs typos by @janosh in https://github.com/materialsproject/atomate2/pull/373
* Update FireWorks section of docs by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/378
* Add a copy button to code blocks by @Andrew-S-Rosen in https://github.com/materialsproject/atomate2/pull/382
* clean up doc, remove left-overs from amset example by @JaGeo in https://github.com/materialsproject/atomate2/pull/394
* More details for lobster documentation by @JaGeo in https://github.com/materialsproject/atomate2/pull/431
* Deploy docs on every commit to `main` by @janosh in https://github.com/materialsproject/atomate2/pull/422
* Add clearer documentation on lobster worker by @JaGeo in https://github.com/materialsproject/atomate2/pull/440
* Docs: add basic workflow tutorial by @rkingsbury in https://github.com/materialsproject/atomate2/pull/408
* Use GitHub's `deploy-pages` action to deploy docs by @janosh in https://github.com/materialsproject/atomate2/pull/475

### House-Keeping 🧹

* More `ruff` by @janosh in https://github.com/materialsproject/atomate2/pull/344
* Move all type-hint only imports behind `if TYPE_CHECKING` by @janosh in https://github.com/materialsproject/atomate2/pull/354
* `ruff` select `perflint` `flake8-slots` by @janosh in https://github.com/materialsproject/atomate2/pull/395
* Bump `ruff` and fix `PERF401`: Use a list comprehension to create transformed list by @janosh in https://github.com/materialsproject/atomate2/pull/421
* Simplify: `dict.get(key, None)` -> `dict.get(key)` by @janosh in https://github.com/materialsproject/atomate2/pull/429
* `dict.setdefault` instead of `if key not in dict: dict[key] = ...` by @janosh in https://github.com/materialsproject/atomate2/pull/452

### New Contributors

* @naik-aakash made their first contribution in https://github.com/materialsproject/atomate2/pull/279
* @matthewkuner made their first contribution in https://github.com/materialsproject/atomate2/pull/322
* @gpetretto made their first contribution in https://github.com/materialsproject/atomate2/pull/414

**Full Changelog**: https://github.com/materialsproject/atomate2/compare/v0.0.10...v0.0.11)

## v0.0.10

Lobster workflow with VASP implementation ([@JaGeo][jageo], [@naik-aakash][naik-aakash] [#200](https://github.com/materialsproject/atomate2/pull/200))

## v0.0.9

New features:

* Defect formation energy workflow with VASP implementation ([@jmmshn][jmmshn], [#215](https://github.com/materialsproject/atomate2/pull/215))
* Job to retrieve a structure from the MP API at run-time ([@mkhorton][mkhorton], [#176](https://github.com/materialsproject/atomate2/pull/176]))

Enhancements:

* Documentation of phonon workflow ([@QuantumChemist][quantumchemist], [#232](https://github.com/materialsproject/atomate2/pull/232))
* Refactor defect code ([@jmmshn][jmmshn], [#214](https://github.com/materialsproject/atomate2/pull/214))
* Use `ruff` for linting ([@janosh][janosh], [#250](https://github.com/materialsproject/atomate2/pull/250))

Bug fixes:

* Use correct k-point density in phonon workflow ([@JaGeo][jageo], [#177](https://github.com/materialsproject/atomate2/pull/177))
* Fix use of `expanduser` path ([@nwinner][nwinner], [#180](https://github.com/materialsproject/atomate2/pull/180))
* Correct `calcs_reversed` to be in the proper order ([@Zhuoying][zhuoying], [#182](https://github.com/materialsproject/atomate2/pull/182))
* Bugfix for `store_volumetric_data` ([@jmmshn][jmmshn], [#212](https://github.com/materialsproject/atomate2/pull/212))

## v0.0.8

New features:

* VASP Phonopy workflow ([@JaGeo][jageo], [#137](https://github.com/materialsproject/atomate2/pull/137))
* Molecular dynamics VASP job ([@mjwen][mjwen], [#134](https://github.com/materialsproject/atomate2/pull/134))

Enhancements:

* Update IO classes to use pymatgen base classes ([@rkingsbury][rkingsbury], [#141](https://github.com/materialsproject/atomate2/pull/141))
* Read and write VASP structures with higher precision ([@JaGeo][jageo], [#167](https://github.com/materialsproject/atomate2/pull/167))

Bug fixes:

* Fix code examples in docs ([@JaGeo][jageo], [#169](https://github.com/materialsproject/atomate2/pull/169))
* Fix f-orbital DOS properties ([@Andrew-S-Rosen][arosen], [#138](https://github.com/materialsproject/atomate2/pull/138))
* Fix `mock_run_vasp` testing to accept args ([@mjwen][mjwen], [#151](https://github.com/materialsproject/atomate2/pull/151))
* Regenerate calc_types enum ([@mjwen][mjwen], [#153](https://github.com/materialsproject/atomate2/pull/153))

## v0.0.7

New features:

* Include band-related features (e.g. band center, bandwidth, skewness, kurtosis) in
  VASP schema ([@Andrew-S-Rosen][arosen], [#92](https://github.com/materialsproject/atomate2/pull/92))
* Add `use_auto_ispin` and `update_user_potcar_functional` powerups

Enhancements:

* Add `is_hubbard` and `hubbards` to VASP task doc.
* Migrate build system to pyproject.toml.
* Migrate docs to jupyter-book.
* Docs improvements ([@janosh][janosh], [@mjwen][mjwen])

Bug fixes:

* Fix HSE tags.
* Fix running bader.
* Make potcar_spec argument usable ([@jmmshn][jmmshn], [#83](https://github.com/materialsproject/atomate2/pull/83))
* Replace monty which with shutil which ([@Andrew-S-Rosen][arosen], [#92](https://github.com/materialsproject/atomate2/pull/92))
* Fix `calculate_deformation_potentials()` ([@janosh][janosh], [#94](https://github.com/materialsproject/atomate2/pull/94))
* Fix gzipping of files with numerical suffixes ([@jmmshn][jmmshn], [#116](https://github.com/materialsproject/atomate2/pull/116))

## v0.0.6

New features:

* cclib task document supporting virtually all popular molecular DFT codes out-of-the-box
  ([@Andrew-S-Rosen][arosen], [#64](https://github.com/materialsproject/atomate2/pull/64))

Enhancements:

* Add mag_density to VASP output doc ([@Andrew-S-Rosen][arosen], [#65](https://github.com/materialsproject/atomate2/pull/66))
* Double relax maker now supports two different Makers ([@Andrew-S-Rosen][arosen], [#32](https://github.com/materialsproject/atomate2/pull/32))

Bug fixes:

* Store band structure efermi in CalculationOutput ([@Andrew-S-Rosen][arosen], [#66](https://github.com/materialsproject/atomate2/pull/66))
* Support for VASP6 and latest pymatgen ([@Andrew-S-Rosen][arosen], [#75](https://github.com/materialsproject/atomate2/pull/75))
* Fixed atomate2 version string.
* Disabled orbital projections in the electron-phonon workflow.

## v0.0.5

This version removed Python 3.7 support following numpy and pymatgen.

New features:

* Base schema for molecule task documents ([@Andrew-S-Rosen][arosen], [#54](https://github.com/materialsproject/atomate2/pull/54))

Bug fixes:

* Fix VASP relaxation using custodian "FULL_OPT" ([@Andrew-S-Rosen][arosen], [#42](https://github.com/materialsproject/atomate2/pull/42))
* Fix supercell generation and input sets in electron-phonon workflow.
* Fix `HSEBSSetGenerator` INCAR settings.
* Fix issue with magnetism in SOC structures.
* Fix bug with Fermi level and IBRION=1
* Better handling of URI generation.
* Tweak k-spacing formula to stop large band gaps giving negative values

## v0.0.4

Lots of improvements and bug fixes this release.

New features:

* AMSET workflow.
* Electron phonon band gap renormalisation workflow.
* Specific uniform and line mode band structure makers.
* Optics maker.
* Transmuter maker.

Enhancements:

* Support for automatic handling of ISPIN.
* Add MP base sets ([@Andrew-S-Rosen][arosen], [#27](https://github.com/materialsproject/atomate2/pull/27))
* Docs updates ([@Andrew-S-Rosen][arosen], [#13](https://github.com/materialsproject/atomate2/pull/13) [#17](https://github.com/materialsproject/atomate2/pull/17))
* Options to strip band structure and DOS projects to reduce object sizes.
* Input sets now use generators to avoid serialization issues.
* Use smart efermi finding to remove errors with tetrahedron integration in VASP 6.
* Powerups can now work on `Maker` objects directly.

Bug fixes:

* Use PBEsol by default.
* Increase number of significant figures when writing POSCAR files.
* Remove unused INCAR settings ([@Andrew-S-Rosen][arosen])
* Add missing LASPH flags on vdW functionals ([@Andrew-S-Rosen][arosen], [#31](https://github.com/materialsproject/atomate2/pull/31))
* Use `NSW=0` in static calculations ([@Andrew-S-Rosen][arosen], [#10](https://github.com/materialsproject/atomate2/pull/10))
* `LREAL = False` in static jobs by default ([@Andrew-S-Rosen][arosen], [#23](https://github.com/materialsproject/atomate2/pull/23))
* Add missing functionals in output schema ([@Andrew-S-Rosen][arosen], [#12](https://github.com/materialsproject/atomate2/pull/12))
* Many output schema fixes.
* Better support for FireWorks.
* Support writing additional files in VASP jobs.

## v0.0.3

Many updates to use the latest jobflow store features.

## v0.0.2

Automated releases.

## v0.0.1

Initial release.

[contributors]: <> (CONTRIBUTOR SECTION)
[nwinner]: https://github.com/nwinner
[jageo]: https://github.com/JaGeo
[zhuoying]: https://github.com/Zhuoying
[jmmshn]: https://github.com/jmmshn
[mkhorton]: https://github.com/mkhorton
[QuantumChemist]: https://github.com/QuantumChemist
[janosh]: https://github.com/janosh
[mjwen]: https://github.com/mjwen
[arosen]: https://github.com/Andrew-S-Rosen
[rkingsbury]: https://github.com/rkingsbury
[naik-aakash]: https://github.com/naik-aakash
