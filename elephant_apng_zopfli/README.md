the original image : elephant_apng_zopfli.png

![elephant_apng_zopfli.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/elephant_apng_zopfli.png)

the result image using the code below

`Animation animation;`

`imreadanimation("elephant_apng_zopfli.png", animation);`

`imwrite("converted_fromelephant_apng_zopfli.png", animation.frames);`

note : the animation speed information is lost when using `imwrite` to save the animation.

![converted_fromelephant_apng_zopfli.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/converted_fromelephant_apng_zopfli.png.png)

the result image using the code below

`Animation animation;`

`imreadanimation("elephant_apng_zopfli.png", animation);`

`imwrite("converted_fromelephant_apng_zopfli.avif", animation.frames);`

note : the animation speed information is lost when using `imwrite` to save the animation.

![converted_fromelephant_apng_zopfli.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/converted_fromelephant_apng_zopfli.png.avif)

