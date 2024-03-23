# ro-client
### Creating the client
1. Download a raw kRO client on [Nemo website](http://nemo.herc.ws/downloads/) and take note of its version.
2. Download a corresponding client .exe on [Nemo website](http://nemo.herc.ws/clients/) that is a lower version and close to the raw client version above.
3. Install the raw kRO client, then copy the entire Ragnarok install folder to a clean folder.
4. Download and add the [RO Patcher Lite](https://nn.ai4rei.net/dev/rsu/) to the root of this Ragnarok folder. Run and wait until it finishes updating.
5. Download and add the [RO OpenSetup](https://nn.ai4rei.net/dev/opensetup/) to the root of this Ragnarok folder.
6. Download and add the [RO Translation Project](https://github.com/llchrisll/ROenglishRE) to a new folder.
7. On RO Translation Project, run [Tools/ClientGenerator.bat](https://github.com/llchrisll/ROenglishRE/blob/master/Tools/ClientGenerator.bat).
8. Open a new GRF in GRF Editor, then copy the data folder generated above into the program, then save it as anything other than data.grf into the new Ragnarok folder.
9. Copy the System and .txt files generated above into the new Ragnarok folder.
10. Create a new DATA.INI file into the new Ragnarok folder containing the following code:
```
[Data]
0=data_en.grf <- the name of the .grf generated in step 8.
1=data.grf
```
11. Download WARP on [Github](https://github.com/Neo-Mind/WARP). Select the client downloaded in step 2 and click on load sources. After that, correct the references to .lub files related to the translation folder. Then apply patches.