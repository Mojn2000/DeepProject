#  README FOR PROJECT IN DEEP LEARNING

## PROJECT NAME:

Anomaly detection in time series data using autoencoders.

## STUDENTS: 

Ida B. Villesen (s174385), 
Mads E. Hansen (s174434)

## DESCRIPTION:

Use cheaply avaiable data from rental cars (specifically accelerometer info) to detect poor roads.

## CODE GUIDEDANCE:
To run the code please do the following:

1: Download the data from the link below (at the very bottom)

2: Mount google drive (or change header s.t. the data is read correctly)

3: Run "add_padding" to pre-process the data 

4: Run the desired model (e.g. RNN_v_1_1)

5: Run "Performance_plots" to compare performance of the models

## CODE VERSIONS:

1_1 -> AE, Bi-directional RNN (GRU)

1_3 -> AE, Uni-directional RNN (GRU)

2_0 -> Supervised, Uni-directional RNN (GRU)

## NB:

We used ~1gb of data. It is not possible to upload files larger than 25mb to a free github. The data is available here:

https://drive.google.com/drive/folders/1SS_IpHoa0S4WfVYzxabk8zFGLHGqmc6e
