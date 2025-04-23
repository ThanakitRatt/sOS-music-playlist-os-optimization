
# OS Optimization Simulation: Music Playback & Visualization

This project simulates an OS-optimized music playback system using multithreading, caching, and memory management. It also tracks execution time to show performance efficiency.

## Features

- Simulated audio playback and visual rendering
- Multithreaded execution (CPU optimization)
- RAM and cache simulation (memory optimization)
- Execution time tracking to measure performance
- Real resource handling with `psutil` (optional)

## Concepts Demonstrated

- **Threading**: Playback and visualization handled in parallel  
- **Caching**: Frequently played songs are loaded faster  
- **Memory Simulation**: RAM stores recently played songs  
- **Time Measurement**: Measures how long the process takes  

## Requirements

- Python 3.x  
- (Optional) `psutil` for real system resource tracking  
  Install with:
  ```bash
  pip install psutil
  ```

## How to Run

```bash
python your_script_name.py
```

Or paste into a Python notebook (e.g., Google Colab or Jupyter).

## Output Example

```
Now Playing: Super Lady by (G)I-DLE
[Disk] Streaming 'Super Lady by (G)I-DLE' from disk
[Memory] 'Super Lady by (G)I-DLE' loaded to RAM (now 1 items)

...

Time: 8.12874031 sec
```

## Notes

- This is a simulation: no actual audio is played.
- Designed to illustrate how OS-level resource handling can improve efficiency.
