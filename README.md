### CS5567 Deep Learning Final Project Instructions (Spring 2024)

#### General Guidance:
- [x] Approach this project step-by-step; don't feel overwhelmed.
- [x] Assistance is available anytime; don't hesitate to ask for help.

#### Required Files:
- [ ] **Download**: Obtain "Final.zip", which includes necessary Jupyter Notebook (.ipynb) files.
- [ ] **Setup**: Load the provided scripts in Google Colab or your local Python workspace. If you need help setting up your workspace, please ask.
- [ ] **Data Handling**: Most data will be loaded via scripts; however, some data integration will be required. Numerous examples and helpful links are provided in the scripts.

#### Project Parts and Experiments:
- [ ] **Parts A & B**: Detailed in the Experiments table below.
- [ ] **Results Documentation**: Record and save all experimental results, noting configurations tested. Include both training and testing metrics. Visual representations (plots) of data are preferred over numerical tables.
- [ ] **Final Report** (1-2 pages): Summarize your findings from experiments in Parts A and B. Ensure proper terminology and include references where applicable.
- [ ] **Discussion and Video Presentation**: Provide a comprehensive explanation of your efforts, responses to the discussion questions, and a video presentation of your results. This video replaces the final exam and should be uploaded to Canvas.

### Detailed Experiments:

#### Part A: Utilizing Pre-Trained Feature Layers

1. **End-to-End Classification (Color Images)**
   - [ ] **Dataset**: CIFAR-10
   - [ ] **Task**: Build and train a custom image classification model.
   - [ ] **Approach**: Use informed decision-making rather than exhaustive grid search for setting hyperparameters.
   - [ ] **Results**: Track and record performance metrics. Save your model as it will be required for future experiments.

2. **Transfer Learning**
   - [ ] **Datasets**: CIFAR-10, CIFAR-100, Tiny ImageNet
   - [ ] **Task**: Implement transfer learning using provided pre-trained models (VGG19 and ResNet).
   - [ ] **Process**: For each model, freeze the base layers and train the top classification layer. Document each configuration and its outcomes.

3. **Fine-Tuning**
   - [ ] **Dataset**: Tiny ImageNet
   - [ ] **Task**: Fine-tune your model from Experiment 1 to this new dataset.
   - [ ] **Process**: Adjust and unfreeze your model, then retrain. Record how your model adapts to this more complex task.

4. **Memory Loss or Functional Gain**
   - [ ] **Task**: Evaluate if the fine-tuned model retains or improves performance on original tasks (e.g., CIFAR-10).
   - [ ] **Process**: Test your model on CIFAR-10 and analyze feature extraction or representation gains.

#### Part B: Segmentation and Style Transfer

1. **Localization**
   - [ ] **Source**: Find datasets formatted for TensorFlow Object Detection.
   - [ ] **Task**: Modify and apply a provided YOLO v8 script to a new dataset. Document performance and save relevant outputs.

2. **Segmentation with SegFormer**
   - [ ] **Process**: Tune the SegFormer model provided in the script on sample images from the included dataset. Record and analyze the segmentation performance.

3. **Generative Models - [ ] Style Transfer**
   - [ ] **Task**: Apply artistic styles to your selected images using the provided style transfer tools. Submit your favorite transformed images for a class contest.

#### Discussion Questions:
- [ ] Compare and discuss the training and testing performance across all experiments.
- [ ] Reflect on how each model performed and relate these observations to the course content.
- [ ] Consider the future of deep learning and its implications on emerging machine intelligence.