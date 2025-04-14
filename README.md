//       ESP32-S3-Touch-LCD-7
//       WAVESHARE
//////////////////////////////////////
//       Arduino IDE ----> Strumenti:
//       Flash Size "8MB (64Mb)"
//       PSRAM: "OPI PSRAM"


//       Libraries
//       GFX_Library_for_Arduino
//       TouchLib   url=https://github.com/mmMicky/TouchLib     

//       Driver LCD   ST7262
//       Driver Touch GT911

//       I2C
//       SDA 8
//       SCL 9
//       INT 4
//       RES -1

//       SPI
//       MISO -1
//       MOSI 6
//       SCK  7
//       CS   5
//       DC   4

//       default 0 BACKLIGHT_TYPE_SWITCH_GPIO
//       default 1 BACKLIGHT_TYPE_SWITCH_EXPANDER
//       default 2 BACKLIGHT_TYPE_PWM_LEDC
//       default 3 BACKLIGHT_TYPE_CUSTOM

//       GT911_SLAVE_ADDRESS1  = 0X5D
//       GT911_SLAVE_ADDRESS2  = 0X14

//       Arduino_ESP32RGBPanel *rgbpanel = new Arduino_ESP32RGBPanel(
//       5 /* DE */, 3 /* VSYNC */, 46 /* HSYNC */, 7 /* PCLK */,
//       1 /* R0 */, 2 /* R1 */, 42 /* R2 */, 41 /* R3 */, 40 /* R4 */,
//       39 /* G0 */, 0 /* G1 */, 45 /* G2 */, 48 /* G3 */, 47 /* G4 */, 21 /* G5 */,
//       14 /* B0 */, 38 /* B1 */, 18 /* B2 */, 17 /* B3 */, 10 /* B4 */,
//       0 /* hsync_polarity */, 8 /* hsync_front_porch */, 4 /* hsync_pulse_width */, 8 /* hsync_back_porch */,
//       0 /* vsync_polarity */, 8 /* vsync_front_porch */, 4 /* vsync_pulse_width */, 8 /* vsync_back_porch */,
//       1 /* pclk_active_neg */, 16000000 /* prefer_speed */, false /* useBigEndian */,
//       0 /* de_idle_high */, 0 /* pclk_idle_high */, 0 /* bounce_buffer_size_px */
//       );
