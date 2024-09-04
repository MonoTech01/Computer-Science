# OSI Model

## Definition

* **OSI Model (Open Systems Interconnection Model):** A conceptual framework that standardizes communication between different computer systems.
* **Developed by:** International Organization for Standardization (ISO).
* **Purpose:** To provide a common language for network communication, enabling interoperability between diverse systems.

## Seven Layers of the OSI Model

1. **Application Layer:**
    * Interface for user applications (e.g., web browsers, email clients).
    * Provides services to applications outside the OSI model.
    * Handles tasks like data synchronization, error recovery, and resource availability.
2. **Presentation Layer:**
    * Formats data for presentation to the user (e.g., encryption, compression).
    * Ensures data is presented in a readable format.
3. **Session Layer:**
    * Manages communication sessions between devices.
    * Handles session setup, data exchange, and termination.
    * Implements flow control to prevent data overload.
4. **Transport Layer:**
    * Ensures reliable end-to-end data transmission.
    * Provides error checking and recovery mechanisms.
    * Segments data into packets and manages their delivery.
5. **Network Layer:**
    * Determines the optimal path for data packets across the network (routing).
    * Addresses packets and manages network congestion.
6. **Data Link Layer:**
    * Provides error-free transmission between adjacent nodes on a network.
    * Handles MAC (Media Access Control) addressing and frame synchronization.
7. **Physical Layer:**
    * Defines the physical characteristics of the network (e.g., cables, connectors, signaling).
    * Transmits raw bits over the physical medium.

## How the OSI Model Works

* Each layer performs specific functions and communicates with the layers above and below it.
* Data travels down the layers on the sending device, across the network, and back up the layers on the receiving device.

## Analogy: Sending a Letter

* **Application Layer:**  Dictating the letter (user application).
* **Presentation Layer:** Transcribing shorthand into a readable letter (formatting).
* **Session Layer:**  Handing the letter to the mail room (establishing a communication session).
* **Transport Layer:** Choosing a reliable courier service (ensuring reliable delivery).
* **Network Layer:** Deciding the best route for the letter (routing).
* **Data Link Layer:**  Packaging the letter in an envelope (framing and error detection).
* **Physical Layer:** Transporting the letter via plane and truck (physical transmission).
