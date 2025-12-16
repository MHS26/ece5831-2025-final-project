**ECE5831-2025-Final-Project**

**CNN-BASED DERMATOLOGICAL DECISION SUPPORT TOOL**

**Project Overview**
The goal of this project is to build a CNN-based Dermatological Decision Support Tool for automatic skin disease classification. The system was trained on the DermNet dataset, which contains dermatoscopic images classified into various skin disease classes.

**Dataset**
The Project dataset consists of 6 classes of images:

Psoriasis pictures / Lichen Planus (1405 images)
Seborrheic Keratoses (1371 images)
Tinea / Ringworm / Fungal Infections (1300 images)
Eczema (1235 images)
Warts / Molluscum / Viral Infections (1086 images)
Acne / Rosacea (840 images)
The images were split into training (70%), validation (20%), and test (10%) sets.

Model Selected
->VGG16
    Base model: Pretrained on ImageNet.
    Training stages:
                    Stage 1: Classifier head trained while freezing the base layers.
                    Stage 2: Fine-tuning of the last few layers for better performance.

**Below are the links to access everything related to the project**
 
Presentation Slides: (Drive) https://drive.google.com/drive/u/0/folders/1mbpPH4v99wenjakP1V6jex8XgmnD3W5s
Report: (Drive) https://drive.google.com/drive/u/0/folders/1mbpPH4v99wenjakP1V6jex8XgmnD3W5s
Dataset: (Drive) https://drive.google.com/drive/u/0/folders/1mbpPH4v99wenjakP1V6jex8XgmnD3W5s

The Drive link provided consists of the Presentation slides, Final report and both the Dataset(Initial full DermNet and Split data)