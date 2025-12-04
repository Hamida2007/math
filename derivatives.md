# Derivatives: A Comprehensive Guide

## Table of Contents
1. Introduction
2. Definition of Derivative
3. Rules of Differentiation
4. Common Derivatives
5. Applications
6. Examples

---

## 1. Introduction

The derivative is one of the most important concepts in calculus. It measures how a function changes as its input changes. In other words, it represents the rate of change or the slope of a function at a particular point.

The derivative has numerous applications in physics, engineering, economics, and many other fields.

---

## 2. Definition of Derivative

### Formal Definition

The derivative of a function $f(x)$ at a point $x = a$ is defined as:

$$f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}$$

Alternatively, using the limit definition:

$$f'(x) = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}$$

### Notation

The derivative of $f(x)$ can be denoted as:
- $f'(x)$ (Lagrange notation)
- $\frac{df}{dx}$ (Leibniz notation)
- $\frac{d}{dx}f(x)$ (operator notation)
- $D_x f(x)$ (operator notation)

### Geometric Interpretation

The derivative represents the slope of the tangent line to the curve $y = f(x)$ at a given point. A positive derivative means the function is increasing, while a negative derivative means it's decreasing.

---

## 3. Rules of Differentiation

### Power Rule

For $f(x) = x^n$ where $n$ is any real number:

$$\frac{d}{dx}(x^n) = nx^{n-1}$$

**Example:** $\frac{d}{dx}(x^3) = 3x^2$

### Sum and Difference Rule

For functions $u(x)$ and $v(x)$:

$$\frac{d}{dx}[u(x) + v(x)] = \frac{du}{dx} + \frac{dv}{dx}$$

$$\frac{d}{dx}[u(x) - v(x)] = \frac{du}{dx} - \frac{dv}{dx}$$

### Product Rule

For functions $u(x)$ and $v(x)$:

$$\frac{d}{dx}[u(x) \cdot v(x)] = u'(x) \cdot v(x) + u(x) \cdot v'(x)$$

Or in short form: $(uv)' = u'v + uv'$

### Quotient Rule

For functions $u(x)$ and $v(x)$ where $v(x) \neq 0$:

$$\frac{d}{dx}\left[\frac{u(x)}{v(x)}\right] = \frac{u'(x) \cdot v(x) - u(x) \cdot v'(x)}{[v(x)]^2}$$

Or in short form: $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$

### Chain Rule

For a composite function $y = f(g(x))$:

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

Where $u = g(x)$.

---

## 4. Common Derivatives

| Function | Derivative |
|----------|-----------|
| $c$ (constant) | $0$ |
| $x^n$ | $nx^{n-1}$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x \ln(a)$ |
| $\ln(x)$ | $\frac{1}{x}$ |
| $\log_a(x)$ | $\frac{1}{x \ln(a)}$ |
| $\sin(x)$ | $\cos(x)$ |
| $\cos(x)$ | $-\sin(x)$ |
| $\tan(x)$ | $\sec^2(x)$ |
| $\cot(x)$ | $-\csc^2(x)$ |
| $\sec(x)$ | $\sec(x)\tan(x)$ |
| $\csc(x)$ | $-\csc(x)\cot(x)$ |

---

## 5. Applications of Derivatives

### Rate of Change

Derivatives measure how quantities change over time. For example, velocity is the derivative of position with respect to time.

### Optimization

Finding maximum and minimum values of functions. This is crucial in business (maximizing profit), physics (finding equilibrium points), and engineering.

### Curve Sketching

The first derivative tells us where the function is increasing or decreasing. The second derivative tells us about concavity.

### Related Rates

Problems where multiple quantities are related and change with respect to time.

### Physics

- **Velocity:** $v = \frac{ds}{dt}$ (derivative of position)
- **Acceleration:** $a = \frac{dv}{dt}$ (derivative of velocity)
- **Force:** $F = \frac{dp}{dt}$ (derivative of momentum)

---

## 6. Examples

### Example 1: Power Rule

Find the derivative of $f(x) = 5x^4 - 3x^2 + 7$

**Solution:**
$$f'(x) = 5 \cdot 4x^3 - 3 \cdot 2x + 0 = 20x^3 - 6x$$

### Example 2: Product Rule

Find the derivative of $f(x) = (2x + 1)(x^2 - 3)$

**Solution:**

Let $u = 2x + 1$ and $v = x^2 - 3$

Then $u' = 2$ and $v' = 2x$

Using the product rule:
$$f'(x) = 2(x^2 - 3) + (2x + 1)(2x)$$
$$= 2x^2 - 6 + 4x^2 + 2x$$
$$= 6x^2 + 2x - 6$$

### Example 3: Chain Rule

Find the derivative of $f(x) = (3x^2 + 2)^5$

**Solution:**

Let $u = 3x^2 + 2$, then $\frac{du}{dx} = 6x$

Using the chain rule:
$$f'(x) = 5(3x^2 + 2)^4 \cdot 6x = 30x(3x^2 + 2)^4$$

### Example 4: Quotient Rule

Find the derivative of $f(x) = \frac{x^2 + 1}{x - 1}$

**Solution:**

Let $u = x^2 + 1$ and $v = x - 1$

Then $u' = 2x$ and $v' = 1$

Using the quotient rule:
$$f'(x) = \frac{2x(x - 1) - (x^2 + 1)(1)}{(x - 1)^2}$$
$$= \frac{2x^2 - 2x - x^2 - 1}{(x - 1)^2}$$
$$= \frac{x^2 - 2x - 1}{(x - 1)^2}$$

---

## Conclusion

Understanding derivatives is fundamental to calculus and has applications throughout science, engineering, and economics. By mastering the rules and concepts presented here, you'll be well-equipped to solve a wide variety of problems involving rates of change and optimization.
