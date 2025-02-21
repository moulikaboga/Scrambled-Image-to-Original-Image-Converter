# Scrambled-Image-to-Original-Image-Converter
This project provides a simple yet effective solution for reconstructing an image that has been scrambled into smaller pieces. Using a predefined mapping, the program rearranges the scrambled image back to its original form.

Here is the **README.md** file without the original code so you can directly paste it into your GitHub repository:  

```md

## Features  
- Automated Image Reconstruction – Rearranges scrambled image tiles into their correct positions.  
- Uses Predefined Mapping – Supports a 5x5 grid-based scrambling pattern.  
- Simple and Fast Processing – Uses Pillow (PIL) for image manipulation.  
- Customizable Mapping – Can be modified for different image scrambling patterns.  
- Outputs a Restored Image – Saves the reconstructed image in PNG format.  

---

## How It Works  
1. The scrambled image is loaded into the program.  
2. A mapping table defines how scrambled pieces correspond to their original positions.  
3. The script extracts and rearranges the pieces into the correct order.  
4. The final reconstructed image is saved as reconstructed_image.png.  

---

## Requirements  
Make sure you have Python 3.x installed along with the required libraries:  

```bash
pip install pillow
```

---

## Usage  
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Place your scrambled image (jigsaw.webp) in the project directory.  
3. Run the script:  
   ```bash
   python reconstruct.py
   ```
4. The reconstructed image will be saved as reconstructed_image.png.  

---

## Example  
### Input: Scrambled Image (jigsaw.webp)  
### Output: Reconstructed Image (reconstructed_image.png)  

---

## Customization  
You can modify the mapping data inside the script to support different scrambling patterns.  

---

## License  
This project is open-source and available under the MIT License.  

---

## Author  
- Your Name  
- GitHub: [Your GitHub Profile](https://github.com/your-username)  
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile)  

---

Star this repository if you find it useful.
