Readme

This project summarizes the development and selection of a machine learning model. 
The candidate models were trained, validated and tested on a data set consisting of 
human movement during weight-lifting exercises, kindly made available by Eduardo Velloso 
and colleagues (see Velloso et al., 2013, [http://groupware.les.inf.puc-rio.br/work.jsf?p1=11201] 
for further details). The dependent measure was error type. Participants performed unilateral 
dumbbell bicep curls with a 1.25 kg dumbell, in one of five ways: 

(A) correctly, 
(B) throwing elbows forward, 
(C) lifting only halfway, 
(D) lowering only halfway, 
(E) throwing hips forward. 

These error type codes are listed in 
column classe in the data set. Movement data is provided in 152 columns, detailing various 
aspects of the trajectories, velocities and distributional characteristics of movements 
recorded by sensors on (i) the upper arm, (ii) forearm, (iii) waist, and (iv) dumbbell. 
Additionally, the first 6 columns of the data set provide metadata: participant identifiers 
and various formats of time information. The data set is available for download here: 

training data [https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv] 
test data [https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv]

Additional information from the research group who collected it is available at the 
project website [http://groupware.les.inf.puc-rio.br/har].