# WS1.2
Workshop 1.2 Numerical Modelling
CEGM1000 MUDE

Written by: Anna Störiko, Ronald Brinkgreve

Due: Wednesday, September 9, 2026.

Part 1: Discharge Estimation and Numerical Integration
Discharge Estimation by Dilution Gauging
In many hydrological and engineering applications, it is important to know how much water flows through a river or stream. A simple method to estimate the discharge in small rivers and streams is so called dilution gauging. In this method, a known amount of salt is added to the river and the concentration of the salt is measured downstream.


Based on a mass balance, the discharge 
 [
] can then be estimated from the injected mass 
 and the area under the concentration curve 
:

 
end
 
where 
 is the concentration of salt in the river above the baseline level at time 
 and 
end
 is the end time of the measurement, well after the concentration returned to its baseline value.

The plot below shows such a concentration curve. In this assignment, you will determine the discharge based on this curve. To evaluate the integral under the curve from the discrete measurements, you will have to use numerical integration techniques.
