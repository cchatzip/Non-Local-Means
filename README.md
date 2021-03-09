# Non-Local-Means
Image denoising using NLM algorithm

You can easily test the code using google colab by following the next 6 steps:
step 1: Add "!nvcc --version" instruction in a new cell 
step 2: Add "!pip install git+git://github.com/andreinechaev/nvcc4jupyter.git " instruction in a new cell 
step 3: Add "%load_ext nvcc_plugin" instruction in a new cell 
step 4: Change runtime type to GPU
step 5: Use the code provided in this folder in a new cell. Type the file name you want to process in the function getArray() -> fptr = fopen("file_name.txt","r");
step 6: Assign the image dimensions in the main function by changing the values of n,m. You can use the patchsize you wish by changing the global variables patch_w,patch_h.
