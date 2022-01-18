# Hard_4811_Pill

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/Hard_4811_Pill/blob/main/4811_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

Let's say dp[the number of W] [ the number of H] is our dp.

dp[W][0~30] will be 1 (W , WW, WWW, ... WWWWWW...WWW)

dp[W][i] will be i because we only have one H and add it into upper string.

Then how to find dp[W][H] ? This can be founded with adding W to dp[W-1][H] and adding H to dp[W][H-1]. 

Because we are saving only possible cases in the dp, that will work.

Then printing dp[input][input] will be the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
