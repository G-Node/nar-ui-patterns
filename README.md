# nar-ui-patterns

Neural activity experimental metadata UI pattern prototypes.

## Purpose

Designing a metadata entry user interface (UI) for complex 
experimental set up such as study of neuronal activity with 
multi modal methods under complex hierarchical experimental 
design is a challange. Here we are collecting a UI design
patterns addressing this challange with compact prototypes.

## UI Patterns

### Multi-select with conditional UI presentation

A use case appear if there are multi modalities in the experiment
and each modality has its own set of metadata. It is not practical
to show all metadata. For this reason, related metadata will be 
presented based on given selection.
See `src/sp5_metadata_hierarchical_entry.html`

### Experimental Design: Dynamic definitions

Dynamic definition of a set of metadata and another set that depends on 
the arbitrary combination of the previous. This allows experimenter
to define arbitrary number of metadata `key-value` pairs and able to
create new ones combining the previous definitions. 

See `src/sp5_metadata_dynamic_task_trial_design_sessions.html`

## Usage/Test

* Open `index.html` in any browser capable of running modern Javascript.
* For offline use JS/CSS files under `ext`. These should be pointed 
  instead of angularjs/bootsrap URLs.
* Prototypes are tested with angularjs/1.6.4 and bootstrap/3.1.1.

## Relevant Links
* [Network interactions in motor cortex in relation to behaviour](http://www.fz-juelich.de/inm/inm-6/EN/Forschung/Gruen/MotorBehavior.html?nn=724620)
* [Experimental Design](https://en.wikipedia.org/wiki/Design_of_experiments)
* [User Interface Design](https://en.wikipedia.org/wiki/User_interface_design)
* [AngularJS](https://angularjs.org/)
* [Bootstrap](http://getbootstrap.com/)
