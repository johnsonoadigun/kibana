<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-core-server](./kibana-plugin-core-server.md) &gt; [ElasticsearchServiceSetup](./kibana-plugin-core-server.elasticsearchservicesetup.md) &gt; [adminClient](./kibana-plugin-core-server.elasticsearchservicesetup.adminclient.md)

## ElasticsearchServiceSetup.adminClient property

A client for the `admin` cluster. All Elasticsearch config value changes are processed under the hood. See [IClusterClient](./kibana-plugin-core-server.iclusterclient.md)<!-- -->.

<b>Signature:</b>

```typescript
readonly adminClient: IClusterClient;
```

## Example


```js
const client = core.elasticsearch.adminClient;

```

