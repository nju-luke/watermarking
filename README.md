# watermarking
This is a project for blind watermarking using DWT and SVD.

How to use? 

```python
from watermarking import watermarking
watermarking = watermarking()
watermarking.watermark(img="lena.jpg", path_save=None)
watermarking.extracted(image_path="watermarked_lena.jpg",extracted_watermark_path = None)
```

With the previous code, there things have being done.

1. the initialization of watermarking will use 'watermark.jpg' as the default watermark, and set deault values for pywt. The deault watermark can be replaced with parameter `watermark_path`

2. `watermarking.watermark()`method will watermark the deault image 'lena.jpg', and generate a watermarked image 'watermarked_lena.jpg'. 

3. The watermark is extracted from the image 'watermarked_lena.jpg'  and saved as 'watermark_extracted.jpg'.

   