# automatic-single-axis-solar-tracker
automatic single axis solar tracker built using Arduino nano/uno/mega.

As the non-renewable energy resources are decreasing, use of renewable resources for producing electricity is increasing. 
Solar panels are becoming more popular day by day. 
Solar panel absorbs the energy from the Sun, converts it into electrical energy and stores the energy in a battery.
This energy can be utilized when required or can be used as a direct alternative to the grid supply. 
Utilization of the energy stored in batteries is mentioned in below given applications.
The position of the Sun with respect to the solar panel is not fixed due to the rotation of the Earth. 
For an efficient usage of the solar energy, the Solar panels should absorb energy to a maximum extent.
This can be done only if the panels are continuously placed towards the direction of the Sun. 
So, solar panel should continuously rotate in the direction of Sun. This article describes about circuit that rotates solar panel.

The Sun tracking solar panel consists of two LDRs, solar panel and a servo motor and ATmega328 Micro controller.
Two light dependent resistors are arranged on the edges of the solar panel. Light dependent resistors produce low resistance when light falls on them. 
The servo motor connected to the panel rotates the panel in the direction of Sun. Panel is arranged in such a way that light on two LDRs is compared, and panel is rotated towards LDR which have high intensity i.e., low resistance compared to other. Servo motor rotates the panel at certain angle.
When the intensity of the light falling on right LDR is more, panel slowly moves towards right and if intensity on the left LDR is more, panel slowly moves towards left. 
In the noon time, Sun is ahead and intensity of light on both the panels is same. In such cases, panel is constant and there is no rotation.
