# Alarm-Clock

This project implements a digital alarm clock using Verilog HDL. The design simulates the working of a real-time clock that keeps track of hours, minutes, and seconds while providing an alarm feature that triggers when the set alarm time matches the current time.

The system is designed using hardware description concepts and can be simulated using digital design tools. It demonstrates clock generation, time initialization, alarm configuration, and alarm control logic.

Features

Clock signal generation for real-time counting
Initialization of clock time to a specified value
Ability to set a separate alarm time
Alarm enable and disable functionality
Alarm trigger when the set alarm time matches the current time
Option to stop or reset the alarm output

Working Principle

The clock operates by incrementing seconds with each clock pulse. When seconds reach their maximum value, minutes are incremented, and similarly hours are updated when minutes overflow. The system continuously compares the current time with the configured alarm time. When both match and the alarm is enabled, the alarm output is activated. The alarm can be manually stopped using a control signal.

Project Structure

The project includes the Verilog module implementing the alarm clock logic along with helper functions for time calculations. The design uses input signals for resetting the system, loading time, loading alarm time, and enabling or stopping the alarm. Outputs represent the current time and the alarm signal.

Applications

-Digital alarm clocks  
-Embedded timing systems  
-Learning digital design using Verilog  
-FPGA-based timing projects

Conclusion

This project demonstrates how digital hardware concepts can be used to design a functional alarm clock. It highlights the use of Verilog HDL in implementing timekeeping logic, alarm comparison mechanisms, and control features in a modular and scalable way.
