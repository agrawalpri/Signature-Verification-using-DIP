# Signature-Verification-using-DIP
To verify the authenticity of signatures using image processing techniques.
#Steps
1. Image Selection:

User selects both original and forged signatures via file dialog

2. Preprocessing:

Grayscale conversion

Gaussian blur to reduce noise

Binary thresholding

Resize for uniformity

3. Edge Detection:

Canny edge detector

4. Comparison:

Calculate Mean Squared Error (MSE) between edge maps

Decision based on threshold


