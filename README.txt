# cami_infinit

**Cami Infinit** is a symbolic math expression engine using a custom notation `}-\-{` invented by **Mark R.**  
It allows evaluation of infinite series, products, derivatives, integrals, plotting, and symbolic expressions easily.

---

## 🔥 Custom Symbol: `}-\-{`

Any expression wrapped in `}-\-{[ ... ]}` is evaluated by the library.

---

## ✅ Supported Features

| Feature         | Example                                                              |
|----------------|----------------------------------------------------------------------|
| Sum            | `}-\-{[sum: i=1 to 100 (i**2)]}`                                      |
| Product        | `}-\-{[product: i=1 to 10 (i)]}`                                      |
| Derivative     | `}-\-{[derivative: sin(x)**2 over x]}`                               |
| Integral       | `}-\-{[integral: x**2 over x from 0 to 1]}`                          |
| Double Integral| `}-\-{[integral2: x*y over x from 0 to 1 and y from 0 to 1]}`        |
| Solve          | `}-\-{[solve: x**2 - 4 = 0 for x]}`                                  |
| Plot           | `}-\-{[plot: sin(x)/x over x from -10 to 10]}`                       |
| Partial Sum    | `}-\-{[partial_sum: i=1 to 100 (1/i**2) from 1 to 50]}`              |
| Evaluate       | `}-\-{[eval: 3 + 5 * (2 - 1)]}`                                      |
| Sequence       | `}-\-{[sequence: i=1 to 5 (i*2+1)]}`                                 |
| Variable Assign| `}-\-{[let: a=5; sum: i=1 to a (i)]}`                                |

---

## 🔧 Installation

```bash
pip install cami_infinit
