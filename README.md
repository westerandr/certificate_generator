# Certificate Generator

This Python script generates certificates for a list of names provided in the `name_list` variable. The certificates are created by overlaying the names on a certificate template image using a specified font. The resulting certificates are saved as PDF files in the `certificates` directory.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Pillow library (PIL) for image processing: Install using `pip install Pillow`

## Usage

1. **Prepare your certificate template:**
   - Ensure your certificate template is in a supported image format (e.g., PNG, JPEG).
   - Name the template image file `cert.png` and place it in the same directory as the script.

2. **Prepare your font file:**
   - Choose a TrueType font (TTF) file to be used for the names on the certificates.
   - Name the font file `BRUSHSCI.TTF` (or update `font_path` variable in the script) and place it in a `fonts` directory in the same location as the script.

3. **Modify the list of names:**
   - Open the script in a text editor and update the `name_list` variable with the names you want to generate certificates for.

4. **Run the script:**
   - Open a terminal or command prompt and navigate to the directory containing the script.
   - Run the script by executing `python script_name.py` (replace `script_name.py` with the actual name of your Python script).

5. **Generated Certificates:**
   - The generated certificates will be saved as PDF files in the `certificates` directory.

## Notes

- Ensure the font size and location settings in the script (`font_size`, `location`) are appropriate for your certificate template.
- Verify the color settings (`text_color`) for proper visibility against the certificate background.
- Test the script with a small set of names first to ensure the certificates are generated as expected.
