<div style="text-align: center;">
  <img height="200px" src="images/outlogo.png" alt="Logo">
  <h1>Attendo</h1>
  <p>Attendance System based on Face Recognition for graduation project (2023)</p>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>Features ✨</h2>
  <ul style="list-style-type: none; padding-left: 20px;">
    <li>📷 Take Attendance with Face Recognition</li>
    <li>🔢 Take Attendance with QR Code and ID</li>
    <li>📊 Generate Reports</li>
    <li>🔄 Automating Attendance Tracking Process</li>
    <li>📋 Admin Dashboard</li>
    <li>📘 API Docs</li>
    <li>📱 Mobile Application</li>
    <li>🌐 Cross-platform</li>
  </ul>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>Background 📚</h2>
<h3>Smart Attendance System with Face Recognition and QR Codes <a href="#ref-1">[1]</a> </h3> 
  <p>A research study by Singh et al. (2018) proposed a smart attendance system that integrated face recognition and QR codes for tracking attendance in a university setting. The system achieved high accuracy and significantly reduced the time required for attendance-taking compared to traditional manual methods.</p>

  <h3>Effectiveness of RFID-Based Smart Attendance System</h3>
  <p>Sahu and Bhatt (2018) examined the effectiveness of an RFID-based smart attendance system in a manufacturing company. The study found that the system led to a remarkable reduction in absenteeism and improved attendance tracking accuracy and efficiency.</p>

  <h3>Impact of Smart Attendance System on Student Attendance and Academic Performance</h3>
  <p>A study by Khan and Ahmed (2019) investigated the impact of a smart attendance system on student attendance and academic performance. The findings revealed that the system positively influenced attendance rates, particularly among previously absent or tardy students. Moreover, it correlated with improved academic performance, with students attending more classes achieving higher grades.</p>

  <h3>Smart Attendance System with Face Recognition and Deep Learning</h3>
  <p>Han et al. (2019) developed a smart attendance system using face recognition and deep learning techniques. The system exhibited superior accuracy even with large datasets and challenging lighting conditions, making it a robust solution for attendance tracking.</p>

  <h3>Biometric-Based Smart Attendance System in Educational Institutions</h3>
  <p>Alshehri and Drews (2020) conducted a study comparing a biometric-based smart attendance system with traditional attendance tracking methods in educational institutions. The results demonstrated that the smart system outperformed conventional methods, offering better accuracy, efficiency, and user satisfaction among students and teachers.</p>

  <h3>Enhancing Attendance Accuracy and Efficiency in Primary Schools</h3>
  <p>Tsoi et al. (2019) explored the use of a smart attendance system in a primary school setting. The study revealed that the system improved attendance accuracy and reduced the time required for attendance-taking, making it beneficial for educational institutions.</p>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>Architecture 🏛️</h2>
  <img src="images/archi.png" alt="Architecture" style="max-width: 100%; display: block; margin: 20px auto;">
  <p>The smart attendance system consists of various modules, each playing a crucial role in its operation. Here are the key modules and their functions:</p>

  <table style="width: 100%; border-collapse: collapse;">
    <tr>
      <th>Module</th>
      <th>Description</th>
    </tr>
    <tr>
      <td>Face Recognition Module</td>
      <td>A container for facial recognition that serves a Face Embedding Model and a Face Classification Model. The Face Embedding Model transforms facial images into high-dimensional numerical representations (embeddings), enabling efficient face recognition and similarity comparisons. The Face Classification Model discriminates between different individuals and accurately recognizes known faces.</td>
    </tr>
    <tr>
      <td>Web Server Module</td>
      <td>A container that hosts the backend server, handling incoming requests from clients (such as web browsers) and serving responses over the internet. It manages communication protocols and processes requests.</td>
    </tr>
    <tr>
      <td>Application API Module</td>
      <td>A software component that handles incoming requests from clients and serves responses over the internet. It manages communication protocols and processes requests.</td>
    </tr>
    <tr>
      <td>Image Store Module</td>
      <td>A file system module for managing and serving the system's images, facilitating efficient image storage and retrieval.</td>
    </tr>
    <tr>
      <td>PostgreSQL Database Module</td>
      <td>A container Database Management System that stores information about the system resources (e.g., attendees, instructors, subjects) in records in a table format.</td>
    </tr>
    <tr>
      <td>Front End Application</td>
      <td>Software used by system users (attendees, instructors, and admins) to interact with the system through an easy-to-use interface, facilitating seamless user experience.</td>
    </tr>
    <tr>
      <td>Mobile Application</td>
      <td>A mobile application built using Flutter [1] that enables taking attendance using face recognition and QR code technologies. It utilizes the device's camera to capture and analyze facial features or scan QR codes for identification purposes.</td>
    </tr>
    <tr>
      <td>Dashboard Application</td>
      <td>A GUI that serves as an administrative tool for managing the system resources. It provides functionalities for adding new users, updating existing data, deleting records, and performing other administrative tasks through a user-friendly interface.</td>
    </tr>
  </table>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>Diagrams 📊</h2>

  <h3>Usecase Diagram</h3>
  <img src="images/usecase.png" alt="Usecase Diagram" style="max-width: 100%; display: block; margin: 20px auto;">
  
  <h3>Sequence Diagram 1</h3>
  <img src="images/seq1.png" alt="Sequence Diagram 1" style="max-width: 100%; display: block; margin: 20px auto;">
  
  <h3>Sequence Diagram 2</h3>
  <img src="images/seq2.png" alt="Sequence Diagram 2" style="max-width: 100%; display: block; margin: 20px auto;">
  
  <h3>Class Diagram</h3>
  <img src="images/classdiagram.png" alt="Class Diagram" style="max-width: 100%; display: block; margin: 20px auto;">
  
  <h3>Database Schema</h3>
  <img src="images/db.png" alt="Database Schema" style="max-width: 100%; display: block; margin: 20px auto;">
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>DataSets 📊</h2>
  
  <h3>LFW Dataset</h3>
  <p>Description: Labeled Faces in the Wild (LFW) is a popular benchmark dataset in face recognition research.</p>
  <p>Statistics: Contains around 13,000 images of 5,749 unique individuals.</p>
  
  <h3>Microsoft Artificial Dataset</h3>
  <p>Description: The Microsoft Artificial Dataset comprises a significant number of artificially generated face images.</p>
  <p>Statistics: The DigiFace1M subset of the dataset contains 1 million synthetic face images.</p>
  
  <h3>Personal Dataset</h3>
  <p>Description: The Personal Dataset includes images of 7 individuals captured specifically for this project.</p>
  <p>Statistics: 10 images per person, totaling 70 images.</p>
  
  <h3>Celebrity Dataset</h3>
  <p>Description: The Celebrity Dataset consists of images of 10 well-known celebrities from various sources.</p>
  <p>Statistics: 10 images per celebrity, totaling 100 images.</p>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>Development 🚀</h2>

  <h3>-  Classification Model 🏆</h3>
  <p>In our experiment, we explored the performance of four different classification models: EfficientNetB0, EfficientNetB2, VGGFace [5], and ResNet50 [6]. We evaluated these models on three distinct datasets: LFW, Celebrity, and Personal. Each dataset provided a unique set of challenges and variations in facial images.</p>
  <p>🔍 We systematically combined each model with every dataset to observe the resulting accuracy and loss. By examining the combination of models with different datasets, we aimed to understand the strengths and weaknesses of each model in different contexts. </p>
  <p><strong>In the following table, we trained the models for 50 epochs and observed:</strong></p>
  <img src="images/exp.png" alt="Experiment Results" style="max-width: 100%; display: block; margin: 20px auto;">
  <p>📈 Based on our comprehensive evaluation of the four classification models—EfficientNetB0, EfficientNetB2, VGGFace, and ResNet50—in combination with the LFW, Celebrity, and Personal datasets, we have determined that EfficientNetB2 is the most suitable model for our intended application. Through rigorous analysis, we found that EfficientNetB2 consistently achieved high accuracy and demonstrated remarkable performance across multiple datasets. </p>
  <p>💪 EfficientNetB2 exhibited superior results on both the Celebrity and Personal datasets, indicating its ability to capture intricate facial features and adapt well to various image variations. Its impressive performance, combined with its efficiency in terms of computational resources, makes EfficientNetB2 an ideal choice for our facial recognition task. </p>
  <p>✅ Considering the importance of accuracy, generalization capabilities, and computational efficiency, we have made an informed decision to employ EfficientNetB2 as our primary classification model for the proposed application. This selection ensures a reliable and efficient facial recognition system that can effectively handle diverse real-world scenarios. </p>
  
  <p><strong>Test Accuracy for EfficientNet-B2 on the three datasets:</strong></p>
  <img src="images/acc.png" alt="Test Accuracy" style="max-width: 100%; display: block; margin: 20px auto;">
  
  <p><strong>Test Loss for EfficientNet-B2 on the three datasets:</strong></p>
  <img src="images/loss.png" alt="Test Loss" style="max-width: 100%; display: block; margin: 20px auto;">
  <h3>- Embedding 🧠</h3>
<p>🎭 As another powerful technique, we delved into face embedding—a process that transforms a face image into a high-dimensional feature representation. This representation, known as an embedding, captures the unique characteristics of a face and facilitates measuring similarities or distances between faces. </p>

<p>🔍In our experiments, we harnessed the potential of a Siamese network architecture combined with the triplet loss function. The Siamese network comprises three identical subnetworks, sharing the same weights. Taking three face images as input, it produces their corresponding embeddings. The triplet loss function then trains the network by minimizing the distance between an anchor face embedding and a positive (same identity) face embedding, while maximizing the distance between the anchor face embedding and a negative (different identity) face embedding. </p>

<img src="images/emb.png" alt="Face Embedding" style="max-width: 100%; display: block; margin: 20px auto;">

<p><strong>Triplet Loss Formula:</strong></p>
<p>loss = max(0, ||A-P||^2 - ||A-N||^2 + α)</p>
<p>where:</p>
<ul style="list-style-type: disc; padding-left: 20px;">
  <li>A: Anchor embedding vector</li>
  <li>P: Positive embedding vector</li>
  <li>N: Negative embedding vector</li>
  <li>α: Margin that determines the minimum separation between positive and negative pairs</li>
</ul>

<p>😕 The naive approach in face recognition involves randomly selecting triplets for training the embedding model without considering the difficulty of the samples. In this case, the model learns from triplets that may not provide sufficient discriminative information, leading to suboptimal performance. </p>

<p>🚀 To overcome this challenge, we embraced the online triplet [19] approach, dynamically selecting hard triplets during training. A hard triplet consists of an anchor, a positive (same identity) sample, and a negative (different identity) sample that are challenging to distinguish. By focusing on hard triplets, the model is pushed to learn more robust and discriminative embeddings. </p>

<p>🏆 As our experiments progressed, we encountered difficulties in achieving optimal performance solely with our custom-built network architecture. To overcome this, we decided to harness the power of transfer learning and adopted the FaceNet pretrained model. FaceNet is a widely recognized face recognition model trained on a large-scale dataset, demonstrating outstanding performance in embedding faces into a high-dimensional space. By leveraging the FaceNet model, we achieved higher accuracy and benefited from its robust features. </p>

  
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2 >Screenshots 📸</h2>

  <h2 align="center">API Docs</h2>
  <img width="1000px" src="images/api-docs.png" alt="API Image">

  <h2 align="center">Dashboard</h2>
  <table>
    <tbody>
      <tr>
        <td align="center"><img width="2000px" src="images/dashboard-1.png" alt="Dashboard Image 1"></td>
        <td align="center"><img width="2000px" src="images/dashboard-2.png" alt="Dashboard Image 1"></td>
        <td align="center"><img width="2000px" src="images/dashboard-3.png" alt="Dashboard Image 1"></td>
      </tr>
      <tr>
        <td align="center"><img width="2000px" src="images/dashboard-4.png" alt="Dashboard Image 1"></td>
        <td align="center"><img width="2000px" src="images/dashboard-5.png" alt="Dashboard Image 1"></td>
      </tr>
    </tbody>
  </table>

  <h2 align="center">Mobile Application</h2>
  <table>
    <tbody>
      <tr>
        <td align="center"><img width="1000px" src="images/application-1.png" alt="Application Image 4"></td>
        <td align="center"><img width="1000px" src="images/application-2.png" alt="Application Image 4"></td>
        <td align="center"><img width="1000px" src="images/application-3.png" alt="Application Image 4"></td>
        <td align="center"><img width="1000px" src="images/application-4.png" alt="Application Image 4"></td>
      </tr>
      <tr>
        <td align="center"><img width="1000px" src="images/application-5.png" alt="Application Image 5"></td>
        <td align="center"><img width="1000px" src="images/application-6.png" alt="Application Image 5"></td>
        <td align="center"><img width="1000px" src="images/application-7.png" alt="Application Image 5"></td>
        <td align="center"><img width="1000px" src="images/application-8.png" alt="Application Image 5"></td>
      </tr>
      <tr>
        <td align="center"><img width="1000px" src="images/application-9.png" alt="Application Image 6"></td>
        <td align="center"><img width="1000px" src="images/application-10.png" alt="Application Image 6"></td>
        <td align="center"><img width="1000px" src="images/application-11.png" alt="Application Image 6"></td>
        <td align="center"><img width="1000px" src="images/application-12.png" alt="Application Image 6"></td>
      </tr>
    </tbody>
  </table>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2 style="text-align: center;">Meet the Brilliant Minds Behind the Project 🌟</h2>
  <div style="display: flex; justify-content: space-around; margin: 50px 0;">
    <div style="text-align: center;">
      <a href="https://www.github.com/minasaad47">
        <img src="images/author1.png" alt="Author 1" width="150px" height="150px" style="border-radius: 50%;">
        <br>
        <strong>@minasaad47</strong>
      </a>
    </div>
    <div style="text-align: center;">
      <a href="https://www.github.com/mina329">
        <img src="images/author2.png" alt="Author 2" width="150px" height="150px" style="border-radius: 50%;">
        <br>
        <strong>@mina329</strong>
      </a>
    </div>
  </div>
</div>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<div>
  <h2>References 📚</h2>
  <ul style="list-style-type: none; padding-left: 20px;">
    <li>
      [1] <a name ="ref-1"> Singh, A., Dey, A., Dutta, S., Pal, U., & Bhattacharya, U. (2018). A Smart Attendance System using Face Recognition and QR Codes. International Journal of Computer Applications, 179(24), 20-25.</a>
    </li>
    <li>
      [2] <a name="ref-2">Sahu, S. K., & Bhatt, R. (2018). An RFID-Based Smart Attendance System in Manufacturing Companies. International Journal of Innovative Research in Science, Engineering, and Technology, 7(4), 5133-5137.</a>
    </li>
    <li>
      [3] <a name="ref-2"> Khan, M. F., & Ahmed, M. K. (2019). Impact of Smart Attendance System on Student Attendance and Academic Performance. International Journal of Research in Engineering, Science and Management, 2(3), 90-95.</a>
    </li>
    <li>
      [4] <a name="ref-2"> Han, X., Li, B., Li, T., & Jiang, G. (2019). A Smart Attendance System using Face Recognition and Deep Learning Techniques. 2019 International Conference on Artificial Intelligence and Computer Science (AICS).</a>
    </li>
    <li>
      [5] <a name="ref-2"> Alshehri, S., & Drews, P. (2020). Evaluation of Biometric-Based Smart Attendance System in Educational Institutions. International Journal of Computer Applications, 174(34), 10-14.</a>
    </li>
    <li>
      [6] <a name="ref-2"> soi, K. H., Chan, C. S., & Au, O. K. (2019). Smart Attendance System in Primary Schools. International Journal of Computer Applications, 182(35), 42-47.</a>
    </li>
  </ul>
</div>



2023 graduation project
