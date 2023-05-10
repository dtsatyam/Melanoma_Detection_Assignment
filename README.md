# Melanoma Skin Cancer Detection Case study
> To build a CNN based model which can accurately detect melanoma.

> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths:

    . A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Analysis Methodology
1. Data Sourcing
2. Creating Dataset
3. Visualizing the data and perform analysis
4. Create, Compile & Train model
5. Create model with augmentation
6. Create model with Class rebalance

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Initially, as the number of epochs increase, the training accuracy increases whereas the validation accuracy increases to a max value of ~51% and then fluctuates with 1%. As the number of epochs increase, the training loss decreases whereas the validation loss decreases at the starting and later increasing

With augmentation, it can be observed that the training and validation accuracy are almost equal. Also the overfitting of the model is reduced when compared to the initial model but the overall accuracy is not improved.

With Class rebalance, the training accuracy and validation accuracy both increased. The validation loss also decreases. The training accuracy increased from ~55% to ~91% and validation accuracy also increased from ~56% to ~85%. Finally, Class rebalancing improved the overall accuracy of the model.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.21.5
- pandas - 1.4.2
- matplotlib - 3.5.1
- seaborn - 0.11.2
- python - 3.7
- tensorflow - 2.12.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to
- https://www.geeksforgeeks.org/
- https://pandas.pydata.org/
- https://seaborn.pydata.org/
- https://stackoverflow.com/


## Contributor
Created by 
- Satyanaraya D
> [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/dtsatyam) 

Please feel free to contact us.

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->