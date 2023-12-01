# Riemann Hypothesis

### 1. Integral

![01Integral](Resources/01Integral.jpg)

### 2. Derivative

![02Derivative](Resources/02Derivative.jpg)

### 3. X^3/X Halts

![03X^3_XHalts](Resources/03X^3_XHalts.jpg)

``` javascript
function decider(x)
{
	while (x != 0)
	{
		if (x > 0)
		{
			x--;
			if (x == 0)
			{
				return 1/2;
			}

		}	

		if (x < 0)
		{
			x++;
			if (x == 0)
			{
				return 1/2;
			}
		}

		if (x < 0)
		{
			x++;
			if (x == 0)
			{
				return 1/2;
			}
		}
	}
}
```

Next Problem:

What separates an integer from a real number?

-----

### References

Ung, E. (2024). Topology Of Javascript. https://github.com/ericung/TopologyOfJavascript

Ung, E. (2024). Harmonic Monomial Deciders. https://github.com/ericung/HarmonicMonomialDeciders

Weisstein, E. W. (2021). Riemann hypothesis. Retrieved November 30, 2023, from https://mathworld.wolfram.com/RiemannHypothesis.html
