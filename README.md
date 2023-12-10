# Blur-and-Clear Images Classification
## Classifying the Blur and Clear Images



`As the Now, the era of Deep Conv Nets has suppressed the Standard Computer Vision Techniques, 
Thus I focussed on the root of it which is Neural Nets.`
`Neural Nets learn very Quickly the complex features, therefore can be used much easily then std. CV technique.
Tuning ANN efficiently can provide me the results much better than CV TEchnique.`

## Neural Network Model
`Model has 3 Layers`
`Containing`
```
 1 Input Layer -> 100*100 U
 
 1 Hidden Layer -> 300 HU
 
 1 Output Layer -> 2 U
```
**I have used the Backprop Algorithm for Training ANN using the SGD Optimizer with Momentum.
Rescaled the Images to 100 x 100 Pixels in Grayscale Coding and done median filtering to filter out the noise from Images.**


# Quick Start
`Need the Images that are clear in the separate folder and one with blurred in another folder.`
```ruby

# Python3+ user install Tkinter package (Python 3.5.xx)
# Currently code is supported for Python 3.5.xx version only
sudo apt-get install python3-tk
# Clone the repo
git clone https://github.com/aditya9211/Blur-and-Clear-Classification.git
# Change the working Directory
cd Blur-and-Clear-Classification/
# Install the requirements
pip install -r requirements.txt
# Train the Network
python train.py  --good_path  '/home/......good/'  --bad_path  '/home/......./bad/'
# Test the Network 
python test.py
# Predict output 
python predict.py --img '/home/....../laptop.png'

```

