# IRMI

Intelligent Remote Medical Imaging
The idea of this project is to have a collection of intelligent disease detecting systems (medical imaging based for now) AIO. This could be a very useful tool for doctors (Consultation and advisory) and patients (advisory). We can have such a system in all the hospitals around the world, ultimately beneficial for the humanity.

Terminator Pun alert: Basically, a skynet for doctors!

**ABSTRACT**

Many patients die every year due to lack of treatment or error in diagnosis of a certain disease. Developing an artificial intelligence based detection system can help in early diagnosis and treatment of many diseases.
In this paper, we present a potential approach to having a collection of disease detection mechanisms using deep learning which utilize medical imaging for classification. To demonstrate this experiment we use two of the most major diseases detectable using medical imaging: Tuberculosis (TB) and Breast Cancer.
We have used CNN architecture and compared the performance of the network using three different activation functions. In the case of Breast Cancer, we used the INbreast dataset which has a total of 115 cases (410 images) of which 90 cases are from women with both breasts (4 images per case) and 25 cases are from mastectomy patients (2 images per case). Our network achieves an accuracy of 94.51% in predicting the cancer in breast. In the case of TB, we used the Shenzhen dataset which has 326 normal x- rays and 336 abnormal x-rays showing various manifestations of tuberculosis. Our network achieves an accuracy of 96% in predicting TB in chest X-rays.
To further demonstrate our experiment we have created an API (Application Programming Interface) for both of our detection programs which uses the Flask framework on Python. Using an API we can utilize these detection programs in any OS (operating system), program or device which can be connected to the internet. For public consumption we’ve created a simple front-end web and mobile application based on PHP and Swift languages, respectively.

**NOTICE**

The repo is still under construction so please hold your horses.
Looking for contributors! Need more data, computer scientists, data scientists, doctors and funds for collaboration!
The project only supports breast cancer detection and tuberculosis detection for now (which also need more accuracy). I hope we can expand on that.

**HOW TOs**

Run app.py to start the web server.
Mammogram processing can take upto 5 minutes given your processing power.
