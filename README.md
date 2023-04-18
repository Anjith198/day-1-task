# day-1-task
1 Write a blog on Difference between HTTP1.1 vs HTTP2

HTTP1.1 was known to have poor response time. With websites becoming more resource-intensive, the protocol was losing its efficiency. It progressively became essential to minimize latency and boost page load speeds.whereas HTTP2 is the second version of HTTP with most of the shortcomings of its predecessor addressed in it. It has come with advancements in efficiency, speed, and security. Till the date, HTTP/2 is supported on almost all popular web browsers, such as Chrome, Firefox, Internet Explorer, and Safari.Launching of the HTTP/2 was an attempt to overcome the limitations of HTTP/1.1 and make it a more efficient web protocol
                      HTTP1.1                                                          HTTP2
   - It works on the textual format.                                         It works on the binary protocol.
   - It uses requests resource Inlining for use getting multiple pages       It uses PUSH frame by server that collects all multiple pages 
   -It compresses data by itself.                                            It uses HPACK for data compression.


2 Write a blog about objects and its internal representation in Javascript

Objects in javascript is the most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) .object is a collection of named values having state and behavior 
  
const o = new Object();
o.foo = 42;
 
console.log(o);
// { foo: 42 }
