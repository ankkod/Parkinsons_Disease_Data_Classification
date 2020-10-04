# Parkinsons_Disease_Data_Classification

Ensemble Techniques Project

Data Description & Context: Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased. Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician Domain: Medicine Attribute Information: name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%) - MDVP jitter in percentage

MDVP:Jitter(Abs) - MDVP absolute jitter in ms

MDVP:RAP - MDVP Relative Amplitude Perturbation

MDVP:PPQ - MDVP five-point Period Perturbation Quotient

Jitter:DDP - Average absolute difference of differences between jitter cycles

MDVP:Shimmer - MDVP local shimmer

MDVP:Shimmer(dB) - MDVP local shimmer in dB

Shimmer:APQ3 - Three-point amplitude perturbation quotient

Shimmer:APQ5 - Five-point amplitude perturbation quotient

MDVP:APQ - MDVP n point amplitude perturbation quotient

Shimmer:DDA - Average absolute differences between the amplitudes of consecutive periods

NHR - (Noise-to-Harmonics Ratio) Measure of ratio of noise to tonal components in the voice

HNR - (Harmonics-to-Noise Ratio) Measure of ratio of noise to tonal components in the voice

status - Health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE - (Recurrence Period Density Entropy) nonlinear dynamical complexity measure

D2 - (Correlation Dimension) nonlinear dynamical complexity measure

DFA - (Detrended Fluctuation Analysis) Signal fractal scaling exponent

spread1, spread2 - Two nonlinear measures of fundamental frequency variation

PPE - (Pitch Period Entropy) nonlinear measures of fundamental frequency variation

Learning Outcomes:

● Exploratory Data Analysis

● Supervised Learning

● Ensemble Learning

Objective: Goal is to classify the patients into the respective labels using the attributes from their voice recordings

Steps and tasks:

    Load the dataset
    It is always a good practice to eye-ball raw data to get a feel of the data in terms of number of records, structure of the file, number of attributes, types of attributes and a general idea of likely challenges in the dataset. Mention a few comments in this regard
    Using univariate & bivariate analysis to check the individual attributes for their basic statistics such as central values, spread, tails, relationships between variables etc. mention your observations
    Split the dataset into training and test set in the ratio of 70:30 (Training:Test)
    Prepare the data for training - Scale the data if necessary, get rid of missing values (if any) etc
    Train at least 3 standard classification algorithms - Logistic Regression, Naive Bayes’, SVM, k-NN etc, and note down their accuracies on the test data
    Train a meta-classifier and note the accuracy on test data
    Train at least one standard Ensemble model - Random forest, Bagging, Boosting etc, and note the accuracy
    Compare all the models (minimum 5) and pick the best one among them
