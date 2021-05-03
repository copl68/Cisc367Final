# 
    
### Problem
Astroturfing and inaccurate negative sentiment in product reviews in the Amazon marketplace

### Background
Amazon.com is a household name that dominates the e-commerce space. Many users of Amazon's online shopping services rely on 
customer reviews on products that they are interested in. In fact, 20% of sales on Amazon.com are attributed to product reviews. Additionally, 1 out of 3 shoppers say that they will not purchase a product unless it has been positively reviewed.
<sup>1</sup> However, these reviews are not always honest reviews from paying customers with real opinions. There are numerous instances of fake reviews and ratings on Amazon.com, which portray a false image of a product to the audience. One example may be the use of bots and workers at click farms to mark negative reviews on their competitors products as "helpful" in order to give those products a false portrayal of bad customer experiences. <sup>2</sup>
<br>Another example that may give false positive portrayal is the fact that some sellers on Amazon pay others to leave good reviews on Amazon. This process is called "astroturfing" and there are monetary incentives offered when submitting a positive review, which results in numerous inaccurate and positive reviews on undeserving products. One particular study has found 23 Facebook groups that are solely a dedicated place for sellers to hire fake reviewers for their products. On average, these groups include about 16,000 members and 570 posts per day.<sup>3</sup> With so much corruption within the reviews section of Amazon, it may be helpful to analyze the data withing these comments to potentially identify patterns within the data. 

### Research Questions
- Are negative and positive reviews more commonly associated with objective or subjective speech?
- Does there appear to be a pattern across the time of **day** or **year** the review was posted?
- Are there any inconsistancies in the spread of number of reviews across time? 

### Question Justification 
- By finding patterns between the level of objectiveness and the positivity (or lack of) or a product review, we may be able to use found relationships to classify outliers. For example, if positive reviews tend to have a very high level of subjectiveness, positive reviews with *less than* high levels of subjectiveness could be cause for concern. Deviations from the expected pattern may highlight possible souces of fake reviews.  
- Sharp spikes in a graph showing the number of reviews posted across time in a day and time in a year may seem unusual, especially for certain times in the day. For example, if there were many upvotes for a negative review late in the night, there should be some concern. It is unlikely that many legitimate reviewers submit reviews and ratings very late at night. Therefore, unusual peaks may be helpful in determining how accuarate reviews are.  
- A good indication of a fake review is said to be a short spurt of many similar reviews. <sup>4</sup> This is because many fake reviewers may respond to a single advertisement, promising compensation for good reviews, soon after the ad is posted. The similarity of these reviews that have been posted close to each other is also a good indication of whether or not the suspected reviews are fake.   

### Datasets
Combination of the [metadata](http://deepyeti.ucsd.edu/jianmo/amazon/index.html) links, as well as a similar combination of 5-core datasets found [here](https://nijianmo.github.io/amazon/index.html#complete-data)

### Dataset Explanation
Metadata links - Provides important information for  items in each category, such as their ASIN (Amazon Standard ID Number), brand, title, and price. The data is split up between the categories in the Amazon marketplace. 
5-core datasets - These links are split up by category of products on Amazon as well and includes important information, such as overall ratings, time posted, and content of the reviews text. 

### Ethical Concerns
There are some major ethical concerns when dealing with the problem of fake reviews for products on Amazon. One of the stakeholders in this situation is the competition of said companies. When a seller has a very large amount of positive reviews, the seller appears as though they are a seller with great products. This takes business away from legitimate businesses, that are earning good reviews for themselves without any outside help. This results in a greatly unfair business model for legitimate sellers on Amazon. <sup>1</sup>
<br> This leads to the next stakeholder: the customers. When customers shop on Amazon, many of them will tend to buy the products with many high ratings. However, the products with the most best reviews did not rightfully earn their good reviews, while legitimately good products will not gain as much attention. Therefore, the customers will likely order a product with lower quality than the better product of the competing company because of the reviews. 
<br> Lastly, Amazon itself is a huge stakeholder. Due to these false reviews, Amazon looses sellers. The legitimate sellers can either no longer compete or simply to not want to compete with those sellers with inaccurate reviews. This applies to both small sellers, such as personal shops, and big sellers, such as Nike. Since these sellers to not want to sell in the Amazon marketplace anymore, Amazon loses quality customers. <sup>1</sup> 

### Resources
- https://www.usatoday.com/story/tech/news/2017/03/20/review-you-wrote-amazon-priceless/99332602/
- https://www.cnbc.com/2020/09/06/amazon-reviews-thousands-are-fake-heres-how-to-spot-them.html
- https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3664992
- https://www.nytimes.com/wirecutter/blog/lets-talk-about-amazon-reviews/