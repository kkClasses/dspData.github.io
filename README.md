# dspData.github.io
# for DSP Data 

import pickle <br>
#Give path for the downloaded file <br>
file_name = "faceData.pkl"  <br>
open_file = open(file_name, "rb")  <br>
loaded_list = pickle.load(open_file)   <br>
open_file.close()   <br>
trainx=loaded_list['trainx']   <br>
testx=loaded_list['testx']   <br>
trainlabel=loaded_list['trainlabel']   <br>
testlabel=loaded_list['testlabel']  <br>
