# Image_generator_GAN
 ###
<strong>It uses Generative adversarial network to generate new MNIST images. </strong>

### Dateset
* We are using MNIST digit images. 


### Model description
Models are described in Generator and Discriminator classes in the jupyter notebook. It is using Linear layers to create the model.

* Model Structure
  - Generator and Discriminator both use 4 Linear layers.
  - It uses Leaky ReLu with Dropout.
* Loss : Binary Cross Entropy Loss.
* Optimizer : Adam Optimizer.


### Usage
To use the code, Load samples using the Generator object to get fake digits.

      
### How to Contribute
Find any typos? Have another resource you think should be included? Contributions are welcome!

* Fork this repository.

* Clone the repository to your desktop to make changes.

      $ git clone {YOUR_REPOSITORY_CLONE_URL}

* Issue a pull request by clicking on the green pull request icon.

Instead of cloning the repository to your desktop, you can also go to README.md in your fork on GitHub.com, hit the Edit button (the button with the pencil) to edit the file in your browser, then hit the Propose file change button, and finally make a pull request.

### License
This repository has been licensed under Apache 2.0.
