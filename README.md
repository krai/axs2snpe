# axs2snpe-dev

Recipe for downloading the SNPE SDK, libraries and models.
Please keep in mind the SNPE SDK development environment is limited to Ubuntu version 18.04.
Setup Link: [https://developer.qualcomm.com/sites/default/files/docs/snpe/setup.html](https://developer.qualcomm.com/sites/default/files/docs/snpe/setup.html)

Download and extract the SNPE library.
```
axs byquery extracted,snpe_lib
```

Download the pre-generated SNPE resnet50 DLC.
```
axs byquery snpe_dlc,model_name=resnet50
```

Download the pre-generated SNPE resnet50 quantized DLC.
```
axs byquery snpe_dlc,quantized,model_name=resnet50
```

If you want to generate the DLCs yourself there are instructions on the docs linked above for both generating and quantizing DLCs.
