+++
title = "Parallel Forecast"
outputs = ["Reveal"]
+++
<!--- menu currently not working, hence some noise in body.HTML
and nav.html --->


{{% section %}}

<div style="text-align: left" >
<div id="termynal" data-ty-typeDelay="20" data-ty-lineDelay="600" data-termynal>
    <span data-ty="input" data-ty-prompt="~/user >">python</span>
    <span data-ty="input" data-ty-prompt=">>>">import tensorflow as tf</span>
    <span data-ty="input" data-ty-prompt=">>>">import gym</span>
    <span data-ty="input" data-ty-prompt=">>>">env = gym.make('MontezumaRevenge-v0')</span>
    <span data-ty="input" data-ty-prompt=">>>">env.reset()</span>
    <span data-ty="input" data-ty-prompt=">>>">for episode in range(100000):</span>
    <span data-ty="input" data-ty-prompt=">>>">&nbsp;&nbsp;&nbsp;&nbsp; <!--- this not an input!! ---> tf.cheap_model_based_RL_agent(env)</span>
    <span data-ty="progress"></span>
    <span data-ty>Score: 200.000</span>
    <span data-ty>Completed all 24 rooms at superhuman level</span>
    <span data-ty>Total training time: 10 min</span>
</div>

How probable is this is possible by 2022?

<!--- </div> --->


---

<div style="text-align:left">

We're building more robust tools for forecasting AI progress

<font size=5>

{{% fragment %}} _1 Prediction markets_ &nbsp;&nbsp; By constructing a futures contract on metrics of interest, we can use the market mechanism to incentivize forecasts and generate robust prices. Prediction markets have a rich theoretical grounding ([Arrow et al., 2008](http://science.sciencemag.org/content/320/5878/877)), and a track-record of predicting events ranging from elections ([Berg et al., 2008](https://econpapers.repec.org/article/eeeintfor/v_3a24_3ay_3a2008_3ai_3a2_3ap_3a285-300.htm)), infectious disease activity ([Polgreen et al., 2007](https://academic.oup.com/cid/article/44/2/272/330878)), tech product sales ([Plott & Kay-Yut, 2002](https://authors.library.caltech.edu/44358/)) and more.{{% /fragment %}}

{{% fragment %}} _2 Superforecasting_ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Prediction markets can fail due to lack of liquidity, errors in contract formulation, or catastrophic events events which leave the insurer unable to settle the contract. Hence, in collaboration with [Metaculus](https://www.metaculus.com/questions/), we're also building a dedicated community of AI forecasters, and aggregating their predictions using algorithms based on their track-record.{{% /fragment %}}

</font>

---

<div style="text-align:left">

Reach out at: _hello@parallelforecast.com_

<font size=5>

We’re a team from Google and Oxford who believe in the importance of building better institutions for making intellectual progress.

We’d especially like to hear from you if:

* You work in a role relying on good forecasts of AI (e.g. policy researcher, grantmaker, safety researcher)
* You have an excellent forecasting track-record (supported by e.g. a PredictionBook or Metaculus profile)


</div>
</font>

{{% /section %}}
