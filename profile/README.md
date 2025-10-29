# BYU Racing

![Fast car go brrrrrrrrrrrrrrrrrrrrr](https://brightspotcdn.byu.edu/dims4/default/3a521e5/2147483647/strip/true/crop/8192x5464+0+0/resize/1920x1281!/quality/90/?url=https%3A%2F%2Fbrigham-young-brightspot-us-east-2.s3.us-east-2.amazonaws.com%2Fd2%2F9b%2F589545a645d482fe5828e24c88e3%2F2408-31-702.jpg)
BYU Racing Team Repository

## Our Goals

- Build a car that runs and won't break
- Learn how to make next year's car better
- Create networking and other opportunities for team members

## Requirements

<details>
<summary><B>Rules</B></summary>
<b>Rules</b> 
 <br>

- Brake light [T.3.4]
- - Must be visible, even in intense sunlight
- Accelerator system [T.4]
- - Must have two electrically separate sensors
- - Sensors must have different transfer functions
- - Sensor circuits must have resistors to make a short circuit result in a 0% reading
- - If a reading is received that is outside of the possible range, the motor controller must deactivate motor power
- - The motor controller may only accept up to a 10% difference in readings for 100 msec before deactivating motor power
- - Must have a detachable connector or switched breakout box to allow for disconnecting each sensor
- - ETC systems form must contain a detailed description of all possible failure modes including, but not limited to signal out of range, time outs, corrupted messages, and lost messages
- - Integrity of motor command signal must be maintained at all stages
- Brake system encoder (BSE) [T.4.3]
- - There must be a sensor for measuring brake line pressure or pedal position
- - If an abnormal or no reading is read for more than 100 msec, the motor power must be deactivated
- - The ETC systems form must contain a detailed description of all possible failure modes including, but not limited to signal out of range, time outs, corrupted messages, and lost messages
- Low Voltage Battery [T.9.2]
- - Low voltage batteries must be securely mounted within the chassis below the height of the shoulder belt mount
- - Low voltage batteries must have overcurrent protection that trips at or below the maximum specified discharge current of the cells
- - The positive terminal must be insulated
- - Any wet-cell battery in the driver’s compartment must be contained in a nonconductive marine type container or equivalent
- - Lithium chemistry battery packs must have a sturdy, rigid casing made from nonconductive material or be commercially available as an OEM style replacement
- - All batteries using chemistry other than lead-acid must be presented at technical inspection with markings identifying it for comparison to a datasheet or other documentation that prove that the pack and supporting electronics meet all rules requirements

- Grounded low voltage system general requirements [EV 4.4]
- - The grounded low voltage system must be below 60 V DC and must be grounded to the chassis
- - The grounded low voltage system must include two master switches that meet the following requirements
- - The grounded low voltage system must have a measuring point that is connected to the ground of the low voltage system
- - - This measuring point must be next to the tractive system measuring point
- - - The measuring point must be be a black 4mm banana jack marked “GND”
- Vehicle operation
- - The vehicle must energize in the following manner: grounded low voltage active, tractive system active, then ready to drive.
- - Ready to drive
- - - The vehicle will respond to motor inputs once the tractive system is active, the brake pedal is pressed and held, and the driver preforms a specific manual action to activate (such as pressing a specific button in the cockpit)
- - - Once the ready to drive state is activated, the vehicle must make a ready to drive sound for one to three seconds that is easily recognizable and is at least 80 dBA

</details>

<details>
 <summary><B>Syntax Guide</B></summary>
 
## Syntax Guidelines
https://google.github.io/styleguide/cppguide.html

## Core Principles

Optimize for the reader, not the writer – Code should be easy to read and maintain.
Consistency – Use consistent styles across the codebase to enable automation and reduce cognitive load.
Avoid surprising or dangerous constructs – Prefer clarity and safety over cleverness.
Concede to optimization when necessary – Performance can justify exceptions to style rules.

**Function Definitions**

Include one line comment before each function is defined for clarity of reader. 
Define functions in header files.

**Include Order**

Use angle brackets for system and standard headers.
Use quotes for project headers.
Alphabetize includes within each section.

**Namespaces**

Use project-specific namespaces.
Avoid using namespace directives.
Prefer named namespaces over inline or unnamed ones.

**Header Files**

Refer to ReadMe in include folder.

**Naming Conventions**

Use consistent naming for files, types, variables, constants, functions, namespaces, etc.
Avoid abbreviations unless widely understood.
Use CamelCase for types and functions, snake_case for variables, constants should be capitalized snake_case.

**Comments**

Include one line comment before each function is defined for clarity of reader.
Clarifiying comments within functions should be in-line.
Use comments to explain non-obvious code.
Follow consistent comment styles for files, classes, functions, and variables.
Use TODO comments with an identifier and explanation.

**Formatting**

Line length: 100 characters max (excluding in-line comments).
Use tabs over spaces.
Consistent formatting for function declarations, initializers, loops, conditionals, etc.
Avoid non-ASCII characters unless necessary.
</details>
