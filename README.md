# Cloud Based Analysis of Cobbles from Seabed Imagery using SegmentEveryGrain

---


This is a workflow on how to use the SegmentEveryGrain with Google Colab, note this is for demonstration only and to run large datasets specialised computer resource will be required.

This work is based upon https://github.com/zsylvester/segmenteverygrain

with adaptions based on their example workbook
https://github.com/zsylvester/segmenteverygrain/blob/main/notebooks/Segment_every_grain_colab.ipynb

Sylvester, Z., Stockli, D. F., Howes, N., Roberts, K., Malkowski, M. A., Poros, Z., Martindale, R. C., & Bai, W. (2025). Segmenteverygrain: A Python module for segmentation of grains in images. Journal of Open Source Software, 10(112), 7953. https://doi.org/10.21105/joss.07953

---
Please use the [USER_INTERFACE_Segment_every_grain_Cefas_Workflow.ipynb ](https://colab.research.google.com/github/CefasRepRes/CEFAS_SegmentAnyGrain_example/blob/main/USER_INTERFACE_Segment_every_grain_Cefas_Workflow.ipynb?authuser=1#scrollTo=E2HCqcJ2T_Be) using the 6 example images included in this repository. 
Project funded under EMODnet Geology.

Created By Hayden Close (Cefas)
hayden.close@cefas.gov.uk

The purpose of this repository is to provide an easy to use colab workbook to enable the segmentation of sediment grains from seabed imagery. See below for example imagery. 
The workflow is ran entirely from USER_INTERFACE_Segment_every_grain_Cefas_Workflow.ipynb with functions brough automatically from CefasCobblesTools.ipynb with example images too selected using widgets.
<img width="5184" height="3456" alt="WWBF_CEND0121_WWBF013_STN_180_A1_006" src="https://github.com/user-attachments/assets/1f194fdb-973b-4752-98bb-bd8d5b43bd68" />


<img width="1500" height="1000" alt="WWBF_CEND0121_WWBF013_STN_180_A1_006" src="https://github.com/user-attachments/assets/33664600-cc44-4e6e-ba38-fe134c4181bb" />

Your own imagery can be used as long as a spatial scale is available, such as laser scaling commonly used in seabed imagery. The scale is used to convert pixel measurements into real-world dimensions, allowing individual grains to be measured and characterised by metrics such as major and minor axis length, roundness (shape), and phi-scale grain-size distributions.
<img width="608" height="473" alt="image" src="https://github.com/user-attachments/assets/91e523a0-aa8c-461a-accf-d7371a44eeea" />
