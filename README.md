# JPG-to-PNG-converter
This project is a bit more complicated than the previous 2; using a few different functions. It takes all the JPG images you have saved in a folder and converts them to PNG images and saves them in another folder. It does this by using a combination of SYS, OS and PILLOW functions/ library. Image_folder = Sys.argv[1] function allows me to assign in the terminal that the second argument I give will be the original image folder. The first argument I give to the terminal is the python file to run the code.  Then I assign output_folder = sys.argv[2] so the 3rd argument I give the terminal will be the output folder. Next I used an if statement along with OS (operating system) to see if the output folder already existed or not and if it didn’t then to make one. Finally with a for loop I looped through all the images in my input folder and saved them all as PNG files and changed the names. 
