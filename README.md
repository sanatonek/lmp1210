# LMP1210 Winter 2023 
## Basic principles of machine learning in biomedical research

![](../2023/assets/lmp_signature_image.jpeg)


**Course syllabus and policies:**  [Course handout](assets/misc/syllabus.pdf).

**Teaching staff:**  

* Instructor: 
  * [Bo Wang](https://wanglab.ml/)
  * Office hours: Wed 10-10:30 AM ([Zoom](https://vectorinstitute.zoom.us/j/89136190143?pwd=VlluYXZRZEkvS3M5YmlWYWZiV2hrdz09), Meeting ID: 891 3619 0143, Password: lmp1210)
  * Email: *bowang.wang@utoronto.ca*

* Head TA: 
  * [Zeinab Navidi](https://www.cs.toronto.edu/~zeinabnvd/)
  * Email: *zeinab.navidi@mail.utoronto.ca*

Please do not send the instructor or the TAs email about the class directly to their personal accounts.

**Piazza:** Students are encouraged to sign up [Piazza](https://piazza.com/utoronto.ca/winter2023/lmp1210) to join course discussions.
If your question is about the course material and doesn't give away any hints for the homework, please post to Piazza so that the entire class can benefit from the answer.

**In Person lectures and online tutorials:** The access to online lectures and tutorials will be communicated via course mailing list. Course videos and materials belong to your instructor, the University, and/or other sources depending on the specific facts of each situation, and are protected by copyright. Do not download, copy, or share any course or student materials or videos without the explicit permission of the instructor and/or student(s). For questions about recording and use of videos in which you appear please contact your instructor.

**Lecture and tutorial hours:**  


|           | Time      | Location  |
|-----------|--------------|--------------|
| Lecture | Thursday 10:30-12:30 PM  | University College Room 179  | 

<br>
<br>

---


## Announcements

 - **Jan 9**: Winter term starts! First class session! 
 - **Jan 12**: First LMP1210 class session! 
 - **Jan 19**: Assignment 1 Released, Due February 02!
 - **Feb 2**: Assignment 2 Released, Due February 16!

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
| **Assignment #1**   |  [Homework1](assets/hw1.pdf), [data](assets/hw1_data.csv)  | February 2 2023
| **Assignment #2**   |  [Homework2](assets/hw2.pdf), [data](assets/hw2_data.csv)  | February 16 2023
| **Assignment #3**   |    | TBA
| **Final Project**   |  [Handout](assets/project_handout.pdf)  | February 20 2023 (Proposal)


<br/> 
Lateness: Assignments and Projects will be accepted up to 3 days late, but 10% will be deducted for each day late, rounded up to the nearest day. After that, submissions will not be accepted and will receive a score of 0.
<br/> 


---

## Calendar

Suggested readings included help you understand the course material. They are not required, i.e. you are only responsible for the material covered in lecture. Most of the suggested reading listed are more advanced than the corresponding lecture, and are of interest if you want to know where our knowledge comes from or follow current frontiers of research. Please refer to the [Resources](#Resources) section for the texts.

B = Pattern Recognition and Machine Learning (by Bishop)

DL = Deep Learning Book

MK = Information Theory, Inference, and Learning Algorithms (by MacKay)

RG = Roger Grosse's Notes

|       | Date&nbsp;&nbsp;&nbsp;&nbsp;    | Lecture Topic                  | Slides  | Suggested Readings | Deliverables
|-------|----|------------------------|---------|------------------------------------------|-----------------
| **Lecture&nbsp;1** | Jan 12 | Intro to ML in medicine, nearest neighbor classifier | [Slides](assets/slides/Lecture01.pdf)  | B: 1-2 (emphasis on 2.5.2); DL: 2-5   |
| **Lecture&nbsp;2** | Jan 19 | Linear methods for regression and classification; tree-based classifier | [Slides](assets/slides/Lecture02.pdf)|  B: 3-4; RG: [Linear Regression](https://csc413-uoft.github.io/2021/assets/readings/L01a.pdf), [Linear Classifiers](https://csc413-uoft.github.io/2021/assets/readings/L01b.pdf), [Training a Classifier](https://csc413-uoft.github.io/2021/assets/readings/L01c.pdf), MK: p. 22-36 | 
| **Lecture&nbsp;3** | Jan 26 | Introduction to Python; basic linear algebra; evaluation methods |  [Colab](https://colab.research.google.com/drive/1GjFs_E9k-zbAXpOOUMScaDNJbIXCbpvU?usp=sharing) | DL: 2, [David Liu's CSC110/111 Course Notes](https://www.teach.cs.toronto.edu/~csc110y/fall/notes/)  |
| **Lecture&nbsp;4** | Feb 02  | ENSEMBLE-based methods; neural networks  |  [Slides](assets/slides/Lecture04.pdf)  |  DL: 6-8; RG: [Multilayer Perceptrons](https://csc413-uoft.github.io/2021/assets/readings/L02a.pdf), [Backpropagation (quite technical)](https://csc413-uoft.github.io/2021/assets/readings/L02b.pdf)  | Assignment #1 Due
| **Lecture&nbsp;5** | Feb 09  | Supervised learning; Python tutorial for supervised learning practice  |  [Slides](assets/slides/Lecture05.pdf), [Colab](https://colab.research.google.com/drive/1cjYq1XL7qLrWa3qnSkFfdvV01Vxoxr0G?usp=sharing)  |   |
| **Lecture&nbsp;6** | Feb 16  | Unsupervised learning for clustering: K-means, Gaussian mixture models | [Slides](assets/slides/Lecture06.pdf)  | B: 9; RG: [Mixture Models](https://www.cs.toronto.edu/~rgrosse/courses/csc311_f21/readings/Mixture%20Modeling.pdf)  | Assignment #2 Due
| **Reading Week** | Feb 23  |   |  |   |
| **Lecture&nbsp;7** | Mar 02   | Unsupervised learning for clustering: auto-encoder, graph-based methods; Python tutorial for unsupervised learning practice  | [Slides](assets/slides/Lecture07.pdf), [Colab](https://colab.research.google.com/drive/1T-zM9rwGRZDn-xjtp20aactSraBIIP4w?usp=sharing) |  [Jaan Altosaar's VAE Tutorial](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/); [Introduction to VAEs (Kingma and Welling)](https://arxiv.org/abs/1906.02691)  |
| **Lecture&nbsp;8** | Mar 09   | Guest Lecturer: [Dr. Kiaren Campbell](https://www.camlab.ca) |  |   |
| **Lecture&nbsp;9** | Mar 16  | Guest Lecturer: [Dr. Joseph Cafazzo](https://ihpme.utoronto.ca/faculty-profile/joe-a-cafazzo/) |  |   |
| **Lecture&nbsp;10** | Mar 23  | Advanced deep learning methods for medical image analysis |  |  | Assignment #3 Due
| **Lecture&nbsp;11** | Mar 30  | Term project presentation |   |   |
| **Lecture&nbsp;12** | Apr 06   | Term project presentation |   |   |

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


