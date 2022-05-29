# mask-detetction

dataset: https://github.com/cabani/MaskedFace-Net
reference: https://www.youtube.com/watch?v=FPRFYYMlhyw&t=3086s

Procedure:

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
	
	
![image](https://user-images.githubusercontent.com/98291038/170888425-c076670e-3cce-49f8-88c9-042890e4e700.png)

