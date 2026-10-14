I just start again.

Okay now the first part is finished:
- It contains single, united system of physical ranks I would map to Laegna letters.

I am working on this further:
- I aligned to find some constraints where Laegna could show digit values *meaningfully* connected to infinities and zeroes - based on it's voyage.
- I think maybe the number system should be same for different units.

Well I need one day thinking that I got these simple numbers :)
- I decide about formulation where I can cover more of them.
- This initial thing is not full Laegna Voyage - I won't solve every equation of relativity and space growth ratios. Rather I linearize this type of system and find out what can be right or wrong. This will be very symmetric.

# Laegna Algorithm Consciousness

We need to map infinities.

These are basic infinities

##### ~0.97 light years => 1 light year. horizon 1 of 2nd degree.

Let's call it *E*, rank-1 infinity.

##### Earth circumference 40 000 km. horizon 3 of 1st degree.

This is second expansion to the series.

##### ~16,000,000,000 => horizon 4 of 2nd degree.

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
- We can work with decimals and materials now separately.

We need:
- Convert continuous decimal and binary rank functions to fourier maps on octaves: integral-differential orders need to be used with base-4 number, with two rank calculations in parallel.

Consider Laegna numbers:
- Digit - band1, band2
- I - 0, 0
- O - 0, 1
- A - 1, 0
- E - 1, 1
- Each number has two boolean band digits and purely encodes acceleration.

Now the ranks themselves, integral orders where number has constant or linear growth, must be turned into bits:
- First bit, 0 for IO and 1 for AE, encodes exp-2 and log-2 relations; E is exponential growth and I is logarithmic shrinking - they are just encoded to this series of numbers. This is lazy exponent growth. This small atomic exponent is the infinity space slowly passing. 16 is symmetric to infinity scale.
- Second bit, 0 for IA and 1 for OE, encodes exp-second-rank-10 relations. 1, 10, 10000, 1000000000 is the growth factor.
  - Large numbers are needed for precise local relations inside each infinity area.

Base-4 encoding of these:
- On integral-differential scale, each bit position represents single band, a piece of fourier map; such as if EEE is 3rd rank, integral might be calculated such that it spans 0.0 to 1.5 or 0.0 to 3.0 depending on internal functions (i.e. is constant or linear function being anchor for ranks): in each case, fourier composition must show each digit now has this rank data. If digits are added, the existing digits should still encode the same values.

"U" should encode "1", "do not change", in which case *the value of that frequency is not used and others are combined to number in remaining range*; some default input does not change if 1 is applied:
- Plus and minus is used for whole digit series, where they do not change order.
- Exponential bits should exist directly in exponential order - the 0, 1, 2, 3 or 1, 2, 3, 4; this means they must be reflected in growth function; with 1 it might be still.
- Lower bits should have the material scale 1, 10, 10000, 1000000000. In function, this grows linearly.

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
