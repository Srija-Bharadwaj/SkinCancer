# UML Documentation for Skin Cancer Prediction App

This directory contains UML diagrams that document the architecture and design of the Skin Cancer Prediction application.

## Diagrams

### 1. Class Diagram (`class_diagram.puml`)
- Shows the main classes and their relationships in the application
- Illustrates the core components: Flask server, SkinCancerPredictor, EfficientNetModel, and ImageProcessor
- Demonstrates how different components interact with each other

### 2. Sequence Diagram (`sequence_diagram.puml`)
- Depicts the flow of operations when a user uploads an image for prediction
- Shows the interaction between different components during the prediction process
- Illustrates the step-by-step flow from image upload to result display

### 3. Component Diagram (`component_diagram.puml`)
- Provides a high-level view of the system architecture
- Shows how different components are connected and interact
- Illustrates the data flow between components

## How to Use

These diagrams are created using PlantUML. To view or modify them:

1. Install PlantUML (http://plantuml.com/)
2. Use a PlantUML-compatible IDE or editor
3. Open the .puml files to view or edit the diagrams

## Diagram Generation

To generate PNG or SVG versions of these diagrams:

```bash
plantuml class_diagram.puml
plantuml sequence_diagram.puml
plantuml component_diagram.puml
```

This will create corresponding .png files in the same directory. 