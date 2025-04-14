# Image Transfer through Li-fi
## Table of Contents
- [About the Project](about-the-project)
- [Methodolgy](Methodogy)
- [Excpeted Outcomes](expected-outcomes)
- [Conclusion](conclusion)
## About The Project
In today's more connected world, the need for quicker, safer, and more efficient means of data transfer is ever-increasing. Older wireless technologies such as Wi-Fi and Bluetooth have transformed the way we communicate, but they are not without their limitation, everything from spectrum congestion to possible security risks. As digital communication continues to grow more data-heavy, especially with the proliferation of smart devices, IoT networks, and multimedia data, there is increasing demand for new communication solutions that can address these challenges directly. Li-Fi (Light Fidelity) is a new technology that presents an interesting solution.

With the use of visible light to transmit data, Li-Fi creates a huge, unregulated spectrum that is many times larger than the conventional radio frequency spectrum. In contrast to Wi-Fi, which uses radio waves to transmit data, Li-Fi uses modulated light signals usually LEDs or lasers to wirelessly transfer data. This enables very high-speed data transfer and introduces a physical security layer, as light cannot pass through solid objects, thus restricting data leakage. This project investigates the practical application of Li-Fi technology in real-time digital image transfer.

The objective is to create an operational prototype with the ability to transmit compressed image data via a laser-based Li-Fi system within a short range. A laser diode acts as the transmitter of light and a photodiode as the receiver. A microcontroller that is an ESP32 is the core of the system, handling the control of data flow as well as modulating and demodulating the signals. To optimize image transmission, we implement methods like PCA- based auto-encoder to compress the image during transmission. This reduces the data size remarkably without affecting the quality of the recovered image. The compressed image is encoded in binary form and transmitted through modulated light pulses. These signals are decoded at the receiver and an image is recovered using the onboard processing capacity of the ESP32.

In addition, the project uses cloud technology through the incorporation of Dropbox API for safe storage and recovery of image files. This way, the image data is not only communicated efficiently but also stored and available remotely.

## Methodology

![image](https://github.com/user-attachments/assets/6b214142-7809-425d-b5f1-7fa37b372192)


## Expected Outcomes
1. Data transfer in limited range.
2. Secured Data.
## Conclusion

Developed a working Li-Fi prototype for image transfer using ESP32 and optical components, achieved efficient image compression through PCA-based autoencoder, reliable data transmission. Demonstrated a secure, short-range communication system with cloud-based file management.

