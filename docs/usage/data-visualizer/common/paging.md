The paging options are available for all data sources.

| Setting | Description | Default value |
| --------| ----------- |---------------|
|**Show paging** | Hide or display the paging control.
|**Number of items per page** | Specify the number of items to show per page. The maximum limit is 500 items per page. Depending of the data source,  this value will be handled automatically or manually. For instance, the SharePoint Search and SharePoint CAML will take care of this value automatically. However, the OData data source can use this value by usin the `{itemsCountPerPage}` token to build a dynamic query (ex: `$top={itemsCountPerPage}`).
|**Number of pages to display in range** | Determines the number of pages to display in range.
|**Hide navigation buttons (prev page, next page)** | Self explicit.
|**Hide first/last navigation buttons** | Self explicit.
|**Hide navigation buttons (prev, next, first, last) if they are disabled** | Self explicit.

**Data source paging behaviors**

Paging is available for all data sources. However, they can handle it differently.

| Data source | Paging behavior | Comments |
|-------------| ----------------|-----------|
| **SharePoint CAML**| Dynamic | Paging is done calculating the next page link based of the last item ID of the current results set. Therefore, pages are "discovered" along the way when browsing, meaning you can only increase the page number by one every time.
| **SharePoint Search** | Dynamic | All page links are pre-calculated since the search engine returns the total items count matching the query regardless the page number. It means you can directly go the last page of results matching the query if you want. 
| **OData** | Dynamic/Static | Dynamic when using the `@odata.nextLink` information if present ('server-side paging') or `$skip` or `$skipToken` in the URL to determine the next page link URL. When dynamic, the pages are "discovered" along the way when browsing. Static when using the items array directly.
| **Static Data** | Static | Paging is done statically base on the items array.