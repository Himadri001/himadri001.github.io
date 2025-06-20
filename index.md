---
layout: homepage
---
<h2 class="h2-color" style="margin-bottom:4px;"> About Me</h2>
<p class="par-color" style="text-align: justify">I am currently pursuing my Master’s in Computer Science at Georgia Southern University, where I serve as a Research Assistant. My research focuses on developing AI-driven solutions in the fields of medical imaging and speech pathology. Presently, I’m working on:

Breast Cancer Segmentation using deep learning architectures and Voice Disorder Classification and Detection using deep transformer-based methods for clinical voice analysis
<br><br>
I bring five years of industry experience from Bangladesh, where I developed scalable, distributed transportation and logistics platforms serving millions of users in real time. I hold a Bachelor’s degree in Computer Science from BRAC University, where my background in competitive debating sharpened my logical thinking—an ability that now fuels both my engineering and research pursuits.

 </p>

<!-- <h2 class="h2-color" style="margin-bottom:4px"> Research Interests </h2> -->

<!-- <ul>
  <li class="par-color">Software Engineering</li>
  <li class="par-color">Human Computer Interaction</li>
  <li class="par-color">High Performance Computing</li>
</ul> -->


<h2 class="h2-color" style="margin-bottom:4px"> Current Research </h2>
<h3 class="h2-color" style="margin-bottom:3px"> Deep Multi Magnification Network for Multi-Class Breast Cancer Tissue Segmentation</h3>
<p class="par-color" style="text-align: justify">Currently, I am studying Multi-Encoder Multi-Decoder Multi-Concatenation network which takes image patches from  breast cancer whole side image at multi-magnification level as input and outputs the classification and segmentation of the tissue subtypes. Currently, the model can segment 6 classes of tissue subtypes. My objective is to retrain the network with publicly available datasets (CAMELYON16,17) and to include more class predictions to increase the accuracy of the pathological examination of breast cancer.</p>

<h3 class="h2-color" style="margin-bottom:3px">Voice Disorder Detection and Classification Using Deep Transformer Based Models</h3>
<p class="par-color" style="text-align: justify">I am exploring the use of transformer-based deep learning models for the early detection of speech and communication disorders. This research aims to improve diagnostic accuracy and intervention timelines by leveraging large-scale speech datasets and advanced sequence modeling techniques, contributing to more accessible and intelligent speech-language pathology tools.</p>


<h2 class="h2-color"  style="margin-bottom:8px">Professional Experience</h2>
<h3 class="h2-color" style="margin-bottom:8px">Engineering Manager MGH Logistics Ltd. MGH Group [Jan'23 to Present]</h3>
<p class="par-color" style="margin-bottom:8px; text-align: justify;">Starting of the year 2024, I was appointed as the engineering manager of a logistics and order management platform( <strong><a href="https://drive.google.com/file/d/1nhzC6554nGKg1rjZufO3UVJvUGfPqoj9/view?usp=sharing"><i style="color:#e74d3c">Learn More</i></a></strong>), V-SOL (A Infor Nexus Product) for MGH freight forwarding wing. Currently, I am leading the `Shipment Tracking` project for sea and air freight. I have developed a standalone microservice which pulls ship and container tracking information from the carrier's system and posts it to V-SOL through Infor ION middleware. I have followed the Domain-Driven-Design with an API gateway to connect with the carriers. The API is consumed periodically via a background/cron job. Users of the platform can now view the location of their shipment on a world map with shipment information such as the date and time of departure from the origin port, transition port arrival-departure and destination arrival. </p>

<p class="par-color" style="margin-bottom:22px; text-align: justify;">
Furthermore, I am working on developing an Exception Management service for V-SOL. The service will notify the buyer and LSP users from MGH in real time if any exception is taking place during the total shipment process. The exceptions rules can be set by the buyer and easily changable through an admin portal. To notify we are using Event-Bus architecture and the information will be sent by organisation messaging channels such as Microsoft Teams.</p>



<h3 class="h2-color" style="margin-bottom:8px">Senior Software Engineer, OBHAI Solutions Ltd. [Jan'21 to Dec'22]</h3>
<p class="par-color" style="margin-bottom:8px; text-align: justify;">At Obhai, I contributed to the system scaling to serve one million customers daily. Moreover, improved the monolithic system by creating modular and reusable functions. Furthermore, I introduced the Master-Slave architecture for database servers which improved the traffic management of the platform.</p>

<p class="par-color" style="margin-bottom:8px; text-align: justify;">
Additionally, I was one of the core developers of the `Cashless Payment` project. I have developed the direct debit feature so that the users do not have to initiate the payment manually. The payment is deducted from the selected payment method after ending the ride automatically. To prevent unwanted cases I have added a retry mechanism for failed transactions. I have also contributed to the `Payout` project. In Obhai, drivers get their commission in real-time after completing the ride which has increased the trust and reliability of the platform. I developed the function to calculate the driver's balance and the amount to be disbursed through payout. It ensured the correctness of the transactions.</p>

<p class="par-color" style="margin-bottom:8px; text-align: justify;">
During that time I was involved in building an ML-based fare engine which utilises the Obhai customer profile data and provides dynamic taxi fares based on the customer's historical journey with Obhai. The service was launched in the last quarter of 2022. The service eventually increased the number of daily rides by 13%.  
<p class="par-color" style="margin-bottom:8px; text-align: justify;">
<strong><a href="https://big-ball-477.notion.site/Real-Time-Fare-Prediction-Model-186a0571a31b4fd8993b049f04704356?pvs=4"><i style="color:#e74d3c">Taxi Fare Predictor</i></a></strong></p>

<p class="par-color" style="margin-bottom:8px; text-align: justify;">
In addition to my technical contributions, I led a backend team and regularly conducted sprint planning, code reviews, and internal technical troubleshooting. Aside from that, I took an active role in the hiring process and training the new joiners.</p> 

<p class="par-color" style="margin-bottom:8px; text-align: justify;">
<strong><a href="http://www.obhai.com"><i style="color:#e74d3c">Company Website  </i></a></strong> </p>
<p class="par-color" style="margin-bottom:8px; text-align: justify;">
<strong><a href="https://drive.google.com/file/d/16vC21IPxDQdZeD3h-70zP2Ezbx2d23h4/view?usp=drive_link"><i style="color:#e74d3c">App Demo</i></a></strong></p>



<h3 class="h2-color"  style="margin-bottom:8px;">Software Engineer, OBHAI Solutions Ltd. [Apr'19 to Dec'21]</h3> 
<p class="par-color" style="margin-bottom:8px; text-align: justify;">I joined Obhai right after my graduation as a backend developer. My first project was A Dynamic Commission Module of Obhai drivers. I built a tool to define commission rates for the drivers based on geo-location, service type and performance score. The method later on was adopted by other ride-sharing platforms in the market.</p>
<p class="par-color" style="margin-bottom:8px; text-align: justify;">
Aside from that, I worked on developing administrative tools and BI reports.</p>

<!-- ## News

- **[Feb 2020]** Our paper about incremental learning is accepted to [CVPR 2020](http://cvpr2020.thecvf.com/).
- **[Feb 2020]** We will host the [ACM Multimedia Asia 2020](https://mmasia2020.org/) conference in Singapore!
- **[Sep 2019]** Our paper about few-shot learning is accepted to [NeurIPS 2019](https://nips.cc/Conferences/2019).
- **[Mar 2019]** Our paper about few-shot learning is accepted to [CVPR 2019](http://cvpr2019.thecvf.com/). -->




<!-- <h2 class="h2-color">Selected Projects</h2> -->
<!-- Projects -->
<h2 class="h2-color" style="margin-top:24px; margin-bottom:4px">Projects</h2>

<h4 class="h2-color" style="margin : 0">Graph-Based Analysis of Data Relationships in Privacy Policies</h4>
<p class="par-color" style="margin-top: 0; margin-bottom:12px; text-align: justify;">This project investigates how major e-commerce platforms describe user data collection and processing in their privacy policies. Using outputs from the Polygrapher tool, we extracted COLLECT and SUBSUM relationships and semantically unified them using sentence embeddings. The processed relationships were then structured, merged, and visualized into a generalized graph across providers like Walmart, Publix, Target, Temu, and Instacart. The final knowledge graph reveals recurring data practices and helps compare privacy approaches across services.

Key Technologies: NetworkX, Neo4j, Sentence Transformers, GraphML, Excel Automation
Core Features: Data relationship extraction, semantic normalization, cross-provider pattern analysis
Status: Submitted to ASONAM 2025</p>

<h4 class="h2-color" style="margin : 0">Drowsy Drivers</h4>
<p class="par-color" style="margin-top: 0; margin-bottom:12px; text-align: justify;">A Computer Vision and Deep Learning based program which detects drowsy drivers while driving. The program uses OpenCV and Dlib's facial landmark detection algorithm to detect and segment eye regions from a real-time video stream. The model can detect drowsy eyes by measuring eye aspect ratio and trigger an alarm if the eyes are kept closed for 5 seconds continuously.</p>


<h4 class="h2-color" style="margin : 0">Stock Market Analysis and Forecasting</h4>
<p class="par-color" style="margin-top: 0; margin-bottom:12px; text-align: justify;">It is stock price analysis and forecasting project using Deep Learning (pytorch, gru). I have used the GRU model and Amazon, Google, Microsoft's timeseries stock data to perform forecasting of the companies stock values. <strong><a href="https://github.com/Himadri001/stock_forecasting"><i style="color:#e74d3c">Project Link</i></a></strong></p>

<h4 class="h2-color" style="margin : 0">Thesis</h4>
<p class="par-color" style="margin-top: 0; text-align: justify;">Detection of Acute Lymphocyte Leukemia (ALL) AND Its Type By Image Processing and Machine Learning. I have used ADL dataset includes signle slide images lukemia cancer and normal patient. <strong><a href="./assets/pdf/Thesis_Fall_18.pdf"><i style="color:#e74d3c"> Learn More</i></a></strong></p>


<h2 class="h2-color" style="margin-bottom:4px">Honours & Awards</h2>
  <ul>
    <li class="par-color">Awarded best idea in`Codeahead` hackathon by ShopUp, 2018.</li>
    <li class="par-color">BRAC University Vice Cancelor's Certifications for exceptional performance in academic and co-curricualr activities, 2015.</li>
  </ul>
<!-- ## Selected Talks

- **Learning to Self-Train for Semi-Supervised Few-Shot Classification**
  <br>
  NeurIPS Official Meetups
  <br>
  Beijing, China, December 2019 [[Slides](https://people.mpi-inf.mpg.de/~yaliu/files/learning-to-self-train-slides.pdf)]

- **Multi-Class Incremental Learning**
  <br>
  School of Computer Science and Engineering, Nanyang Technological University
  <br>
  Singapore, July 2019 [[Slides](https://people.mpi-inf.mpg.de/~yaliu/files/multi-class-incremental-learning.pdf)]

- **Meta-Transfer Learning for Few-Shot Learning**
  <br>
  School of Computing, National University of Singapore
  <br>
  Singapore, April 2019 [[Slides](https://people.mpi-inf.mpg.de/~yaliu/files/meta-transfer-learning-slides.pdf)]

## Services

- Co-organizer: [ACM MM Asia 2020](https://mmasia2020.org/).
- Conference Reviewers: [NeurIPS 2020](https://neurips.cc/Conferences/2020), and [CVPR 2020](http://cvpr2020.thecvf.com/).
- Journal Reviewers: [T-PAMI](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34), and [IJCV](https://www.springer.com/journal/11263). -->


<!-- <h2 class="h2-color" style="margin-bottom:4px">Test Scores</h2>
<ul>
  <li class="par-color"><strong>GRE(312)</strong> Quant: 165 | Verbal: 147 | AWA: 3.5</li>
  <li class="par-color"><strong> IELTS(7.5)</strong>Listening: 8 | Reading: 8 | Speaking: 7 | Writing: 7</li>
</ul> -->
