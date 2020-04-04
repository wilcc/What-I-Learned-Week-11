# What-I-Learned-Week-11

use obj.slice() or [...obj] to avoid mutate original obj when sort, filer, map

function myFunction() {
    let d = new Date();
    let n = d.toLocaleTimeString();
    return n;
}
give you the current time

make sure the function you use return the exact thing you want
ie when you are looking for an array make sure your function is not returning a string, otherwise it would be `undefined`
