
# Apollo Client/Server RT messaging with channels and subscriptions

GraphQL real-time messaging with channels, now using subscriptions over websocket instead of polling. 

From the apollo docs:
>Important: Compared to queries and mutations, subscriptions are significantly more complex to implement. Before you begin, confirm that >your use case requires subscriptions.

I can confirm this was significanly more challenging with subscriptions whereas polling was quite simple. Chat is one use case that does work well with subscriptions. Nearly all my cacheing was removed due to the speed of the subscription, even when I throttled down to slow 3G. 

 ## Installation and Usage
````
npm i
npm run dev
``````

# Credits

https://www.apollographql.com/blog/graphql/examples/full-stack-react-graphql-tutorial/

I converted the above tutorial to v3. 
