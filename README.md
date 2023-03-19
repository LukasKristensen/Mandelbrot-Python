# Mandelbrot-Mini-Project
Implementation of the Mandelbrot set for the Numerical Scientific Computing Course (Computer Engineering 8th semester, AAU)

- To compare the performance between the algorithms run the [``main.py``](main.py) file.
- To generate a plot showing the mandelbrot set configure one of the parameters to ``show_figure=True`` in [``main.py``](main.py).

</br>

## Generated Content
Generated sequence of zoom into fractals [``AnimatingMandelbrotZoom/mandelbrot_animation.py``](AnimatingMandelbrotZoom/mandelbrot_animation.py)

![alt text](AnimatingMandelbrotZoom/animated_zoom_export.gif)


High resoultion render of the mandelbrot set [``AnimatingMandelbrotZoom/mandelbrot_animation.py``](HighResolutionRender/ImageRender.py)


![alt text](HighResolutionRender/MandelbrotOutput.png)
**Image computed using:**
- Size: (1e4, 1e4)
- Threshold: 100
- Iterations: 100

</br>

## Setup
Install the necessary packages by running the command within the root project directory:

```shell
pip install -r requirements.txt
```


</br>

## Project Hand Ins
**Mini-Project Part 1** ([``Hand-In``](Part%201%20-%20Algorithms%20with%20performance%20analysis/Mini%20Project%20Report%20Part%201.pdf))</br>
- Naive
- Vectorized
- Numba-optimized
- Parallel using multi-processing
- Computation analysis of speedup between parameters</br>

**Mini-Project Part 2** ([``Hand-In``](Part%202%20-%20DASK%20and%20Datatypes/Numerical%20Scientific%20Computing%20Mini%20Project%20Part%202.pdf))</br>
- Performance of data types (Numpy.Float64, Numpy.Float32, Numpy.Float16)
- Dask compared to numpy
- Dask local execution
- Dask distributed execution
- Performance optimizations (Early stopping, data types, lazy loading)

</br>

## Group
- Lukas Bisgaard Kristensen 
