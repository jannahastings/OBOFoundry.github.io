---
layout: ontology_detail
id: mondo
label: ECTO
title: Exposures Conditions and Treatments Ontology
description: Represents organismal exposure events
license:
  url: http://creativecommons.org/licenses/by/4.0/
  label: CC-BY
contact:
  email: vasilevs@ohsu.edu
  label: Nicole Vasilevsky
taxon:
  id: NCBITaxon:33208
  label: Metazoa
domain: environment
homepage: https://github.com/EnvironmentOntology/environmental-exposure-ontology/
tracker: https://github.com/EnvironmentOntology/environmental-exposure-ontology/issues
canonical: ecto.owl
products:
 - id: ecto.owl
   title: Main OWL edition
   description: Complete ontology
   format: owl-rdf/xml
   is_canonical: true
 - id: ecto.obo
   title: obo-format edition
   format: obo
   derived_from: ecto.owl
 - id: ecto.json
   title: json edition
   description: Equivalent to the OWL edition
   format: json
   derived_from: mondo.owl

---

The purpose of this ontology is to create compositional classes that
assemble existing OBO ontologies such as ExO, CHEBI and ENVO to make
ready-made precomposed classes for use in describing:

 * experimental treatments of plants and model organisms (e.g. modification of diet, lighting levels, temperature)
 * exposures of humans or any other organisms to stressors through a variety of routes, for purposes of public health, environmental monitoring etc
 * stimuli, natural and experimental
 * any kind of environmental condition or change in condition that can be experienced by an organism or population of organisms on earth

The scope is very general and can include for example plant treatment regimens, as well as human clinical exposures (although these may better be handled by a more specialized ontology)
