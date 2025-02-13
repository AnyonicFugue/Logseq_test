- ((63e38a70-4b41-476b-b989-2419e008da6d))
- Idea: {{cloze Introduce auxiliary parameters to simplify the expression, then change the order of integration.}} #card
  card-last-interval:: 42
  card-repeats:: 2
  card-ease-factor:: 2.7
  card-next-schedule:: 2023-11-09T00:50:34.260Z
  card-last-reviewed:: 2023-09-28T00:50:34.260Z
  card-last-score:: 5
	- The trick is usually followed by changing the order of integrations and shifting integration variables (To complete the square).
	- So there's the inherent problem: Can we really exchange the order of integration?
	  collapsed:: true
		- Similar problems abound. For example, lots of things don't converge absolutely.
- $$
  \frac{1}{A B}=\int_0^1 d x \frac{1}{[x A+(1-x) B]^2}=\int_0^1 d x d y \delta(x+y-1) \frac{1}{[x A+y B]^2}
  $$
- card-last-score:: 5
  card-repeats:: 4
  card-next-schedule:: 2024-06-06T17:01:46.022Z
  card-last-interval:: 297.18
  card-ease-factor:: 2.66
  card-last-reviewed:: 2023-08-14T13:01:46.023Z
  $$
  \frac{1}{A_1 A_2 \cdots A_n}=\int_0^1 d x_1 \cdots d x_n \delta\left(\sum x_i-1\right) \frac{(n-1) !}{\left[x_1 A_1+x_2 A_2+\cdots x_n A_n\right]^n}
  $$
  #card
	- Core: It turns an awkward product into a summation.
	- The proof is to be completed.
-
- card-last-score:: 5
  card-repeats:: 4
  card-next-schedule:: 2023-09-08T03:36:46.375Z
  card-last-interval:: 188.16
  card-ease-factor:: 2.8
  card-last-reviewed:: 2023-03-04T00:36:46.376Z
  $$
  \frac{1}{A B^n}=\int_0^1 d x d y \delta(x+y-1) \frac{n y^{n-1}}{[x A+y B]^{n+1}}
  $$
   #card
	- Proof. Differentiate the first identity wrt B