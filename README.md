🌤 Quadratic Weather Simulation: A Learning Tool for SDLC Models
🔍 Overview
This project introduces a basic yet insightful weather simulation using a quadratic equation to estimate temperature across various hours of the day. The equation:
T = a·t² + b·t + c
...where t is time in hours, T is the temperature in °C, and a, b, and c are adjustable parameters that shape the temperature curve.
Beyond its mathematical foundation, the project serves as a dual-purpose educational tool—demonstrating how different Software Development Life Cycle (SDLC) models (Waterfall, Iterative, Agile) can be applied to a simple forecasting problem.

🎯 Goals
Illustrate how quadratic equations can simulate temperature fluctuations.
Provide a hands-on example of SDLC methodologies using a weather-based scenario.
Deliver a lightweight Python script ideal for experimentation and learning.

❓ Challenge
Weather prediction typically involves complex algorithms and live data feeds. However, this project simplifies the concept by using a quadratic function to mimic temperature changes over time. It also integrates SDLC principles to show how different development strategies tackle the same problem in unique ways.

🧪 Approach
The core of the program is a Python function:
def quadratic_weather_model(t):
    a, b, c = 0.05, -0.3, 25
    return a * t**2 + b * t + c

This function estimates temperature for any given hour t. The predictions are then organized according to three SDLC models:
🧱 Waterfall Model
Executes in a linear, sequential manner.
Example: Calculates temperatures every 6 hours without revisiting earlier steps.
🔁 Iterative Model
Refines predictions through repeated cycles.
Example: Evaluates temperatures every 12 hours across multiple iterations.
⚡ Agile Model
Uses flexible, sprint-based development.
Example: Predicts temperatures at 0, 6, 12, 18, and 24 hours, revisiting and refining in short bursts.

✅ Functional Requirements
Must compute temperature using a quadratic formula.
Should support Waterfall, Iterative, and Agile modes.
Coefficients a, b, and c should be easily modifiable.

⚙️ Non-Functional Requirements
Should execute quickly and efficiently.
Code must remain clean and beginner-friendly.
Designed for educational use and demonstrations.


🚀 Future Enhancements
Incorporate real-world weather data for improved realism.
Compare the quadratic model with machine learning techniques.
Add graphical visualizations for better data interpretation.
Transform the script into an interactive classroom tool or web demo.

🧠 Final Thoughts
This project bridges the gap between math and software engineering by:
Using quadratic equations to simulate basic weather patterns.
Demonstrating SDLC models through practical implementation.
Making learning engaging by combining concepts from multiple disciplines.
