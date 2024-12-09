!["aequos"](./assets/aequos_logo_noir.png){: .center .logo}

# aequos Modern Data Visualizer solution

!["Current version"](https://img.shields.io/github/v/release/aequos-solutions/modern-data-visualizer?include_prereleases)

The 'Modern Data Visualizer' solution is a set of SharePoint Online modern Web Parts allowing SharePoint super users, webmasters and developers to create highly flexible and personalized data viewing and filtering experiences in minutes.

It is the enhanced product version of the well known ["Pattern & Practices Modern Search"](https://github.com/microsoft-search/pnp-modern-search) open-source solution **that we also created**.

!!! info
    Want to know what are the differences between the commercial and open source solutions to help you decide which one is the right for you? Take a look at our detailled [features comparison table](./features/).

    Don't be wrong: **we still continue to invest time and support for the open-source solution**. If it suits your current requirements, feel free to go with it. We will never push someone to purchase the licensed solution.

## What's included?

The solution includes the following Web Parts:

| Component | Description |
| --------- | ----------- |
| **[Data Visualizer](./usage/data-visualizer/index.md)** | Retrieve data from a data source and render them in a specific layout.
| **[Data Filters](./usage/data-filters/index.md)** | Filter and refine data displayed in 'Data Visualizer' Web Parts.
| **[Data Verticals](./usage/data-verticals/index.md)** | Browse data as silos (i.e. tabs) from multiple data sources.
| **[Search box](./usage/search-box/index.md)** | Let users enter free text queries sent to 'Data Visualizer' Web Parts.
| **[Group Metadata Editor](./usage/group-metadata-editor/index.md)** | Allows owners to classify their team/ Microsoft 365 group based on Microsoft Graph schema extensions.

**Overview video: let's build a complete search center**

Here is a overview video on how to build a complete search center in minutes using all available Web Parts whithin a SharePoint page including multiple data sources.

<iframe width="560" height="315" src="https://www.youtube.com/embed/EECqOBWq3wo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Supported browsers

Here is the list of supported browsers:

- Chrome
- Firefox
- Edge
- Edge Chromium
- Brave
- Safari

**We don't support Internet Explorer 11**. We think there are plenty of other options for enteprise scenarios in the market. Maybe it's time to move on. For developers, it represents an **huge** ammount of time to make the solution compatible for a very low benefit. Hope you understand, ain't personal ;).

## Extensibility model

By getting this solution, you also benefit from an advanced [extensibility model](./extensibility/index.md) allowing you to customize the solution according to your requirements if default features don't do the job for you. 

**The supported extensions are:**

- [Custom data sources](./extensibility/custom_data_source.md).
- [Custom layouts](./extensibility/custom_layout.md).
- [Custom web components](./extensibility/custom_web_component.md).
- [Custom suggestions providers](./extensibility/custom_suggestions_provider.md).
- [Custom Handlebars customization (helpers, partials, etc.)](./extensibility/handlebars_customizations.md).

With these available customizations options, you can do pretty much anything!

## Import Export Feature

For all webparts, the information section has "Import/Export" feature. It allows the user to download the webpart properties, edit the same and upload them as well.

!["Import Export Section"](./assets/importExport.png) 

## Troubleshooting

To help us to resolve your issue, you can include screenshots or error messages coming from:

- The faulty Web Part itself. 
- Errors displayed in the browser console (typically pressing F12).
- Errors displayed in the SharePoint console (pressing CTRL+F12)

## Issues, questions, feedback?

For any issue, question or feedback, please the [official GitHub repository](https://github.com/aequos-solutions/modern-data-visualizer/issues). We will be happy to help you!