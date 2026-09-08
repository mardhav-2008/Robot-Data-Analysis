# Robot Data Analysis

Analysis of real-world robot driving telemetry using Python.

This project explores sensor and motion data collected from a real robot, with a focus on understanding its movement, trajectory, sampling behaviour, and motor activity through numerical analysis and visualization.

## Dataset

The dataset used in this project is:

**NCDTech/real-robot-driving-sessions**

The dataset can be downloaded from the [Hugging Face dataset repository](https://huggingface.co/datasets/NCDTech/real-robot-driving-sessions/tree/main).

After downloading the three CSV files, rename them as:

```text
session_1.csv
session_2.csv
session_3.csv
```

and place them in the `data/` directory:

```text
data/
├── session_1.csv
├── session_2.csv
└── session_3.csv
```

The dataset files are excluded from this repository using `.gitignore`.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- SymPy

## Analysis

The current analysis includes:

- Sampling interval and sampling frequency analysis
- Robot trajectory visualization
- Total distance travelled
- Velocity calculation
- Acceleration calculation
- Motor PWM analysis
- Visualization of robot motion over time

## Project Structure

```text
Robot-Data-Analysis/
├── data/
│   ├── session_1.csv
│   ├── session_2.csv
│   └── session_3.csv
├── src/
│   └── robot_sensor_analysis/
│       ├── __init__.py
│       └── main.ipynb
├── .gitignore
├── .python-version
├── README.md
├── pyproject.toml
└── uv.lock
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/mardhav-2008/Robot-Data-Analysis.git
cd Robot-Data-Analysis
```

Install the project dependencies using [uv](https://docs.astral.sh/uv/):

```bash
uv sync
```

Download the dataset and place the CSV files in the `data/` directory as described above.

The analysis can then be explored through the Jupyter notebook.

## Future Work

Planned areas of analysis include:

- IMU sensor analysis
- Ultrasonic sensor analysis
- Sensor validation
- Signal filtering
- Sensor fusion
- Correlation between motor commands and robot motion
- Analysis across multiple driving sessions

## License

This project is intended for educational and analytical purposes.

The dataset is provided by NCDTech under the **CC BY 4.0** license. See the [dataset repository](https://huggingface.co/datasets/NCDTech/real-robot-driving-sessions/tree/main) for the original dataset and licensing information.