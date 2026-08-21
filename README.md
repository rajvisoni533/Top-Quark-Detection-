# Deep-Learning-for-Real-Time-Top-Jet-Tagging
End-to-end MATLAB&reg; workflow for Real-Time Top Quark Jet Tagging is presented. 
Live script contains a predictive model, based on deep convolutional 
neural network, that discriminates top quark (signal) jets from QCD plain 
vanilla (background) jets. Besides a predictive model, the workflow presented 
includes: accessing and preprocessing particle scattering data, transforming 
jets to 2D images, and code generation for deployment of the network on FPGA. 

**Setup**

To Run:
1. Download particle jets open datasets as instructed in the Reference Datasets section of
the Live script. Open Python, import part of the randomly sampled data as pandas 
dataframes and save in parquet format.
2. Import parquet data as a MATLAB table, preprocess jets to images and save to disc.
3. Build deep convolusional neural network using App designer&reg; and train network
using training datasets.
4. Check accuracy of the network on test datasets.
5. Deploy trained network on FPGA following Deploy Trained Network on FPGA section of the Live script.

**MathWorks Products** (https://www.mathworks.com)

Requires MATLAB release R2020a or newer
* [Deep Learning Toolbox](https://www.mathworks.com/products/deep-learning.html)
* [Statistics and Machine Learning Toolbox](https://www.mathworks.com/products/statistics.html)
* [Deep Learning HDL Toolbox](https://www.mathworks.com/products/deep-learning-hdl.html)
