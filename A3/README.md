# PLUS_softwaredev_2025_Flosrepo

## Assignment #3 Function

Create an environment based on the yml file profided in this folder
conda env create --file envname.yml
If the .yml is in the directory you are in (which it should be) and is called
environment.yml (which it is not), you can simplify the command:
conda env create

## Furthermore you need a sentinel Image ##
I downloaded an image from:
https://apps.sentinel-hub.com/eo-browser/?zoom=12&lat=47.80151&lng=13.04489&visualizationUrl=U2FsdGVkX1%2Bmw8N5QTfzXe5VnPcJZAIG%2Bu%2Fx%2FP0jEeaERC7HYOVWrV9E8Vz7NNmw53ZJCmjkXndGjlwPv505xjEI65OR4XICGYam1lw2cdQmoQFjrpvAVNSLBe00jovZ&datasetId=S2L2A&fromTime=2025-04-04T00%3A00%3A00.000Z&toTime=2025-04-04T23%3A59%3A59.999Z&layerId=1_TRUE_COLOR&demSource3D=%22MAPZEN%22 

but you can use any Sentinel 2 image. Keep in mind that you need Band 4 and Band 8 for the NDVI

The code to calculate the NDVI can be found in calculateNDVI.ipynb
