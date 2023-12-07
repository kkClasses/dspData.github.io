# dspData.github.io
# for DSP Data 

import pickle
#Give path for the downloaded file
file_name = "faceData.pkl"
open_file = open(file_name, "rb")
loaded_list = pickle.load(open_file)
open_file.close()
trainx=loaded_list['trainx']
testx=loaded_list['testx']
trainlabel=loaded_list['trainlabel']
testlabel=loaded_list['testlabel']
