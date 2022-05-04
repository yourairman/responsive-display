# responsive-display
Bootstrap-Display

<h2>Display property</h2>

Quickly and responsively toggle the display value of 
components and more with our display utilities. 
Includes support for some of the more common values, as well as some extras for controlling display when printing.

As such, the classes are named using the format:

.d-{value} for xs
.d-{breakpoint}-{value} for sm, md, lg, xl, and xxl.
<ul> Where value is one of:


  <li>none</li>
<li>inline</li>
<li>inline-block</li>
<li>block</li>
<li>grid</li>
<li>table</li>
<li>table-cell</li>
<li>table-row</li>
<li>flex</li>
<li>inline-flex
</li>
</ul>


<h4>Hiding elements</h4>

<p>For faster mobile-friendly development, use responsive display classes for showing and hiding elements by device. Avoid creating entirely different versions of the same site, instead hide elements responsively for each screen size.

To hide elements simply use the .d-none class or one of the .d-{sm,md,lg,xl,xxl}-none classes for any responsive screen variation.

To show an element only on a given interval of screen sizes you can combine one .d-*-none class with a .d-*-* class, for example .d-none .d-md-block .d-xl-none .d-xxl-none will hide the element for all screen sizes except on medium and large devices.</p>

<table>
  <tr>
    <th>Screen size	</th>
    <th>Class</th>
  </tr>
  <tr>
    <td>Hidden on all	</td>
    <td style="color:red">.d-none</td>
  </tr>
  
  <tr>
    <td>Hidden only on xs	</td>
    <td style="color:red">.d-none .d-sm-block
</td>
  </tr>
  
  <tr>
    <td>Hidden only on sm		</td>
    <td style="color:red">.d-sm-none .d-md-block
</td>
  </tr>
  
  <tr>
    <td>Hidden only on md	</td>
    <td style="color:red">.d-md-none .d-lg-block
</td>
  </tr>
  
  <tr>
    <td>Hidden only on lg		</td>
    <td style="color:red">.d-lg-none .d-xl-block
</td>
  </tr>
  
  <tr>
    <td>Hidden only on xl		</td>
    <td style="color:red">.d-xl-none .d-xxl-block
</td>
  </tr>
  
  <tr>
    <td>Hidden only on xxl		</td>
    <td style="color:red">.d-xxl-none
</td>
  </tr>
  
  <tr>
    <td>Visible on all		</td>
    <td style="color:red">.d-block
</td>
  </tr>
  
  <tr>
    <td>Visible only on xs		</td>
    <td style="color:red">.d-block .d-sm-none
</td>
  </tr>
  
  <tr>
    <td>Visible only on sm		</td>
    <td style="color:red">.d-none .d-sm-block .d-md-none
</td>
  </tr>
  
  <tr>
    <td>Visible only on md		</td>
    <td style="color:red">.d-none .d-md-block .d-lg-none
</td>
  </tr>
  
  <tr>
    <td>Visible only on lg		</td>
    <td style="color:red">.d-none .d-lg-block .d-xl-none
</td>
  </tr>
  
  <tr>
    <td>Visible only on xl		</td>
    <td style="color:red">.d-none .d-xl-block .d-xxl-none
</td>
  </tr>
  
  <tr>
    <td>Visible only on xxl		</td>
    <td style="color:red">.d-none .d-xxl-block
</td>
  </tr>
</table>
