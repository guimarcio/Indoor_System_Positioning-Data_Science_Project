# Files to be updated!

https://archive.ics.uci.edu/dataset/422/wireless+indoor+localization

# Indoor System Positioning: Data Science Project

## Introduction and Context

Global Positioning Systems (GPS) enable mobile devices to determine their location almost anywhere on the planet by combining signals transmitted by satellites. However, their performance is significantly reduced in indoor environments such as houses, offices, and commercial buildings. Physical structures like walls and floors attenuate satellite signals, which decreases positioning accuracy.

To overcome this limitation, Indoor Positioning Systems (IPS) have been developed specifically for enclosed environments. Several technologies can be used in these systems, including:

- Wi-Fi (WPS – Wi-Fi Positioning System)

- Bluetooth

- Infrared

- Ultrasound

The choice of approach depends on the application and the characteristics of the environment.

With the widespread adoption of smartphones, IPS applications have expanded across multiple sectors, including:

- Navigation and accessibility in smart environments (homes, buildings, shopping malls, airports, hospitals, museums);

- Augmented reality;

- Events and exhibitions;

- Security and restricted-area monitoring;

- Resource management (material and human), aiming at cost reduction and efficiency improvement.

In this project, machine learning algorithms are applied to classify the location of mobile devices within an office environment located in Pittsburgh, USA. The objective is to determine in which of four different rooms the device is located.

The dataset consists of RSSI (Received Signal Strength Indicator) measurements collected from Wi-Fi routers, a technique belonging to the Wi-Fi Positioning System (WPS) approach for indoor localization. The original study classified device location into three rooms using optimized neural networks. In this project, the analysis is extended to four rooms, exploring the performance of different machine learning algorithms.

