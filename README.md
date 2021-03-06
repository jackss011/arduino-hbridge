# HBridge
This arduino library provides an easy way to control an H-Bridge IC

<h2> How to use </h2>

<h3> Basics </h3>
<p>This library provides a <code>HBridge</code> class to control the IC. Member functions are described below.</p>

<h3> Initialization </h3>
<p>Initialize the H bridge using <code>init(enable pin, input1 pin, input2 pin)</code>.</p>
  
<h3> Usage </h3>
<p>
  Control the H-Bridge using <code>Update(int value)</code>.
  
  <h4>@param <em>value</em></h4>
  <p>Range from -255 to 255.</p>
  <p>The sign of <em>value</em> indicates the motor's spin direction. The absolute value is the motor's spin velocity.
</p>
  
<h3> Tips </h3>
<p>Invert input 1 and input 2 on <code>init(input 1, input 2)</code> if you want to reverse the spin direction.<p/>
<p>Use <code>map()</code> to map your value range into <code>update()</code> range if they are different.</p>


<h2> How to install </h2>

<ol>
  <li>Click <em>Download as ZIP</em></li>
  <li>In the Arduino IDE select <em>Sketch > Include Library > Add .ZIP library</em>.</li>
  <li>Select the downloaded file and confirm. The library will be automatically included</li>
</ol>
