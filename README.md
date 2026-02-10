# FM Receiver in GNU Radio

This repository contains an FM receiver implemented in **GNU Radio**.  
The flowgraph receives FM broadcast signals and uses an FFT waterfall display to easily identify available channels.

## Contents
- `FM_Reciver_GNU_Radio.grc` – GNU Radio Companion flowgraph
- `FM_Reciver_flowgraph.png` – Flowgraph overview
- `FM_waterfall_FFT_Rx.png` – Waterfall/FFT display of received FM channels

## Waterfall Display
The waterfall plot visualizes the FM spectrum and makes it easier to identify active channels.  
The receiver includes sliders to adjust the center frequency and the receiver gain if needed.

In this setup, a low-quality antenna was used for low frequencies, which results in weak received signals, but still allows listening to the broadcast and receiving the signals.

![FM Waterfall FFT](FM_watterfall_FFT_Rx.png)


## Flowgraph
![FM Receiver Flowgraph](FM_Reciver_flowgraph.png)

