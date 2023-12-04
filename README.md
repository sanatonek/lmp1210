# LMP1210 Winter 2024 
## Basic Principles of Machine Learning in Biomedical Research

![](files/lmp_signature_image.jpeg)


**Course syllabus and policies:**  [Course handout](files/pdfs/syllabus.pdf).

**Teaching staff:**  

* Instructors: 
  * [Rahul G. Krishnan](https://www.cs.toronto.edu/~rahulgk/index.html) and [Sana Tonekaboni](https://www.cs.toronto.edu/~stonekaboni/)

Please do not send the instructor or the TAs email about the class directly to their personal accounts.

**Piazza:** Students are encouraged to sign up [Piazza](https://piazza.com/utoronto.ca/winter2024/lmp1210h) to join course discussions.
If your question is about the course material and doesn't give away any hints for the homework, please post to Piazza so that the entire class can benefit from the answer.

**Lecture and tutorial hours:**  


|           | Time      | Location  |
|-----------|--------------|--------------|
| Lecture | Thursday 10:30 AM -12:30 PM  | Sydney Smith building, Room 1079  | 
| Office hours | TBD  | TBD  | 

<br>
<br>

---

## Course Overview

This course is intended for graduate students in Health Sciences to learn the basic principles of machine learning in biomedical research and to build and strengthen their computational skills of medical research. The course aims to equip students with the fundamental knowledge of machine learning (ML). During the course, the students will acquire basic computational skills and hands-on experience to deploy ML algorithms using python. The students will learn the current practices and applications of ML in medicine, and understand what ML can and cannot do for medicine. The goal of this course to establish an essential foundation for graduate students to take the first steps in computational research in medicine.

Introduction to basic principles and current practices of machine learning in biomedical research. Focus on the fundamental ML algorithms with applications in biomedical data; the application of unsupervised learning in genomic data; the application of supervised learning for medical images.

<br>
<br>

---

## Assignments


|           | Handout                | Due
|-----------|------------------------|---------
| **Math Diagnostics**   |  [Handout](files/pdfs/math_diagnostic.pdf)  | January 18 2023
| **Assignment #1**   |  [Homework1](files/assignments/hw1.pdf), [data](files/assignments/hw1_data.csv)  | February 1 2023
| **Assignment #2**   |  [Homework2](files/assignments/hw2.pdf), [data](files/assignments/hw2_data.csv)  | February 15 2023
| **Assignment #3**   |  [Homework3](files/assignments/hw3.pdf), [data (zip)](files/assignments/A3_data.zip)  | March 7 2023
| **Final Project**   |  [Handout](files/assignments/project_handout.pdf)  | February 29 2023 (Proposal)


<br/> 
Lateness: Assignments and Projects will be accepted up to 3 days late, but 10% will be deducted for each day late, rounded up to the nearest day. After that, submissions will not be accepted and will receive a score of 0.
<br/> 


---


## ChatGPT-GPT4 and the use of generative AI tools for learning


There are several generative AI tools such as ChatGPT, GPT4, Bard, Claude available for public use as general purpose chatbots. These machine learning models are incredibly powerful and are capable of providing responses to arbitrarily complex text (and sometimes image) queries. You may use generative artificial intelligence (AI) tools, including ChatGPT and GitHub Copilot, as learning aids.

Generative AI is not required to complete any aspect of this course, and we caution you to not rely entirely on these tools to complete your coursework. Instead, we recommend treating generative AI as a supplementary tool only for exploration or drafting content. Ultimately, you (and not any AI tool) are responsible for your own learning in this course, and for all the work you submit for credit. It is your responsibility to critically evaluate the content generated, and to regularly assess your own learning independent of generative AI tools. Overreliance on generative AI may give you a false sense of how much you’ve actually learned, which will lead to poor performance on the midterm test and final exam, in later courses, or in future work or studies after graduation. You will not be permitted to use generative AI on the midterm test or final exam. Remember that you (and not any AI tool) are responsible for your own learning in this course, and for the final work you submit for this assignment.  This assignments and homeworks are designed to be doable without the use of generative AI, using only concepts and skills we have covered in lecture and in the course readings.

While some generative AI tools are currently available for free in Canada, please be warned that these tools have not been vetted by the University of Toronto and might not meet University guidelines or requirements for privacy, intellectual property, security, accessibility, and records retention. Generative AI may produce content which is incorrect or misleading, or inconsistent with the expectations of this course. They may even provide citations to sources that don’t exist—and submitting work with false citations is an academic offense. These tools may be subject to service interruptions, software modifications, and pricing changes during the semester. 

The final work you submit for assignments in this course must be your own, and may not include any verbatim content from generative artificial intelligence (AI) tools. You may, however, use generative AI to support your work on this assignment in the following ways:

* To answer general questions about high-level concepts covered in this course or assignment
* To provide examples on the usage of a library’s API 
* To summarize information 
* To generate test cases for your code 
* To assist with understanding and debugging errors
  
If you choose to use any generative AI tools while working on this assignment, you must acknowledge which generative AI tools you used and how you used them. It is an academic offence to not credit sources—including generative AI—in work that you submit. This acknowledgment should take the form of:
* A statement at the beginning of the solution pdf highlighting which, tool was used and how.
* You should submit a seperate txt file listing all raw ChatGPT transcripts that record your interactions with the tool while working on each assignment. 
* For code, you should use comments in your code acknowledging which functions, classes, or blocks of code were created in collaboration with generative AI. e.g. #genai - dataloader was created with chatgpt

Any uses of generative AI beyond the ones listed above are not allowed, and will be considered use of an unauthorized aid, which is a form of cheating. In summary:
* This course is designed with a view to not have to use any such tools to fully absorb the course material and content.
* The use of generative AI tools can be both useful and simultaneously harmful to learning the fundamentals of machine learning. Your knowledge of the concepts will be tested on the final exam and midterm exam where you will not have access to generative AI tools.
* Any use of GPT4/ChatGPT must be documented i.e. students should explicitly state which model they used, and list the queries they found helpful. Each submitted assignment will require submission of a list of queries used with generative AI tools.
* Students may use GPT4/ChatGPT to help understand and personalize concepts taught in homework and lectures on their own time. Warning: Please note that the model can hallucinate and can fail in unpredictable ways and students should expect this.
* Using GPT4/ChatGPT's output directly in any material handed in for homework constitutes an academic violation. Students are expected to write their own homework assignments even if such tools were used as aids to learn concepts.


<br>
<br>

---


## Calendar

Suggested readings included help you understand the course material. They are not required, i.e. you are only responsible for the material covered in lecture. Most of the suggested reading listed are more advanced than the corresponding lecture, and are of interest if you want to know where our knowledge comes from or follow current frontiers of research. Please refer to the [Resources](#Resources) section for the texts.

B = Pattern Recognition and Machine Learning (by Bishop)

DL = Deep Learning Book

MK = Information Theory, Inference, and Learning Algorithms (by MacKay)

RG = Roger Grosse's Notes

|       | Date&nbsp;&nbsp;&nbsp;&nbsp;    | Lecture Topic                  | Slides  | Suggested Readings | Deliverables
|-------|----|------------------------|---------|------------------------------------------|-----------------
| **Lecture&nbsp;1** | Jan 11 | Intro to ML in medicine, nearest neighbor classifier | Slides | B: 1-2 (emphasis on 2.5.2); DL: 2-5   |
| **Lecture&nbsp;2** | Jan 18 | Linear methods for regression and classification; tree-based classifier | Slides|  B: 3-4; RG: [Linear Regression](https://csc413-uoft.github.io/2021/assets/readings/L01a.pdf), [Linear Classifiers](https://csc413-uoft.github.io/2021/assets/readings/L01b.pdf), [Training a Classifier](https://csc413-uoft.github.io/2021/assets/readings/L01c.pdf), MK: p. 22-36 | Math diagnostic Due
| **Lecture&nbsp;3** | Jan 25 | Introduction to Python; basic linear algebra; evaluation methods |  [Colab](https://colab.research.google.com/drive/1GjFs_E9k-zbAXpOOUMScaDNJbIXCbpvU?usp=sharing) | DL: 2, [David Liu's CSC110/111 Course Notes](https://www.teach.cs.toronto.edu/~csc110y/fall/notes/)  |
| **Lecture&nbsp;4** | Feb 01  | ENSEMBLE-based methods; neural networks  | Slides |  DL: 6-8; RG: [Multilayer Perceptrons](https://csc413-uoft.github.io/2021/assets/readings/L02a.pdf), [Backpropagation (quite technical)](https://csc413-uoft.github.io/2021/assets/readings/L02b.pdf)  | Assignment #1 Due
| **Lecture&nbsp;5** | Feb 08  | Supervised learning; Python tutorial for supervised learning practice  |  Slides, [Colab](https://colab.research.google.com/drive/1cjYq1XL7qLrWa3qnSkFfdvV01Vxoxr0G?usp=sharing)  |   |
| **Lecture&nbsp;6** | Feb 15  | Unsupervised learning for clustering: K-means, Gaussian mixture models | Slides  | B: 9; RG: [Mixture Models](https://www.cs.toronto.edu/~rgrosse/courses/csc311_f21/readings/Mixture%20Modeling.pdf)  | Assignment #2 Due
| **Reading Week** | Feb 22  |   |  |   |
| **Lecture&nbsp;7** | Feb 29   | Unsupervised learning for clustering: auto-encoder, graph-based methods; Python tutorial for unsupervised learning practice  | Slides, [Colab](https://colab.research.google.com/drive/1T-zM9rwGRZDn-xjtp20aactSraBIIP4w?usp=sharing) |  [Jaan Altosaar's VAE Tutorial](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/); [Introduction to VAEs (Kingma and Welling)](https://arxiv.org/abs/1906.02691)  | Final project proposal Due
| **Lecture&nbsp;8** | Mar 07   | Guest Lecturer: TBD |  |   | Assignment #3 Due
| **Lecture&nbsp;9** | Mar 14  | Guest Lecturer: TBD |  |   |
| **Lecture&nbsp;10** | Mar 21  | Advanced deep learning methods for medical image analysis | Slides |  | 
| **Lecture&nbsp;11** | Mar 28  | Term project presentation |   |   |
| **Lecture&nbsp;12** | Apr 04   | Term project presentation |   |   |

<br>
<br>

---

## Resources

| Type | Name | Description 
|-----------|------------------------|---------
|Related Textbooks| [Deep Learning (Goodfellow at al., 2016)](https://www.deeplearningbook.org/) | The Deep Learning textbook is a resource intended to help students and practitioners enter the field of machine learning in general and deep learning.
|| [Pattern Recognition and Machine Learning (Bishop, 2006)](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf) | Classic introductory text on machine learning, less emphasis on deep learning approaches.
|| [Information Theory, Inference, and Learning Algorithms (MacKay, 2003)](http://www.inference.org.uk/mackay/itprnn/book.html) | A good introduction textbook that combines information theory and machine learning.
|General Framework| [PyTorch](http://pytorch.org/) | An open source deep learning platform that provides a seamless path from research prototyping to production deployment.
|Computation Platform| [Colab](https://colab.research.google.com) | Colaboratory is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud.
|| [GCE](https://cloud.google.com/compute/) | Google Compute Engine delivers virtual machines running in Google's innovative data centers and worldwide fiber network.
|| [AWS-EC2](https://aws.amazon.com/ec2/) | Amazon Elastic Compute Cloud (EC2) forms a central part of Amazon.com's cloud-computing platform, Amazon Web Services (AWS), by allowing users to rent virtual computers on which to run their own computer applications.


