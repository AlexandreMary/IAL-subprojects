Subprojects in the IFS-Arpege-LAM code repository, as of pre-CY49
=================================================================

| Project | Contents | Legitimate place |
|:-----------------|:-----------------|:----------------------|
| aeolus | aeolus observations pre-processing | Y |
| aladin | LAM counterparts routines to arpifs | Y |
| algor | linear algebra (minimizers, etc...) | Y |
| arpifs | models core: dyn, phy, control, algo, obs op, ... | Y |
| atlas\_apps | ESCAPE dwarfs reintegrated into IFS | ? |
| bin | ? | N |
| biper | LAM biperiodicization: mathematical routines | Y |
| blacklist | observations blacklisting (pre-processed) | Y |
| bufr2odb |  |  |
| climfield | IFS surface generation | Y |
| cmake | definition/configuration files for compilation with cmake | Y |
| contrib | (fiat/ectrans, temporarily) | Y |
| coupling | LAM coupling/relaxation | Y |
| doc | auxiliary files for automatic doc generation ? | Y |
| dummy | dummies for IFS (aladin, etc...) |  |
| enkf | IFS ENKF |  |
| etrans | LAM spectral transforms | (should join ectrans soon) |
| glomap | ? | ? |
| ifsaux | auxiliary libs used by arpifs and other sub-projects (file formats, ...). | Y |
| ifsobs | abstraction layer between IFS and ODB |  |
| mpa | Meso-NH/AROME physics | externalisation planned in 49T1, only interfaces may remain |
| mse | interface to SURFEX | Y |
| nemo | IFS ocean model : Managed externally, to be taken out ? | N |
| obstat | diagnostics about observations assimilation | Y |
| odb | ODB format (+ tools) | Y |
| oopsifs | interface to OOPS objects | Y |
| prepdata | observations pre-processing |  |
| radiation | radiation scheme (ecrad ?) |  |
| satrad | satellite retrievals (incl. RTTOV) | Y |
| scat | scatterometers processing ? |  |
| scmec | single column model |  |
| ssa | surface fields analysis |  |
| surf | IFS surface scheme | Y |
| surfex | copy of SURFEX | externalisation planned for CY50 ? |
| trans | leftovers of spectral transforms | N |
| utilities | external programs using ifsaux, should not use arpifs (but does) | ? |
| wam | IFS wave model: managed externally ? | N |
