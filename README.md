

### NEW Sketch Drawing Generator Demo Online  
 
Our Sketch Drawing Generator is online. Visit [here](http://sketch.etos.world) and enjoy!
![](imgs/sketch_demo.jpg)


### etos face swap
Swap face between two photos for Python 3 with OpenCV and dlib.

a tool for [etos](https://etos.world) ecosystem.

### Get Started
```sh
python main.py --src imgs/test1.jpg --dst imgs/test5.jpg --out results/output1_5.jpg --correct_color
```

| Source | Destination | Result |
| --- | --- | --- |
|![](imgs/test1.jpg) | ![](imgs/test5.jpg) | ![](results/output1_5.jpg) |

```sh
python main.py --src imgs/test1.jpg --dst imgs/test5.jpg --out results/output1_5_2d.jpg --correct_color --warp_2d
```

| Source | Destination | Result |
| --- | --- | --- |
|![](imgs/test1.jpg) | ![](imgs/test5.jpg) | ![](results/output1_5_2d.jpg) |

### Install
#### Requirements
* [dlib](http://dlib.net/)
* OpenCV 3

Note: See [requirements.txt](requirements.txt) for more details.
```
pip install -r requirements.txt
```
### Git Clone
```sh
git clone https://github.com/etosworld/etos-faceswap
```
### Swap Your Face
```sh
python main.py ...
```
Note: Run **python main.py -h** for more details.

## More Results
| From | To |
| --- | --- |
| ![](imgs/test2.jpg) | ![](results/output1_2.jpg) |
| ![](imgs/test3.jpg) | ![](results/output1_3.jpg) |
| ![](imgs/test4.jpg) | ![](results/output1_4.jpg) |
| ![](imgs/test9.jpg) | ![](results/output1_9.jpg) |
| ![](imgs/test7.jpg) | ![](results/output1_7.jpg) |
