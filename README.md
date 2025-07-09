# Mortgage-Calculator
An interactive mortgage calculator web app that helps users estimate their monthly mortgage repayments and total repayment over the loan term, based on input values like mortgage amount, interest rate, term, and repayment type.

<!-- You can replace this with your hosted image path -->

Features
 Input: Mortgage amount, term (years), interest rate (%)

 Selectable mortgage types: Repayment or Interest-Only

 Dynamic calculation of:

Monthly repayments

Total repayment over the term

 Responsive, clean UI with Tailwind CSS

Built entirely with HTML, JavaScript, and TailwindCSS

🛠 Tech Stack
HTM

CSS 

Vanilla JavaScript

🧮 Calculation Logic
Repayment mortgage uses the amortized loan formula:

𝑀
=
𝑃
⋅
𝑟
1
−
(
1
+
𝑟
)
−
𝑛
M= 
1−(1+r) 
−n
 
P⋅r
​
 
Where:

M = Monthly repayment

P = Loan amount

r = Monthly interest rate

n = Total number of months

Interest-only mortgage formula:

𝑀
=
𝑃
⋅
𝑟
M=P⋅r
