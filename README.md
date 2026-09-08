# Robot Data Analysis

Analysis of real-world robot driving telemetry.

## Dataset
NCDTech/real-robot-driving-sessions

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- SymPy

## Current Analysis
- Sampling-rate analysis
- Robot trajectory
- Distance travelled
- Velocity
- Acceleration
- Motor PWM analysis

## Project Structure
├── data
│   ├── session_1.csv
│   ├── session_2.csv
│   └── session_3.csv
├── pyproject.toml
├── README.md
├── src
│   └── robot_sensor_analysis
│       ├── __init__.py
│       └── main.ipynb
└── uv.lock



## Future Work
- IMU analysis
- Ultrasonic sensor analysis
- Signal filtering
- Sensor fusion

## Dataset

The datasets used in this project can be downloaded from the
[Hugging Face dataset repository](https://huggingface.co/datasets/NCDTech/real-robot-driving-sessions/tree/main).

After downloading, rename the three CSV files as follows:

- `session_1.csv`
- `session_2.csv`
- `session_3.csv`

Place them inside the `data/` directory:

```text
data/
├── session_1.csv
├── session_2.csv
└── session_3.csv
