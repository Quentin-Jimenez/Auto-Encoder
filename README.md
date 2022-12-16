# Comparison of Auto-Encoding Techniques with Simple and Complex Data
Image compression has existed almost as long as digital images, and it is widely credited
for allowing the proliferation of computer-based imagery. In 1992 one of the first standardized
compression algorithms, JPEG, was introduced, allowing for images to be stored and
compressed to about 10x their original size. JPEG uses a variation of the FFT algorithm to
efficiently compress images, but it is not reversible and therefore results in lossy compression.
Further algorithms have improved upon JPEG in other areas, allowing for transparency, motion,
and lossless compression.

Recent innovations in artificial intelligence have birthed a new form of image
compression, using neural networks to compress images to latent space, and then reversing the
process to produce the original image. By training the AI on groups of images, the neural
network is able to recognize patterns in the image and reduce the image size, maintaining
representations of the image while decreasing the size of the data.

This works similarly to JPEG, which uses DCT to reduce an image signal into the
frequency domain, then reducing the image down to its most significant parts, shrinking the size
of the image. Auto-encoding is also lossy like JPEG, since the inverse neural-network process
does not completely replicate the original image. This limits its use, similar to JPEG where after
several iterations the image can become unrecognizable.

Although it has limitations, auto-encoding improves with time and training, which may
allow it to be used as a standard. While it does seem to have similar drawbacks as the JPEG
format, the more these algorithms learn the better they will become at efficient compression and
the loss-prevention. This project showcases a simple auto-encoding algorithm to display how it
works and how it can be improved.

<p align="center">
<img src="http://puu.sh/JuisA/f485c62174.png" alt="Latent"/>
<img src="http://puu.sh/Juit9/0eeb70f83a.jpg" alt="Latent"/>
<img src="http://puu.sh/Juite/e4d0ea3392.jpg" alt="Latent"/>
<img src="http://puu.sh/Juitm/dbffa146d6.jpg" alt="Latent"/>
</p>
