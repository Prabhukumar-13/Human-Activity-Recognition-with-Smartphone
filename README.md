# Human Activity Recognition (HAR) with Smartphones

**Human Activity Recognition (HAR)** involves the automatic detection and classification of physical activities performed by individuals, such as walking, running, sitting, standing, etc., using data from sensors. When applied to smartphones, HAR typically leverages data from built-in sensors like accelerometers, gyroscopes, and sometimes magnetometers, which capture motion and orientation information.

## Key Aspects:

### Sensors:

- **Accelerometer**: Measures acceleration forces, useful for detecting movements like walking or running.
- **Gyroscope**: Measures rotational movements, aiding in detecting activities that involve changes in orientation.

### Data Collection:

- The smartphone continuously records sensor data as the user performs different activities.
- This data is often segmented into windows of fixed length, creating a series of time-series data points.

### Feature Extraction:

- Features are extracted from the raw sensor data to capture essential characteristics of the activities.
- These features may include statistical measures (mean, variance), frequency domain features, and more.

### Activity Classification:

- Machine learning models, such as Logistic regression, support VectorMachines (SVM), Decision Trees, Naive Bayes, Multi-Layer Perceptron’s (MLP), or Deep Learning models like Convolutional Neural Networks (CNNs), are trained to classify the extracted features into specific activities.

## Applications:

- Fitness tracking
- Healthcare monitoring (e.g., detecting falls or sedentary behavior)
- Context-aware computing (adapting smartphone behavior based on user activity)


## Dataset

- [Human Activity Recognition with Smartphones Dataset](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones?resource=download)
