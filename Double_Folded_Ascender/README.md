# Double Folded Ascender Extruder - Release 1

# A Foreword from Mr. Rentable Socks

This is the Double Folded Ascender is the next mutation of the "Ascender" worm drive extruder family, boasting better performance across the board. OG Ascender and Folded Ascender are both geared at 40:1, which limits the usable range of the extruder due to forcing the motor into a high speed, low torque range. Double Folded Ascender cuts the ratio down to 20:1, and therefore can keep up with other extruders with higher acceleration, Pressure Advance, and feed rate. A well-built Double Folded Ascender should be able to run easily at 40mm^3/s, with 1.5k accel, and a PA value of 0.01 (klipper). Motor current can stay at 300-350mA. The PA value may sound low, but since the worm drive is not backdrivable, the motor doesn't act like a spring on the filament like with most extruders, which allows a small reduction in PA, even if the filament length between the drive gear and the hotend is the same.

The trick with Double Folded Ascender is that it is using a 2 start worm with a wheel with teeth spaced for 1 start worms. The extra "fold" comes from tilting the motor to correct for the helix angle mismatch between the worm and wheel.  Though not ideal, it works well and hasn't missed a beat.

This extra fold also comes with a drawback.  Double Folded Ascender is NOT mirrorable via slicers. Since when you mirror the parts in the slicer, the helix angle would swing in the opposite direction. The worm and wheel helix angle offset must stay the same in order to function. Therefore, for some builds that require a specific orientation like K3, there is a "mirrored" version available as well. DO NOT run a slicer-mirrored version of the standard parts, it will ruin your wheel.

# Improvements:
 - Reduced gear ratio to 20:1
 - Better PA handling
 - Higher acceleration values
 - Higher maximum throughput

# Notes:
 - 2 start worm.
 - For running above ~20mm^3/s, drilling and tapping the wheel for an m3 or m4 set screw (4-5mm length) is required to prevent slippage. Recommended to do in all cases.
 - Do not mirror parts in slicer.
 - This is an early version, bootstrapped off of a previous version.  Things will change significantly later, but mounting pattern should remain the same going forward.
 - No, I don't know why KHK sells a 2 start worm but not the matching wheel for 5mm bore, 4No, I don't know why KHK sells a 2 start worm but not the matching wheel for 5mm bore in a 40t variant.

![Folded Ascender](Images/double_folded_ascender.png)
