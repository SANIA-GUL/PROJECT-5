# PROJECT-5
SONET in Echoes

Step 1: 

This step generates long audio files of 12-sec duration from short audio files.

Step2:

This step generates the binaural reverberated mixtures at specific RT60 for a target at a specific angle in the range [15:15:90] and interferer at 0 degrees using either long or short audio files.

Step3:

Choose any of the following dereverb methods for mixture and generate the input for SONET
        Step3_Precedence_Effect_DMix.m
        Step3_SMIF_DMix.m 
        Step3_Spectral_Subtraction.m
        Step3_WPE.m
        Step3_WPE_and_SS.m
        
Step4:

Pass the dereverberated mixture through SONET ang generate ILD and IPD masks for target and interferer.

Step5: 

Apply the ILD/IPD masks over the mixtures and evaluate the estimated outputs.

Cite As: •	Sania Gul, M. S. Khan, and S. W. Shah.: “Enabling an anechoic U-Net based speech separation model for online and offline applications in reverberant conditions”, Applied Acoustics, Vol. 179, August 2021. 

