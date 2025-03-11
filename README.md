# The Amazing Trace

## Introduction
The Amazing Trace is a Python script that runs traceroute commands to a destination and then parses the output into a structured format, and generates graphs. This helps analyze network routing and performance.


### Installation
Before running the script, make sure to install the Python libaries `matplotlib`, `pandas`, and `numpy`.

1. Install libaries:

```python
pip install matplotlib pandas numpy
```

2. Ensure `traceroute`is installed on your Linux system. This is typically already installed on most Linux-based systems.


## Usage
To run the script and generate the traceroute data:

1. Run the script in the terminal or command prompt, navigate to the directory where `amazing_trace.py`is saved. Then run:

```python
python amazing_trace.py
```

2. View the output: The script will execute `traceroute`for each destination. (For my example it's going to be google.com, amazon.com, and bbc.co.uk), parse the output, and make graphs showing the roung trip times (RTT) for each hop. The graphs will be saved in an `output/`folder within the current directory.


### Running the Script

1. Run the script from the terminal: Navigate to the folder containing the script and run:

```python
python amazing_trace.py
```

This will generate traceroutes for the given destinations and save the graphs to the `output/`directory.