# Arias Intensity
[![@ppizarror](http://ppizarror.com/resources/images/author.svg)](http://ppizarror.com)
[![Licencia GPL](http://ppizarror.com/resources/images/licensegpl2.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

Function in matlab to calculate AI (Arias Intensity) parameter from a seismic accelerogram.

## Usage

The arias intensity function is defined by:

```matlab
ai = arias_intensity(t, acc)
```

Where:

| Variable | Description |
| :-: | :--|
| t | Time of the seismic accelerogram |
| acc | Acceleration (g) of the seismic accelerogram |

## Example

Lets suppose that a seismic registry is stored on *data/CNV_APED_201604162359_N_100.txt*, the file structure is like:

```
0.000000	-6.329500
0.010000	2.539600
0.020000	12.822900
0.030000	9.435300
0.040000	-5.397100
0.050000	-14.233900
...
```

Then:

```matlab
ai = arias_intensity(t, acc);
>> ai = 0.198232
```

## License
This project is licensed under GPLv2 (GNU General Public License, version 2) [https://www.gnu.org/licenses/gpl-2.0.html].

## Author
Author: <a href="http://ppizarror.com">Pablo Pizarro R.</a>, 2017.<br>
Acknowledgments to Felipe Ochoa.