## Statement of the inequality

### Simplified version

> Let $X_1,\dots,X_n$ be i.i.d. random variables such that $|X_i|\le c$ almost surely for some $c>0$. Then for any $\delta>0$, 
> 
> $$\P\left(\frac{1}{n}\sum_{i=1}^n X_i -\E[X] > \sqrt{\frac{2\mathrm{Var}(X)t}{n}}+\frac{c t}{n} \right)\le e^{-t}$$

### General version

> Let $X_1,\dots,X_n$ be independent real random variables. Assume that there exist positive constants $v$ and $c$ such that $\sum_{i=1}^n \E[X_i^2]\le v$ and for any integer $q\ge 3$,
$$\E[(X_i)_+^q]\le \frac{q!}{2}vc^{q-2} $$
> Then, for any $t>0$, 
> 
> $$\P\left(\sum_{i=1}^n (X_i -\E[X]) > \sqrt{2vt}+c t \right)\le e^{-t}$$

---

## See also

* <$link to="Hoeffding's inequality"/>

## Reference 

Boucheron, S., Lugosi, G., & Massart, P. (2013). Concentration Inequalities - A Nonasymptotic Theory of Independence.