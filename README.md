# understanding sentiments about oil prices

## project log

- started with the idea to analyze how sentiment (from twitter/reddit/news) affects prices. crypto was first choice, but too volatile and noisy. switched to oil.
- scraped news data, fetched oil prices using yfinance api. storing news articles by date, grouping all articles per day.
- sentiment analysis done (vader, etc). tried to weigh sentiment by likes/upvotes, but data was sparse.
- tried averaging monthly sentiment scores, but correlation with oil prices was weak. positive and negative news just cancel out.
- realized hype and short-term sentiment spikes might matter more than averages.
- current summary: built a pipeline to collect, store, and summarize oil-related sentiment. data isn't super representative yet. more statistical analysis needed to find real patterns.
- next steps: experiment with different sentiment aggregation methods, maybe look at sentiment volatility or outliers instead of averages.

## tl;dr

- code works, data flows, learnt a lot about text analysis but insights are meh. need more stats analysis

