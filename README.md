| Section         | Adapter color | Device Pin | Acorn Pin      | Purpose    | Notes                                                                                                                                                                                                                                                     |
| --------------- | ------------- | ---------- | -------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| X               | Blue          | PUL-       | H6/PIN 2       | Pulse Neg. |                                                                                                                                                                                                                                                           |
| Red             | PUL+          | PSU V1     | Pulse Pos.     |            |
| Green           | DIR-          | H6/PIN 3   | Direction Neg. |            |
| Red             | DIR+          | PSU V1     | Direction Pos. |            |
| NC              | ENA-          | H2/EN1     | Enable         |            |
| Y1              | Blue          | PUL-       | H6/PIN 4       | Pulse Neg. |                                                                                                                                                                                                                                                           |
| Red             | PUL+          | PSU V1     | Pulse Pos.     |            |
| Green           | DIR-          | H6/PIN 5   | Direction Neg. |            |
| Red             | DIR+          | PSU V1     | Direction Pos. |            |
| NC              | ENA-          | H2/EN2     | Enable         |            |
| Y2              | Blue          | PUL-       | H6/PIN 4       | Pulse Neg. |                                                                                                                                                                                                                                                           |
| Red             | PUL+          | PSU V1     | Pulse Pos.     |            |
| Green           | DIR-          | H6/PIN 5   | Direction Neg. |            |
| Red             | DIR+          | PSU V1     | Direction Pos. |            |
| NC              | ENA-          | H2/EN2     | Enable         |            |
| Z               | Blue          | PUL-       | H6/PIN 6       | Pulse Neg. |                                                                                                                                                                                                                                                           |
| Red             | PUL+          | PSU V1     | Pulse Pos.     |            |
| Green           | DIR-          | H6/PIN 7   | Direction Neg. |            |
| Red             | DIR+          | PSU V1     | Direction Pos. |            |
| NC              | ENA-          | H3/EN3     | Enable         |            |
| Stepper Drives  | NC            | ENA+       | JUMP TO DIR+   | Enable     |                                                                                                                                                                                                                                                           |
| Limit Switches- | Black         | GND        | H4/IN1         | Home All   | [Wire in parallel for NC switches<br>Cut limit switch cable and rewire. Use strain relief STL to support the cable<br>Connect black to input and red to 5v<br>Example Wiring](https://www.centroidcnc.com/dealersupport/schematics/uploads/S14954.r5.pdf) |
| Limit Switches+ | Red           | 5V         | 5V             | Home All   |
| X               | Blue          | X          | X              | Home All   |
| Y1              | Yellow        | X          | X              | Home All   |
| Y2/Z            | Purple        | X          | X              | Home All   |
| Spindle Power   | Blue          | DB44-16    | RB4/NC         | SPO        |                                                                                                                                                                                                                                                           |
| Blue/White      | DB44-20       | H4/IN4     | SPRDY          |
| Brown           | DB44-1        | X          | ACLR           |
| White/Orange    | DB44-10       | H8/AN GND  | ANA-           |
| Orange          | DB44-26       | H8/AN OUT  | ANA+           |
| White/Brown     | DB44-5        | H4/IN3     | ALM            |
| Green           | DB44-31       | H9/24VDC   | COM+           |
| White/Green     | DB44-23       | H9/COM     | COM-           |
| Spindle Encoder | Blue          | DB44-13    | P10/PIN 8      | A+         | Requires DB9 cable with shielded, twisted pair                                                                                                                                                                                                            |
| White/Blue      | DB44-28       | P10/PIN 5  | A-             |
| Green           | DB44-14       | P10/PIN 7  | B+             |
| White/Green     | DB44-29       | P10/PIN 4  | B-             |
| Brown           | DB44-15       | P10/PIN6   | Z+             |
| White/Brown     | DB44-30       | P10/PIN3   | Z-             |
| Drain           | DB44-12       | P10/PIN 2  | GND            |