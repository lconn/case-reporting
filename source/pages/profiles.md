---
title: Profiles defined as part of this Guide
layout: default
active: profiles
---

source file: source/pages/_include/{{page.md_filename}}.md  file

<!-- { :.no_toc } -->

<!-- TOC  the css styling for this is \pages\assets\css\project.css under 'markdown-toc'-->

<!-- * Do not remove this line (it will not be displayed)
{:toc} -->


<!-- end TOC -->


### Trigger Code Transaction

This implementation guide does not provide profiles for the ValueSet resource at this time. Rather, this guide provides instances of ValueSet resources that match the content of the RCTC spreadsheets available from [PHIN VADS](https://phinvads.cdc.gov/vads/SearchVocab.action). Future versions of this specification will provide ValueSet resource profiles so that PHAs may provide their own trigger code sets.

<!--
The following Logical Models have been defined for this implementation guide.

{ % include list-simple-logicals.xhtml % }
-->

---
<br />

### eICR Transaction

The following profiles and extensions have been defined for the eICR transactions

#### Profiles

<ul>
<li><a href="StructureDefinition-eicr-composition.html">eICR Composition Profile</a></li>
<li><a href="StructureDefinition-ecr-organization.html">eCR Organization Profile</a></li>
<li><a href="StructureDefinition-eicr-condition.html">eICR Condition Profile</a></li>
<li><a href="StructureDefinition-eicr-encounter.html">eICR Encounter Profile</a></li>
<li><a href="StructureDefinition-eicr-procedurerequest.html">eICR Lab Orders Profile</a></li>
<li><a href="StructureDefinition-eicr-location.html">eICR Location Profile</a></li>
<li><a href="StructureDefinition-eicr-pregnancystatus.html">eICR PregnancyStatus Profile</a></li>
<li><a href="StructureDefinition-eicr-travelhistory.html">eICR TravelHistory Profile</a></li>
<li><a href="StructureDefinition-eicr-occupationhistory.html">eICR-OccupationHistory Profile</a></li>
</ul>

#### Extensions

<ul>
<li><a href="StructureDefinition-extension-trigger.html">Trigger Code Flag</a></li>
<li><a href="StructureDefinition-extension-valueAddress.html">Travel history address</a></li>
</ul>

<!--
The following Logical Models have been defined for this implementation guide.

{ % include list-simple-logicals.xhtml % }
-->

---
<br />

### Reportability Response Transaction

The following profiles and extensions have been defined for the Reportability Response transactions.

#### Profiles

<ul>
<li><a href="StructureDefinition-rr-communication.html">Reportability Response Communication Profile</a></li>
<li><a href="StructureDefinition-rr-plandefinition.html">Reportability Response PlanDefinition Profile</a></li>
<li><a href="StructureDefinition-ecr-organization.html">eCR Organization Profile</a></li>
<li><a href="StructureDefinition-eicr-encounter.html">eICR Encounter Profile</a></li>
<li><a href="StructureDefinition-eicr-operationoutcome.html">eICR Operation Outcome Profile</a></li>
</ul>

#### Extensions

<ul>
<li><a href="StructureDefinition-extension-practitioner-role.html">PractitionerRole reference</a></li>
<li><a href="StructureDefinition-extension-location-relevance.html">Location Relevance</a></li>
<li><a href="StructureDefinition-extension-manual-init.html">Initial Case Report Manual Initiation Flag</a></li>
<li><a href="StructureDefinition-extension-manual-init-reason.html">Initial Case Report Manual Initiation Reason</a></li>
<li><a href="StructureDefinition-extension-status-reason.html">eICR processing status reason</a></li>
<li><a href="StructureDefinition-extension-topic-subject.html">Topic subject Line</a></li>
<li><a href="StructureDefinition-extension-topic-summary.html">Topic Summary</a></li>
<li><a href="StructureDefinition-extension-topic-dor.html">Determination of Reportability</a></li>
<li><a href="StructureDefinition-extension-topic-dor-reason.html">Determination of Reportability Reason</a></li>
<li><a href="StructureDefinition-extension-topic-dor-rule.html">Determination of Reportability Rule</a></li>
<li><a href="StructureDefinition-extension-publisher-reference.html">Publisher reference</a></li>
<li><a href="StructureDefinition-extension-rel-artifact-category.html">External Resource Category</a></li>
<li><a href="StructureDefinition-extension-rel-artifact-priority.html">External Resource Priority</a></li>
</ul>

<!--
The following Logical Models have been defined for this implementation guide.

{ % include list-simple-logicals.xhtml % }
-->

---
