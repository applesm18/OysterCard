dependence: three.js

start environment

node version 18.14.0

1. npm install
2. npx vite


test guide line

1. first click station is the station of take up.
2. next click station is the station of take off.
3. you can see the price

4. if you click swipe off, that means you doesn’t swipe out



/*
The Oyster Card Problem
This is made by msapple0338@gmail.com for the test of tech with london bus card problem.

Everystation has their price of take up a bus and their price is not constant.
Also Everystaton has their fee is that means the fee of passin bus.
maxfee is the baned price that is applyed anyone who dosen't swipe off.
var stations = [
    {x: 0.2, y: 0.78, name: 'Holborn', price: 2.5, fee: 0.5, max: 3.20},
    {x: -0.6, y: 0.46, name: 'Earl’s Court', price: 2.0, fee: 0.25, max: 3.20},
    {x: -1.2, y: -0.02, name: 'Wimbledon', price: 2.0, fee: 0.25, max: 3.20},
    {x: -1.0, y: -0.76, name: 'Hammersmith', price: 2.0, fee: 0.25, max: 3.20}
];

those x, y of stations is the position of station in the londonmap.

if you click the station first then you take up the bus, after you click the station secondly you will take off the bus, finally you can show the total fare.

if you click the button of swipe off, additional penalties will apply to you  with max price
*/