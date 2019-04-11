# Black Hole Image on a Budget

##### By Alan Wong (April 10, 2019)

In this tutorial, we will generate an image of a black hole for a fraction of
the budget of top world scientists. You don't even need a telescope for this;
just go install [GIMP](https://www.gimp.org/) for free! You can find lots of
pictures of black holes online (e.g. from
[NASA](https://www.jpl.nasa.gov/news/news.php?feature=7372)). Some are real...
others are not, like the ones we will make here.

## Space

Let's begin with dark space. Create an image with a single layer.

![Figure 1: Hello Darkness](images/img_01.png)

## Reddish blob

On a new layer, use the paint brush or the ink tool to make a reddish blob. 
Just get an overall shape you like. This is not an exact science! Here, I just
"eye-balled" a color I liked. Alternatively, you could pull up an official black
hole image and use the color picker tool to get a closer fit.

![Figure 2: Starting with a Reddish Blob](images/img_02.png)

I then applied a Gaussian Blur (radius 100px on a 640x480 px image) to my
reddish blob. I adjusted the opacity of the layer to get values closer to what I
liked.

![Figure 3: Bluring the Reddish Blob](images/img_03.png)

## Donut thing part 1

Next, I added an orange donut thing with the paint brush or ink tool like we
just did with the reddish blob. I did this on a new (transparent) layer.

![Figure 4: Drawing a Donut](images/img_04.png)

I then applied a Gaussian Blur, as before with the reddish block (radius 75px).

![Figure 5: Blurred Donut](images/img_05.png)

## Smiley event horizon

At this point, we're at the final stage of our scientific graphic production. I
repeated the same procedure of adding layers, painting, and blurring.

![Figure 6: Egg Yoke Looking Thing](images/img_06.png)

You can experiment with blur radius values to find what looks right to you.

![Figure 7: Blurred Egg Yoke Thing](images/img_07.png)

Finally, I added some final sparkly highlights...

![Figure 8: Highlights](images/img_08.png)

Things here are of course very fuzzy. You can play around with your layers (opacity values, etc.) until you get a result you like.

Here's my black hole!

![Figure 9: Finished](images/img_09.png)

You can use your new black hole image(s) in applications like this curiosity
driven graphic: 

![Figure 10: Important Questions](images/img_10.png)

<hr>
I generated an HTML document for this document using `pandoc` and
[this](https://gist.github.com/killercup/5917178) CSS sheet by killercup.

```bash
pandoc README.md -c pandoc.css -so index.html
```
