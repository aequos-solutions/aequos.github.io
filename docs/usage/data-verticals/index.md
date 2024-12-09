# Data Verticals Web Part

The 'Data Verticals' Web Part allows to conditionally render a 'Data Visualizer' Web Part according to the selected vertical. It is a simple way to build a complete search center including multiple sources.

!["aequos Data Verticals Web Part"](../../assets/webparts/data_verticals/data_verticals_wp_picker.png){: .center}

!["aequos Data Verticals Web Part"](../../assets/webparts/data_verticals/data_verticals_wp_default.png){: .center} 

## Configuration

The configuration of the 'Data Verticals' Web Part is fairly simple.

!["Verticals configuration"](../../assets/webparts/data_verticals/configure_verticals.png){: .center} 

### Configure verticals

The options for a vertical are as follow:

| **Setting** | **Description** |
|------------|-----------------|
| **Tab name** | The vertical name (i.e. tab) 
| **Tab value** | The vertical value that will be sent to connected 'Data Visualizer' Web Parts. You can use this value using the `{verticals.value}` token. See [tokens](../data-visualizer/tokens.md) for more info.
| **Fluent UIFabric icon name** | The optional Fluent UI icon to display for the tab. Refer to [Office UI Fabric documentation](https://developer.microsoft.com/en-us/fluentui#/styles/web/icons) to see all available icons.
| **Is hyperlink** | If checked, the tab will behave as an hyperlink meaning it won't trigger any selected event.
| **Link URL** | If the tab is an hyperlink, the link URL to use. Tokens `{<TokenName>}` are supported here. See [tokens](../data-visualizer/tokens.md) for more info.
| **Open behavior** | If the tab is an hyperlink, the opening behavior (new tab or current tab).
| **Show link icon** |  If the tab is an hyperlink, display or hide an icon next to the tab name indicating the tab is a link (same page or external).
| **Enable Target Audience** | If checked, the tab will only be visible to targetted audience.
| **Target Audience Group** | If target audience is enabled, this is a people picker field to add users and groups who will be able to see this tab.

> The 'Data Verticals' Web Part does not need to be connected to any Web Part. However, it is meant to be used by a 'Data Visualizer' Web Part to get it work. More info about configuration [here](../data-visualizer/connections/index.md).

> We recommend to configure the 'Data Visualizer' Web Parts that will use verticals **before connecting them to the verticals Web Part**.