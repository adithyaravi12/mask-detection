
# Mask Detection using OpenCV

The algorithm is trained on a dataset including photos of masked and unmasked people of all ethnicities and religions, and it can recognize and determine if a person is wearing a mask in real time using a webcam.


## Procedure

	1. Import dependencies
	2. Import dataset - create a for loop to import all images all together
		a. Define directory variable and set it to the folder having dataset
		b. Define classes as "with-mask","without-mask"
		c. Set path
		d. Read images and convert bgr to rgb
		e. Plt.show()
	3. Resize dataset to 224x224
	4. Read the dataset and convert them to array and shuffle them
	5. Split the dataset input to the data feature and labels into two different arrays
	6. Normalize the arrays
	7. Store all data and preprocessing into pickle to train the deep learning model
	8. Import existing deep learning models using tensorflow
		a. Change the input and output layers and the activation function and create new_model with the modified changes
	9. Compile model and fit it with necessary parameters
	10. Test the model with few images
    11. Run on real time 

## Run Locally

Clone the project

```bash
  git clone https://https://github.com/adithyaravi12/mask-detetction
```

Go to the project directory

```bash
  cd mask-detetction
```

Install necessary dependencies 
```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Screenshots

![App Screenshot](https://github.com/adithyaravi12/mask-detetction/blob/main/proj2.gif)


## Documentation

- [Reference](https://www.youtube.com/watch?v=FPRFYYMlhyw&t=3086s)
- [Dataset](https://github.com/cabani/MaskedFace-Net)







## 🔗 Links
[![My Portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](http://adithyaravi12.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adithya-ravi-707443126/)


