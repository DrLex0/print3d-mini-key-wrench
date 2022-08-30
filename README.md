# Mini Hex Key Socket Wrench
*3D printable key-style socket wrenches for M2, M2.5, M3, M4 nuts, and hex screwdriver bits (formerly thing:1959962)*

### License
[Creative Commons - Attribution](https://creativecommons.org/licenses/by/4.0/)

### Gallery

![Photo 1](thumbs/photo1.jpg)[🔎](images/photo1.jpg) ![Photo 2](thumbs/photo2.jpg)[🔎](images/photo2.jpg)


## Description and Instructions

This is a simple key- or thumbscrew-shaped socket wrench for metric nuts between M2 and M4, for those times when space is cramped.

Sizes provided are M2, M2.5, M3, and M4. There is also a model that fits hex screwdriver bits.

Unless you can print these in actual metal, you should of course not expect too much from these, they are meant for light duty work that does not involve a lot of torque.


### Printing

The strength of the end result will depend a lot on the material and print parameters. For most consumer printers, the best option is probably **PETG** in 0.1 or 0.15 mm layers, with minimal cooling. If you can print in polycarbonate, it would be better, but even then you should keep in mind that plastic is not metal.

Print with 4 perimeters. This should already result in the models being almost solid regardless of the infill, but you can still set infill to 100% to fill up any remaining voids.

Unfortunately you would be extremely lucky if you simply print this and get an immediate perfect fit. There is too much variability in 3D printers and even in the 3D printing process within a single printer, to obtain perfect tolerances from the first time. The tolerances I used in the models work well for my particular printer, but probably not for yours. **You will most likely need to go through a few iterations of printing test pieces to obtain well-fitting wrenches.**

Instead of printing entire wrench(es) from the start, it is a good idea to start by printing smaller test pieces first, and only print the full model(s) when you know the correct parameters to obtain a good fit.<br>
A possible procedure to end up with accurate wrenches:

1. Decide which of the variants you need.
2. For each model you want, create a cut-down version with only its lower 6 mm part. Usually you can do this directly in your slicer program. Alternatively, you could abort each test print when it reaches about 6 mm height.<br>
This is just to save time and material. (Of course you could simply print entire wrenches each time if you don't mind wasting time and filament.)
3. Add 4 extra copies of this test piece:
   - one scaled up to 101%,
   - one scaled up to 102%,
   - one scaled down to 99%,
   - one scaled down to 98%.
4. Print all 5 test pieces together arranged on one build plate. Make sure to keep track of which is which.
5. Check the fit for these prints. Don't aim for a tight fit, especially not for the hex bits (see below). If one is good, you now know the optimal scale for this model: remember it.<br>
   If they are all too tight, print another set of 5 pieces, scaled to 103%, 104%, 105%, 106%, and 107%. Conversely, if they are too sloppy, scaled to 97%, 96%, 95%, 94%, and 93%. Repeat steps 4 and 5 until you find the optimal fit.
6. When you know the optimal scale for each variant you want to print, scale each full wrench model with its optimal scale factor. Then print 5 final wrenches together. If you need all variants, you're good, because there are 5. If you only need one or a few models, duplicate some of them to end up with at least 5 parts on your build plate before you start the final print. (These things are small and easily lost, so having spares won't hurt anyway.)

You can tweak this procedure as you wish, for instance only print 3 pieces at a time, or maybe even just one. The only things that really matter, are that:
* you keep using the exact same print settings all the time;
* you always print the same number of parts, both for the test pieces and final wrenches. (Above a count of 5 parts this becomes less important, the difference between 5 and 6 or more should be small.)

This is the only way to guarantee that the dimensions will be accurate. Any big change in parameters is likely to affect the tolerances of the end result, and for smaller numbers of parts, printing a different number can also affect the cooling and shrinking of the material.

For the screwdriver hex bit wrench, *do not aim for a nice friction fit.* Even if you get a perfect fit for a particular bit, it will probably not be perfect for other bits, and even for the same bit it will likely become too tight when using the wrench in a much colder environment due to the fact that plastic shrinks and expands a lot more with temperature than metal.
You should deliberately print the hex bit wrench rather sloppy, such that for each hex bit you can find, none are difficult to insert and remove. Then, glue a tiny **magnet** inside the final wrench. A recess is provided for a round magnet of up to 6 mm diameter, about 1.5 mm thick.


## Updates

### 2016/12/11
Published original M3 wrench on Thingiverse.

### 2022/07/31
Migrated to GitHub and re-designed the model, added hex bit variant and more metric sizes between M2 and M4. License is now CC-BY.


## Tags
`hex`, `hex nut`, `key`, `m3 nut`, `socket`, `socket wrench`, `spanner`, `tool`, `wrench`