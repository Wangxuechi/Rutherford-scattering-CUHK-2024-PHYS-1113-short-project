# Rutherford-scattering-CUHK-2024-PHYS-1113-short-project
For CUHK students enrolled in PHYS 1111 or 1113 who need reference on Rutherford scattering experiment data process.\\
Pay attention, there are tow versions with tiny difference. The original one **used np.append()** function, which has a terrible performance. So, a latest version I added **scipy.integrate.solve_ivp()** (solve initial value problem) to accelerate.\\
However, due to solve_ivp use advanced numerical method to do integral, in the deviation analysis part, there may be some "strange" phenomenon. But, in general, it makes sense and I also add explanation.\
Further more, I want to say some words off topic. In my opinion, the most crucial thing in our academic life is 
## Passion
