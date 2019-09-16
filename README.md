<h1 align="center">
  <img alt="Arias Intensity" src="https://res.ppizarror.com/other/matlab.png" width="200px" height="200px" />
  <br /><br />
  Arias Intensity</h1>
<p align="center">Function in matlab to calculate AI (Arias Intensity) parameter from a seismic accelerogram</p>
<div align="center"><a href="https://ppizarror.com"><img alt="@ppizarror" src="https://res.ppizarror.com/badges/author.svg" /></a>
<a href="https://www.gnu.org/licenses/old-licenses/gpl-2.0.html"><img alt="GPL V2.0" src="https://res.ppizarror.com/badges/licensegpl2.svg" /></a>
</div><br />

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

This project is licensed under GPLv2 [https://www.gnu.org/licenses/gpl-2.0.html]


## Author
<a href="https://ppizarror.com" title="ppizarror">Pablo Pizarro R.</a> | 2017
