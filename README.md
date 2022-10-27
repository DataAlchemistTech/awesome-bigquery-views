# Awesome BigQuery Views

Here are some examples of how to derive insights from on-chain crypto data. Not all networks have examples here - you can find the complete list of crypto datasets in [blockchain-etl/public-datasets](https://github.com/blockchain-etl/public-datasets)

| Network | Description | Query | Screenshot | BigQuery | DataStudio | Notes
| --- | --- | --- | --- | --- | --- | ---
| Band | Latest oracle prices | [📝](band/latest-prices.sql) | | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:9d41f5f621fe4deea11ed3be32ed0a5d) | | | 
| Bitcoin | Top 1K addresses, by balance | [📝](bitcoin/top-bitcoin-balances.sql) |  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:9bd85ce4d6174e909cfc89c09cb1cc55) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/p_a72nk0pzzc) | |
| Bitcoin | Bitcoin Gini index, by day | [📝](bitcoin/gini-index-by-day.sql) |  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:531f2d1edf614723b2120a839e5df04b) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/p_a72nk0pzzc) | [[1](https://cloud.google.com/blog/products/data-analytics/introducing-six-new-cryptocurrencies-in-bigquery-public-datasets-and-how-to-analyze-them)]
| Ethereum | Top 1K addresses, by balance  | [📝](ethereum/top-ethereum-balances.sql)|  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:a8286e1cee0e4ee2b16872640faa31c2) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/9tC6C) | [[1](https://medium.com/google-cloud/how-to-query-balances-for-all-ethereum-addresses-in-bigquery-fb594e4034a7)]
| Ethereum | Every account balance on every day | [📝](ethereum/every-balance-every-day.sql)|  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:c5323064f9fb45529ebdd65fb4091374) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/9tC6C) | [[1](https://medium.com/google-cloud/plotting-ethereum-address-growth-chart-55cc0e7207b2)]
| Ethereum | Unique addresses by day | [📝](ethereum/unique-addresses-by-day.sql) |  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:69f31a0f8e7e44d39d99737c4a37ce9b) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/9tC6C) | [[1](https://medium.com/google-cloud/plotting-ethereum-address-growth-chart-55cc0e7207b2)]
| Ethereum | Ether supply by day | [📝](ethereum/ether-supply-by-day.sql)| [🖼️](ethereum/ether-supply-by-day.png) | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:7bd873dec1cd417b89552495cad09e56) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/9tC6C) | [[1](https://medium.com/google-cloud/how-to-query-ether-supply-in-bigquery-90f8ae795a8)]
| Ethereum | Shortest path between addresses | [📝](ethereum/shortest-path-via-traces.sql) |  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:2d202e496bf343a0aa1060f4ef35ffff) | ❌
| Zilliqa | Shortest path between addresses v2 | [📝](zilliqa/shortest-path-via-traces-v2.sql) |  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:c4c9b9294acb42b183233b158cc67074) | ❌
| Multiple | Transaction throughput comparison of multiple blockchains | [📝](multi/transaction-throughput-comparison.sql) |  | [🔍](https://console.cloud.google.com/bigquery?sq=896878822558:8348a785cb274d7b88cf6b3d07e0a5c6) | [📊](https://datastudio.google.com/u/1/reporting/c61d1ee3-0e67-4f19-a322-4aed82a21e1b/page/p_hg8d80pzzc) | [[1](https://medium.com/@medvedev1088/comparing-transaction-throughputs-for-8-blockchains-in-google-bigquery-with-google-data-studio-edbabb75b7f1)]

## More Queries

Check out this awesome repository: https://github.com/RokoMijic/awesome-bigquery-views
