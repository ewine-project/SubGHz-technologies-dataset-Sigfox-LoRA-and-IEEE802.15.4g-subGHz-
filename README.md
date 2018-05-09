# SubGHz technologies dataset, Sigfox, LoRA and IEEE802.15.4g (subGHz)
## Dataset description
We provide a dataset comprises of IQ samples of the three subGHz technologies including Sigfox, LoRA and IEEE 802.15.4 (subGHz). From the three technologies, 8-classes of signals were generated including, 6 classes of LoRA with spreading factors (SFs) 7, 8, 9, 10, 11 and 12 each of bandwidith 125KHz, 1 class of sigfox transmitting dynamically on the sigfox channels c0, c180,...c400 of bandwidth 100Hz, and 1 class of IEEE802.15.4g (subGHz) of bandwith 600KHz. For each signal class, the data was captured for a duration of 120 sec (120,000,000 IQ samples per class). We consider a use case in which the technologies operate in Europe at a center frequency of 868MHz. For the sigfox case, a TD1207R radio was used as a sigfox transmitter, which was programmed to give a packet duration of 2.08 sec. Each packet was transmitted thrice on three dynamically selected channels giving a total duration of 3*2.08+2*0.0625 = 6.3650 sec. For the LoRA case, LoRA nodes were programmed to transmit with SFs 7, 8, 9, 10, 11 and 12 and the corresponding packet durations are: 0.0698, 0.12339, 0.214029, 0.428637, 0.8564 and 1.715, respectively. For the IEEE 8.2.15.4g (subGHz) case, a zolertia mote [1] was programmed to mimic the IEEE802.15.4 g(subGHz) with a packet duration of 0.0162sec and data rate of 50kbps. For the sake of visualization, 


