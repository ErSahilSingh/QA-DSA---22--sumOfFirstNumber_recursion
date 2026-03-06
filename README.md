# QA-DSA---22--sumOfFirstNumber
function sumN(n) {
  // your solution here
  if (typeof n !== 'number' || !Number.isFinite(n) || n < 0 || !Number.isInteger(n)) {
    return false;
  }
  if (n == 0) { return 0 }

  return n + sumN(n - 1)

}

module.exports = { sumN };
