# SMS Spam Detection Using SMOTE and Supervised Machine Learning Techniques

## Introduction
The global surge in smartphone usage, with over 6.8 billion users, has led to the ubiquity of Short Message Service (SMS). However, this popularity has also given rise to an increase in SMS spam, posing challenges unique to the nature of SMS communication. This research project focuses on developing a robust SMS spam detection model using machine learning techniques.

## Objective
The primary goal is to apply various machine learning algorithms (Naïve Bayes, Support Vector Machines, Logistic Regression, Random Forest, and K-Nearest Neighbors) to address the SMS spam detection problem. The study uses a dataset of 5,574 text messages from the UCI Machine Learning repository.

## Related Work
Prior studies have explored ML and DL algorithms for SMS spam detection, achieving notable results. This project differentiates itself by proposing dataset balancing before model training, aiming to enhance performance.

## Methodology
The proposed SMS spam detection model involves three steps: text preprocessing, applying machine-learning algorithms, and evaluating models with a test set. The dataset undergoes outlier removal, tokenization, stop word removal, and TF-IDF vectorization. SMOTE oversampling and Min-Max Normalization create four datasets for training machine-learning algorithms.

<p align="center">
  <img width="500" alt="Screenshot 2024-01-09 at 2 31 29 PM" src="https://github.com/Profzubbyd/spam-classifier/assets/46527701/bf68e7e2-21ab-4c01-8378-006b3c01df8a">
</p>

<p align="center">
  Figure 1: Proposed SMS spam detection framework
</p>


## Experimental Setup
The UCI dataset, consisting of 13.4% spam and 86.6% ham messages, is used for performance evaluations. The evaluation metrics include accuracy, precision, recall, and F-measure.

<p align="center">
  <img width="500" alt="image" src="https://github.com/Profzubbyd/spam-classifier/assets/46527701/396b4842-60fb-4e4e-9e51-5b72ae6b04a2">
</p>

<p align="center">
  Figure 2: Distribution of UCI Dataset classes
</p>

## Results
<p align="center">
  <img width="500" alt="image" src="https://github.com/Profzubbyd/spam-classifier/assets/46527701/74f370a9-9022-44bc-8c69-b603ae8b5b23">
</p>

<p align="center">
  Figure 3: Word Cloud of Ham SMS Messages
</p>

<p align="center">
  <img width="500" alt="image" src="https://github.com/Profzubbyd/spam-classifier/assets/46527701/e43c6761-e1e3-495d-bf69-61f71c8a2678">
</p>

<p align="center">
  Figure 4: Word Cloud of Spam SMS Messages
</p>

The experimental results show that oversampling and normalization significantly improve model performance. The Random Forest algorithm consistently outperforms others, achieving the highest accuracy and precision. Naïve Bayes excels in recall, while Logistic Regression performs well after normalization.

<p align="center">
  <img width="500" alt="image" src="https://github.com/Profzubbyd/spam-classifier/assets/46527701/2ca42d39-bddf-48fd-a849-df3733b1e2a9">
</p>

<p align="center">
  <img width="500" alt="image" src="https://github.com/Profzubbyd/spam-classifier/assets/46527701/7eee07a2-92d5-4433-937b-510d68ecb179">
</p>

## Conclusion
The study concludes that oversampling and normalization contribute to improved SMS spam detection. Random Forest emerges as the most effective algorithm, considering accuracy, precision, and overall performance. Future work involves testing models on additional datasets to assess generalizability.

## References
[1]	  Online: https://explodingtopics.com/blog/smartphone-stats 

[2] 	Online: https://www.slicktext.com/blog/2022/10/17-spam-text-statisitics-for-2022 

[3] 	X. Liu, H. Lu and A. Nayak, “A Spam Transformer Model for SMS Spam Detection,” in IEEE Access, vol. 9, pp. 80253-80263, 2021, doi: 10.1109/ACCESS.2021.3081479.

[4] 	Pavas Navaney, Gaurav Dubey, Ajay Rana, “SMS Spam Filtering using Supervised Machine Learning Algorithms.,” in 8th International Conference on Cloud Computing, Data Science & Engineering, 978-1-5386-1719-9/18/ 2018 IEEE.

[5] 	S. Gadde, A. Lakshmanarao, and S. Satyanarayana, “SMS Spam Detection using Machine Learning and Deep Learning Techniques,” 2021 7th International Conference on Advanced Computing and Communication Systems (ICACCS), Coimbatore, India, 2021, pp. 358-362, doi: 10.1109/ICACCS51430.2021.9441783.

[6] 	S. Sheikhi, M. T. Kheirabadi, A. Bazzazi, “An Effective Model for SMS Spam Detection Using Content-based Features and Neural Network”, International Journal of Engineering, IJE TRANSACTIONS B: Applications Vol. 33, No. 2, (February 2020) 221-228.

[7] 	A. Karami and L. Zhou, ‘‘Improving static SMS spam detection by using new content-based features,’’ in Proc. 12th Amer. Conf. Inf. Syst., Savannah, GA, USA, 2014, pp. 1–9. [Online]. Available: https://aisel.aisnet.org/cgi/viewcontent.cgi?article=1205&context=amcis2014

[8] 	Luo GuangJun, Shah Nazir, Habib Ullah Khan, Amin Ul Haq, “Spam Detection Approach for Secure Mobile Message Communication using Machine Learning Algorithms.,” in Hindawi, Security and Communication Networks, Volume 2020, Article id:8873639.July-2020.

[9] 	Tian Xia, Xuemin Chen, “A Discrete Hidden Markov Model for SMS Spam Detection.,” in Applied Science, MDPI, Appl. Sci. 2020, 10, 5011; doi:10.3390/app10145011.

[10] 	Nilam Nur Amir Sjarif, N F Mohd Azmi, Suriayati Chuprat, “SMS Spam Message Detection using Term Frequency-Inverse Document Frequency and Random Forest Algorithm,” in The Fifth Information Systems International Conference 2019, Procedia Computer Science 161 (2019) 509–515, ScienceDirect.

[11] 	M. Nivaashini, R. S. Soundariya, A. Kodieswari, P. Thangaraj, “SMS Spam Detection using Deep Neural Network,” in International Journal of Pure and Applied Mathematics, Volume 119 No. 18 2018, 2425-2436.

[12] 	Gomatham Sai Sravya, G Pradeepini, Vaddeswaram, “Mobile Sms Spam Filter Techniques Using Machine Learning Techniques,” International Journal Of Scientific & Technology Research Volume 9, Issue 03, March 2020.

[13] 	I. Ahmed, D. Guan, and T. C. Chung, “SMS classification based on Naïve Bayes classifier and Apriori algorithm frequent itemset,” International Journal of Machine Learning and Computing, vol. 4, no. 2, p. 183, 2014.

[14] 	Online: https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection 

[15] 	Forman, G., “An Extensive Empirical Study of Feature Selection Metrics for Text Classification George,” J. Mach. Learn. Res. 2003, 1, 1289–1305.

[16] 	Gashti, M.Z., “Detection of Spam Email by Combining Harmony Search Algorithm and Decision Tree,” Eng. Technol. Appl. Sci. Res. 2017, 7, 1713–1718.
