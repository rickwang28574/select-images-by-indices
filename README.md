# Select Images by Indices

This Python script selects a specific set of images from a folder containing images numbered from 1 to 1000, and copies them to a specified destination folder. The script uses the `os` and `shutil` libraries in Python.

## Usage

1. Clone or download this repository to a local folder.
2. Open the script file `main.py`.
3. Modify the following variables:
   - `src_folder`: the source folder path.
   - `dst_folder`: the destination folder path.
   - `selected_indices`: the list of indices to select.
4. Run the script.
5. The selected images will be copied to the destination folder.

## Notes

- If the source folder contains other files, those files will also be copied.
- If you only want to copy specific file types, you can add a conditional statement while traversing the folder.
- If the selected images already exist in the destination folder, they will be overwritten.