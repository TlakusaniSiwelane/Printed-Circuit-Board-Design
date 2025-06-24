# Printed-Circuit-Board-Design
📄 Overview:

This project demonstrates a simple PCB design using a 555 Timer IC and a 4013 Dual D Flip-Flop IC to control two LEDs — a red LED and a green LED — based on a timing and flip-flop logic circuit. The design was created and simulated in Proteus Design Suite.

🛠️ Components Used:

1 × NE555 Timer IC

1 × CD4013 Dual D Flip-Flop IC

1 × Red LED

1 × Green LED

Resistors & capacitors for timing configuration

PCB layout for clean and stable circuit implementation

⚙️ How It Works:

The 555 Timer is configured in astable mode to generate a continuous square wave signal.

This signal acts as a clock input for the 4013 Flip-Flop, toggling its state on each clock pulse.

The red and green LEDs are connected to the Q and Q̅ (Q-bar) outputs of the 4013, so they switch alternately:

When Q = HIGH → Red LED ON, Green LED OFF

When Q = LOW → Red LED OFF, Green LED ON

The result is a simple flip-flop controlled LED indicator that shows a clear alternating signal.

📐 Design & Simulation:

Schematic diagram was drawn and verified in Proteus.

PCB layout was created with optimized component placement and neat copper traces.

Design Rule Check (DRC) was performed to ensure there are no electrical or layout errors.

📁 Files Included:

Proteus project file (.DSN / .PDSPRJ)

PCB layout files

Gerber files (for fabrication, if needed)

Screenshots: Schematic, PCB layout, and 3D view

✅ What I Learned:

Configured a 555 Timer in astable mode for clock signal generation.

Integrated a flip-flop IC (4013) for basic digital logic control.

Practiced PCB design principles: schematic capture, footprint placement, routing, and DRC.

Gained hands-on experience in Proteus for both simulation and PCB design workflow.

🔗 Usage:

This PCB can be used as:

A simple LED flasher

A demonstration of timer and flip-flop operation

A practice board for beginners to learn PCB layout techniques

📌 How to Run:

Open the Proteus project file to view the schematic and PCB.

Simulate the circuit in Proteus to observe the LED toggling behavior.

If needed, export the Gerber files and fabricate the PCB.
