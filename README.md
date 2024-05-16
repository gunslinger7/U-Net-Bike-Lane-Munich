# U-Net-Bike-Lane-Munich
Semantic Segmentation of bicycle lanes in Neuperlach-Munich area.

## General Info:

The model was initially trained on a custom augmented dataset consisting of around 500 images for 19 epochs, gathered from GoPro Hero 4 mounted on bike, and masks labeled on makesense.ai website.
Later the training of the model was continued on a new augmented dataset consisting of 1970 images, trained for additional 40 epochs.

### Below you can see some of the predicted masks:


![1](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/9ac4d08b-a966-4674-8216-640e400e00f4)


![2](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/bf482277-50c1-4ca5-b3e0-2418b3325e6c)

![3](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/8db496ae-73f8-4e82-a4b0-769ded8fe13c)

### There are some falsely segmented spots which indicate lacking in data variety.

![4](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/12192374-e783-40fd-83c5-3f112f51924c)

![5](https://github.com/gunslinger7/U-Net-Bike-Lane-Munich/assets/167663925/072bdfec-38ae-401e-84c8-34693fa6db72)

Still, the model performs pretty well considering this little training data. It is also prone to quickly genearalize to new types of bike lanes with few examples.

#### All in all, it's clear that the model lacks variety in training data, but is able to quickly generalize to new data with just few examples.
