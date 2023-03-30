# Message-queues

This code implements a message queuing system on an LPC1768 microcontroller using FreeRTOS. The system consists of a server thread and multiple client threads, each with their own message queue. The server receives messages from the clients and displays the message data on the microcontroller's LEDs.

<b><h2>Requirements</b></h2>

This code requires the following dependencies to be installed:
- FreeRTOS v10.4.3
- LPCOpen v3.02

<b><h2>Usage</b></h2>

- Clone this repository to your local machine.
- Install the required dependencies listed above.
- Open the project in your preferred ARM GCC compiler.
- Compile the code with the required flags listed above.
- Flash the compiled binary onto an LPC1768 microcontroller.
- Connect LEDs to the microcontroller's pins 28, 29, 31, and 2-6 (inclusive).
- Power on the microcontroller.
- Observe the LEDs blinking to display the messages received by the server.
