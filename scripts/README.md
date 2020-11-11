# Scripts for Ender-3 V2
Scripts for my Ender-3 V2 as seen on the video series on Category5 Technology TV.

## Related Links

- **Video Series and Documentation:** https://cat5.tv/3dprinting

## Descriptions

### hyperlapse
A python script that takes any gcode and injects my hyperlapse button press trigger between each layer. Revised script is output to screen or you can pipe it into a new file.

Not only does hyperlapse automate the insertion process, placing trigger code between each layer to snap a picture for your hyperlapse, but it also retracts the filament to reduce stringing, and even returns to the print area prior to returning the filament to the hot end. I have also included an option for either left (default) or right switch positions.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/qaSmzV_p_Hg/0.jpg)](https://www.youtube.com/watch?v=qaSmzV_p_Hg)

Test from version 1.3 - I still need to lock my camera exposure, but the hyperlapse script worked perfectly. The only stringing you see is actually due to the model I printed (was a scan of a house from a drone).

![Sample](trigger_test_v1.2.gif)

Test from version 1.2 - Still a bit of an issue with the skirt, but the actual print goes well with almost no stringing. Extruder retraction 6mm and return is 7mm.
