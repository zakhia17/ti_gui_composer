# Tutorial to Texas Instruments GUI Composer
by Zak Abichar

March 8, 2024

## About

In this tutorial, we will build dashboard applications that interact with the microcontroller LaunchPad board. This tutorial is provided in two versions: the __dashboard__ version and the __v3__ version described below.

### Dashboard Version Tutorial

This is the old version of dashboard, however, it is very simple to design. It provided multiple built-in components (e.g. gauges, buttons, LED indicators, plots).

### v3 Version Tutorial

This is the latest version of GUI composer. It is mostly code based and allows adding components from Web Components. Therefore, it's more versatile. However, it's a bit harder to use.

Click on the two files in this repository to access the tutorials.

Testing images... Here is a picture of Earth

![abc](/files/earth.jpg)

Let's try quoting code... we're indicating that this is the C language.

```C
#define redLED BIT0
#define greenLED BIT7

int main() {
  P1OUT |= redLED;
  P9OUT &= ~greenLED;

  return 0;
}
```
