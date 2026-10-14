I just start again.

# Laegna Algorithm Consciousness

We need to map infinities.

These are basic infinities

##### ~0.97 light years => 1 light year. horizon 1.

Let's call it *E*, rank-1 infinity.

##### Earth circumference 40 000 km

This is second expansion to the series.

##### ~16,000,000,000 => horizon 4.

Let's call it EEEE, rank-3 infinity.

## Infinity Rank conclusion

Without units, let's have these ranks:
- **I**: 1
- **O**: 20
- **A**: 40 000
- **E**: 16 000 000 000

These can be very basic parts of initial physics.

To make it invariant as we go on we now want the lower ranks:

| Rank | Symbol | Number | rank | symbol | number |
|---|---|---:|---|---|---:|
| -I | -EEEE | -16 000 000 000 | -i | -IIII | -0.0000000000625 |
| -O | -EEE | -40 000 | -o | -III | -0.000025 |
| -A | -EE | -20 | -a | -II | -0.05 |
| -E | -E | -1 | -e | -I | -1 |
| +I | +E | 1 | +e | +I | 1 |
| +O | +EE | 20 | +a | +II | 0.05 |
| +A | +EEE | 40 000 | +o | +III | 0.000025 |
| +E | +EEEE | 16 000 000 000 | +i | +IIII | 0.0000000000625 |

For our own experimentation, this becomes equivalent of Laegna physics SI table of basic ranks:
- We can work with decimals

---

# Theory part

Let's define Laegna octaves:

Laegna Real Octaves:
- 1D: 1, **2**, 4, 8, 16..
- 2D: 1, 4, **16**, 1024, 4048

Decimal Pseudooctaves - Laegna understanding based on ranks:
- I: 1 - 0 * 1
- O: 1 0 - 1 * 1
- A: 1 00 00 - 2 * 2
- E: 1 000 000 000 - 3 * 3

## Continuous Exponential Rank Function

### Mathematics

Forward conversion:

$$
e(n)=10^{n^2}
$$

Reverse conversion for $x\geq 1$:

$$
e^{-1}(x)=\sqrt{\log_{10}(x)}
$$

Thus, $n\geq0$ maps to $x\geq1$, and the inverse recovers the original rank.

Series: 1, 10, 10000, 1000000000, ...

Exponent orders: 0, 1, 4, 9, ...

### Python

```python
import math

e = lambda n: 10 ** (n * n)
e_inv = lambda x: math.sqrt(math.log10(x))
```

### JavaScript

```python
const e = n => 10 ** (n * n);
const e_inv = x => Math.sqrt(Math.log10(x));
```

## Continuous Octave Growth Function

Octave growth doubles with each rank: octave 0 = 1, octave 1 = 2, octave 2 = 4, octave -1 = 0.5, and octave -2 = 0.25.

### Mathematics

Forward conversion:

$$
o(n)=2^n,\qquad n\in\mathbb{R}
$$

Reverse conversion:

$$
o^{-1}(x)=\log_2(x),\qquad x>0
$$

### Python

```python
import math

o = lambda n: 2**n
o_inv = lambda x: math.log2(x)
```

### JavaScript

```javascript
const o = n => 2 ** n;
const o_inv = x => Math.log2(x);
```
