# ML for sounds classification

Assignment description:

This dataset corresponds to an auditory fMRI study focusing on subcortical responses. The response elicited by sounds belonging 
to seven categories was measured in voxels across four regions of interest (ROI) in ten subjects. The sound labels corresponds to: 
label 1 = speech, label 2 = voice, label 3 = animal, label 4 = music, label 5 = tool, label 6 = nature, label 7 = monkey. 
The regions of interest are:  Medial geniculate body (MGB), Superior olivary complex  (SOC), Cochlear nucleus (CN) and 
Inferior colliculus (IC). The article describing the experimental details can be found at https://elifesciences.org/articles/48932. 
The dataset is divided in training and test data.  The initial goal of the assignment is to develop a subject specific 
(trained and tested in each subject separately) multiclass classifier between the seven categories at each of the regions of interest. 
Give that classes are balanced the chance level is 1/7. 

Folder structure:

Mat files one for each ROI. Each mat file contains: training data (Xtr) of size: 126 sounds x num of voxels(features) and 
test data (Xte) of size: 42 test sound x num of voxels (features) and the corresponding training and test labels. This is a 
difficult classification task due to the low quality of the fMRI signal in the brainstem. We do not expect to obtain high values 
for the classification accuracy. 

MSB1011 - Machine Learning and Multivariate Statistics
Final Assignment

### Author 

Giorgia Del Missier
i6292403

