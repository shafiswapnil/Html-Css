# Image Replacement

To use a logo on your website, you might think you will nest an `img` on `h1` tag. This is the first way of using a logo in your website. But in more common way, is to use **image replacement**. The way it works is, you instead apply the image as a background of the `h1` element.

So in `h1` you can still specify the name of your logo. This way your markup will be more clean and efficient.

Remember, 

 - Heading element have a display of block. So the image will definitely repeat it self by default. To fix this, use `no-repeat`.
 
 - Use `text-indent` to push the text off the screen. Use a huge negative number as value.

 - Image can be cut off because of not specifying the real widht and height. So, use real width and height to show the full image.

 - And yes, why we're still manually writing the name of the logo in markup? The reasons are,
 	
	- Bad network connection. What if the image is load for some reason, maybe it's not referenced properly, or accidently delete the image in the future, nothing will display.
	
	- If browser has turned off image loading. The image will not be shown.

	- If CSS is disabled entirely in browser.


Example Code:

```
h1 {
	background: url(img.png) no-repeat;
	text-indent: -9999px;
	widht: 142px;
	height: 43px;
}
```
