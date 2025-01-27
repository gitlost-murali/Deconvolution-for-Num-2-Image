# Deconvolution-for-Num-2-Image
Takes a number and generates the images of those numbers. Trained on MNIST using Deconvolution Neural Networks (Fancy word for Transposed Convolution)

Notebook has been created with markdowns and comments to make it self-explainable. Still, I'll try uploading a detailed explanation of the code.

If the given number is 288791, we convert that to [2,8,8,7,9,1] and create a batch of numbers and pass it through generator. Images generated for each number are stitched through matplotlib. Output for 288791 is

![alt_text](https://github.com/Murali81/Deconvolution-for-Num-2-Image/blob/master/images_vae/output_img.PNG)

Generator output after just 1 epoch of training,

![alt text](https://github.com/Murali81/Deconvolution-for-Num-2-Image/blob/master/images_vae/vae_generated_image_epoch_1.png)

# References

[1] <a href="https://datascience.stackexchange.com/questions/6107/what-are-deconvolutional-layers"> What is Deconvolution ?</a>
