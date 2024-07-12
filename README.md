# peopleCounter

Implementation of https://pyimagesearch.com/2018/08/13/opencv-people-counter/

This simple project process an input video/stream and detect predefined classes of objects, tracking their movement and counting the number of times they crosses a horizontal line in the middle of the screen.

## Usage

### To read and write back out to video:
python main.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input *inputFilePath* --output *outputFilePath*

### To read from webcam and write back out to disk:
 python main.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --output *outputFilePath*
