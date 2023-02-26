const size = prompt("Enter the size of array: ");
const arrays = [];

for (let i = 0; i < size; i++) {
  arrays.push(Math.floor(Math.random() * 201) - 100);
}

console.log(arrays);

function binarySearch(list, item) {
  let low = 0;
  let high = list.length - 1;

  while (low <= high) {
    let mid = Math.floor((low + high) / 2);
    let guess = list[mid];

    if (guess === item) {
      return mid;
    }

    if (guess > item) {
      high = mid - 1;
    } else {
      low = mid + 1;
    }
  }

  return null;
}

const target = prompt("Enter the desired number: ");
const searchh = Number(target);
console.log("Your number is here", binarySearch(arrays, searchh));
