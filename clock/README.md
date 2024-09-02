the original image : clock.png

![clock.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/clock.png)

the result image using the code below

`Animation animation;`

`imreadanimation("clock.png", animation);`

`imwrite("converted_fromclock.png", animation.frames);`

note : the animation speed information is lost when using `imwrite` to save the animation.

![converted_fromclock.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/converted_fromclock.png.png)

the result image using the code below

`Animation animation;`

`imreadanimation("clock.png", animation);`

`imwriteanimation("imwriteanimation_clock.png.png", animation);`

note : the animation speed information should saved correctly ( bug #1 ).

![imwriteanimation_clock.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/imwriteanimation_clock.png.png)


the result image using the code below

`Animation animation;`

`imreadanimation("clock.png", animation);`

`imwrite("converted_fromclock.avif", animation.frames);`

note : the animation speed information is lost when using `imwrite` to save the animation.

![converted_fromclock.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/converted_fromclock.png.avif)

the result image using the code below

`Animation animation;`

`imreadanimation("clock.png", animation);`

`imwriteanimation("imwriteanimation_clock.png.avif", animation);`

note : the animation speed information should saved correctly ( bug #2 ).

the animation don't stop ( related bug #3 ).

![imwriteanimation_clock.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/imwriteanimation_clock.png.avif)



the result image using the code below

`Animation animation;`

`imreadmulti("clock.png", animation.frames, IMREAD_COLOR);`

`imwrite("without_alpha_clock.png.png", animation.frames);`

![without_alpha_clock.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/without_alpha_clock.png.png)


the result image using the code below

`Animation animation;`

`imreadmulti("clock.png", animation.frames, IMREAD_GRAYSCALE);`

`imwrite("gray_clock.png.png", animation.frames);`

![gray_clock.png.png](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/gray_clock.png.png)


the result image using the code below

`Animation animation;`

`imreadmulti("clock.png", animation.frames, IMREAD_COLOR);`

`imwrite("without_alpha_clock.png.avif", animation.frames);`

![without_alpha_clock.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/without_alpha_clock.png.avif)


the result image using the code below

`Animation animation;`

`imreadmulti("clock.png", animation.frames, IMREAD_GRAYSCALE);`

`imwrite("gray_clock.png.avif", animation.frames);`

![gray_clock.png.avif](https://raw.githubusercontent.com/sturkmen72/opencv-apng/master/clock/gray_clock.png.avif)
