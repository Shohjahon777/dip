# Digital Image Processing — Lab Work

Course notebooks and lab assignments for the Digital Image Processing (DIP) course.

---

## Repository Structure

```
DIP_WORKS/
├── Week 01/                         # OpenCV Fundamentals
│   ├── 01_opencv_basics.ipynb       # Core OpenCV functions reference
│   ├── 02_image_processing_without_opencv.ipynb  # NumPy-only processing
│   └── 03_reading_images_extended.ipynb           # Image I/O deep dive
│
├── Week 02/                         # Image Operations
│   ├── 00_beginning.ipynb           # Week 2 environment setup
│   ├── 01_reading_writing_displaying.ipynb        # I/O and display details
│   ├── 02_grayscaling.ipynb         # Grayscale conversion methods
│   ├── 03_cropping.ipynb            # ROI extraction and slicing
│   ├── 04_color_spaces.ipynb        # RGB, HSV, LAB, YCrCb
│   └── lab2.ipynb                   # Lab 2: Arithmetic operations on images
│
├── Week 03/                         # Image Enhancement
│   ├── 05_alpha_channel_channels.ipynb   # Alpha channel and channel ops
│   ├── 06_bitwise_operations.ipynb       # AND, OR, XOR, NOT and masking
│   ├── 07_drawing_and_annotation.ipynb   # Lines, shapes, text
│   ├── 08_arithmetic_operations.ipynb    # Add, subtract, multiply, blend
│   ├── 09_brightness_contrast.ipynb      # Linear brightness/contrast
│   ├── 10_gamma_correction.ipynb         # Non-linear gamma correction
│   └── lab3.ipynb                        # Lab 3: Geometric transformations
│
└── Week 04/                         # Thresholding and Binarization
    ├── 11_thresholding_binarization.ipynb  # All cv2.threshold() types
    ├── 12_otsu_binarization.ipynb          # Otsu's automatic method
    ├── 13_adaptive_thresholding.ipynb      # Adaptive thresholding
    └── lab4.ipynb                          # Lab 4: Grayscale, mirror, bit-planes
```

---

## Week Summaries

### Week 01 — OpenCV Fundamentals
Introduction to OpenCV and basic image operations.
- Reading, writing, displaying images (BGR vs RGB)
- Image properties: shape, dtype, size
- Color conversion, resize, crop, flip, rotate
- Pixel access, drawing, arithmetic
- NumPy-based processing without OpenCV

### Week 02 — Core Image Operations
Deeper exploration of image I/O and fundamental transformations.
- Image formats: JPEG vs PNG (lossy vs lossless)
- Grayscale conversion and luminance formula
- Cropping with NumPy slicing (view vs copy warning)
- Color spaces: RGB, HSV, LAB, YCrCb
- **Lab 2:** Add/subtract/multiply/divide intensity values per channel

### Week 03 — Image Enhancement
Enhancement techniques and low-level operations.
- Alpha channels and RGBA images
- Bitwise operations (AND, OR, XOR, NOT) with masks
- Drawing lines, shapes, and text on images
- Arithmetic operations (add, subtract, blend with addWeighted)
- Linear brightness and contrast adjustment
- Gamma correction (non-linear intensity mapping)
- **Lab 3:** Geometric transformations — translation, rotation, scaling, shearing

### Week 04 — Thresholding and Binarization
Converting grayscale images to binary for segmentation.
- All 5 `cv2.threshold()` types
- Otsu's automatic optimal threshold selection
- Adaptive thresholding for non-uniform lighting
- Histogram analysis for threshold selection
- **Lab 4:** Color→Grayscale, mirror effect, image negative, bit-plane slicing

---

## Setup

```bash
# Install dependencies
pip install opencv-python numpy matplotlib pillow

# Or with the provided environment
uv sync
```

**Python version:** 3.11+

---

## Image Files

Each week folder contains the images used in that week's notebooks:
- `sealion_hero.png` — main sample image
- `images.jpg` — secondary sample image
