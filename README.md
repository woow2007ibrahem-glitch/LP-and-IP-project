# Linear and Integer Programming for Hajj Transport Optimization

## Overview

This project uses Linear and Integer Programming to optimize the transportation of pilgrims from pickup points to hotels, minimizing both cost and travel time.

## Objective

- **Reduce costs** for pilgrim transportation
- **Minimize travel time** between pickup points and destinations
- **Increase efficiency** of the hajj transport system

## Requirements

- Python 3.8+
- NumPy
- Pandas
- Matplotlib

## Installation

### Option 1: Local Machine

```bash
# Clone the repository
git clone https://github.com/woow2007ibrahem-glitch/LP-and-IP-project.git
cd LP-and-IP-project

# Install dependencies
pip install numpy pandas matplotlib scipy
```

### Option 2: Google Colab

```python
pip install numpy pandas matplotlib scipy
```

Then upload your files or clone the repository in Colab.

## Usage

```bash
python main.py
```

Or in Google Colab:

```python
# Upload files or clone repository
git clone https://github.com/woow2007ibrahem-glitch/LP-and-IP-project.git
%cd LP-and-IP-project

# Run the project
%run main.py
```

## How It Works

1. **Input Data**: Load pilgrim locations and hotel destinations
2. **Define Variables**: Set up decision variables for transport routes
3. **Objective Function**: Minimize cost [Z]
4. **Constraints**: Define capacity of bus is x <= 50
5. **Solve**: Use linear and Integer programming
6. **Output**: Display optimal routes and statistics


## Course Information

- **Course Code**: AI 382

## Results & Visualization

The project generates:
- Transport route maps
- Cost comparison charts
- Time efficiency graphs
- Optimization statistics

## Future Improvements

- [ ] Add real-time traffic data
- [ ] Implement machine learning for prediction
- [ ] Add vehicle capacity constraints
- [ ] Support multiple optimization objectives
- [ ] Create web interface

## Authors

Ibrahem Arif 
Ahmed Abdullah 
Omar Mohammed 
Samih Alsebai 
