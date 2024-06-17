These documents provide details for performing a double robust triple crossfit on simulation and real data using python. 


In HDFPCA-function.ipynb, 
  we implement the functional PCA for high-dimensional functional data, i.e. the image data, on simulation study.

  
In DR-function.ipynb, 
  we documented how to build the double robust estimator and the relevant base learners in superlearner.

  
In Triple-crossfit-Simulation.ipynb, 
  we documented the generating of simulation data, the whole process of estimation of ATE by double robust estimator with triple crossfit, 
  double crossfit and without crossfit in the case of using superlearner, linearmodel and true model settings.

  
In newSimulation.ipynb, 
  We used slices of real MRI images to replace the images in "Triple-crossfit-Simulation.ipynb",
  to observe the universality of the double robust triple crossfit estimation for estimating the effect of complex images. 


"Real-data-imageprocess.ipynb", "Real-data-dataprocess.ipynb" and "Real-data-triple-crossfit.ipynb" document the processing of the MRI images and clinical data in the ADNI dataset, and the use of double robust triple crossfit estimatio for the ADNI dataset
