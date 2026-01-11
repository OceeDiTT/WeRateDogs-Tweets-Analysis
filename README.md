# WeRateDogs-Tweets-Analysis

WeRateDogs is a Twitter account that rates people’s dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because “they’re good dogs Brent.” WeRateDogs has over 4 million followers and has received international media coverage. The following datasets were used for this analysis:

1. Enhanced Twitter Archive
2. Additional Data via the Twitter API
3. Image Predictions File
(More information can be found in the Wrangling report)

Three source was given for the data gathering exercise, the first source was a CSV file provided by Udacity and downloaded from website, and it was read into the pandas. The second was a TSV file extracted from a page from Udacity website using requests library and also writing the data into a file that was loaded into pandas. The third source was to be gotten from twitter API, but due to some inconveniences, I resulted to using the TXT file provided by Udacity, it was obtained using requests, loaded with JSON and was loaded into the pandas DataFrame.
