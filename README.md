# Integration trial of StepZen with Kontent API

This is a trial to integrate [Kentico Kontent Delivery REST API](https://docs.kontent.ai/reference/delivery-api) with [Stepzen](stepzen.com) using the [Stepzen "Connect Type Customer to Your Custom Backends" docs section](https://my.stepzen.com/docs/platform/customerotherbackends).

But the docs says:
> Coming Soon: We will soon be relesing the ability to connect to any REST API that returns JSON (through the directive @rest that you will see in this tutorial, but with additional parameters), and backends that support GraphQL (through the directive @graphql).

I tried to map these Kontent Delivery REST endpoints via StepZen GraphQl endpoint:
* [Retrieve a content item](https://docs.kontent.ai/reference/delivery-api#operation/retrieve-a-content-item)
* [List of content items](https://docs.kontent.ai/reference/delivery-api#operation/list-content-items)
  * including [Filtering content operators](https://docs.kontent.ai/reference/delivery-api#tag/Filtering-content/filtering-operators)
  * including [Projection](https://docs.kontent.ai/reference/delivery-api#tag/Projection)
