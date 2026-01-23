# Conceptual-UAV-design-of-Vertical-take-off-and-landing
<img width="1142" height="708" alt="file" src="https://github.com/user-attachments/assets/a9b99fef-410e-4d23-a08c-3e8ba39cef28" />

This project focuses on the conceptual design of a Vertical Take-Off and Landing (VTOL) Unmanned Aerial Vehicle (UAV) intended for efficient low-speed take-off, hover, and fixed-wing forward flight. The design combines the advantages of rotary-wing capability for vertical operations with fixed-wing aerodynamics for extended range and endurance.

The module covers preliminary configuration selection, wing sizing, aerodynamic analysis, and stability assessment, emphasizing performance, controllability, and manufacturability at the conceptual design stage.

<h2>Wing Design</h2>

The wing is designed to provide high lift-to-drag ratio during cruise while maintaining acceptable stall characteristics for transition phases. Key features include:

High-aspect-ratio straight wing optimized for low Reynolds number operation

Selected airfoil suitable for UAV cruise and low-speed performance

Moderate wing loading to balance endurance and maneuverability

Wing positioned to ensure aerodynamic stability and smooth interaction with VTOL propulsion units

The wing geometry was iteratively refined to achieve optimal lift characteristics and minimal drag penalty during forward flight.

<h2> Configuration Description </h2>

The UAV adopts a hybrid VTOL configuration, consisting of Multiple vertical lift motors for take-off, hover, and landing
Fixed-wing layout for efficient forward flight,Central fuselage housing payload, avionics, battery, and flight controller
Symmetrical motor placement to reduce yaw and roll moments during hover

<h2> XFLR5 Direct Foil Design (Spline Foil) </h2> 
 <h3> Foil Design Overview </h3>
 
The airfoil was custom-designed using the Direct Foil Design module in XFLR5, employing a spline-based geometry approach. This method allows precise control over the airfoil shape by modifying discrete spline control points, enabling optimization for low-Reynolds-number UAV flight conditions typical of VTOL and fixed-wing cruise operations.


<img width="1351" height="605" alt="fc57d058-80a0-43fc-a872-58848e8e3a7a" src="https://github.com/user-attachments/assets/fcb69df1-e457-4c8b-95d6-2f37ab5ee23f" />

<h3> Geometric Characteristics </h3>

From the direct foil design data:

Maximum Thickness: 2.24% of chord

Thickness Location: 5.9% chord (forward-positioned)

Maximum Camber: 0.17%

Camber Location: 87.5% chord

<h3> Comparison with Standard Airfoils </h3>

For validation and benchmarking, standard airfoils such as NACA 0012 and NACA 4417 were also included in the design workspace. The custom spline foil provides.

Lower thickness compared to NACA 0012

Reduced camber compared to NACA 4417

Improved suitability for efficient cruise performance rather than high-lift conditions

<h3> Application in VTOL UAV </h3>

The designed spline airfoil is intended for use in the fixed-wing segment of a hybrid VTOL UAV:

Vertical lift is provided by rotors during take-off and landing.

The wing operates primarily during transition and cruise phases.

Aerodynamic efficiency and stability are prioritized over extreme lift capability.

This custom foil design supports extended endurance, smooth transition behavior, and reduced energy consumption in forward flight.
Number of Surface Points: 158
This custom foil design supports extended endurance, smooth transition behavior, and reduced energy consumption in forward flight.
