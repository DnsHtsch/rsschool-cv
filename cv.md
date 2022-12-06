# **Denis Hantsevich**

## Frontend Developer

---

### _Contact information_
#### Phone: +375298188787
#### E-mail: DnsHtsch@gmail.com
#### Discord: DnsHtsch#3664
#### [GitHub]: https://github.com/DnsHtsch

--- 

### _Skills_
* HTML & CSS
* Java Script

### _Code Example_

```const quickSort = arr => {
  const a = [...arr];
  if (a.length < 2) return a;
  const pivotIndex = Math.floor(arr.length / 2);
  const pivot = a[pivotIndex];
  const [lo, hi] = a.reduce(
    (acc, val, i) => {
      if (val < pivot || (val === pivot && i != pivotIndex)) {
        acc[0].push(val);
      } else if (val > pivot) {
        acc[1].push(val);
      }
      return acc;
    },
    [[], []]
  );
  return [...quickSort(lo), pivot, ...quickSort(hi)];
};
```

---

### Language:
* English - A1
* Russian - native