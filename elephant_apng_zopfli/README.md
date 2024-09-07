the original image : elephant_apng_zopfli.png

![elephant_apng_zopfli.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/elephant_apng_zopfli.png)

the result image using the code below

`Animation animation;`

`imreadanimation("elephant_apng_zopfli.png", animation);`

`imwrite("converted_fromelephant_apng_zopfli.png", animation.frames);`

note : the animation speed information is lost when using `imwrite` to save the animation.

![converted_fromelephant_apng_zopfli.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/converted_fromelephant_apng_zopfli.png)

the result image using the code below

`Animation animation;`

`imreadanimation("elephant_apng_zopfli.png", animation);`

`imwriteanimation("imwriteanimation_elephant_apng_zopfli.png", animation);`

note : the animation speed information should saved correctly ( bug #1 ).

![imwriteanimation_elephant_apng_zopfli.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/imwriteanimation_elephant_apng_zopfli.png)


the result image using the code below

`Animation animation;`

`imreadanimation("elephant_apng_zopfli.png", animation);`

`imwrite("converted_fromelephant_apng_zopfli.avif", animation.frames);`

note : the animation speed information is lost when using `imwrite` to save the animation.

![converted_fromelephant_apng_zopfli.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/converted_fromelephant_apng_zopfli.avif)

the result image using the code below

`Animation animation;`

`imreadanimation("elephant_apng_zopfli.png", animation);`

`imwriteanimation("imwriteanimation_elephant_apng_zopfli.avif", animation);`

note : the animation speed information should saved correctly ( bug #2 ).

the animation stops ( refreshing the page make it start again ) ( bug #3 ).

![imwriteanimation_elephant_apng_zopfli.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/imwriteanimation_elephant_apng_zopfli.avif)



the result image using the code below

`Animation animation;`

`imreadmulti("elephant_apng_zopfli.png", animation.frames, IMREAD_COLOR);`

`imwrite("without_alpha_elephant_apng_zopfli.png.png", animation.frames);`

![without_alpha_elephant_apng_zopfli.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/without_alpha_elephant_apng_zopfli.png.png)


the result image using the code below

`Animation animation;`

`imreadmulti("elephant_apng_zopfli.png", animation.frames, IMREAD_GRAYSCALE);`

`imwrite("gray_elephant_apng_zopfli.png.png", animation.frames);`

![gray_elephant_apng_zopfli.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/gray_elephant_apng_zopfli.png.png)


the result image using the code below

`Animation animation;`

`imreadmulti("elephant_apng_zopfli.png", animation.frames, IMREAD_COLOR);`

`imwrite("without_alpha_elephant_apng_zopfli.png.avif", animation.frames);`

![without_alpha_elephant_apng_zopfli.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/without_alpha_elephant_apng_zopfli.png.avif)


the result image using the code below

`Animation animation;`

`imreadmulti("elephant_apng_zopfli.png", animation.frames, IMREAD_GRAYSCALE);`

`imwrite("gray_elephant_apng_zopfli.png.avif", animation.frames);`

![gray_elephant_apng_zopfli.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/elephant_apng_zopfli/gray_elephant_apng_zopfli.png.avif)
