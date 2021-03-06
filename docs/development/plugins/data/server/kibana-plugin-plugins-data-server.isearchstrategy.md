<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-data-server](./kibana-plugin-plugins-data-server.md) &gt; [ISearchStrategy](./kibana-plugin-plugins-data-server.isearchstrategy.md)

## ISearchStrategy interface

Search strategy interface contains a search method that takes in a request and returns a promise that resolves to a response.

<b>Signature:</b>

```typescript
export interface ISearchStrategy<SearchStrategyRequest extends IKibanaSearchRequest = IEsSearchRequest, SearchStrategyResponse extends IKibanaSearchResponse = IEsSearchResponse> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [cancel](./kibana-plugin-plugins-data-server.isearchstrategy.cancel.md) | <code>(id: string, options: ISearchOptions, deps: SearchStrategyDependencies) =&gt; Promise&lt;void&gt;</code> |  |
|  [search](./kibana-plugin-plugins-data-server.isearchstrategy.search.md) | <code>(request: SearchStrategyRequest, options: ISearchOptions, deps: SearchStrategyDependencies) =&gt; Observable&lt;SearchStrategyResponse&gt;</code> |  |

