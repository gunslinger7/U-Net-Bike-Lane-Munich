# U-Net-Bike-Lane-Munich
Semantic Segmentation of bicycle lanes in Neuperlach-Munich area.

## General Info:

The model was trained on a custom augmented dataset consisting of around 500 images, gathered from GoPro Hero 4 mounted on bike, and masks labeled on makesense.ai website.

Currently the model is trained on 469 images (including augmented ones), for 19 epochs on google colab, and in my humble opinion, performs really well for this little training.

### Below you can see some of the predicted masks:

![5](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/3e52e946-033a-4a4b-8e7e-96162baa213c)


#### There are some falsely detected spots, which are the consequence of little training data. I presume doubling the size of the dataset would fix this issue.
![4](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/bf966840-5b8d-4e5f-8f68-b30691734b77)

![1](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/8369f8ac-0f19-4c5c-8e54-60b112788ec6)

#### All in all, it's clear that the model lacks training data, which is the main objective now.
