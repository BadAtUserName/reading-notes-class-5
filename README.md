# reading-notes-class-5

Class 5 Reading notes


Using images in html. <br>
How to put images on a webpage<br>
Use < img > element<br> 
Is void element cannot have an end tag. <br>
Requires 2 attributes to be useful src and alt.<br>
src contains contains url pointing to image you want to use can be relative url or absolute url<br> 
Without src attribute an < img > will note load<br>
	2. Linking absolute urls is not recommended should host on your own site<br>
	     a)    Which means keeping image 4 ur website on the same server as ur html<br> 
	     b)    if you did not create images make sure you have the permissions to use them<br>

3. Alternative Text<br>
	     a) alt value is suppose to be textual description of image. Use for sitches where 	image cannot be viewed. <br>
	     b) why would you need alt text reasons<br>
		1. User visually impaired or using screen reader<br>
		2. Spelled file name of path wrong<br>
		3. Browser doesn’t support image type<br>
		4. Provide text for search engine to use<br>
		5. Users turned off images to reduce data transfer volume<br>


4. What should be inside alt attribute<br>
		1. Decoration should use css background images for decoration but if you must use html add black alt = if image isn’t part of content.<br>
		2. Content if image provide significant information provide brief alt describing. 
		3. Link if you put an image inside an < a > tag to turn into link must still provide accessible link text<br>
		4. Text, you should not put your text into images. If your main heading needs 	drop shadow use css rather than putting image into text. <br> IF YOU MUST DO IT you must add alt as well<br> 

	B. Width and Height<br>
		1. Use width and height to spec your image<br>
		2. Can find width an height a number of ways use command I on a Mac. 
			a) reasons for knowing this it’s good to know since the browser loads in html 1st, and typically your image after so it will load text then image and make text move down. Which is distracting. 
		3. If spec size then browser knows before it has downloaded image how much space remains.<br>

	C. Image Titles<br>
		1. As with links can add tile to images to provide more info. We put it inside the image tag with all the src, alt, width, height stuff. But you shouldn’t use it.<br>

	D. Media assets and Licensing/ images on web and other a media asset types released under various license types, must have permission to use it. <br>

	1. Understanding license types
			a. All rights reserved- copyright protection the creator has exclusive rights to use it. To use something w. All rights reserved must <br>
				1. Obtain explicit written permission from the copyright holder<br>
				2 Pay license fee to use them, could be one time fee for unlimited used (royalty free)<br> or rights managed might have to pay specific fees depending on slot time, geographic region, industry or media type etc.<br>
				3.Limit your uses to this that would be considered fair use or fair dealing in your jursidiction<br>
				4. Authors are not required to include a copyright notice or license terms with their work. Copyright exists automatically.<br> if find image online not copyright assume it has one.<br> 

		b. Permissive
				1. If image release under permissive license like mid bed or suitable creative common license CC you do not need to pay a license fee. MUST FILL CONDITIONS<br>
					a. Provide link to go source of image and credit creator <br>
					b. Indicate whether any changes were made to it.<br> 
					c. Share derivative works created using the image under the same license as og<br>
					d. Not use image in commercial works<br>
					e. Include copy of license along with any release that uses image<br>
			c. Copy-left used in software mostly for forking og software encores source code of project  will also be made available for use.<br>
		
		d. Public domain/ no rights reserved can be used without permission<br>
				1. Easiest way to release work into public domain is to license under CCO specific creative license. <br>
			
		e. Searching for permissively-licensed images. 
				1. Can find images for projects using search engine or repositories. 
				2. Search using image description of image add public domain images<br> or public domain image library<br> open license images or similar<br>
				3. Image repository sites like flickr shutter stock and pixaby have permissive license options. <br>

	D. Annoting images with figures and figure captions 
		1. Can use p tag but shouldn’t<br>
		2 should use < fig caption > tells browsers and assistive tech that caps describes the content of the < figure > element<br>
		3. Figure does not need to be image<br>
			a) express your meaning in a compact easy to grasp way.<br>
			b) could go in several places in the pages linear flow<br> 
			c) Provides essential info supporting main text<br>
	
	E. CSS background images. Can use CSS to embed images into webpages. Use CSS background-image prop and other background-* properties<br>
		1. Result embedded image easier to position and control
		2. Css images are just for decoration they do not have semantic meaning<br> 
		3. If image has meaning in terms of content use HTML if is just for decoration use css<br>


II. HTML Common file types
	A. Image file type details in tables below bits per component ref to the number of bits used to rep color component.<br> Ex RGB color depth of 8 indicates the each of red green blue comments are repped by 8 bit val. <br>
		1. BIT DEPTH is the total number of bits used to rep each pixel in mem<br>
	
B. APNG Animated portable network graphics<br>
		1. File format intro’d by Mozilla extends PNG standard to add support of animated images. <br> Similar to animated gif.<br>
		2. APNG is more capable in that it support a variety of color depths gif only supports 8-bit indexed color.<br> 
		3. APNG useful for animations that don’t sync up with anything don’t need a soundtrack great for animation throwers.<br>

C. AVIF image<br>
		1. Open source and royalty free file. AV1 bitstreams in the High Efficiency Image File Format HEIF container.<br> 
		2. Av1 is coding format design for vid transmission over internet. Benefits from sig advances in video encoding recent years. Disadvantages for some cases as video and image encoding have diff req’s<br>
		3. Format offers<br>
			a. Excellent lossy compression<br>
			b. Generally has bette compression than webP<br>
			c. Lossless compression<br>
			d. High Dynamic Range (HDR) support for storing images. <br>
			e. Wide color gamut<br>
			f. DOES NOT SUPPOR PROGRESSIVE RENDERING<br>
	
D. BMP Bitmap file<br>
		1. Most prevalent on windows computers<br>
		2. Used in special cases oil apps and connects. <br>
		3. In theory supports a variety of data reps. Simplest most commonly used <br>				    is uncompressed raster image. Each px occupying 3 bits repped r g b<br>
		4. Features<br>
			a. Support Dif bit depths<br>
			b. Indexed color<br> 
			c. Alpha channels<br>
			d. Diff pixel orders<br>

E. GIF graphics interchange format<br>
		1. GIF one of the first graphics supported by HTM along with XBM.<br>
		2. It was invent in the 80’s<br>
		3. Each pixel repped by 8bit val is index to palette of 24 bit colors.<br>
		4. Simulate more than 255 or 256 colors <br>
		5. Pixels are opaque unless specified<br>
		6. GIF supports simple animation<br>
		7. GIF has been popular for decades however social media has helped it<br> 				    make a comeback with meme’s and videos
		8. Populare feature of GIF is support for interlacing. Rows of pixels stored in<br>
		    order so that partially received files can be displayed in lower quality<br>
		9. GIF good choice for simple images and animations<br>
		10. Converting  to full color images can result in dithering<br> 

F. ICO MS window icon<br>
		1. Designed by MS of desktop icons of window systems.<br>
		2. Early versions of web prose ice file named favicon has to do with where<br>
		    it is displayed <br>
		3. ICO file can contain multiple icons<br>
		4. Icon data store as bmp image w/o filed header<br>
		5. Or complete PNG image including header<br.>
		6. If using use BMP<br>

G. JPEG joint photographic experts group image<br>
		1. Widely used lossy compression format. <br>
		2. Useful for photos<br>

H. PNG portable network graphics<br>
		1. Lossless compression <br>
		2. Supporting higher color depths than GIF<br>
		3. Full alpha transparency support<br>
		4. Now widely supported<br>

K. SVG scalable vector graphics.
		1. Specs contents of images as a set of drawing commands that create<br> 				     
       shapes, lines, apply color, filters etc<br>
		2. SVG files contain source code that when interpreted draws image<br>
		3. SVG can be used in web content in two ways
			a. Directly Wirth <svg>  within html containing svgs elements<br>
			    to draw image<br>
			b. Can display an sag anywhere you can use any other image type. 
		4. Great for images that can be repped using series of drawing commands<br>
		    especially if size at which image rendered unknown.<br>

L. TIFF tagged image file format. <br>
		1. Raster image created to store scanned photos.<br> 
		2. Files usually larger/metadata is included<br>
		3. Supports many compression methods, CCITT used by fax machines<br>
		4. Every value in tiff supported using it’s tag and it’s type. Followed by<br>
		    length array of values to assign to tag.<br> 
		5. Allows diff data types to be used for same properties<br>
		6. Single tiff file can contain many images may be used to rep multi-page<br>
		     docs<br>
		7. Supports many colors Rob cymk YCbCr. 
		8. Some web browsers support but not many<br>
	
M. WebP Image<br>
		1. Lossy compression via predictive coding.<br> 
		2. Smaller than jpeg 25-35%<br>
		3. Supports animation<br>
		4. Now has broad support for latest versions of web browsers<br>

	
			
  N. XBM X window system bitmap<br>
		1. Files first supported on web. <br>
		2. NO LONGER USED SHOULD BE AVOIDED. <br>
	
O. Choosing image format<br>
		1 photos fare well with lossy compressions. <br>
			a. Jpeg<br>
			b. WebP<br>

2. Icons smaller images <br>
			a. WebP<br>
			b. Png<br>
		
	3. Screenshots<br>
			a. If want to comp on quality use lossless format<br>
			b. PNG best bet<br>
		4. Diagrams drawings and charts.<br> 
			a. SVG best choice for all those lines<br>

	P. Providing image call backs please see https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types

			
III. HTML/CSS using color<br>
	A. Things that can have color. <br>
		1. At element level everything in html can have color applied to it.<br> 
		2. fundamental level color prop defines foreground color of html elements<br>
		3. Fundamental level background color def’s background color on just<br>
		     about any elements background color<br>

B. Text / whenever element is rendered props used to detrained color, text<br> 
	     background and decorations on the text<br> 
		1. color use when drawing text and text deocrations<br>
		2. background<br>
		3 text-shadow configs shad effect to apply to text<br>
		4. text-decoration-color default to color of of text applied to, can<br>
		     override.
		5. text-emphasis-color color to used when drawing emphasis characters<br>
		6. caret-color color when drawing caret. AKA the text input cursor, within<br>
		
C. Boxes every element is a box with some sort of content, background, border<br>
		1. Borders see borders section<br>
		2. Background color color areas with no foreground content<br>
		3. column-rule-color color of lines in columns<br>
		4. outline-color used for outline<br>

D. Borders
		1. Basic element border has a line drawn around it. See box model for more<br>
		2. Can use shorthand property<br>
		3. Use border-block-start-color and border-block-end-color<br>
		4. border-inline-start-color and border-inline-end-color<br>

E. Other ways to use colors 
		1. HTML canvas api lets draw 2d bitmapped graphics in canvas <br>
		2. SVG<br> 
		3. WebGL<br>
	
F. How to describe color<br>
		1. To rep color in css must translate from analog to digital<br> 
		2. Keywords, there are some keyword colors you can use. <br>
		3. RGB <br>
			a. Hexadecimal string notations starts with # bunch letters follow<br>
		4. RGB functional notation<br>
		5. HSL functional notation see MDN doc for more<br> 
		6. HWB functional notation<br>
	
G. Using color
		1. Specifying colors in stylesheets  use it there to let it be colored<br> 
			a. Html to get your elements<br>
			b. CSS to color them.<br>
		2. Letting user pick a color<br>
			a. See https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color

H. Using color wisely GET TO KNOW COLOR THEORY<br>
		1. finding the right colors. There are tools.<br> 
		2. Base color color that defines your website.<br> 
			a. Color naturally associated with product like mt, dew<br>
			b. Color comes with imagery for you product.<br>
		3. Browser extensions that help<br> 
			a. Colorzilla offers eyedropper tool for color picking<br>

I. Fleshing out the palette<br>
		1. Make sure using appropriate colors, use color theory<br>
		2. A few tools to help<br> 
			a. MDN color picker tool<br>
			b. Paletton<br>
			c. Adobe color cc online color wheel<br>

J. Color theory resources<br>
		1. Color science online<br>
		2. Kahn academy in association wit pixar<br>
		3. Color theory on wikipedia<br>

K. Color and accessibility<br>
		1. Many waist color can be accessibility problem. <br>
			a. Improper use or carelessness can lead to reduced traffic<br> 
		2. Color blindness do own research on this<br> 
		3. Color palette creation use paletton to make cute pallet<br>

L. Color backgrounds, contrast, and printing<br>
		1. What looks good on screen may look different on paper and ink<br> 
		    is expensive. 


III. CSS styling html text element/ fundamental text and font styling.<br> 
	A. Things involved in styling text in css. <br>

B. Css props used to style text fall into two categories. 
		1. Font styles properties that affect a texts fond, size, weight, style<br>
		2. Text layout styles. Props affect spacing , allow manipulation like<br>
		    space  between lines and letters. 

C. Fonts. See example at https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals for fonts. 

D. Color<br>
		1. Color prop sets color of foreground content of selected elements. <br>
		    see example https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals<br>

G. Font Families
		1. To change fond use font-family properties, allows your to spec a font or<br>
		    a list of fonts. 
		2. Browser will only display font if it is available on machine. Or will display<br>
		     default font<br> 

H. Web safe fonts. <br>
		1. Certain number of fonds get avail across systems they are web safe<br>
		2. See list of web safe fonts. https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals<br>
		3. Default fonts five generic names for fonts<br>
			a. Serif<br>
			b. Sans-serif<br>
			c. monospace<br>
			d. Cursive<br>
			e. Fantasy<br>
	
I. Font stacks
		1. Cannot guarantee avail. of fonts, so smart to stack and give second<br>
		    option<br>

J. Font size
		1. px pixels num of px high you want font. 
		2. em equal to font size of parent element of the current element<br>
		 3. rem works like em except 1 rem is quant to the font size of the root<br>
		     element of dock. Makes math easier but is not supported by old<br>
		     browsers<br>
		4. Things get tricky when you start changing the font size of nested<br>
		     elements, need to use some math to figure this one out. See<br>
		     https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals for more<br>

K. Font style, font weight, text transform, and text decoration<br>

1. Font-style suet to turn italic on and of.<br> 
			a. Normal sets text norm<br>
			b. italic sets text italic<br>
			c. oblique sets text to use simulates version of italic font<br>
		
2. font-weight sets how bold text is. <br>
			a. normal, bold<br>
			b. lighter, bolder sets elements boldness to step heavier or <br>
			     lighter<br> 
			c. 100-900 numeric boldness<br>

	3. text-transform allows you to set your font to be transformed<br>
			a. none: prevents transformation<br>
			b. uppercase: transform all caps<br>
			c. lowercase: transforms to all lowercase<br>
			d. capitalize: transforms all words to have first letter capped<br>
			e. full-width: transforms all glyphs to written inside a fixed width<br>
			    square similar to monospace. 
		
		4. text-decoration sets/unsets text decoration on fonts mainly used 2 unset<br>
			a. none: unsets decorations already	present<br>
			b. underline: underlines text<br>
			c. overline: Gives the text an overline<br>
			d. Line-through: puts a strikethrough over the text<br>

	L. Text Drop shadows can apply shadows with text-shadow prop. 4 props<br>
			a. The horizontal offset<br>
			b. The vertical offset<br>
			c. The blur radius<br>
			d. The base color of the shadow<br>
	
	M. Multiple Shadows. Can add multiples to the same text separate by comma<br>

	N. Text layout. <br>
		a. Text alignment<br>
			1. left<br>
			2. right<br>
			3. center<br>
			4. justify<br>
	
	b. Line Height prop that sets the height of each line of text, can take most<br>
		    length and size units, can also take valueless unit<br>
	
	c. Letter and word spacing letter-spacing and word-spacing props allow<br>
		    set space  between letters and words in your text not used often<br> 

	d. Other props worth looking at see below. 
			1. https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals


Reading questions
Reading questions class 4

1. What is a real world use case for the alt attribute being used in a website?
  a. Alt give an alternate name / text for an image, it is meant to give a description of the image. 

2.How can you improve accessibility of images in an HTML document?
  a. We an improve accessibility by adding in alt text so those unable to see will have some idea of what the image was suppose to be. This is also handing if the page does note load properly

3.Provide an example of when the figure element would be useful in an HTML document.
  a. Figure is helpful when you want to provide information supporting the main text or the image. An example would be figure is a container holding a thing, when you want to give clear captions that is a great time for figure. 


4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
  a. SVG is an image that is scaleable what this means is you can make it as big or as small as you want. SVG is great for for creating charts, and icons and graphs. GIF were created to be smaller and maybe a small loop able video. The popularity or GIF’s has increased in the past couple of years due to social media, people love sending small videos. 

5. What image type would you use to display a screenshot on your website and why?
	a. The type of image you should use for a screenshot is PNG which is better than jpeg as it is more accurate. However lossless WebP is better compressed. 

CSS questions
1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
	a. Lets think about background and foreground as a book, the background is a page, and the foreground is a page. The background color is going to be on a page further from your face, is the background. The pages closer to your face are the foreground. When we are talking about colors we think of them in those terms, foreground color close to use, background color further. 

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
  a. I would first ask if there was a color they were thinking of. From there If there is one I would use probably paletton, to finish out colors that work best together. 

3. What should you consider when choosing fonts for an HTML document?
  a. One of the many things to consider when using fonts is if they are accessible by browsers, and you should choose a back up just incase they are note supported. 

4. What do font-size, font-weight, and font-style do to HTML text elements?
  a. Font-size changes the height of a font, font weight changes the thickness of a font, and font style changes if it is normal, bold or italic. 

5. Describe two ways you could add spacing around the characters displayed in an h1 element.
  a. To change the spacing of and h1 element is to use letter-spacing. It is used to change the horizontal spaces between characters, it is a css property. https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing





## Things I want to know more about 
  nesting em, what are the actual image types you should use. How do i get better at css selectors. 

	
	

