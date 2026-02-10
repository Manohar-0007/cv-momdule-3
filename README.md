# Image Blurring: Spatial Convolution vs Fourier Multiplication (Python)

## Goal
Show that blurring by spatial convolution produces the same result as multiplying by the Fourier-domain filter:
F{f*h} = F{f} · F{h}

## Files
- blur_spatial_vs_fourier.py : runs spatial and Fourier blurring and compares results
- input.jpg : test image (place in repo root)
- outputs/ : generated results

## Setup
```bash
pip install -r requirements.txt
