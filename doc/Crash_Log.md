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


## Header
