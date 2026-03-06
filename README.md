# QA-DSA---22--sumOfFirstNumber
function sumFirst(n) {
    if (n === 0) return 0
    return n + sumFirst(n-1)
}

console.log(sumFirst(5))
