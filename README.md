# Non-Local-Means
Image denoising using NLM algorithm

You can easily test the code using google colab by following the next 6 steps:
1. Add "!nvcc --version" instruction in a new cell 
2. Add "!pip install git+git://github.com/andreinechaev/nvcc4jupyter.git " instruction in a new cell 
3. Add "%load_ext nvcc_plugin" instruction in a new cell 
4. Change runtime type to GPU
5. Use the code provided in this folder in a new cell. Type the file name you want to process in the function getArray() -> fptr = fopen("file_name.txt","r");
6. Assign the image dimensions in the main function by changing the values of n,m. You can use the patchsize you wish by changing the global variables patch_w,patch_h.

Note: script1 and script2 are matlab scripts. Script1 is used to extract the pixel numbers from an image to a .txt file and script2 is used to visualize the unfiltered image, the filtered image and the residual.
