# Removing EXIF data has never been this easy!
This Python3 script removes the EXIF data from all JPG files in its directory.

# Usage for the Python file:

1. Make sure that the pillow library is installed (Windows: pip install pillow, Ubuntu: sudo pip3 install pillow)
2. Put the Python script into the same directory that all your JPG files are in.
3. Run the Python script.


# Usage for the EXE binary:

1. Make sure that you run the 64-bit version of Windows 10.
2. Put the EXE file into the same directory that all your JPG files are in.
3. Open CMD in the correct path and use "certutil -hashfile remove_exif.exe SHA256" to calulate the SHA256 hash.
4. Make sure that the EXE has the following SHA256: ab0fb9fac9b9fa21a160dd856407a4c82def6cca75558c14384d455aecca1a6b
5. Run the EXE file.


# How did you create the binary?

I used "pyinstaller --onefile remove_exif.py" to convert the Python file into an EXE.

