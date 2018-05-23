# Nordic nRF5 SDK v15.0.0
Mirror of the latest (v15.0.0) Nordic nRF5 SDK, downloaded from [Nordic DevZone](https://developer.nordicsemi.com/nRF5_SDK/nRF5_SDK_v15.x.x/) (nRF5_SDK_15.0.0_a53641a.zip).

Please refer to Nordic's [official documentation](http://infocenter.nordicsemi.com/index.jsp?topic=%2Fcom.nordic.infocenter.sdk5.v15.0.0%2Findex.html) for any questions.

The following files have been removed as they are not related to GCC-based development:

- all iar, keil, arm4, arm5_no_packs and ses directories and some of the arm directories related to MKD ARM (Keil)
- all IAR project files (.eww)
- all MDK ARM (.lib) and IAR libraries
- all assembler files related to MDK ARM, IAR and SES
- ./nRF5x_MDK_8_16_0_IAR_NordicLicense.msi
- ./nRF5x_MDK_8_16_0_Keil4_NordicLicense.msi

Also most of the documentation was omitted for clarity and size.

The complete list of all files removed from the original *nRF5_SDK_15.0.0_a53641a.zip* is in [removed_files_and_directories.txt](https://github.com/bojanpotocnik/nRF5-SDK/blob/master/removed_files_and_directories.txt).

## Licensing
This is **not** an official repository, but provided as a mirror for my projects using this SDK, eventualy containing any fixes and changes to better suit my needs (as few as possible).

Please refer to [Nordic's Licensing Documentation](https://github.com/bojanpotocnik/nRF5-SDK/blob/master/license.txt). All copyright notices and disclaimers have been maintained in their entirety within this repository.

Thanks to [jamesmunns](https://github.com/jamesmunns/nRF5-sdk) repository (mirror of the v13.0.0 SDK) for the idea and basis of this readme file.
