BIT 2118: SCIENTIFIC COMPUTING

PART A: NumPy Arrays and Numerical Computation
OBJECTIVE
To use NumPy arrays to analyze temperature readings and convert temperatures from Celsius to Fahrenheit.

INPUT DATA
24 hourly temperature readings in degrees Celsius.

MATHEMATICAL OPERTAIONS

* Calculate the mean, minimum and maximum temperatures.
* Convert the temperatures using F = 1.8C + 32.

RESULTS AND INTERPRETATION
The mean temperature was 23.12°C, the minimum was 17.50°C and the maximum was 29.40°C.

PARAMETER CHANGE
Changing 18.5°C to 20.5°C increases the mean by approximately 0.08°C,while the minimum and maximum remain unchanged.

RELATED REAL-WORLD EXAMPLE
Classroom temeperature monitoring can use hourly readings to calculate average,minimum and maximum temperatures,helping determine whether ventilation is needed.


PART B: Mathematical Functions and Vectorization
OBJECTIVE
To compare a Python loop with NumPy vectorization when processing network latency measurements.

INPUT DATA
One million simulated latency measurements between 5 and 250 milliseconds.

MATHEMATICAL OPERTAIONS
Convert milliseconds to seconds, square the values and measure execution time.

RESULTS

* Loop execution time: 0.6401 s
* Vectorized execution time: 0.0122 s
* Approximate speed-up: 52.4 x

INTERPRETATION
NumPy vectorization is generally faster because it uses optimized numerical operations, making it useful for large datasets.

PARAMETER CHANGE
Reducing the measurements from 1,000,000 to 100,000 generaly reduces execution time for both methods.The speed-up may also change.

RELATED REAL-WORLD EXAMPLE
Website response times can be processed using NumPy to analyze large amounts of simulated or recorded network data and understand performance.
