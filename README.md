# AutoWCEBleedGen-Challenge
This repository consists of training, output obtained through model and related information. <br>

The weight files and results i.e., confusion matrix, precision, recall, F1 confidence score curve and validation images used can be found in train11 folder in detailed.<br><br><br>
Test dataset results for 1 and 2 datasets can be found and downloaded from here: <br>
"https://github.com/Hotragn/AutoWCEBleedGen-Challenge/blob/main/Test%20Dataset%20Predicted%20Results.xlsx" 
<br> As per test datasets, given and the results show the different classes with respect to bleeding and non-bleeding for images  and these have been stored in an xlsx file.

<br>
Direct link for metrics:<br>

(https://github.com/Hotragn/AutoWCEBleedGen-Challenge/blob/main/train11/results.csv)


<br>
The below is validation images showing its detection with confidence score:<br>  
<img width="649" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/fc7de6e7-bbdf-4750-a6be-55111d0e0493"><br>
<img width="649" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/189d0daa-c73f-43dc-9ae0-d466d2849e9c">
<br><br><br>

The achieved interpretability plots are shown below:
<img width="648" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/1eeaf597-3c92-4e5f-87f0-7b86181bdbf7"><br>
This curve tells us the models overall performance is not bad since it is 0.65.<br>
<img width="649" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/4645bca9-0a99-4fd2-8d0a-7144345aff53"><br>
F1 score curve for the dataset and based on it, this is best model.<br>
<img width="279" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/08519751-fecb-4cea-aa18-94bb17c32080"><br>
The tradeoff between precision and recall at particular threshold can be identified from this plot<br>
<img width="241" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/5d399d2b-975f-4ee7-877a-fa66e15d09b2"><br>
As we can see above, the detection has been done for bleeding which automatically help us in detection of non-bleeding images and the results are shown in csv for this.

<br><br>
The detected images for the batch_1 validation:
<img width="505" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/68b355ba-48d5-42c7-a42c-b4871386a21a">
<br>

Example of Excel sheet containing the image IDs and predicted class labels of testing dataset 1 and 2:<br>
Testing dataset-1:<br>
<img width="505" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/a082a6f1-661d-4993-accc-ca200eb4138c">
<br>Testing dataset-2:<br>
<img width="505" alt="image" src="https://github.com/Hotragn/AutoWCEBleedGen-Challenge/assets/103170876/f8fb5aa1-8d5b-481c-b642-9c755dca5248">
<br>
<br>
The code and respective files for training and dependencies can be found<br>
click here[https://github.com/Hotragn/AutoWCEBleedGen-Challenge]

<br>
The end of the file.




