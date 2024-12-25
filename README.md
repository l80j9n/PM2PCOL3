java c
PM2PCOL3 - Mathematical Modelling for Pharmacology
Autumn Term Assignment 2023
This coursework constitutes 15% of the final module mark and is marked out of 100, with a further breakdown of marks provided beside each question.
Consider the three variable PKPD model shown in Figure 1 which describes the absorp-tion, distribution, metabolism and excretion of a drug in the body. Here a bolus of the drug is delivered intravenously to the blood compartment whereby it transfers to the liver compartment with rate constant k1 and the remaining body tissue with rate constant k2. The drug then transfers from the tissue to the liver with rate constant k3 and may then return to the blood from the liver with rate constant k−1 or be eliminated from body via the liver according to first order elimination kinetics. The mass of drug in the blood, liver and tissue compartments is denoted MB = MB(t), ML = ML(t) and MT = MT (t), respectively, with corresponding volumes VB, VL and VT .

Figure 1: A three compartment PKPD model describing the dosing of a drug delivered to the blood compartment.
1. By considering the mass of drug in each compartment and its subsequent transfer between compartments, show the concentration of the drug in the blood and liver compartments is given by


Table 1: The PKPD model parameter values.
with the initial conditions
CB(0) = CB0 and CL(0) = 0,                                                                                                (3)
and in so doing derive the equation describing the drug concentration in the tissue compartment and its initial condition. Here CB = CB(t) is the concentration of the drug in the blood, CL = CL(t) the liver and CT = CT (t) the tissue and we define VLB = VL/VB, VT L = VT /VL and VBT = VB/VT . Remember to show your working in deriving all three equations.                        [20 marks]
2. In the case of k−1 = 0 determine the eigenvalues of the system you wrote down for question (1).                       [15 marks]
3. Returning to k−1 being non-zero and utilising the parameter values given in Table 1 determine numerical solutions 代 写PM2PCOL3 - Mathematical Modelling for Pharmacology Autumn Term Assignment 2023R
代做程序编程语言to your system of equations using Matlab for a period of 100 hours.                               [15 marks]
4. Undertake a local sensitivity analysis of the model transfer rate constants (you do not need to consider the volume ratios or initial conditions) to determine which of these parameters have the greatest effect on the concentration of the drug in the tissue compartment at steady-state (you should choose a specific time justifying your choice). Your answer needs to either graphically or in tabular form. complemented with written text summarise the importance of each parameter in affecting the steady-state concentration.           [35 marks]
5. Again utilising the parameter values given in Table 1 and assuming a daily dose of 50 mg/l/hour every 24 hours (starting at t = 0 on the first day and lasting 30 mins in duration), simulate the effect of regular drug dosing for a period of 5 days.
Remember to ensure the lines
pts = odeset(’MaxStep’,1e-2);
[t,y]=ode45(@assignment2324odes, [0 150], [CB0 CL0 CT0], opts, k1, ...);
are included in your code as covered in the final part of Computer Practical 3.                           [15 marks]
Your attempt at questions (1) and (2) do not need to be typewritten (handwritten sub-missions are fine). Attempts at all remaining questions should be typewritten and be no longer than three pages in length, including all text, figures and tables. Only that work contained within the first three pages of your response to questions (3) to (5) will be marked, i.e. any work over the three page limit will not be read or marked. Typewritten solutions must be written in a minimum of 12pt font using either Times New Roman, Arial or Helvetica fonts with a minimum of 2cm margins. All figures should be accompanied by captions and any tables have titles. Remember to provide plenty of detail in describing your solutions with appropriate written expla-nation of the mathematics as well as details as to how your model analysis informs the system behaviour, including reference to figures and tables where appropriate.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
