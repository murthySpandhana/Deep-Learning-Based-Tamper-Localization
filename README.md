# Semi‑Fragile Watermarking for Tamper Detection

## About
A digital watermarking scheme that balances robustness and sensitivity: it survives benign transformations (e.g., compression, resizing) but flags malicious edits. Watermarks are imperceptibly embedded into images, enabling precise detection and localization of unauthorized tampering while preserving high visual fidelity.

## Features
- **Semi‑Fragile Embedding**  
  Embeds invisible watermarks that endure common image processing but break upon tampering.
- **Tamper Detection & Localization**  
  Generates tamper maps highlighting altered regions at the pixel level.
- **High Visual Quality**  
  Maintains negligible perceptual distortion in watermarked images.
- **Configurable Parameters**  
  Adjust watermark strength, block size, and detection thresholds.

## Tech Stack
- **Language:** Python
- **Core Libraries:** NumPy, OpenCV, PyWavelets  
- **Visualization:** Matplotlib, Seaborn  
