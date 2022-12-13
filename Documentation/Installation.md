
## Demos

You can find various demo files in the [`/Examples/`] directory  
that can be printed without installing this tool, though you  
may have to adjust the gcode for some printers.

<br>
<br>

## Installation

<br>

1.  Clone or download this repository

    <br>

2.  Install **[Python 3]** on your system

    <br>

3.  Install the dependencies

    ```sh
    python3 -m pip install -r requirements.txt
    ```

    <br>

4.  Adjust the parameters found at the top of the [`main.py`] file,  
    to customize the shape, size and spikiness of the generated  
    shape or create your own, as long as it is a polygon.

    <br>

5.  Ensure that the start / end gcode works for your printer.

    <br>

6.  Run the python program.

    <br>

7.  Examine the generated gcode file that can found in the  
    `output` directory using a service such as **[Repetier Host]**.

    <br>

8.  Try printing it! If you get a successful print using  
    this algorithm, we would love to hear about it.

<br>


<!----------------------------------------------------------------------------->

[`/Examples/`]: ../Examples
[`main.py`]: ../main.py


[Repetier Host]: https://www.repetier.com/download-now/
[Python 3]: https://www.python.org/
