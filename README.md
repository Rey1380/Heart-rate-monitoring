# Heart-rate-monitoring
In this project, we detect and monitor the heart rate of a patient by using our designed IP Cores in Vivado HLS
For this purpose, a suitable Test Bench was written to read each line of the ECG.txt file and then extract the peak locations with Pick Detection IP Core. <br>
In the Heart Rate IP Core, the heart rate was extracted based on the sampling frequency (20 Hz) and sent to the Micro GPIO Input. <br>
In the microcontroller, it was converted into a suitable 7-Segmant code and displayed as two digits on the GPIO Output.
