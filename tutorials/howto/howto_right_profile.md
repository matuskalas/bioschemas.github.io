---
layout: default
title: How to select the right profile for your resource
---

# How to select the right profile for your resource

>In this how-to, we will guide you through the necessary steps for you to select a Bioschemas profile that will be later used to mark up to your own resources.

***
&#9664; Previous tutorial: [What and why bioschemas](../what_why_bioschemas) | Next tutorial: [How to add markup to your own resource](./howto_add_markup) &#9654; 

***

## Your first encounter with Bioschemas profiles

You can find the availabe Bioschemas profiles at http://bioschemas.org/specifications. There, you will be presented with a list of all the current and stable profiles. You can hover on the profile name to see a quick description. Should you need a more detailed information, just click on the profile name.

As seen on Figure 1,  each profile will show you details such as current version, release date, use cases, crosswalk, tasks and issues, usage examples and live deploys. 

| ![Figure 1. List of some Bioschemas profiles](../images/specifications.png) |
| __Figure 1. List of some Bioschemas profiles__ |

<table>
  <tbody>
    <tr>
      <td align="center">
        <img src="../images/information_mark.png" alt="info">
      </td>
      <td>
      <ul>
        <li>Use cases: Used as a basis for the profile</li>
        <li>Crosswalk: Documentation on the brainstorming and process followed by a group in order to come up with a profile specification</li>
        <li>Tasks & issues: Link to a GitHub space where you can report issues with a profile, see the assignees, and participate of the discussion</li>
        <li>Example: Usage examples for the profile</li>
        <li>Live deploy: Link to live deploy for the profile</li>
      </ul>
      </td>
    </tr>
  </tbody>
</table>

Which profile is the right one for you will depend on your resource. In the next section, we will present some hints on those profiles that have been, so far, more broadly used, i.e., mainly customizing generic types rather corresponding to specific Life Science entities.

## A guided tour to some selected Bioschemas profiles

### DataCatalog

Also knows as data repository, a data catalog commonly aggregates more than one dataset. If your resources supports only one dataset, you still could decide to markup your resource, in this case, as [DataCatalog](/specifications/DataCatalog) and also [Dataset](/specifications/Dataset) (this would make it easier if you are thinking on adding more datasets. However, whenever more than one dataset is provided, it totally makes sense to have your resource as a [DataCatalog](/specifications/DataCatalog).

### Dataset

If your resource provides data and you can easily identify a common entity type for all the data contained in it, you should probably go for a [Dataset](/specifications/Dataset) profile. Let's clarify what we mean by "common type". Let's suppose you have chemical compounds including drugs, proteins and cells. If you see them all as the same thing, chemical compound, you have one [Dataset](/specifications/Dataset), and you have found the right profile for you. However, if you actually distinguish drugs from proteins from cells and so, and (maybe even) tailor the information provided for each case, you have a data catalog and multiple datasets, you should use both, one DataCatalog and multiple [Datasets](/specifications/Dataset).

***
&#9664; Previous tutorial: [What and why bioschemas](../what_why_bioschemas) | Next tutorial: [How to add markup to your own resource](./howto_add_markup) &#9654; 

***