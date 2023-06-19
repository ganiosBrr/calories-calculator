# calories-calculator
Use the calorie calculator to estimate the number of daily calories your body needs to maintain your current weight.

I'm using localstorage for holding info about sex and ratio.

I got main variables for calculation - sex, height, weight, age, ratio. We keep main result empty untill all main variables has value in it.

Main idea is to have inputs of sex, height, weight, age and take their values and use them in calc() function. Thats why we have getStaticInformation() function for sex and ratio;
Also we have getDynamicInformation() function for identify values from inputs that users fill.

calc() function calculates daily calories for male and female based on formula taken from this article https://fitseven.ru/zdorovie/metabolism/sutochnaya-norma-kaloriy

