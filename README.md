====== 

1. Decompress and copy the following folders into the appropriate places :  

`$ tar xvf lib_cmake_TensorflowCC.tar.gz`  
`$ sudo cp -rv usr/local/lib/cmake/ /usr/local/lib/`  

`$ tar xvf lib_tensorflow_cc.tar.gz`  
`$ sudo cp -rv usr/local/lib/tensorflow_cc/ /usr/local/lib/`  

`$ tar xvf include_tensorflow.tar.gz`  
`$ sudo cp -rv usr/local/include/tensorflow/ /usr/local/include/`  

2. Add following line into ~/.bashrc  

`export LD_LIBRARY_PATH=/usr/local/lib/tensorflow_cc:${LD_LIBRARY_PATH}`  
