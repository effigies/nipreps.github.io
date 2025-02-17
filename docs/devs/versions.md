
The versions matrix is intended to allow easy reference for the dependencies within the *NiPreps* family of projects.

## *fMRIPrep*

| *fMRIPrep* series | *sMRIPrep* series | *SDCflows* series | *NiWorkflows* series |
|----|----|----|----|
| 20.2.x | `~= 0.7.0` | `~= 1.3.1` | `~= 1.3.0` |
| 20.1.x | `~= 0.6.1` | `~= 1.3.1` | `~= 1.2.3` |
| 20.0.x | `~= 0.5.2` | `~= 1.2.0` | `~= 1.1.7` |
| 1.5.3+ | `~= 0.4.0` | `~= 1.0.1` | `~= 1.0.2` |

(Originally posted at [poldracklab/fmriprep#2054](https://github.com/poldracklab/fmriprep/issues/2054))

## *dMRIPrep*

(Work in progress)

## *sMRIPrep*

sMRIPrep requires niworkflows and generally must depend on one minor series of niworkflows for the duration of an sMRIPrep minor series. Each sMRIPrep series may also be depended on for an fMRIPrep series and/or a dMRIPrep series. Noting these dependencies here should make it easier to track when a new minor series needs to be created.

| *sMRIPrep* series | *NiWorkflows* series | *TemplateFlow* series |
|----|----|----|
| 0.7.x | `~= 1.3.0` | `~= 0.6` |
| 0.6.x | `~= 1.2.0` | `~= 0.6` |
| 0.5.x | `~= 1.1.5` | `~= 0.4.2` |

(Originally posted at [poldracklab/smriprep#172](https://github.com/poldracklab/smriprep/issues/172))


## *MRIQC*

(Work in progress)
