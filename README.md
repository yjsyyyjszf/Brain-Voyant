# Brain Pattern Classifier
A tool for classifying whole-brain patterns from fMRI RAW DICOM data in real-time (and offline) based on machine learning methods.
We use supervised whole-brain data, without prior knowledge of regions of interest (ROIs) to converge on the relevant voxels. 
i.e., our tool will figure out which voxels are contributing to the task and choose them automatically.
The Visual C# code enables you to build an application that uses a .prt protocol and accepts raw-based Dicom files from turbo-brain-voyager for the purpose of creating a machine learning classifier using SVM and IG for feature selection.
it does a bunch of other things, please look at the following papers for details. 
if you plan on using this code for experimental purposes and write a paper, please cite paper #4.

Objective: We have developed an efficient generic machine learning tool for real-time functional magnetic resonance imaging whole-brain classification, which can be used to explore novel brain-computer interface (BCI) or advanced neurofeedback protocols. 
Approach: We use information gain for isolating the most relevant voxels in the brain and a support vector machine classifier. Using our system subjects can control an avatar in a virtual environment. 
Main results: We show good classification results for motor execution, motor imagery, and visual categories. In addition, we allowed six subjects to perform real-time cue-based motor-execution-BCI while embodied in a 3D avatar as well as a free choice navigation task in a virtual environment. The system allowed the subjects to control the 3D avatar using four actions: left turn, right turn, forward and rest for stopping movement. 
Significance: We show an accuracy of 90\% or more can be achieved in execution and imagery classification in a cue-based BCI protocol, and that this method is superior to a previous method based on regions of interest in terms of BCI accuracy and delay. We show that the number of features (voxels) used for classification can be reduced without losing accuracy, and suggest a method for determining the optimal number of features in advance. We show that our system can be used to further extend the amount of classes. Finally, we show that it is possible to use the slow peaking blood-oxygen-level dependent signal for real-time BCI using a delay of only 2 seconds, in a free choice BCI task. 
                                                                                                                           
** please note that there are some missing libraries, which will be documented and added later.

1. Cohen, O, Keith, F, Kheddar, A, Koppel, M, Malach, R, & Friedman, D (2017). Real-time fMRI Control of a Humanoid Robot using Two Brain Networks Simultaneously: A Pilot Study. 7th Graz Brain-Computer Interface Conference, 2017.
2. Cohen, O, Doron D, Koppel, M, Malach, R, & Friedman, D (2017). High Performance in Brain-Computer Interface Control of an Avatar Using the Missing Hand Representation in Long Term Amputees. 8th International IEEE EMBS Conference on Neural Engineering Shanghai, China, May 25 - 28, 2017.
3. Cohen, O, Koppel, M, Malach, R, & Friedman, D (2014). Controlling an avatar by thought using real-time fMRI. Journal of neural engineering, 11(3), 35006.
4. Cohen, O, Ramot, M, Malach, R, Koppel, M, & Friedman, D (2014). A Generic Machine-Learning Tool for Online Whole Brain Classification from fMRI.
5. Cohen, O, Druon, S, Lengagne, S, Mendelsohn, A, Malach, R, Kheddar, A, & ... (2014). fMRI-based robotic embodiment: Controlling a humanoid robot by thought using real-time fMRI. PRESENCE: Teleoperators and Virtual Environments, 23(3), 229-241. (Appeared on the journal’s cover)
6. Cohen, O, Druon, S, Lengagne, S, Mendelsohn, A, Malach, R, Kheddar, A, & ... (2012). fMRI robotic embodiment: a pilot study. Biomedical Robotics and Biomechatronics (BioRob), 2012 4th IEEE RAS & EMBS.
7. Cohen, Ori, Malach, Rafael, Koppel, Moshe, & Friedman, Doron (2016). Can amputees control a brain-computer interface with their missing hand?. Proceedings of the 6th International Brain-Computer Interface Meeting ....
8. Cohen, D, Malach, O and, Koppel, R and, & Friedman, M and (2015). Can amputees control a brain-computer interface with their missing hand?. The 24th Israeli Society for Neuroscience Annual Meeting.
9. Cohen, O, Mendelsohn, A, Koppel, M, Druon, S, Lengagne, S, Kheddar, A, & ... (2013). Robotic re-embodiment: controlling a humanoid robot by thought using real-time fMRI. JOURNAL OF MOLECULAR NEUROSCIENCE 51, S29-S, 29.
10. Friedman, D, Cohen, O, Mendelsohn, A, Drai, D, Koppel, M, & Malach, R (2012). Controlling an avatar by thought using real-time fMRI. JOURNAL OF MOLECULAR NEUROSCIENCE 48, S36-S, 37.
11. Ori Cohen, Avi Mendelsohn, Rafael Malach, Doron Friedman. Controlling an Avatar by Thought using Real-time Functional Magnetic Resonance Imaging. 18th Annual Meeting of the Organization for Human Brain Mapping Beijing, China, 2012.
