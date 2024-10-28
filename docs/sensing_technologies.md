# Sensing Technologies

In this project, we explore a novel 3D scanning approach that uses two complementary sensing technologies: **thin film pressure sensors** and **capacitive touch sensors**. These sensors allow us to gather detailed shape information by detecting both the contact points and the proximity of an object’s surface, offering a comprehensive method for capturing intricate details and contours.

## 1. Thin Film Pressure Sensors

### Overview
Thin film pressure sensors are flexible materials that can detect the force applied to them at specific points. When integrated into the balloon, these sensors help identify the exact locations and intensity of contact between the balloon and the object.

### Advantages
- **Contact Precision**: Able to identify sharp edges, grooves, and high-pressure areas.
- **Durability**: Withstand repeated deformations without losing accuracy.
- **Thin and Flexible**: Suitable for the balloon structure without adding significant bulk.

### Applications in 3D Scanning
Thin film pressure sensors provide detailed data on the object’s pressure points and direct contact areas. These data points create a "contact map" of the object, which can be used to detect complex surface features that might otherwise be hard to identify.

## 2. Capacitive Touch Sensors

### Overview
Capacitive touch sensors detect proximity by measuring changes in capacitance. Unlike pressure sensors, they don’t require direct contact to sense the presence of an object, allowing them to capture the general contours and softer curves of the object’s surface.

### Advantages
- **Non-Contact Detection**: Can detect slight curvatures and areas where pressure is low.
- **High Sensitivity**: Effective for capturing the outline and subtle details.
- **Flexible and Lightweight**: Easily integrated onto curved surfaces like a balloon.

### Applications in 3D Scanning
Capacitive sensing adds another layer of detail to the shape data. By detecting the object’s proximity and contours, these sensors capture areas where the object may not apply enough pressure for the thin film sensors to detect but where shape details are still essential.

## 3. Why Use Both Sensors Together?

Combining thin film pressure and capacitive sensing allows for a more detailed and complete 3D scan:
- **Complementary Strengths**: While pressure sensors capture direct contact points, capacitive sensors detect contours and surface proximity, filling in gaps where pressure data alone might be insufficient.
- **Improved Accuracy**: The combined data creates a more accurate and high-resolution model, covering both high-contact areas and subtle surface variations.
- **Redundant Data for Validation**: Data from each sensor type can cross-validate the other, enhancing the reliability of the final model.

## Future Considerations
Future improvements might include testing additional sensor types, such as resistive touch sensors or piezoelectric sensors, to further enhance the flexibility, accuracy, and sensitivity of the balloon-based 3D scanning approach.

