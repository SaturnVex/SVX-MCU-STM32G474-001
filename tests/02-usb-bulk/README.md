# USB Full-Speed Bulk Echo Test

**Target:** SVX-MCU-STM32G474-001 (STM32G474RBT6)

Program via SWD, connect USB FS and run the PC-side Bulk echo verification as documented.

## Files

- [Test setup, pinout, import and verification guide (PDF)](SaturnVex_STM32G474_USB_Bulk_Test_Guide_EN.pdf)
- [Download source project for STM32CubeIDE (ZIP)](STM32G474_USB_BULK_LED_SaturnVex.zip?raw=true)

## Run

1. Read the PDF guide, especially wiring, supply, and test safety requirements.
2. Download and extract `STM32G474_USB_BULK_LED_SaturnVex.zip`.
3. Import the extracted STM32CubeIDE project as instructed in the PDF, then build and flash with ST-LINK.
4. Perform the test and compare the result with the verification criteria in the PDF.

Source projects retain their supplied structure and original third-party notices.

[← All tests](../README.md) · [← Product home](../../README.md)
