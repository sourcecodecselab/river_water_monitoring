# river_water_monitoring

Program 1:

Objective : Assigning labels to the unlabeled lab dataset.
Input : wqi without labels.csv /* Lab dataset without labels */
Run command: python overall.py /* On python GUI or Console*/



Program 2:

Objective : Assigning labels to the unlabeled sensory dataset.
Input :
1 LabWithLabels.csv /* Lab dataset with labels */
2 Sensor final without label.csv /* Sensory dataset without labels */
Run command: python SensoryMappingLabels.py


Program 3:

Objective : Training deep learning model with labeled sensory dataset.
Input : Sensor final with labels 22nov.csv /* Sensory dataset with labels */
Run command: python Final training without NoiseLoss.py
Output : Accuracy of the build classifier /* Sensory dataset with labels
*/


Program 4:


Objective : Test accuracy of model on unknown data instances.
Input : TestCheck.csv /* Test file without labels */
Run command: python TestLabelPrediction.py


