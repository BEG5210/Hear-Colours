# Hear Colours
A Program that allows one to convert an immage into a sound file

This program is not meant to be one of those programs that converts a file into a sound file (im not sure what filetype yet), like those exe sound waterfalls all over youtube. no. what this program is meant to do, is literally convert every pixel into a sound wave based on its chrominance, and its relevent frequency value, and from its luminance, the volume. with this, you can hear every pixel!

Im not sure what language to use, and i have NO IDEA what im doing. if anyone is willing to contribute, feel free to do so.
(I will use python)




# The way the software will work
1. Load the immage
2. Avg neighbouting pixels to a user specified reselution
3. with the output immage, convert it into two immages: A Chrominance and luminance immage
4. for each pixel (for the sake of this explination i will explain like its one pixel) do the following:
1. Get the chrominance, on a scale from zero to 10. give it a log 10, and thats the volume value multiplier
2. get the luminance, find the exact colour and frequency, and add 1 to the given colour frequency
generate sound frequencies for all the pixels and add them all together. bang. left side of picture is left ear, right side is right. i dont know what im dong




I will create a project design plan (a proper one!), and once i complete it i will upload it here and commence the bababoey :)
