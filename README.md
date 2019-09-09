Siddhi Execution Math
======================================

  [![Jenkins Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-math/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-execution-math/)
  [![GitHub Release](https://img.shields.io/github/release/siddhi-io/siddhi-execution-math.svg)](https://github.com/siddhi-io/siddhi-execution-math/releases)
  [![GitHub Release Date](https://img.shields.io/github/release-date/siddhi-io/siddhi-execution-math.svg)](https://github.com/siddhi-io/siddhi-execution-math/releases)
  [![GitHub Open Issues](https://img.shields.io/github/issues-raw/siddhi-io/siddhi-execution-math.svg)](https://github.com/siddhi-io/siddhi-execution-math/issues)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/siddhi-io/siddhi-execution-math.svg)](https://github.com/siddhi-io/siddhi-execution-math/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The **siddhi-execution-math extension** is a <a target="_blank" href="https://siddhi.io/">Siddhi</a> extension that provides useful mathematical functions such as power, round, random, cos, log, etc.

For information on <a target="_blank" href="https://siddhi.io/">Siddhi</a> and it's features refer <a target="_blank" href="https://siddhi.io/redirect/docs.html">Siddhi Documentation</a>. 

## Download

* Versions 5.x and above with group id `io.siddhi.extension.*` from <a target="_blank" href="https://mvnrepository.com/artifact/io.siddhi.extension.execution.math/siddhi-execution-math/">here</a>.
* Versions 4.x and lower with group id `org.wso2.extension.siddhi.*` from <a target="_blank" href="https://mvnrepository.com/artifact/org.wso2.extension.siddhi.execution.math/siddhi-execution-math">here</a>.

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3">5.0.3</a>.

## Features

* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#percentile-aggregate-function">percentile</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#aggregate-function">Aggregate Function</a>)*<br> <div style="padding-left: 1em;"><p>This functions returns the pth percentile value of a given argument.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#abs-function">abs</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the absolute value of the given parameter. It wraps the <code>java.lang.Math.abs()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#acos-function">acos</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>If -1 &lt;= p1 &lt;= 1, this function returns the arc-cosine (inverse cosine) value of p1.If the domain is invalid, it returns NULL. The value returned is in radian scale. This function wraps the java.lang.Math.acos() function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#asin-function">asin</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>If -1 &lt;= p1 &lt;= 1, this function returns the arc-sin (inverse sine) value of p1. If the domain is invalid, it returns NULL. The value returned is in radian scale. This function wraps the java.lang.Math.asin() function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#atan-function">atan</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>1. If a single <code>p1</code> is received, this function returns the arc-tangent (inverse tangent) value of <code>p1</code>. <br>2. If <code>p1</code> is received along with an optional <code>p1</code>, it considers them as x and y coordinates and returns the arc-tangent (inverse tangent) value. <br>The returned value is in radian scale. This function wraps the <code>java.lang.Math.atan()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#bin-function">bin</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns a string representation of the p1 argument, that is of either 'integer' or 'long' data type, as an unsigned integer in base 2. It wraps the <code>java.lang.Integer.toBinaryString</code> and java.lang.Long.toBinaryString` methods.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#cbrt-function">cbrt</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the cube-root of 'p1' which is in radians. It wraps the <code>java.lang.Math.cbrt()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#ceil-function">ceil</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the smallest double value, i.e., the closest to the negative infinity, that is greater than or equal to the <code>p1</code> argument, and is equal to a mathematical integer. It wraps the <code>java.lang.Math.ceil()</code> method.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#conv-function">conv</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function converts <code>a</code> from the <code>fromBase</code> base to the <code>toBase</code> base.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#copysign-function">copySign</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns a value of an input with the received <code>magnitude</code> and <code>sign</code> of another input. It wraps the <code>java.lang.Math.copySign()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#cos-function">cos</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the cosine of <code>p1</code> which is in radians. It wraps the <code>java.lang.Math.cos()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#cosh-function">cosh</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the hyperbolic cosine of <code>p1</code> which is in radians. It wraps the <code>java.lang.Math.cosh()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#e-function">e</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the <code>java.lang.Math.E</code> constant, which is the closest double value to e, where e is the base of the natural logarithms. </p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#exp-function">exp</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the Euler's number <code>e</code> raised to the power of <code>p1</code>. It wraps the <code>java.lang.Math.exp()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#floor-function">floor</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function wraps the <code>java.lang.Math.floor()</code> function and returns the largest value, i.e., closest to the positive infinity, that is less than or equal to <code>p1</code>, and is equal to a mathematical integer.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#getexponent-function">getExponent</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the unbiased exponent that is used in the representation of <code>p1</code>. This function wraps the <code>java.lang.Math.getExponent()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#hex-function">hex</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function wraps the <code>java.lang.Double.toHexString() function. It returns a hexadecimal string representation of the input, </code>p1`.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#isinfinite-function">isInfinite</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function wraps the <code>java.lang.Float.isInfinite()</code> and <code>java.lang.Double.isInfinite()</code> and returns <code>true</code> if <code>p1</code> is infinitely large in magnitude and <code>false</code> if otherwise.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#isnan-function">isNan</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function wraps the <code>java.lang.Float.isNaN()</code> and <code>java.lang.Double.isNaN()</code> functions and returns <code>true</code> if <code>p1</code> is NaN (Not-a-Number), and returns <code>false</code> if otherwise.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#ln-function">ln</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the natural logarithm (base e) of <code>p1</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#log-function">log</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the logarithm of the received <code>number</code> as per the given <code>base</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#log10-function">log10</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the base 10 logarithm of <code>p1</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#log2-function">log2</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the base 2 logarithm of <code>p1</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#max-function">max</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the greater value of <code>p1</code> and <code>p2</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#min-function">min</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the smaller value of <code>p1</code> and <code>p2</code>.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#oct-function">oct</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function converts the input parameter <code>p1</code> to octal.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#parsedouble-function">parseDouble</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the double value of the string received.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#parsefloat-function">parseFloat</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the float value of the received string.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#parseint-function">parseInt</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the integer value of the received string.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#parselong-function">parseLong</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the long value of the string received.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#pi-function">pi</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the <code>java.lang.Math.PI</code> constant, which is the closest value to pi, i.e., the ratio of the circumference of a circle to its diameter. </p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#power-function">power</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function raises the given value to a given power.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#rand-function">rand</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This returns a stream of pseudo-random numbers when a sequence of calls are sent to the <code>rand()</code>. Optionally, it is possible to define a seed, i.e., <code>rand(seed)</code> using which the pseudo-random numbers are generated. These functions internally use the <code>java.util.Random</code> class.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#round-function">round</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the value of the input argument rounded off to the closest integer/long value.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#signum-function">signum</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This returns +1, 0, or -1 for the given positive, zero and negative values respectively. This function wraps the <code>java.lang.Math.signum()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#sin-function">sin</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This returns the sine of the value given in radians. This function wraps the <code>java.lang.Math.sin()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#sinh-function">sinh</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This returns the hyperbolic sine of the value given in radians. This function wraps the <code>java.lang.Math.sinh()</code> function. </p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#sqrt-function">sqrt</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the square-root of the given value. It wraps the <code>java.lang.Math.sqrt()</code>s function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#tan-function">tan</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the tan of the given value in radians. It wraps the <code>java.lang.Math.tan()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#tanh-function">tanh</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function returns the hyperbolic tangent of the value given in radians. It wraps the <code>java.lang.Math.tanh()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#todegrees-function">toDegrees</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function converts the value given in radians to degrees. It wraps the <code>java.lang.Math.toDegrees()</code> function.</p></div>
* <a target="_blank" href="https://siddhi-io.github.io/siddhi-execution-math/api/5.0.3/#toradians-function">toRadians</a> *(<a target="_blank" href="http://siddhi.io/en/v5.0/docs/query-guide/#function">Function</a>)*<br> <div style="padding-left: 1em;"><p>This function converts the value given in degrees to radians. It wraps the <code>java.lang.Math.toRadians()</code> function.</p></div>

## Dependencies 

There are no other dependencies needed for this extension. 

## Installation

For installing this extension on various siddhi execution environments refer Siddhi documentation section on <a target="_blank" href="https://siddhi.io/redirect/add-extensions.html">adding extensions</a>.

## Support and Contribution

* We encourage users to ask questions and get support via <a target="_blank" href="https://stackoverflow.com/questions/tagged/siddhi">StackOverflow</a>, make sure to add the `siddhi` tag to the issue for better response.

* If you find any issues related to the extension please report them on <a target="_blank" href="https://github.com/siddhi-io/siddhi-execution-math/issues">the issue tracker</a>.

* For production support and other contribution related information refer <a target="_blank" href="https://siddhi.io/community/">Siddhi Community</a> documentation.
