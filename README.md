# black---white-image-colorization

Before running this program download pretrained caffemodel from the below website and place it under the model folder.
https://www.dropbox.com/s/dx0qvhhp5hbcx7z/colorization_release_v2.caffemodel?dl=1

Make sure 'colorization_deploy_v2.prototxt' and 'pts_in_hull.npy' are in the same folder with 'colorization_release_v2.caffemodel'.
Make sure the location provided for the above files in program are accurate.

To change input image you can change the location of image in image = cv2.imread(' ')
ex.. image = cv2.imread('new image location')
