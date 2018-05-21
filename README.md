# SubGHz technologies dataset, Sigfox, LoRA and IEEE802.15.4g (subGHz)
## Dataset description
As part of eWINE, we provide a dataset comprises of IQ samples of the three subGHz technologies including Sigfox, LoRA and IEEE 802.15.4 (subGHz). From the three technologies, 8-classes of signals were generated including, 6 classes of LoRA with spreading factors (SFs) 7, 8, 9, 10, 11 and 12 each of bandwidith 125KHz, 1 class of sigfox transmitting dynamically on the sigfox channels c0, c180,...c400 of bandwidth 100Hz, and 1 class of IEEE802.15.4g (subGHz) of bandwith 600KHz. For each signal class, the data was captured for a duration of 120 sec (120,000,000 IQ samples per class). We consider a use case in which the technologies operate in Europe at the center frequency of 868MHz. For the sigfox case, a TD1207R radio was used as a sigfox transmitter, which was programmed to give a packet duration of 2.08 sec. Each packet was transmitted thrice on three dynamically selected channels yields a total duration of 3*2.08+2*0.0625 = 6.3650 sec. For the LoRA case, LoRA nodes were programmed to transmit with SFs 7, 8, 9, 10, 11 and 12 and the corresponding packet durations are: 0.0698, 0.12339, 0.214029, 0.428637, 0.8564 and 1.715, respectively. For the IEEE 8.2.15.4g (subGHz) case, a zolertia mote [1] was programmed to mimic the IEEE802.15.4 g(subGHz) transmission with a packet duration of 0.0162sec and data rate of 50kbps. A visualization of 4-classes of signals out of the 8-classes of signals is shown in Figure 1. 
![figure1](https://user-images.githubusercontent.com/24733570/39812955-e72dc7de-538e-11e8-840a-d9b331e3ef21.png)
## Dataset generation 
The setup that we used for generating the dataset for the 8-classes of the signals from the subGHz technologies is shown in Figure 2. It comprises of a USRP B200mini which is used for capturing IQ samples from the LoRA, Sigfox and IEEE 802.15.4 (subGHz) transmitters. The IQ samples were captured with a sampling rate of 1M samples/sec and the data was only captured when the radios were made ON by manual triggering.  
![drawing2](https://user-images.githubusercontent.com/24733570/39812996-0786ed6c-538f-11e8-959e-25c3b16f61d2.png)
## Reference
[1] https://github.com/Zolertia/Resources/wiki/RE-Mote

More information can be found in the deliverable accessable at (https://ewine-project.eu/wp-content/uploads/eWINE_D4.3_Final.pdf)
## Contact
For an access to the dataset, you are welcomed to contact adnan.shahid@ugent.be

