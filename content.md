To include images in your Atomic Learning content, you can use the HTML <code class="language-html">&lt;img&gt;</code> tag. Image files should typically be placed in the <code>resources</code> directory in the root of the repository. This means the value passed to the <code>src</code> attribute of the <code class="language-html">&lt;img&gt;</code> tag should be a relative path to the image file within that directory, such as <code>resources/image_name.png</code>

# Sizing

You can control the size of an image using the <code>width</code> and <code>height</code> attributes within the <code class="language-html">&lt;img&gt;</code> tag. For reference, the width of text on a content page is around 750 pixels, so the value passed to <code>width</code> should be less than or equal to this value.

When choosing dimensions, a height should be chosen such that the image fits within the window of a typical browser window. As a guideline, a height of 600 or less should be used.

If both height and width are specified, make sure they preserve the aspect ratio of the original image.

# Positioning
    
Images will be automatically centred horizontally relative to the margins of the test on the page.

# Styling

Images are automatically styled by the Atomic Learning page so you should not set the <code>style</code> attribute of the <code class="language-html">&lt;img&gt;</code> tag.

# Examples

The following code:

<pre><code class="language-html">&lt;img src="resources/my_image.png" width="750" height="500"&gt;</code></pre>

produces the following image:

<img src="resources/my_image.png" width="750" height="500">

![A sample image](resources/my_image.png =750x500)

Gifs can also be included by using the same <code class="language-html">&lt;img&gt;</code> tag with a <code>src</code> attribute pointing to the gif file:

<pre><code class="language-html">&lt;img src="resources/animated_sine.gif" width="750" height="500"&gt;</code></pre>

which produces:

<img src="resources/animated_sine.gif" width="750" height="500">

If you would like to see the entirety of the repository used to create this page as an example, you can find it <a target="_blank" rel="noopener noreferrer" href="https://github.com/Atomic-Learning/atomic-learning-programming-sequencing">here</a>.