# tweet-data-analysis
Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations
## About the dataset
For this project, there are 3 datasets that are combined and wrangled.
### 1. Enhanced Twitter Archive [twitter-archive-enhanced.csv]
> The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

### 2. Additional Data via the Twitter API [tweet-json.txt]
> Retweet count and favorite count are not included in the twitter archive. This additional data can be gathered using the Twitter's API.

### 3. Image Predictions File [image_predictions.tsv]
> A table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).
