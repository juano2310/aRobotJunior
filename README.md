# Adafruit FormulaPi3

Hardware ($150):
https://www.servocity.com/junior - $27.99
https://www.amazon.com/gp/product/B00Z9QVE4Q - $29.99
https://www.adafruit.com/products/3055 - $39.95
https://www.adafruit.com/product/2348 - $22.5
https://www.adafruit.com/products/3099 - $29.95
https://www.adafruit.com/products/2336 (2) - 0.75

Assembly:
https://www.youtube.com/watch?v=hQCypE4pDBo
https://learn.adafruit.com/adafruit-dc-and-stepper-motor-hat-for-raspberry-pi/assembly

1 --- 2
   -
   -
3 --- 4

Software:

sudo apt-get install python-dev git

Copy files
install-opencv.sh
cd Adafruit-dc-and-stepper-motor-hat-for-raspberry-pi
sudo python setup.py install

Designed to use Python 2.7

1) Designed to run on a RaspberryP 3, using the full power of that board

2) Rather than using the standard ZeroBorg motor driver, it uses the DC & Stepper Motor HAT for Raspberry Pi.

3) Uses OpenCV3.x

To install OpenCV3 on your RasperryPi, use this script:
https://gist.github.com/willprice/c216fcbeba8d14ad1138
