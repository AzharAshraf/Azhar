<h1>5 easy steps for beginners on physical computing (Arduino)</h1>
experts was once beginners too! so Im here just to help you ease out the process on physical computing. JUST with 5 steps :)



  <p><h2>1. What is Arduino?</h2></p>
  Arduino is an open-source prototyping platform based on easy-to-use hardware and software. In other words, a cute way of being on a cricut IN REAL LIFE!You can tell your board what to do by sending a set of instructions to the microcontroller on the board.

  <p><h3>2. before you start... </h3></p>
Before you begin plugging things into your new Arduino, it may be good to know what can damage the board.
<ul>
  <li>Drawing more than 40mA from an output pin.</li>
  <li>Drawing more than 200mA from all output pins together.</li>
  <li>Supplying more than 5v to the 5v pin</li>
  <li>Reversing the polarity of the power supply</li>
</ul>
SO DONT! lol



 <p><h4>3. KNOW your equipment </h4></p>
 Before you start anything, be prepared!!! It is important to see what electronics Aruduino give you. So have a play around. See what they have on offer AND have fun with it.
 
 
 
 <p><h5>4. Hardware & Electronics </h5></p>
 Before we begin, I'll explain some of the basic electronic components. If you only just started with electronics, this is for you!
 <ul>
  <li>Electricity is the flow of electric charge carriers: electrons (in most cases).</li>
  <li>Electrons are the negatively charged particles that whirl around the positively charged nucleus of an atom.</li>
  <li>Resistors are components with - as the name implies - an electrical resistance, in other words, they limit the flow of electrons, so they are often used to limit the current.</li>
  <li>You can power your Arduino from a USB port, but this solution is limited to 5v and only 500mA, so if you want to use things like motors, or things that require a higher voltage, you'll need a power supply.</li>
</ul>




 <p><h6>5. Blink: Digital Outputs  </h6></p>
 When you plug in your Arduino for the first time, you'll see a green light (with 'ON' written next to it - this is the power LED) and an orange light that blinks (with 'L' written next to it). This is the default 'Blink' program, it turns the internal LED on for a second, then turns it off for a second, repeating forever. UNDERSTAND THIS hehe. In the setup, that only runs once when the program is started, we set pin 13 as an output.
In the loop, we make the output of the led HIGH (5v), wait 1,000ms, make it LOW (0v) and wait for another second. This loop will be repeated forever (at least until you restart the Arduino, or upload another program)
 
 
 
 
 
 
 
