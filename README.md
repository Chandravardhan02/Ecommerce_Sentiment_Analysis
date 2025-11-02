**Why doing this?**

  Because for an e-commerce company There are millions of reviews, and humans can’t read them all 

Need to know:

- Which products make customers happy or angry

- What problems customers keep talking about (like late delivery, damaged items, or refunds)

- How to improve service and sales

- So this helps the company understand customer feelings automatically using data.

**How does this code work?**

**Step 1: Cleaning the data**

- It takes all the reviews (text written by customers) and:

- Removes extra symbols like @, #, $

- Converts everything to lowercase

- Removes boring words like “the”, “and”, “is”

This helps the computer focus on important words like “broken”, “fast”, “good”, etc.

**Step 2: Label the sentiment**

If a review has a rating (1–5 stars):

- 4 or 5 →  Positive

- 3 →  Neutral

- 1 or 2 →  Negative

Now each review is tagged with how the customer feels.

**Step 3: Train the AI model**

  It teaches the computer how to read text and guess whether it’s positive or negative.
It does this using:

- TF-IDF → a way to find which words are most important
- Logistic Regression → a simple machine learning model that predicts if something is happy or sad

Then it checks how well the model works using a report (accuracy).

**Step 4: Visualizations**

It creates colorful charts:

- How many positive vs negative reviews

- Which products have the highest ratings 

- Which ones are the worst 

- Word clouds showing the most common words in happy and sad reviews

This helps the company “see” what’s happening instead of reading tons of text.

**Step 5: Finding problem types**

  The code looks inside negative reviews and checks for problem keywords:

- “late”, “delay” → Delivery Issue

- “broken”, “defect” →  Product Quality Issue

- “refund”, “return” →  Refund/Return Issue

- “package”, “box” → Packaging Issue

- “support”, “help” →  Customer Service Issue

So the company knows exactly what is going wrong and where to fix it.

**Step 6: Give recommendations**

Finally, it suggests:

  “This product has low rating because of delivery and packaging issues.
Focus on improving delivery first.”

This turns raw data into useful advice for the business team.
