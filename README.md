# finm32000-homework-7-solved
**TO GET THIS SOLUTION VISIT:** [FINM32000 Homework 7 Solved](https://www.ankitcodinghub.com/product/finm32000-homework-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98429&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FINM32000 Homework 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

The code in the ipynb 􏰑le should do Problem 1 if you set hw7MC.algorithm = ‘value’. It should do Problem 2 if you set hw7MC.algorithm = ‘policy’

Problem 1

Complete the coding of the provided ipynb 􏰑le which prices the Bermudan put option under GBM, with the same parameters as in the Excel worksheet from class (which has been posted on Canvas), using the Longsta􏰐-Schwartz method.

Report an estimated price, based on 10000 paths.

At each exercise date, do the regression using only the paths that are in-the-money (at that speci􏰑c date 􏰏 so there may be di􏰐erent subsamples on di􏰐erent dates), not all of the paths.

Problem 2

The Longsta􏰐-Schwartz method can be regarded as an example of a Reinforcement Learning (RL) algorithm. It selects actions (􏰃exercise􏰎 vs. 􏰃continue􏰎) to try to maximize an expected reward (option payo􏰐) that depends on the transitions of a state variable (the underlying X).

In particular, Longsta􏰐-Schwartz takes a Value-function approach to solving the dynamic pro- gramming formulation of the Reinforcement Learning problem. It 􏰑nds an estimate fˆ (same

notation as L7) of the value function for the continuation action, by using OLS regression, of simu- lated continuation payo􏰐s on the state variable. This estimated continuation value fˆ is compared

against the value function for the exercise action, which is just the payo􏰐 function (for example Payoff(X)=K−X inthecaseofaput):

If fˆ (X ) &gt; Payoff(X ) then continue to hold at time t ntntn n

If fˆ (X ) ≤ Payoff(X ) then exercise at time t ntn tn n

Here we will consider a di􏰐erent approach to RL.

In contrast to Value-function RL, another approach to Reinforcement Learning is the Policy-

based approach. Rather than trying to estimate the value function (for the continuation action), it tries to more directly optimize the time-tn policy function, let’s denote it Φ, which maps each X to one of two outputs: {0,1}, where 0 denotes continuing to hold, while 1 denotes stopping (exercising).

If Φ(Xtn ) = 0 then continue to hold at time tn If Φ(Xtn ) = 1 then exercise at time tn

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
n

</div>
</div>
<div class="layoutArea">
<div class="column">
n

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
In the particular one-dimensional example of put pricing that we have been studying, we know what form the stopping policy function should take. In theory it should be an indicator function

Φcn (X) = 1X≤cn

with a parameter cn is a speci􏰑c 􏰃critical􏰎 or 􏰃threshold􏰎 level of the stock price X. Below cn you should exercise, and above cn you should continue to hold the put. So, in principle, we could try to estimate the optimal threshold cn by choosing it to maximize the average, across all simulated paths, of the simulated payout resulting from the policy Φcn at time tn.

However, this optimization has some numerical di􏰒culties, due to the discontinuity of this 􏰃hard stopping􏰎 decision function Φ which only has two outputs {0,1}. So suppose that we optimize a smoother function, a 􏰃soft stopping􏰎 decision function φ which produces outputs in the interval between 0 and 1. Let φ have two parameters a,b (which may depend on the time slice n) and speci􏰑cally let φ be1 a sigmoid or logistic function of b(X − a):

φa,b(X) = 1 . (*) 1 + exp(−b(X − a))

For large negative b, the φa,b will behave similarly to Φa, in that it’s near 1 for X &lt; a and near 0 for X &gt; a. But unlike the hard stopping decision function, the soft decision function φ is more optimizer-friendly, because it varies continuously between 0 and 1. It can be interpreted as making the exercise decision randomly, with probability φa,b(X) of exercising, and probability 1 − φa,b(X) of continuing to hold, conditional on X. At time tn the optimizer should optimize

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰌1􏰕M􏰓m m m 􏰔􏰍 max φa,b(Xtn)×(K−Xtn)+(1−φa,b(Xtn))×(Continuation payout on the mth path)

</div>
</div>
<div class="layoutArea">
<div class="column">
a,b M m=1

where Xm denotes the mth simulated path. Then calculate payouts by converting this optimized

</div>
</div>
<div class="layoutArea">
<div class="column">
soft stopping decision into a hard stopping decision by

Φ(Xtn ) = 1φaˆ,ˆb(Xtn )≥0.5 × 1Payoff(Xtn )&gt;0

where aˆ and ˆb denote the optimized parameter values. Multiplying by 1Payoff (Xtn )&gt;0 makes sure that you are not exercising OTM options. It should not be needed if your φ has been trained correctly, but we include it as a precaution.

Implement this policy optimization approach, by completing the code in the ipynb 􏰑le. Most of the coding is already provided.

1On this problem, which is simple in the sense that the exercise region in X-space is just a one-dimensional interval, a single sigmoid function (*) is su􏰒cient to approximate the optimal stopping policy.

On harder problems, where the exercise region may be a complicated subset of a multidimensional X-space, the function (*) can be upgraded to a deep neural network.

For instance see http://jmlr.org/papers/volume20/18-232/18-232.pdf

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
