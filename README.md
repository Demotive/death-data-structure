# Death data structure

Exploratory data structure. Initially based on examination of the exemplar forms
in the [Death Certification Reforms consultation](https://www.gov.uk/government/consultations/death-certification-reforms).

## The death

The event. The wrapper for the other pieces.

* [The case](case.json)

## Participants

Who might be part of the establishment of a cause of death? Both in terms of a
defined role and being an information source?

* [The deceased](deceased.json)
* [Next of kin](next-of-kin.json)
* The deceased’s GP
* [The qualified attending practitioner (QAP)](attending-practitioner.json)
* [The medical examiner](medical-examiner.json)
* The medical examiner’s officer
* The coroner
* The coroner’s officer

## Cause of death

What is the cause of death? Increments of how the agreed cause was arrived at.
(Structure currently directly lifted from forms, needs interrogation)

* [Cause of death](cause.json)
* [Cause of death (neonatal)](cause-neonatal.json)

## Establishment of cause timeline

(May be part of cause of death data?) Who communicated to who, what did they
decide, when did they decide it, etc?
