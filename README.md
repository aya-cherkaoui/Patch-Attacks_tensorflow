# Patch-Attacks_tensorflow

Please open Patch_Attack_Tensorflow.ipynb where all the trainnings, reports and definitions of useful functions and classes are inside.


1. Install the necessary packages and import libraries;
2. Please change the variable DATA_DIR to your repository where your wish to save the trainned patchs and other important data;
3. Execute the code of all the definition of fonctions and two classes ModelContainer and MetaModel until the part of Patch Generation
4. Execute the white box, black box trainning process, every patch and data will be saved under DATA_DIR that you define at the beginning
5. After all the trainning, execute the evaluation to see the plot of performance of the patches generated


Image and Patch size are generally (299,299,3)
the attack target label here is 'toaster' and you can modify it to anything you want, but make sure it's in the category of objets that the classifiers are able to recognize
The trainning resulte with a wider difference between SCALE_MIN and SCALE_MAX works better
