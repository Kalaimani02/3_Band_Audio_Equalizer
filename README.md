# 3 Band Audio Equalizer
The 3-band Audio equalizer is designed with **Active filters** built using **Op-Amps** and potentiometers. The user can easily adjust the bass, treble, and mids using the potentiometer and get the required mix. The entire circuitry is designed and simulated in Proteus software.
## Circuit
![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/b0f1fdb2-7a99-422c-9d09-cc77ac379682)
## Working
- The Circuit consists of 3 parts:<br>
    1. Low pass filters – For Bass (Low frequencies 20 Hz – 500 Hz)<br>
    2. Band pass filter – For Mid band (Mid frequencies 500 Hz – 2KHz)<br>
    3. High pass filter – For Treble (High frequencies 2KHz – 20KHz)<br>
- Only the Low pass filter is of 2nd order to make the transition band much steeper.
- Then the potentiometer at the output of each filter is used to control the level of 
that particular band in the output audio.
- Finally there is a summing amplifier to sum all the individual filter contributions 
and we get the final output audio into the speaker.<br>
## Simulation Results
### Bass Test
Input Audio            |  Output Audio (Bass Boosted)
:---------------------:|:-------------------------:
![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/9c871b5b-35c1-4f09-b568-bdb9fdc93e72) | ![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/530d9623-ffd5-4436-a4b7-082f1ad77bac)

### Mid Band Test
Input Audio            |  Output Audio (Mid Band Boosted)
:---------------------:|:-------------------------:
![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/8fb5e668-590c-49cb-8f14-717f937ac728) | ![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/6a0c48e7-6fee-4d01-970e-9a2e6042218f)

### Treble Test
Input Audio            |  Output Audio (Treble Boosted)
:---------------------:|:-------------------------:
![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/b7074250-cdc5-42e4-b5a3-9b1229a0e745) | ![image](https://github.com/Kalaimani02/3_Band_Audio_Equalizer/assets/89019323/7f414426-5a62-4c72-a9db-4cd76f943c30)

## References
 - https://www.electronics-tutorials.ws/filter/filter_7.html
 - https://www.electronics-tutorials.ws/filter/filter_5.html
 - https://www.electronics-notes.com/articles/analogue_circuits/operational-amplifier-op-amp/virtual-earth-mixer-summing-amplifier.php





