## PCB manufacture for an IoT startup

- posted by: [Doug Null](https://stackexchange.com/users/387639/doug-null) on 2016-09-16
- tagged: `tech-company`, `product`, `hardware`
- score: 1

<p>I have a startup company, and am about to have a contract hardware engineer produce my first PCB for my first product.  </p>

<p>Any advice?  Any pitfalls I should be aware of?</p>

<p>I've worked with this engineer before and he's top notch.</p>

<p>Product PCB will be about the size of a quarter, and has only an ARM, an accelerometer, and LDO voltage controller, and a wire connection socket for power, debug serial, programming SDA, and a single digital output.</p>



## Answer 11232

- posted by: [maksschmidt ](https://stackexchange.com/users/9288454/maksschmidt) on 2016-09-29
- score: 2

<p>It depends, if you're planning on shipping rev 1 (which rarely ever happens) I would put all non-essential components to the completed design on a break-off tab (debug connectors, for example. This will help minimize the overall pcb footprint.</p>

<p>If this is rev 1, I would have him/her put either test pads or 0 ohm resistors on any important lines you can't probe from IC pins. If the connection socket is going to end up being for a battery, I would recommend just doing thru hole pads for that, you'll save yourself a lot of z-height as connectors tend to be the tallest components on PCBs.</p>

<p>Depending on the use case, I would recommend putting the accelerometer on the center of the board. This usually makes, for better data collection.</p>

<p>These are all very general based on the info you've given, but I hope this gives you an idea for the design portion.</p>

<p>For getting the PCB's manufactured, I would highly recommend somewhere that does batch orders like OSH park or fusion PCB.</p>

<p>A caveat with fusion PCB, sometimes they might ship a couple non-functional boards, but they usually ship a couple extras.</p>

<p>If you have the equipment, you can save some money assembling the boards yourself, but if you have the extra funds, getting them assembled might save you some time. (I think fusion PCB also has an assembly service) </p>

<p>Just remember the triangle product development: good, fast, and cheap. Pick two.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
