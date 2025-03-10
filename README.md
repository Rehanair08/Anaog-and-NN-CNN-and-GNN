# Image Transfer through Li-fi
## Table of Contents
- [About the Project](about-the-project)
- [Methodolgy](Methodogy)
- [Nerual Network](nerual-network)
- [Excpeted Outcomes](expected-outcomes)
- [Conclusion](conclusion)
## About The Project
This project focuses on secure image compression, encryption, transmission, and reconstruction using an Autoencoder Neural Network and Secure Multi-Party Computation (SMPC) encryption. The system compresses a grayscale image using a convolutional autoencoder, encrypts it by splitting the compressed data into two secret shares, and transmits it securely to an ESP32 microcontroller via serial communication. The received data is decrypted and reconstructed using the trained autoencoder to restore the original image. This approach ensures efficient storage, secure transmission, and accurate image recovery, making it suitable for privacy-preserving applications in medical imaging and secure communication systems.
## Methodology
- Image Acquisition and Pre-processing
- Autoencoder Model for Compression
- Bitstream Generation & Encryption
- Secure Data Transmission to ESP32
- Receiver Side Processing & Reconstruction
## Neural Network
Image classification (code attached)
## Expected Outcomes
1. Data transfer in limited range.
2. Secured Data.
## Conclusion

By this project, we can successfully implement a Li-Fi-based image transfer system. The process involves compressing an image, converting it into bits, encrypting the bits for security, and transmitting them via an ESP32 using Li-Fi technology. The encrypted bits are decrypted and reconstructed to retrieve the original image. It demonstrates the feasibility of using Li-Fi for secure and efficient data transmission, highlighting its potential for high-speed and wireless communication applications.
