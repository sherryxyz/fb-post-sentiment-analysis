# FB Post Sentiment Analysis

### Project Background
As one of the largest social media websites in the world, Facebook serves as an attractive platform for businesses to engage with their consumers. Virtually all consumer-facing businesses have a virtual presence on Facebook, often in the form of Facebook business pages. On a daily basis, Facebook users generate a vast number of posts while visiting these business pages. These user posts may include customer complaints, questions, or appreciations directed towards the focal businesses.

For businesses, these user-generated posts hold valuable information about customers' needs and preferences. Understanding the content of these user posts presents a significant opportunity to gain real-time insights into customer sentiment.

### Dataset and Business Task
#### Dataset

The provided dataset, named "FB_posts_labeled.txt," is a tab-delimited file with the following fields:

postId: A unique identifier for each user post. There are a total of 7961 posts in the dataset.
message: The text content of each post.
Appreciation: A binary (0/1) indicator of whether a post is an appreciation.
Complaint: A binary (0/1) indicator of whether a post is a customer complaint.
Feedback: A binary (0/1) indicator of whether a post is customer feedback (e.g., questions and suggestions).
The three content categories (Appreciation, Complaint, and Feedback) are mutually exclusive in this dataset and represent classes to be predicted by our text classifier.

### Business Task
The main goal of this project is to build a text classifier capable of predicting the content category of a post based on its textual content. By using natural language processing and machine learning techniques, we aim to develop a model that can effectively identify whether a post falls under Appreciation, Complaint, or Feedback.
