---
layout: post
title:  "Machine Learning without Code"
author: soham
categories: [ Jekyll ]
image: assets/images/mlnocode.png
---
This workshop was conducted as a preliminary introduction to Machine Learning, without any prerequisite knowledge of Programming, Statistics or Calculus. This isn't a formal gateway or introduction to the field, but a nosedive into deep-learning, involving a hands-on project. In under 60 minutes, the workshop participants gained a high-level understanding of how machines learn and built their first image classifier (using Google's Teachable Machines). 

## What is Machine Learning?

Machine learning focuses on the use of data and algorithms to imitate the way that humans learn. Atleast that was the motivating idea when it started. Machine Learning falls under the larger umbrella of Artificial Intelligence (AI) which concerns machines that are capable of doing tasks requiring 'human intelligence'. The following illustration should help illustrate this:

![Logging in on Overleaf](/assets/images/ml-venn.png)

## How do Machines learn?

The process of supervised machine learning can be broadly broken down into 3 distinct steps (following [this](https://ischoolonline.berkeley.edu/blog/what-is-machine-learning/) example from UC Berkeley):

1. **A Decision Process:** In general, machine learning algorithms are used to make a prediction or classification. Based on some input data, which can be labelled or unlabeled, your algorithm will produce an estimate about a pattern in the data.
2. **An Error Function:** An error function serves to evaluate the prediction of the model. If there are known examples, an error function can make a comparison to assess the accuracy of the model.
3. **A Model Optimization Process:** If the model can fit better to the data points in the training set, then weights are adjusted to reduce the discrepancy between the known example and the model estimate. The algorithm will repeat this evaluate and optimize process, updating weights autonomously until a threshold of accuracy has been met.  

## Challenges in today's Machine Learning

### Privacy

In 2016, European Union passed the GDPR to protect the personal data of people in the European Union and European Economic Area. Some US states are also developing policies, such as the California Consumer Privacy Act (CCPA), which require businesses to inform consumers about the collection of their data. This recent legislation has forced companies to rethink how they store and use personally identifiable data (PII). This affects the availability of data for training Machine Learning models. This problem gave birth to an active area of research in Privacy-Preserving Machine Learning

### Bias and Discrimination

 In their effort to automate and simplify a process, Amazon unintentionally biased potential job candidates by gender for open technical roles, and they ultimately had to scrap the project. Many similar events have raised other pointed questions around the use of AI within hiring practices, such as what data should you be able to use when evaluating a candidate for a role.

 Bias and discrimination aren’t limited to the human resources function either; it can be found in a number of applications from facial recognition software to social media algorithms.

### Accountability

Since there isn’t significant legislation to regulate AI practices, there is no real enforcement mechanism to ensure that ethical AI is practiced. The current incentives for companies to adhere to these guidelines are the negative repercussions of an unethical AI system to the bottom line. To fill the gap, ethical frameworks have emerged as part of a collaboration between ethicists and researchers to govern the construction and distribution of AI models within society. 

## Workshop Slides and Recordings

<iframe src="/assets/files/ml1.pdf" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>

Recordings are availabe on the CS Society drive (shared internally)
