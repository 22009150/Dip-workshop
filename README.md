# Dip-workshop-1

# WORKING ON IMAGE:

## NAME: ARCHANA K

## REG NO: 212222240011

# INSTRUCTION:
### 1. The image should be a plant, Tree, flower or building

### 2. The filename should be username.jpg

### 3. The image should be Converted to gray scale and HSV 

### 4. Display the H, S and V planes

# PROGRAM:

```
import cv2

image-cv2.imread('building.jpg',1)

image-cv2.resize(image, (400,250))

cv2.imshow('pic',image)

cv2.waitKey(0)
```

# The image should converted to gray scale:
```
import cv2

image = cv2.imread('building.jpg')

gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)

cv2.imshow('gray_scale', gray)

cv2. waitKey(0)

cv2. destroyAllWindows()
```

# The image should be converted to HSV:
```
import cv2

image = cv2.imread('building.jpg')

gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)

cv2.imshow('my_img', gray)

cv2. waitKey(0)

cv2. destroyAllWindows()
```

# Display the H,S and V planes:
```
import cv2

image-cv2.imread("building.jpg",1)

image= cv2.resize(image, (400,250))

image=cv2.cvtColor(image,cv2.COLOR_RGB2HSV)

H,S,V=cv2.split(image)

cv2.imshow('Hue', H)

cv2.imshow('Saturation',S)

cv2.imshow('Value',V)

cv2.waitKey(0)

cv2.destroyAllWindows()
```
# OUTPUT:
## IMAGE:
![image](https://github.com/22009150/Dip-workshop/assets/118708624/e2566465-6315-4918-bdc7-de758c1c4e25)

## GRAY SCALE:
![image](https://github.com/22009150/Dip-workshop/assets/118708624/70cdbabc-9002-430a-a3ae-d934f92b2019)

## HSV:
![image](https://github.com/22009150/Dip-workshop/assets/118708624/659a563f-e94e-41d0-bdab-d81ad206787d)

## HUE, SATURATION AND VALUE :
![image](https://github.com/22009150/Dip-workshop/assets/118708624/5a1a6fe0-d8ce-4dd0-b793-ea879a112ba2)


## RESULT:
### Therefore working on image has been successfully implemented.
