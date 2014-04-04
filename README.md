php-type
========

<table>
   <tr>
    <td>Expression</td>
    <td>gettype($x)</td>
    <td>empty($x)</td>
    <td>boolean:if($x)</td>
    <td>is_null($x)</td>
    <td>isset($x)</td>
   </tr>
   <tr>
    <td>$x = "";</td>
    <td>string</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = null;</td>
    <td>NULL</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
   </tr>
   <tr>
    <td>var $x;</td>
    <td>NULL</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
   </tr>
   <tr>
    <td>$x is undefined</td>
    <td>NULL</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
   </tr>
   <tr>
    <td>$x = array();</td>
    <td>array</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = false;</td>
    <td>boolean</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = true;</td>
    <td>boolean</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = 1;</td>
    <td>integer</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = 42;</td>
    <td>integer</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = 0;</td>
    <td>integer</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = -1;</td>
    <td>integer</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = "1″;</td>
    <td>string</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = "0″;</td>
    <td>string</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = "-1″;</td>
    <td>string</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = "php";</td>
    <td>string</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = "true";</td>
    <td>string</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
   <tr>
    <td>$x = "false";</td>
    <td>string</td>
    <td>FALSE</td>
    <td>TRUE</td>
    <td>FALSE</td>
    <td>TRUE</td>
   </tr>
  </table>