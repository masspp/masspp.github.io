# Mass++: An Open Source MS Data Viewer

This page provides …

## About Mass++

We have been developing a fast spectrum viewer, Mass++, which has been downloaded about 20000 times to date in total of all releases. The version currently under development is Ver.4, which is open-source software, newly rewritten in the Java language to be compatible with multiple operating systems. This time, we have organized the various functions that have been developed to date and generated a package as the official release of Ver. 4 (Ver.4 Gold), focusing on basic functions, especially those related to the display of spectra and chromatograms, such as zooming of spectra/chromatograms, labeling of peaks, exporting of spectra/chromatograms to image files, and functions to narrow down spectra by m/z values and retention time values. This Ver.4 Gold package will be released in four operating system environments: Windows, MacOS, Linux Debian/Ubuntu, Linux RPM.

Note that 'Mass++ Ver.4 Gold' has been renamed to 'Mass++4 Ver.1.0.0' upon release for future version management and to distinguish it from the Ver.2.7 series. We will primarily use this name going forward.

## Binary (installer) package downloads

### Current (Latest) version

* Mass++4 ver.1.0.0 (a.k.a. Mass++ ver.4 Gold (stable) version)

### Previous versions

* Mass++4 ver.0.2.1 (a.k.a. Mass++ ver.4 beta2)
* Mass++4 ver.0.2.0 (a.k.a. Mass++ ver.4 beta) 
* Mass++4 ver.0.1.0 (a.k.a. Mass++ ver.4 alpha)  
* Mass++ ver.2.7.5

## Release notes

* 2025/xx/xx: Mass++4 ver.1.0.0 (Mass++ ver.4.0 Gold) release  
  * Updated whole system to apply new concept  
  * Re-implemented basic functions  
* 2021/12/04: Mass++4 ver.0.2.1 (Mass++ ver.4.0 beta2) release  
  * [Bug-fixed](https://mspp.ninja/2021/12/installers-of-mass-ver-4-beta-2-are-released/) for beta version  
    * To display precursor ion in MS/MS spectra properly  
    * To execute peptide identification process from Project tab properly  
    * To generate peak list of peptide identification properly for macOS/Linux  
* 2020/06/08: Mass++4 ver.0.2.0 (Mass++ ver.4.0 beta) release  
  * Added [some features from alpha version](https://mspp.ninja/2020/11/feature-comparison-of-ver-4-alpha-and-ver-4-beta/)  
    * Run external applications / Data exchange  
    * Data annotation view  
    * Peak picking  
      * Using ProteoWizard ver. 3.0.20123 (only for Windows)  
    * Search engine for peptide annotations  
      * Using Comet ver. 2019.01 rev. 5 (only for Windows)  
    * File support  
      * mzML, MGF, pepXML (manual)  
* 2019/09/17: Mass++4 ver.1.0.0 (Mass++ ver.4.0 alpha) release  
  * Released new version for multi platform  
  * Implemented basic functions  
    * Spectrum/Chromatograms view  
      * TIC, XIC, MS1, MS/MS  
      * Mirror view  
      * Overwrap  
    * Heatmap  
      * 2D, 3D  
    * Data annotation view (manual)  
    * File support  
      * mzML, MGF, pepXML (manual)  
    * OS support  
      * Windows, macOS

## Source code repositories

* current version  
  * Mass++4 ver.1.0.0 (a.k.a. ver. 4.0 Gold (stable))  
    * [mspp4-core](https://github.com/masspp/mspp4-core)  
    * [mspp4-desktop](https://github.com/masspp/mspp4-desktop)
    * [api-sample](https://github.com/masspp/api-sample) (Sample codes for data processing API)

* previous versions  
  * [\~Mass++4 ver.0.2.1 (ver.4.0 beta2)](https://github.com/masspp/mspp4)  
  * [Mass++ ver.2.7.5](https://github.com/masspp/mspp2.7.5)  

## About us

See the pages of Mass++ Users Group ([https://mspp.ninja/?lang=en_us](https://mspp.ninja/?lang=en_us))
