# CRASH LOG

## Bind




<div class="admonition note" name="html-admonition" style="background: #04202d; padding: 10px; text-align: left;">

1. Power On Radio.
1. On <span class="blue">Radio</span>: Long press: 'Sys' > Tools => Express LRS

1. Find and Select <span class="blue">[Bind].</span>

1. Put <span class="amber">Receiver</span> into Bind Mode by Unplugging and Plugging <span class="amber">3x</span>.  

1. On <span class="amber">Receiver</span>, look for Double Blink state.

</div> 

<!-- Receiver LED Status Table -->
<div class="my-table-wrapper">

| LED Indication                                                                          | Status                                              |
|-----------------------------------------------------------------------------------------|-----------------------------------------------------|
| ![Connected](https://www.expresslrs.org/assets/images/LED_ON.gif) &nbsp;&nbsp; Solid on | Connected to a transmitter, or bootloader mode enabled |
| ![Binding](https://www.expresslrs.org/assets/images/LEDSEQ_BINDING_10_10_10_100.gif) &nbsp;&nbsp; Double blink       | Binding mode enabled. <span class="amber">READY TO BIND</span>                          |
| Slow blink 500ms   | Waiting for connection from transmitter            |
| Triple blink       | Connected to transmitter but mismatched model-match configuration |
| Medium speed       | Radio chip not detected                            |
| ![Wifi](https://www.expresslrs.org/assets/images/LEDSEQ_WIFI_UPDATE_2_3.gif) &nbsp;&nbsp; Fast blinking      | WiFi mode enabled                                  |

</div>
<!-- End Table -->



::: {note}
:class: custom-blue

If Binding is not initiated within one minute, receiver will enter WIFI mode [Fast blinking].
:::

![Bind Connect](Images/Receiver/Bind-Connect-C.png)

<br>

![C](Images/Receiver/Bind-Connect-C-cu.png)

<br>

<div class="bg-highlight">

- "C" in the upper right hand corner denotes a successful BIND.  

- Audio: "Telemetry Recovered" 

</div>


<p></p>
<p></p>


::: {card}
<div id=Vid-Link name="Vid-Link" style="padding: 15px 15px 40px 15px; text-align: center;">

<div class="bg-highlight">

  <a href="https://www.youtube.com/watch?v=N0ajKoef3qs" target="_blank" rel="noopener noreferrer">
    <img src="https://img.youtube.com/vi/N0ajKoef3qs/maxresdefault.jpg" alt="YouTube Video Thumbnail" />
  </a>

  <u>[Bardwell Elrs Bind](https://www.youtube.com/watch?v=N0ajKoef3qs)</u>

</div>

</div>
:::

---

## RSSI

[RSSI (Pawel Spychalski FPV University)](https://youtu.be/XyIDTHIFjV0)

<div class="admonition note" name="html-admonition" style="background: #04202d; padding: 10px; text-align: left;">

  - R: Received
  - S: Signal
  - S: Strength
  - I: Indication

</div>

SNR

![Snr](./Images/Receiver/SNR-Signal_To_Noise.png)

<br>

Link Quality (LQ)

![Link Quality](./Images/Receiver/Link_Quality.png)
... and decoded. It is a ratio.  

<br>

[RSSI Find Model Trick - Painless 360](https://youtu.be/diuxIwViSnY?t=179)

Technique:

    - With the model still powered on (battery connected), walk in the direction you last saw it.

    - Access the telemetry or sensor menu on your radio to check RSSI values.

    - As you walk closer to the model, the RSSI number will increase.

    - Every so often, stop and sweep your transmitter in a wide arc (180°) while watching the RSSI   
      reading. This helps identify the direction of strongest signal—your transmitter’s antenna is most sensitive on the sides, not the tip.

    - Continue walking in the direction where RSSI is strongest and keep repeating the process.

    - As you approach the model, the RSSI value will increase much more rapidly—when nearing 85 or higher, you are within a few meters.

Final Search: When you see very high RSSI, stop and sweep your transmitter in a full circle to fine-tune the exact direction.

---

## Battery Packs

- 21700

![Diagram](./Images/Battery_Pack/Diagram-21700.png)

<bt>

![Diagram Close Up](./Images/Battery_Pack/Diagram_Battery_Pack_CU.png)