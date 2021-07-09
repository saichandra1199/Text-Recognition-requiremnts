# **Text Recognition**

<!-- ----------------------------------------------------------------------------------------------  -->

## **Installations**

* [Leptonica](https://docs.google.com/document/d/1Em-0x8zsWR8ikAM5kuFc4Gsu8RISzmdRjsBatEs8jK0/edit)

* [Tesseract -OCR](https://docs.google.com/document/d/1Em-0x8zsWR8ikAM5kuFc4Gsu8RISzmdRjsBatEs8jK0/edit)

* [GO](https://golang.org/doc/install)

## **Usage**

* After all the installation place the model that you want to test in path: __/usr/local/share/tessdata__ with named as **eng.traineddata**
* Keep the test images in __test_images_ folder.
* Open terminal in **Aadhar_TR folder**. Enter command: **go run new_char_conf.go**
* Output of model will be in __csv_reports__ in the form of csv file.
##### Test images
* !["sample Test image"](images/test_image4.jpg)
* !["sample Test image"](images/test_image2.png)
* !["sample Test image"](images/test_image1.jpg)

##### Output format
* !["sample output csv"](images/output.png)


<!-- (/images/test_image2.png) (/images/test_image3png) -->

## **Training process**

* [Here](https://docs.google.com/document/d/1Em-0x8zsWR8ikAM5kuFc4Gsu8RISzmdRjsBatEs8jK0/edit)  are the commands for training the tesseract on new fonts.
* [Video tutorial](https://www.youtube.com/watch?v=TpD76k2HYms&t=463s) for guiding the training process.
* [Official training docs](https://tesseract-ocr.github.io/tessdoc/)

## **Evaluation**

* Run the  [**comparecsv.py**](csv_reports/comaprecsv.py):  python file  in __csv_reports__ folder.

* Install dependency for  **comparecsv.py**:    _pip install pandas_
* We will be having results in __Accuracy.txt__ present in __csv_reports__ .

##  **Results**
* __DE Aadhar Production model__


| GB Percent | GB Accuracy | 
| :---: | :---: | 
| 75.4 | 94.4 | 

* __Image Tesseract Voter POA Production model__

| GB Percent | GB Accuracy | 
| :---: | :---: | 
| 40.0 | 91.5 | 



## **Models**
 * [DE Adhar model](DE_Aadhar_Prod_model/eng.traineddata)
  * [Image tesseract voter poa model ](Voter_poa_Image_tesseract_prod_model/voterPoa_image_tesseract_91.476.traineddata.zip)




---------------------------------------------------------------------------------------------- 




