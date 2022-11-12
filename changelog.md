# Changelog  
  
| modName    | OScience Laboratories (OSL)                                        |
| ---------- | ----------------------------------------------------------------- |
| license    | GPL-2.0                                                           |
| author     | pizzaguy and zer0Kerbal                                           |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209490-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/OScienceLaboratories)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/OScienceLaboratories) |
| spacedock  | (https://spacedock.info/mod/161)                                  |
| ckan       | OScienceLaboratories                                              |

## Version 0.9.99.0-adoption - `<Thank you pizzaguy>`

* Released
  * 10 Nov 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 0.9.99.0

* Adopted by zer0Kerbal
* lint, update, and localize
* new agency, flag, and more

### Adoption by zer0Kerbal

### Config

* Create
  * [ghostparts.cfg]
  * this patch which will go away

### Create Agency

* Create
  * Agency/Agents.cfg
  * create _scaled.truecolor (64x40)_
  * create flag (512x320)

### Parts 0.9.99.0

* Lint and update
* Rename
  * file name
    * xxx --> osl-xxx
  * part name
    * xxx --> osl-xxx

### Asset Updates 0.9.99.0

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
    * AtmoScoop.mbm --> .png
    * Detector.mbm --> .png
    * radioDecayBase.mbm --> .png
    * 12mb --> 1.95mb
  * duplicate models
* relocate part.cfg to Parts/
* closes #9 - Part Asset Updates

### docs/ 0.9.99.0

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [PartsCatalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* Create
  * @thumbs/
  * add thumbnails
  * Hero.png
* Update .version file
  * remove [KSP_VERSION_MAX]
* closes #5 - Create GitHub Pages
* closes #6 - Create HeroLogo.png

### Localization 0.9.99.0

* Create
  * Localization/
    * <en-us.cfg> v1.1.0.0
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Add
  * [OScienceLaboratories.cfg] v1.0.0.0
    * adds localized tags to parts
* <ScienceDefs.cfg> v1.1.0.0
  * Localized Science Experiments (5)
* closes #8 - Create Localization directory and contents
* closes #10 - Create OScienceLaboratories.cfg
* updates #12 - Localization - Master
* closes #13 - English <us-en.cfg>
* closes #30 - Part Localization
* closes #46 - Localize Science Experiments

### Update License 0.9.99.0

* Update License: GPL-2.0
  * was: Expat-MIT
* closes #11 - Update License

### Status 0.9.99.0

* Issues
  * closes #1 - OScienceLaboratories 0.9.99.0-adoption (OSL) `<Thank you pizzaguy>` edition
  * closes #2 - 0.9.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 0.9.99.0 Create Documentation
  * closes #4 - 0.9.99.0 Create Social Media Presence

---

## Version 0.0.7.0-release - `<Archival>`

* 28 Feb 2016
* Released for Kerbal Space Program 1.0.5

This is the offical changelog for the Kerbal Space Program mod OScience Laboratories created by Pizzaguy499.

* More science logs
* New atmo scoop model and texture
* Added laser flag
* Removed science lab
* Fixed not being able to do science experiments from other mods
* Tweaked science outputs
* Rescaled sonic emitter and atmo scoop

### Status 0.0.7.0

* Issues
  * updates #7 - Archival Releases
  * closes #36 - 0.0.7.0-release

---

## Version 0.0.6.0-release - `<Archival>`

* 28 Feb 2016
* Released for Kerbal Space Program 1.0.5

* More science logs
* New atmo scoop model and texture
* Added laser flag
* Removed science lab
* Fixed not being able to do science experiments from other mods
* Tweaked science outputs
* Rescaled sonic emitter and atmo scoop

### Status 0.0.6.0

* Issues
  * updates #7 - Archival Releases
  * closes #35 - 0.0.6.0-release

---

## Version 0.0.5.0-release - `<Archival>`

* 12 Feb 2016
* Released for Kerbal Space Program 1.0.5

* Added new science logs
* Add alpha magnetic spectrometer
* Add new pee experiment model
* Fix no ladder/crew hatch on science lab
* Sciencelab not attaching by the nodes
* Improved some textures

### Status 0.0.5.0

* Issues
  * updates #7 - Archival Releases
  * closes #34 - 0.0.5.0-release

---

## Version 0.0.4.0-release - `<Archival>`

* 12 Feb 2016
* Released for Kerbal Space Program 1.0.5

* More science logs
* Added Pee Experiment
* Added science logs for electrostatic analzyer
* Improved science lab
* Improved pee container

### Status 0.0.4.0

* Issues
  * updates #7 - Archival Releases
  * closes #33 - 0.0.4.0-release

---

## Version 0.0.3.5-release - `<Archival>`

* 07 Feb 2016
* Released for Kerbal Space Program 1.0.5

* Fixed electrostatic analzyer not working
* Fixed sizes of parts
* Fixed science lab not attaching
* Fixed atmo scoop having no texture

### Status 0.0.3.5

* Issues
  * updates #7 - Archival Releases
  * closes #32 - 0.0.3.5-release

---

## Version 0.0.3.0-release - `<Archival>`

* 07 Feb 2016
* Released for Kerbal Space Program 1.0.5

* Added science lab
* Added pee container for future experiments
* Fixed sonic emitter
* Added new science logs

### Status 0.0.3.0

* Issues

  * updates #7 - Archival Releases
  * closes #31 - 0.0.3.0-release

---

Version 0.0.1.0-release - `<Archival>`

* 12 Feb 2016
* Released for Kerbal Space Program 1.0.5

* Added sonic emitter
* Added radial scoop

---
