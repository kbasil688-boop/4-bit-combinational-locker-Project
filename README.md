4-Bit Sequential Logic Security Locker
A digital logic and hardware prototype developed out of personal interest to explore the intersection of theoretical logic and physical circuit implementation.

🚀 Project Status: In Active Development
Note: I am currently refining this project to achieve 100% logic accuracy across all bits. While several logic results are currently successful, I am iteratively updating the hardware to resolve signal discrepancies and improve reliability.
🛠 Project Overview
This project is an independent exploration of digital security systems. The goal is to design and build a functional physical locker that validates a specific 4-bit binary sequence using both combinational and sequential logic.
🧠 The "Cool" Technical BreakdownThe system is divided into two primary stages that bridge the gap between pure math and physical hardware:1. Combinational Logic DecoderThe Digital Key: I developed complex Boolean expressions to act as the "lock" mechanism.Gate Array: The circuit uses a strategic array of NOT and AND gates to decode the 4-bit input (A, B, C, D). Only the precise, pre-defined bit pattern results in a logic HIGH (1) signal.
Sequential Memory & Output (D Flip-Flops)

State Storage: To prevent the result from being a mere momentary pulse, I integrated two Dual D-Type Flip-Flops (SN74F74N).

Stable Feedback: These flip-flops serve as 1-bit memory cells that "capture" the correct input. Once a pin is validated by the logic gates, the Flip-Flop stores that state and passes it to an LED indicator.

Visual Confirmation: A lit LED confirms that the specific pin of the 4-pin sequence has been correctly entered and stored, providing real-time user feedback.
My Role & Contributions
Logic Architecture: Designing the gate-level logic required for sequence validation.

Physical Assembly: Breadboarding the system using 74-series integrated circuits (ICs).

Troubleshooting: Analyzing hardware behavior to resolve discrepancies between simulated logic and physical results.
📈 Academic Context
I am currently a third-year Electrical & Computer Engineering student at the University of Cape Town. This project serves as a practical application of the concepts I have mastered as a 2025 Dean’s List recipient and an EBE Faculty Peer Mentor.

📺 Demo & Media
Hardware Photos & Videos: View the 4-Bit Locker Demo Folder on google drive :https://drive.google.com/drive/folders/1no1eVU8uNiSlT3REweZLbOcmu9KrRv0d?usp=drive_link
