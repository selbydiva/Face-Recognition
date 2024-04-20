# Face-Recognition

This face-recogniiton program utilizes OpenCV as main library and also Tkinter for building user interface. The algorithm used for detecting and recognizing face is Local Binary Pattern. 

# Graphical User Interface (GUI)

This program is a graphical user interface (GUI)-based application. The GUI comprises three main buttons that looks like this :

<img width="208" alt="Screenshot 2024-04-20 at 10 30 57" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/94ac4508-680c-4bd2-8664-4809c15fa996">

Before we talk more about the GUI, there are thing prepared : 

--> A data file (.xlsx) to store all the names of corresponding face.
--> A folder to store all images for face training.

1. Tambah Identitas Wajah Baru button is used to add a new face identity, including a name for labeling and an extracted face image as an .xml file. When clicked, this button will display an entry box for entering the name.

   <img width="321" alt="Screenshot 2024-04-20 at 10 44 49" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/edd8ccb1-ce77-443d-89ba-a8a7a33221fa">

   <img width="258" alt="Screenshot 2024-04-15 at 20 51 56" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/3d555348-f5d1-4015-b2ad-394a53c84553">

2. Input Nama button for storing new added name to data file (.xlsx) and taking our images for training. The taken images will be stored in the prepared folder before.

  ![Untitled design](https://github.com/selbydiva/Face-Recognition/assets/154320650/4768a1e4-d202-4e6c-a72d-7ae62e7e3157)

  For each face, it will be taken 30 images of face detected only. The .xlsx file will looks like this : 

  <img width="176" alt="Screenshot 2024-04-20 at 11 11 36" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/588b00ba-8af9-49e5-8076-e5434ea0f891">

  Since the algorithm uses numeric for labeling each face identity, so we have to make 'Label' column that added automatically in this program.

3. Proses button is used for converting training images to numpy arrays stored as .xml file. This xml file placed in training images folder.

   ![Untitled design-9](https://github.com/selbydiva/Face-Recognition/assets/154320650/264b2f70-ec95-457a-94b5-3925364e6efe)

4. Mulai Video is button for starting real time video and also recognizing each face detected

   <img width="576" alt="Screenshot 2024-04-15 at 20 52 20" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/b51eb3ac-7bdc-4783-bc9c-a4b74a4a994b">

   <img width="785" alt="Screenshot 2024-04-15 at 20 45 49" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/db0aed5d-0eaf-47fc-8254-8a6641bc9bc6">

   <img width="594" alt="Screenshot 2024-04-15 at 20 53 34" src="https://github.com/selbydiva/Face-Recognition/assets/154320650/be3fad86-e342-4475-b1c1-9cd237750d12">

