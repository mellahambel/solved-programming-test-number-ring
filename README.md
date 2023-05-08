Download Link: https://assignmentchef.com/product/solved-programming-test-number-ring
<br>
<strong> </strong><strong><em>Specification: </em></strong>

<ol>

 <li>Please create a project folder (using any programming language) with the following name:</li>

</ol>

<strong>COSC489_PT_2168_<em>&lt;your username&gt;</em></strong>

and please make sure to replace <strong><em>&lt;your username&gt;</em> </strong>portion with your real FSU username.

<ol start="2">

 <li>In the above project you can implement in any programming language to realize the following functions.</li>

 <li>Your program will access an input file with the name “<strong>txt</strong>”, which is located right outside of the above project folder (i.e. your project folder and this input file are sitting in the same folder). Please make sure in your program don’t use absolute path but a relative path to access the input file. A sample of this input file is provided together with this specification.</li>

 <li>Your program will process the above input file and operate as it specifies.</li>

 <li><strong>Initialize a number ring</strong>: read in the initial list of number and create the initial number ring with the first number to be the <strong><em>current</em></strong> number on the ring (the red number is the <strong><em>current</em></strong> number). Given the initial list of numbers of <strong>2 3 5 6 1 4 8 5</strong> we can get.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="296"></td>

  </tr>

  <tr>

   <td></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="227"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="21"></td>

   <td width="5"></td>

   <td width="17"></td>

   <td width="7"></td>

   <td width="5"></td>

   <td width="17"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="5"></td>

   <td colspan="3" rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="7"></td>

   <td colspan="3" rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="8"></td>

   <td colspan="3" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>





































<ol start="6">

 <li><strong>The following list of operations can be carried out in any order and repeated any number of times. The operation names are case in </strong></li>

</ol>































<ol start="7">

 <li><strong>Insert: </strong>it will add a number into the ring right before (counterclockwise) the current number. The newly inserted number will become the new current number.</li>

</ol>







<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="29"></td>

   <td width="285"></td>

   <td width="29"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3"></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="21"></td>

   <td width="149"></td>

   <td width="24"></td>

   <td width="6"></td>

   <td width="23"></td>

   <td width="5"></td>

   <td width="1"></td>

   <td width="8"></td>

   <td width="20"></td>

   <td width="9"></td>

   <td width="24"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="10"></td>

   <td width="29"></td>

   <td width="5"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="17"></td>

   <td colspan="3" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

   <td colspan="3"></td>

   <td colspan="4" rowspan="10"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="7" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2"></td>

   <td rowspan="10"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>7</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="12"></td>

   <td colspan="2"></td>

   <td colspan="7"></td>

   <td rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="10"></td>

   <td></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

   <td colspan="12"></td>

   <td></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>








































<ol start="8">

 <li><strong>Append: </strong>it will add a number into the ring right after (clockwise) the current number. The newly appended number will become the new current number.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="29"></td>

   <td width="285"></td>

   <td width="29"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3"></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="21"></td>

   <td width="149"></td>

   <td width="26"></td>

   <td width="29"></td>

   <td width="3"></td>

   <td width="9"></td>

   <td width="20"></td>

   <td width="9"></td>

   <td width="25"></td>

   <td width="16"></td>

   <td width="13"></td>

   <td width="9"></td>

   <td width="29"></td>

   <td width="5"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="16"></td>

   <td colspan="2" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

   <td colspan="3"></td>

   <td colspan="4" rowspan="9"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2"></td>

   <td rowspan="10"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="8"></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>7</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="9"></td>

   <td></td>

   <td></td>

   <td rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="12"></td>

   <td></td>

   <td colspan="8"></td>

   <td rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="9"></td>

   <td colspan="2"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td colspan="10"></td>

   <td></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>





































<ol start="9">

 <li><strong>Delete:</strong> it will delete the current number. Its right hand side (clockwise) number will become the new current number.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="29"></td>

  </tr>

  <tr>

   <td></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="21"></td>

   <td width="149"></td>

   <td width="23"></td>

   <td width="22"></td>

   <td width="6"></td>

   <td width="1"></td>

   <td width="22"></td>

   <td width="6"></td>

   <td width="23"></td>

   <td width="5"></td>

   <td width="24"></td>

   <td width="5"></td>

   <td width="22"></td>

   <td width="5"></td>

   <td width="24"></td>

   <td width="5"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="21"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="12"></td>

   <td colspan="3" rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="6"></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="8" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2"></td>

   <td rowspan="11"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="9"></td>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="12"></td>

   <td colspan="11"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="10"></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td colspan="8"></td>

   <td colspan="2"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>


































<ol start="10">

 <li><strong>Jump:</strong> it changes the current pointer. If the jump number is too large/small, the counting wraps around the ring again and again. Positive jump number means going clockwise while negative means counter-clockwise.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="29"></td>

   <td width="285"></td>

   <td width="29"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3"></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="21"></td>

   <td width="149"></td>

   <td width="24"></td>

   <td width="21"></td>

   <td width="8"></td>

   <td width="3"></td>

   <td width="18"></td>

   <td width="11"></td>

   <td width="36"></td>

   <td width="16"></td>

   <td width="13"></td>

   <td width="9"></td>

   <td width="29"></td>

   <td width="5"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="21"></td>

   <td colspan="4" rowspan="11"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="11"></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2"></td>

   <td rowspan="10"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td></td>

   <td></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="12"></td>

   <td></td>

   <td colspan="7"></td>

   <td rowspan="6" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="12"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td colspan="10"></td>

   <td></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>








































<ol start="11">

 <li><strong>Sort:</strong> it will sort the numbers in the ring in increasing order clockwise. The current number will be in the same place after sorting.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="29"></td>

  </tr>

  <tr>

   <td></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="21"></td>

   <td width="149"></td>

   <td width="24"></td>

   <td width="21"></td>

   <td width="4"></td>

   <td width="4"></td>

   <td width="21"></td>

   <td width="4"></td>

   <td width="18"></td>

   <td width="29"></td>

   <td width="21"></td>

   <td width="25"></td>

   <td width="4"></td>

   <td width="25"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="20"></td>

   <td rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

   <td colspan="12"></td>

   <td colspan="3" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="12"></td>

   <td></td>

   <td></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2"></td>

   <td rowspan="11"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="9"></td>

   <td></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td></td>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="5" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="10"></td>

   <td colspan="3" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td colspan="8"></td>

   <td colspan="2"></td>

   <td rowspan="4" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>





































<ol start="12">

 <li><strong>Print:</strong> it will print out all the numbers in the ring in one line starting at the current number and going clockwise.</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="29"></td>

  </tr>

  <tr>

   <td></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>4</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="7"></td>

   <td width="17"></td>

   <td width="5"></td>

   <td width="23"></td>

   <td width="29"></td>

   <td width="26"></td>

   <td width="17"></td>

   <td width="12"></td>

   <td width="17"></td>

   <td width="21"></td>

   <td width="149"></td>

   <td width="9"></td>

   <td width="149"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="3" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>3</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>6</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td colspan="4"></td>

   <td colspan="2"></td>

   <td rowspan="8"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="3" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td colspan="2" rowspan="3" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>1</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="6"></td>

   <td></td>

   <td></td>

   <td rowspan="4" width="149">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>2 3 5 6 1 4 8 5 </strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td colspan="3" rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>5</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td rowspan="2" width="29">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>8</strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>





































<ol start="13">

 <li><strong>You are required to demonstrate your program to the instructor on the due day in class in order to receive grades. </strong></li>

</ol>







<strong><em>Submission: </em></strong>




<ol>

 <li>Please zip your <strong>project folder (and do not include any input file)</strong> and you should get a file with this name <strong>(not in rar)</strong>:</li>

</ol>

<strong>COSC489_PT_<em>&lt;your username&gt;.</em>zip</strong>

<ol>

 <li>Be sure to unzip the above file and try the program out to make sure zip works correctly.</li>

 <li>Then submit your zip file to Blackboard <strong>before 10AM, April 12, Wednesday</strong>.</li>

</ol>




<strong><em>Grading: </em></strong>




<ol>

 <li>Grading of this program is based on:

  <ol>

   <li>Whether your program performs as it should (70%);</li>

   <li>Whether your program has the correct logical structure (20%);</li>

   <li>Whether you program follows the recommended programming style (10%).</li>

  </ol></li>

 <li>The total of this test is 100 points.</li>

</ol>

<strong> </strong>


