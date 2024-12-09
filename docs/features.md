The [PnP Modern Search v4](https://microsoft-search.github.io/pnp-modern-search/) shares the same code foundation as the aequos Modern Data Visualizer solutions. However, some features are only available in the commercial solution.

!!! important
    Although these two solutions share the same code foundation, **{==we do not "own" the PnP Modern Search as it is a Microsoft community-driven open source project. It means we do not 'control' or voluntarily 'block' new features and the two solutions evolve independently==}**. However we try as much as possible to ensure the same base concepts remain the same and common issues are adressed on both sides. It is a win-win situation.

## Data sources

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| Available data sources | The data sources you can use to retrieve data. | <ul style="list-style: none"><li>[SharePoint Search](../usage/data-visualizer/data-sources/sharepoint-search/)</li><li>[Microsoft Search](../usage/data-visualizer/data-sources/microsoft-search/)</li><li>**<span style="color:#5dc418">[Microsoft Graph](../usage/data-visualizer/data-sources/odata/#microsoft-graph)</span>**</li><li>**<span style="color:#5dc418">[SharePoint REST API v1/v2](../usage/data-visualizer/data-sources/odata/#sharepoint-rest-api)**</span></li><li>**<span style="color:#5dc418">[Azure AD API (ex Azure Function)](../usage/data-visualizer/data-sources/odata/#azure-active-directory-secured-api)**</span></li><li>**<span style="color:#5dc418">­[Anonymous REST API](../usage/data-visualizer/data-sources/odata/#anonymous)**</span></li></ul> | <ul style="list-style: none"><li>SharePoint Search</li><li>Microsoft Search</li></ul> |
| [Data source slots](../usage/data-visualizer/slots/) | Templates can use placeholder variables mapped to data source fields to make them reusable. | Yes | Yes |
| [Data caching](../usage/data-visualizer/data-sources/#caching) | Data can be put in cache for performances. | **<span style="color:#5dc418">Yes</span>** | No |
| [Data paging](../usage/data-visualizer/data-sources/#paping) | Data can be browsed using paging controls. | Yes | Yes |

## Layouts

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| Available layouts for results | Layouts you can use to display results from a data source. | <ul style="list-style: none"><li>[Cards](../usage/data-visualizer/layouts/#cards)</li><li>[Details List](../usage/data-visualizer/layouts/#details-list)</li><li>[Simple List](../data-visualizer/layouts/#simple-list)</li><li>[Slider](/usage/data-visualizer/layouts/#slider)</li><li>[People](/usage/data-visualizer/layouts/#people)</li><li><span style="color:#5dc418">**Teams**</span></li><li>[Custom](/usage/data-visualizer/layouts/#people)</li></ul> | <ul style="list-style: none"><li>Cards</li><li>Details List</li><li>Simple List</li><li>Slider</li><li>People</li><li>Custom</li></ul> |
| [Available layouts for filters](../usage/data-filters/#filter-templates) | Layouts you can use to display filters. | <ul style="list-style: none"><li>Vertical</li><li>Horizontal</li><li>Panel</li><li>Custom</li></ul> | <ul style="list-style: none"><li>Vertical</li><li>Horizontal</li><li>Panel</li><li>Custom</li></ul>
| [Result types](../usage/data-visualizer/layouts/#result-types) | Define conditions on fields value for conditional rendering. | Yes (handlebars templates only) | Yes (handlebars templates only) |
| [Customize results using Handlebars, HTML and CSS](../extensibility/templating/#handlebars-html-and-css-customizations/) | Use Handlebars, HTML and CSS to build custom results templates. | Yes | Yes |
| [Customize results using Adaptive Cards](../extensibility/templating/#adaptive-cards-customizations) | Use Microsoft Adaptive cards to build custom results templates. | **<span style="color:#5dc418">Yes</span>** | No |
| [Customize filters using Handlebars, HTML and CSS](../extensibility/templating/#handlebars-html-and-css-customizations/) | Use Handlebars, HTML and CSS to build custom filters templates | Yes | Yes |
| [Use basic tokens](../usage/data-visualizer/tokens/) | Ability to transform queries dynamically using basic tokens (current page, hub, user, etc.) | Yes | Yes |
| [Use advanced tokens](../usage/data-visualizer/tokens/#supported-tokens-all-data-sources) | Ability to transform queries dynamically using advanced tokens (verticals, filters) | Yes | Yes |
| [Use Microsoft Adaptive expressions top build dynamic queries](../usage/data-visualizer/tokens/#go-further-with-microsoft-adaptive-expressions) | Ability to use Adaptive Expressions to build dynamic and conditional queries based on tokens. | **<span style="color:#5dc418">Yes</span>** | No |

## Filters

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| [Available templates](../usage/data-filters/#filter-templates) | Templates you can use to filter values. | <ul style="list-style: none"><li>Check box (with search)</li><li>Combo box</li><li>Date range</li><li>Date interval</li><li><span style="color:#5dc418">**Taxonomy picker**</span></li></ul> | <ul style="list-style: none"><li>Check box (without search)</li><li>Combo box</li><li>Date range</li><li>Date interval</li></ul> |
| Configuration options | Available configuration options for filters | <ul style="list-style: none"><li>Filter display name</li><li>Multi value/single value</li><li>Operator between values</li><li>Operator between filters</li><li>Expand by default</li><li>Show values count</li><li>Show values count</li><li>Sort values by name/count (ascending/descending)</li></ul> | <ul style="list-style: none"><li>Filter display name</li><li>Multi value/single value</li><li>Operator between values</li><li>Operator between filters</li><li>Expand by default</li><li>Show values count</li><li>Show values count</li><li>Sort values by name/count (ascending/descending)</li></ul>

## Verticals

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| [Data verticals](/usage/data-verticals/#configure-verticals) 	| Browse data as silos. | Yes | Yes |
| Custom tokens for verticals | Use verticals as tokens including custom data in the results Web Part | Yes | Yes |

## Search box 

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| [Enter free text keywords](../usage/search-box/) | Users can enter free text queries in a search box Web Part.  | Yes | Yes |

## Group Metadata Editor

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| [Tag Microsoft Group / Team](../usage/group-metadata-editor/) | Tag a specific Microsoft 365 group or team using a custom Microsoft Graph schema extension  | **<span style="color:#5dc418">Yes</span>** | No |

## Extensibility

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| [Extensibility method](../extensibility/#advanced-customizations) | The method used to create extensions for Web Parts. | SPFx library components in global or site collection catalog. | SPFx library components in global or site collection catalog. |
| [Custom web components](../extensibility/custom_web_component/) | Developers can create custom web components to use in templates. | Yes | Yes |
| [Custom suggestions providers](../extensibility/custom_suggestions_provider/) | Developers can create custom suggestions providers for the search box. | Yes | Yes |
| [Custom data sources](../extensibility/custom_data_source/) | Developers can create custom data sources with property pane options. | **<span style="color:#5dc418">Yes</span>** | No |
| [Custom layouts](../extensibility/custom_layout/) | Developers can create custom layouts for the results component with property pane options. | Yes  | Yes |
| [Custom Handlebars customizations](../extensibility/handlebars_customizations/) | Developers can create custom helpers or partials for templates using Handlebars. | Yes | Yes |
| Multiple extensibility libraries support | Developers can register one or more extensibility libraries per Web Part instances. | Yes | Yes |

## Import Export Feature

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| Import Export Feature | Allow the users to import and export the webpart properties. | Yes | Yes |

## Miscellaneous, support & price

| Feature               | Description               | aequos Modern Data Visualizer     | PnP Modern Search     |
| :-----------------:   | :---------------------:   | :-----------------------------:   | :-------------------: |
| Supported browsers | | <ul style="list-style: none"><li>Chrome</li><li>Firefox</li><li>Edge</li><li>Edge Chromium</li><li>Brave</li><li>Safari</li><li>**Internet Explorer 11 is not supported**</li></ul> | <ul style="list-style: none"><li>Chrome</li><li>Firefox</li><li>Edge</li><li>Edge Chromium</li><li>Brave</li><li>Safari</li><li>**Internet Explorer 11 is not supported**</li></ul> |
| Support | How the solution is supported when your encounter issues | <span style="color:#5dc418;font-weight:700">Guaranteed by **@aequos**. Major bugs correction within 5 open days.</span> | By the open-source community (including us). No guarantee. If it breaks, it breaks |
| Price | | <span style="color:#5dc418;font-weight:700">[www.aequos.ca](https://www.aequos.ca/#comp-kmng61o4){:target="_blank"}</span> | Free |
| License agreement | |<span style="color:#5dc418;font-weight:700">Commercial license. EULA at [www.aequos.ca/eula](https://www.aequos.ca/eula)</span> | MIT License (anyone can reuse the code for commercial purposes)