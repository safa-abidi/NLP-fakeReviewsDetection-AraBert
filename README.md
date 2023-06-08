# Fake Arabic reviews detection for ABSA (Aspect-based sentiment analysis) in the hospitality industry  

For our end of fourth year of engineering project, we aimed to address the issue of identifying fake Arabic reviews in the hospitality industry by employing semi-supervised techniques, specifically self-learning and Gan-Bert.

 ## Context
 The hospitality industry heavily relies on online reviews to attract customers and maintain a positive reputation. However, the increasing prevalence of fake reviews poses a significant challenge for businesses. Detecting fake reviews is crucial to ensure accurate and reliable feedback from customers, which in turn helps establishments make informed decisions and provide better services.

### Problem Statement
The proliferation of fake Arabic reviews in the hospitality industry has made it difficult for businesses to discern genuine feedback from fabricated ones. Existing manual detection methods are time-consuming, inefficient, and often fall short in accurately identifying fake reviews.

### Solution
Our project proposes a novel approach to tackle the problem of fake Arabic reviews detection. By leveraging semi-supervised techniques, specifically self-learning and Gan-Bert, using large unlabeled datasets, we aim to improve the performance of fake reviews detection models.

## Data
#### 1. Datasets
To train and evaluate our models, we utilized a comprehensive dataset consisting of Arabic hotel reviews. The dataset was carefully curated and included both genuine and fake reviews. It comprised a diverse range of reviews from various sources, ensuring a representative sample of the Arabic hospitality industry.

#### 2. Preprocessing
Before feeding the data into our models, we performed preprocessing steps to enhance the quality and usability of the dataset. These steps involved removing noise, normalizing text, handling missing values, and tokenizing the reviews. Additionally, we employed techniques such as stop-word removal, stemming, and handling imbalanced classes to optimize the dataset for training.

## Models
#### Self-Learning

We employed the self-learning technique, a form of semi-supervised learning, to leverage a small labeled dataset and a larger unlabeled dataset. This approach allowed us to iteratively label the unlabeled data using the trained model and incorporate it into the training process, enhancing the model's performance.

#### Gan-Bert
A combination of Generative Adversarial Networks (GANs) and Bidirectional Encoder Representations from Transformers (BERT), was utilized to further improve the detection accuracy. The GAN component generated realistic fake reviews, while BERT learned to differentiate between genuine and fake reviews, resulting in a robust model for fake Arabic review detection.
## Results
Our models achieved promising results in detecting fake Arabic reviews in the hospitality industry. The evaluation metrics, including accuracy and F1-score, demonstrated the effectiveness of our approach. The models outperformed traditional methods and showcased the potential of semi-supervised techniques in addressing the problem of fake reviews.

## Conclusion and Perspectives
In conclusion, our project successfully addressed the challenge of fake Arabic reviews detection in the hospitality industry using semi-supervised techniques. The developed models showcased significant improvements in accuracy and performance compared to traditional supervised approaches.

Moving forward, there are several avenues for future research and improvement. Further exploration of different semi-supervised learning techniques, as well as experimenting with other deep learning architectures, could potentially enhance the accuracy and efficiency of fake review detection. Additionally, expanding the dataset and incorporating more diverse sources of reviews would help in capturing the evolving nature of fake reviews in the industry.

Our project contributes to the field of sentiment analysis and fake review detection, providing valuable insights and a foundation for future advancements in this area. We hope our work serves as a stepping stone for more robust and reliable methods to combat fake Arabic reviews in the hospitality industry.