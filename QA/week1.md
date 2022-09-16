# Week 1. The time value of money. 

1.  Interest rate and how it's formed.
2.  SAR & EAR.
3.  FV, PV and FoC.
4.  Annuities and perpetuity.
5.  TVM problems.

# Glossary and abbreviations

- IR - Interest rate - процентная ставка.
- Compounding - платежи (idk)
- SAR - Stated annual rate.
- EAR - Effective annual rate.
- FoC - Frequency of Compounding
- PMT - Payment
- r - Interest rate (at the moment).

# Interpretation of the Interest rate

- **Equilibrium rate of return** - Minimum rate of return an investor must receive in order to accept
  the investment.

- **Discount rate** - Rate that must be applied to a cash flow to determine it's present value.

- **The opportunity cost** - Value that investor forgos (loses) by investing.

# How the Interest rate is formed

**Interest rate =**    
**Real risk-free rate** (Reflects the current vs future consumption)  
+  
**Expected inflation premium** (Money costs less over time in a real terms)  
+  
**Default risk premium** (Compensation for possibility and probability that the borrower will default)  
+  
**Liquidity premium** (If financial product has a low liquidity - In case if you want to sell it quickly - you will be forced to take losses by selling it under the market price)  
+  
**Maturity premium** (Long term debts are more sensitive to the future IR falls, if you expect such).  

# SAR and EAR

**SAR - Stated annual rate.** Rate which is stated in the documents.

**EAR - Effective annual rate.** Rate which an investor really gets.

_SAR does not account for infra-year compounding while EAR does._


# FV and PV

**PV - Present Value.**\
**FV - Future Value.**\
**FV_x** **- Future Value after x compounding periods (years by
default)**\

$$FV_x = PV * (1 + SAR)^x$$

# FV depends on FoC

**Frequency of Compounding (FoC)** - how many times during the year the
transaction happens.

$$FV_x = PV * (1 + \frac{SAR}{FoC})^{x*FoC}$$

$$PV = \frac{FV_x}{(1 + \frac{SAR}{FoQ})^{x*FoQ} }$$

# Annuities

[**Annuity is a list of *identical* cash flows**]
[Annuities can be]

1.  [Finite]{.nodecor}

    1.  [**Ordinary annuity** - Cash flows occur ***at the end*** of
        each ***compounding period***.]{.nodecor}

    2.  [**Annuity due** - Cash flows occur ***at the beginning*** of
        each ***compounding period***.]{.nodecor}

2.  [Infinite]{.nodecor}

    1.  [**Perpetuity.**]{.nodecor}

# PV of an annuity

$$
PV = PVofPMT_1 + PVofPMT_2 + \ldots + PVofPMT_n = \\
\frac{PMT}{1 + r} + \frac{PMT}{(1 + r)^2} + \ldots + \frac{PMT}{(1 + r)^n}
$$

We have a geometric sequence with

$$b = \frac{PMT}{1 + r}$$

NOT EDITED BELOW (EP)

[and]{.nodecor}
$$a = \frac{1}{1 + r}$$\
[So the sum equals to]{.nodecor}\
$$S = b * \frac{q^n - 1}{q - 1}$$\
[substitute b and q]{.nodecor}\
$$PV\textsubscript{\textnormal{annuity}} = PMT * \frac{(1 + r)^n - 1}{r * (1 + r)^n}$$

# PV of a perpetuity

$$PV\textsubscript{\textnormal{perpetuiry}} = \lim_{n \to +\infty} PV\textsubscript{\textnormal{annuity}} =  \lim_{n \to +\infty} PMT * \frac{(1 + r)^n - 1}{r * (1 + r)^n} = \frac{PMT}{r}$$
$$
