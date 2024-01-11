# Test Report Markdown export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./actions.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using actions script|
|Description|Test triggered by [@NicoRobertIn](https://github.com/NicoRobertIn) by actions trigger|
|Script|[complete-test.py](https://github.com/acimov-tools/model-test/blob/refs/heads/main/.acimov/model-test/complete-test.py)
|Date|2024-01-11 09:49:22|

***


# Statistic summary

Here is a short overview for this test report

204 Assertions

:boom:0 MajorFail, :exclamation:186 MinorFail, :warning:0 CannotTell, :grey_question:0 NotTested, :white_check_mark:18 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="0%" height="25px"/><img src="../assets/orange.png" width="91%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="0%" height="25px"/><img src="../assets/green.png" width="9%" height="25px"/></div>

<br/>

According to the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary, each outcome type means:
* :x: Fail: The subject failed the test. 
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MinorFail Assertions

Here is the chapter related to the MinorFail assertion

:exclamation:186 MinorFail assertions

<details>
<summary>Fold/Unfold the 186 summary and details</summary>

## MinorFail Assertions Summary

[Jump to statistic summary](#statistic-summary)

:exclamation:186 MinorFail assertions

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-1">1/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-1)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-2">2/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-2)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-3">3/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-3)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-4">4/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-4)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-5">5/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-5)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-6">6/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-6)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-7">7/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-7)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-8">8/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-8)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-9">9/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-9)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-10">10/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-10)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-11">11/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-11)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-12">12/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-12)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-13">13/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-13)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-14">14/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-14)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-15">15/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-15)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-16">16/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-16)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-17">17/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-17)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-18">18/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-18)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-19">19/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-19)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-20">20/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-20)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-21">21/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-21)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-22">22/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-22)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-23">23/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-23)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-24">24/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-24)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-25">25/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-25)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-26">26/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-26)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-27">27/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-27)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-28">28/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-28)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-29">29/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-29)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-30">30/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-30)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-31">31/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-31)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-32">32/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-32)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-33">33/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-33)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-34">34/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-34)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-35">35/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-35)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-36">36/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-36)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-37">37/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-37)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-38">38/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-38)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-39">39/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-39)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-40">40/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-40)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-41">41/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-41)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-42">42/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-42)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-43">43/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-43)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-44">44/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-44)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-45">45/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-45)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-46">46/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-46)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-47">47/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-47)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-48">48/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-48)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-49">49/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-49)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-50">50/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-50)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-51">51/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-51)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-52">52/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-52)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-53">53/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-53)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-54">54/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-54)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-55">55/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-55)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-56">56/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-56)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-57">57/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-57)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-58">58/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-58)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-59">59/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-59)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-60">60/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-60)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-61">61/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-61)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-62">62/186</div>|:exclamation:*MinorFail*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-62)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-63">63/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-63)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-64">64/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-64)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-65">65/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-65)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-66">66/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-66)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-67">67/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-67)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-68">68/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-68)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-69">69/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-69)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-70">70/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-70)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-71">71/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-71)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-72">72/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-72)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-73">73/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-73)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-74">74/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-74)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-75">75/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-75)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-76">76/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-76)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-77">77/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-77)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-78">78/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-78)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-79">79/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-79)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-80">80/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-80)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-81">81/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-81)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-82">82/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-82)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-83">83/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-83)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-84">84/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-84)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-85">85/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-85)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-86">86/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-86)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-87">87/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-87)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-88">88/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-88)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-89">89/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-89)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-90">90/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-90)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-91">91/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-91)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-92">92/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-92)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-93">93/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-93)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-94">94/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-94)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-95">95/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-95)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-96">96/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-96)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-97">97/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-97)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-98">98/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-98)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-99">99/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-99)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-100">100/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-100)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-101">101/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-101)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-102">102/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-102)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-103">103/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-103)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-104">104/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-104)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-105">105/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-105)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-106">106/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-106)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-107">107/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-107)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-108">108/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-108)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-109">109/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-109)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-110">110/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-110)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-111">111/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-111)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-112">112/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-112)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-113">113/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-113)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-114">114/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-114)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-115">115/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-115)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-116">116/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-116)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-117">117/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-117)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-118">118/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-118)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-119">119/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-119)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-120">120/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-120)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-121">121/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-121)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-122">122/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-122)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-123">123/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-123)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-124">124/186</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-124)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-125">125/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-125)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-126">126/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-126)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-127">127/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-127)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-128">128/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-128)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-129">129/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL TC Profile incompatible|[Jump](#minorfail-assertion-number-129)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-130">130/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-130)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-131">131/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-131)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-132">132/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-132)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-133">133/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-133)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-134">134/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-134)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-135">135/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-135)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-136">136/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-136)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-137">137/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-137)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-138">138/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-138)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-139">139/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-139)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-140">140/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-140)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-141">141/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-141)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-142">142/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-142)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-143">143/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-143)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-144">144/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-144)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-145">145/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-145)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-146">146/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL RL Profile incompatible|[Jump](#minorfail-assertion-number-146)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-147">147/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-147)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-148">148/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-148)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-149">149/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-149)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-150">150/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-150)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-151">151/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-151)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-152">152/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-152)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-153">153/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-153)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-154">154/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-154)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-155">155/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-155)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-156">156/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-156)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-157">157/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-157)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-158">158/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-158)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-159">159/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-159)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-160">160/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-160)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-161">161/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-161)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-162">162/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-162)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-163">163/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-163)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-164">164/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-164)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-165">165/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-165)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-166">166/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-assertion-number-166)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-167">167/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-167)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-168">168/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-168)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-169">169/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-169)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-170">170/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-170)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-171">171/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-171)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-172">172/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-172)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-173">173/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-173)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-174">174/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-174)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-175">175/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-175)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-176">176/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-176)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-177">177/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-177)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-178">178/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-178)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-179">179/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-179)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-180">180/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-180)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-181">181/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-181)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-182">182/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-182)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-183">183/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-183)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-184">184/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-184)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-185">185/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-185)|
|[Table top](#minorfail-assertions-summary)|<div id="summary-MinorFail-186">186/186</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-assertion-number-186)|

***

## MinorFail Assertion Details

This subchapter gives more details to the :exclamation:MinorFail assertions

### MinorFail Assertion number 1

[Jump to summary definition](#summary-MinorFail-1)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 2

[Jump to summary definition](#summary-MinorFail-2)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 3

[Jump to summary definition](#summary-MinorFail-3)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 4

[Jump to summary definition](#summary-MinorFail-4)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteNonSweetWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 5

[Jump to summary definition](#summary-MinorFail-5)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteTableWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#TableWine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 6

[Jump to summary definition](#summary-MinorFail-6)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 7

[Jump to summary definition](#summary-MinorFail-7)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 8

[Jump to summary definition](#summary-MinorFail-8)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Not a valid Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 9

[Jump to summary definition](#summary-MinorFail-9)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 10

[Jump to summary definition](#summary-MinorFail-10)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 11

[Jump to summary definition](#summary-MinorFail-11)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 12

[Jump to summary definition](#summary-MinorFail-12)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Not a valid Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 13

[Jump to summary definition](#summary-MinorFail-13)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 14

[Jump to summary definition](#summary-MinorFail-14)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 15

[Jump to summary definition](#summary-MinorFail-15)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 16

[Jump to summary definition](#summary-MinorFail-16)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> .</code></pre>|

***
### MinorFail Assertion number 17

[Jump to summary definition](#summary-MinorFail-17)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 18

[Jump to summary definition](#summary-MinorFail-18)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 19

[Jump to summary definition](#summary-MinorFail-19)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 20

[Jump to summary definition](#summary-MinorFail-20)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 21

[Jump to summary definition](#summary-MinorFail-21)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 22

[Jump to summary definition](#summary-MinorFail-22)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 23

[Jump to summary definition](#summary-MinorFail-23)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 24

[Jump to summary definition](#summary-MinorFail-24)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 25

[Jump to summary definition](#summary-MinorFail-25)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 26

[Jump to summary definition](#summary-MinorFail-26)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 27

[Jump to summary definition](#summary-MinorFail-27)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 28

[Jump to summary definition](#summary-MinorFail-28)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported
Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 29

[Jump to summary definition](#summary-MinorFail-29)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 30

[Jump to summary definition](#summary-MinorFail-30)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 31

[Jump to summary definition](#summary-MinorFail-31)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 32

[Jump to summary definition](#summary-MinorFail-32)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 33

[Jump to summary definition](#summary-MinorFail-33)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 34

[Jump to summary definition](#summary-MinorFail-34)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 35

[Jump to summary definition](#summary-MinorFail-35)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 36

[Jump to summary definition](#summary-MinorFail-36)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 37

[Jump to summary definition](#summary-MinorFail-37)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 38

[Jump to summary definition](#summary-MinorFail-38)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 39

[Jump to summary definition](#summary-MinorFail-39)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 40

[Jump to summary definition](#summary-MinorFail-40)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 41

[Jump to summary definition](#summary-MinorFail-41)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 42

[Jump to summary definition](#summary-MinorFail-42)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Restriction on datatypes|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#yearValue> a owl:DatatypeProperty ;&#10;rdfs:domain &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#VintageYear> ;&#10;rdfs:range xsd:positiveInteger .</code></pre>|

***
### MinorFail Assertion number 43

[Jump to summary definition](#summary-MinorFail-43)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 44

[Jump to summary definition](#summary-MinorFail-44)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 45

[Jump to summary definition](#summary-MinorFail-45)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 46

[Jump to summary definition](#summary-MinorFail-46)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 47

[Jump to summary definition](#summary-MinorFail-47)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|OWL EL: Enumeration with more than one individual or literal|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 48

[Jump to summary definition](#summary-MinorFail-48)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 49

[Jump to summary definition](#summary-MinorFail-49)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported
Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 50

[Jump to summary definition](#summary-MinorFail-50)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 51

[Jump to summary definition](#summary-MinorFail-51)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 52

[Jump to summary definition](#summary-MinorFail-52)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|OWL EL: Enumeration with more than one individual or literal|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 53

[Jump to summary definition](#summary-MinorFail-53)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 54

[Jump to summary definition](#summary-MinorFail-54)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 55

[Jump to summary definition](#summary-MinorFail-55)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 56

[Jump to summary definition](#summary-MinorFail-56)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 57

[Jump to summary definition](#summary-MinorFail-57)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 58

[Jump to summary definition](#summary-MinorFail-58)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 59

[Jump to summary definition](#summary-MinorFail-59)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 60

[Jump to summary definition](#summary-MinorFail-60)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 61

[Jump to summary definition](#summary-MinorFail-61)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 62

[Jump to summary definition](#summary-MinorFail-62)

:exclamation:MinorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Restriction on datatypes|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#yearValue> a owl:DatatypeProperty ;&#10;rdfs:domain &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#VintageYear> ;&#10;rdfs:range xsd:positiveInteger .</code></pre>|

***
### MinorFail Assertion number 63

[Jump to summary definition](#summary-MinorFail-63)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 64

[Jump to summary definition](#summary-MinorFail-64)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 65

[Jump to summary definition](#summary-MinorFail-65)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 66

[Jump to summary definition](#summary-MinorFail-66)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteNonSweetWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 67

[Jump to summary definition](#summary-MinorFail-67)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteTableWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#TableWine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 68

[Jump to summary definition](#summary-MinorFail-68)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 69

[Jump to summary definition](#summary-MinorFail-69)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 70

[Jump to summary definition](#summary-MinorFail-70)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 71

[Jump to summary definition](#summary-MinorFail-71)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 72

[Jump to summary definition](#summary-MinorFail-72)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 73

[Jump to summary definition](#summary-MinorFail-73)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 74

[Jump to summary definition](#summary-MinorFail-74)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> .</code></pre>|

***
### MinorFail Assertion number 75

[Jump to summary definition](#summary-MinorFail-75)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 76

[Jump to summary definition](#summary-MinorFail-76)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Not a valid Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 77

[Jump to summary definition](#summary-MinorFail-77)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 78

[Jump to summary definition](#summary-MinorFail-78)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Not a valid Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 79

[Jump to summary definition](#summary-MinorFail-79)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 80

[Jump to summary definition](#summary-MinorFail-80)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 81

[Jump to summary definition](#summary-MinorFail-81)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 82

[Jump to summary definition](#summary-MinorFail-82)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 83

[Jump to summary definition](#summary-MinorFail-83)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 84

[Jump to summary definition](#summary-MinorFail-84)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 85

[Jump to summary definition](#summary-MinorFail-85)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 86

[Jump to summary definition](#summary-MinorFail-86)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 87

[Jump to summary definition](#summary-MinorFail-87)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 88

[Jump to summary definition](#summary-MinorFail-88)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 89

[Jump to summary definition](#summary-MinorFail-89)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 90

[Jump to summary definition](#summary-MinorFail-90)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 91

[Jump to summary definition](#summary-MinorFail-91)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 92

[Jump to summary definition](#summary-MinorFail-92)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 93

[Jump to summary definition](#summary-MinorFail-93)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 94

[Jump to summary definition](#summary-MinorFail-94)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported
Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 95

[Jump to summary definition](#summary-MinorFail-95)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 96

[Jump to summary definition](#summary-MinorFail-96)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 97

[Jump to summary definition](#summary-MinorFail-97)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 98

[Jump to summary definition](#summary-MinorFail-98)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 99

[Jump to summary definition](#summary-MinorFail-99)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 100

[Jump to summary definition](#summary-MinorFail-100)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 101

[Jump to summary definition](#summary-MinorFail-101)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 102

[Jump to summary definition](#summary-MinorFail-102)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 103

[Jump to summary definition](#summary-MinorFail-103)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 104

[Jump to summary definition](#summary-MinorFail-104)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Restriction on datatypes|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#yearValue> a owl:DatatypeProperty ;&#10;rdfs:domain &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#VintageYear> ;&#10;rdfs:range xsd:positiveInteger .</code></pre>|

***
### MinorFail Assertion number 105

[Jump to summary definition](#summary-MinorFail-105)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 106

[Jump to summary definition](#summary-MinorFail-106)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 107

[Jump to summary definition](#summary-MinorFail-107)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 108

[Jump to summary definition](#summary-MinorFail-108)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 109

[Jump to summary definition](#summary-MinorFail-109)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 110

[Jump to summary definition](#summary-MinorFail-110)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 111

[Jump to summary definition](#summary-MinorFail-111)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 112

[Jump to summary definition](#summary-MinorFail-112)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 113

[Jump to summary definition](#summary-MinorFail-113)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 114

[Jump to summary definition](#summary-MinorFail-114)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|OWL EL: Enumeration with more than one individual or literal|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 115

[Jump to summary definition](#summary-MinorFail-115)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported
Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 116

[Jump to summary definition](#summary-MinorFail-116)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 117

[Jump to summary definition](#summary-MinorFail-117)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|OWL EL: Enumeration with more than one individual or literal|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 118

[Jump to summary definition](#summary-MinorFail-118)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 119

[Jump to summary definition](#summary-MinorFail-119)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 120

[Jump to summary definition](#summary-MinorFail-120)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 121

[Jump to summary definition](#summary-MinorFail-121)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 122

[Jump to summary definition](#summary-MinorFail-122)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 123

[Jump to summary definition](#summary-MinorFail-123)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 124

[Jump to summary definition](#summary-MinorFail-124)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Restriction on datatypes|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#yearValue> a owl:DatatypeProperty ;&#10;rdfs:domain &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#VintageYear> ;&#10;rdfs:range xsd:positiveInteger .</code></pre>|

***
### MinorFail Assertion number 125

[Jump to summary definition](#summary-MinorFail-125)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 126

[Jump to summary definition](#summary-MinorFail-126)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 127

[Jump to summary definition](#summary-MinorFail-127)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 128

[Jump to summary definition](#summary-MinorFail-128)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteNonSweetWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 129

[Jump to summary definition](#summary-MinorFail-129)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL TC Profile incompatible|
|Description|OWL: Expression E in: unionOf, intersectionOf, complementOf, oneOf require: subClassOf E, equivalentClass E, etc|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteTableWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#TableWine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 130

[Jump to summary definition](#summary-MinorFail-130)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 131

[Jump to summary definition](#summary-MinorFail-131)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 132

[Jump to summary definition](#summary-MinorFail-132)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 133

[Jump to summary definition](#summary-MinorFail-133)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 134

[Jump to summary definition](#summary-MinorFail-134)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 135

[Jump to summary definition](#summary-MinorFail-135)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 136

[Jump to summary definition](#summary-MinorFail-136)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> .</code></pre>|

***
### MinorFail Assertion number 137

[Jump to summary definition](#summary-MinorFail-137)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 138

[Jump to summary definition](#summary-MinorFail-138)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Not a valid Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 139

[Jump to summary definition](#summary-MinorFail-139)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 140

[Jump to summary definition](#summary-MinorFail-140)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Not a valid Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 141

[Jump to summary definition](#summary-MinorFail-141)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 142

[Jump to summary definition](#summary-MinorFail-142)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 143

[Jump to summary definition](#summary-MinorFail-143)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 144

[Jump to summary definition](#summary-MinorFail-144)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 145

[Jump to summary definition](#summary-MinorFail-145)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> a owl:Class ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 146

[Jump to summary definition](#summary-MinorFail-146)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL RL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 147

[Jump to summary definition](#summary-MinorFail-147)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 148

[Jump to summary definition](#summary-MinorFail-148)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 149

[Jump to summary definition](#summary-MinorFail-149)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 150

[Jump to summary definition](#summary-MinorFail-150)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 151

[Jump to summary definition](#summary-MinorFail-151)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 152

[Jump to summary definition](#summary-MinorFail-152)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 153

[Jump to summary definition](#summary-MinorFail-153)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 154

[Jump to summary definition](#summary-MinorFail-154)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 155

[Jump to summary definition](#summary-MinorFail-155)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 156

[Jump to summary definition](#summary-MinorFail-156)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported
Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 157

[Jump to summary definition](#summary-MinorFail-157)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 158

[Jump to summary definition](#summary-MinorFail-158)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 159

[Jump to summary definition](#summary-MinorFail-159)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported in a Super Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 160

[Jump to summary definition](#summary-MinorFail-160)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 161

[Jump to summary definition](#summary-MinorFail-161)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 162

[Jump to summary definition](#summary-MinorFail-162)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 163

[Jump to summary definition](#summary-MinorFail-163)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 164

[Jump to summary definition](#summary-MinorFail-164)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 165

[Jump to summary definition](#summary-MinorFail-165)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 166

[Jump to summary definition](#summary-MinorFail-166)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Restriction on datatypes|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#yearValue> a owl:DatatypeProperty ;&#10;rdfs:domain &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#VintageYear> ;&#10;rdfs:range xsd:positiveInteger .</code></pre>|

***
### MinorFail Assertion number 167

[Jump to summary definition](#summary-MinorFail-167)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 168

[Jump to summary definition](#summary-MinorFail-168)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> .</code></pre>|

***
### MinorFail Assertion number 169

[Jump to summary definition](#summary-MinorFail-169)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 170

[Jump to summary definition](#summary-MinorFail-170)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> .</code></pre>|

***
### MinorFail Assertion number 171

[Jump to summary definition](#summary-MinorFail-171)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> .</code></pre>|

***
### MinorFail Assertion number 172

[Jump to summary definition](#summary-MinorFail-172)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> .</code></pre>|

***
### MinorFail Assertion number 173

[Jump to summary definition](#summary-MinorFail-173)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> .</code></pre>|

***
### MinorFail Assertion number 174

[Jump to summary definition](#summary-MinorFail-174)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> .</code></pre>|

***
### MinorFail Assertion number 175

[Jump to summary definition](#summary-MinorFail-175)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 176

[Jump to summary definition](#summary-MinorFail-176)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|OWL EL: Enumeration with more than one individual or literal|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 177

[Jump to summary definition](#summary-MinorFail-177)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported
Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 178

[Jump to summary definition](#summary-MinorFail-178)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported in a Class Expression|
|Pointer|<pre lang="Turtle"><code>[] a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> .</code></pre>|

***
### MinorFail Assertion number 179

[Jump to summary definition](#summary-MinorFail-179)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|OWL EL: Enumeration with more than one individual or literal|
|Pointer|<pre lang="Turtle"><code>[] a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) .</code></pre>|

***
### MinorFail Assertion number 180

[Jump to summary definition](#summary-MinorFail-180)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Dry> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> [ ] ) .</code></pre>|

***
### MinorFail Assertion number 181

[Jump to summary definition](#summary-MinorFail-181)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Vintage> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasVintageYear> ] .</code></pre>|

***
### MinorFail Assertion number 182

[Jump to summary definition](#summary-MinorFail-182)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBordeaux> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SemillonGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Bordeaux> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 183

[Jump to summary definition](#summary-MinorFail-183)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteBurgundy> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:hasValue &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#ChardonnayGrape> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:maxCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Burgundy> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 184

[Jump to summary definition](#summary-MinorFail-184)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteLoire> a owl:Class ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:allValuesFrom [ a owl:Class ;&#10;owl:oneOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#CheninBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#PinotBlancGrape> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#SauvignonBlancGrape> ) ] ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ] ;&#10;owl:intersectionOf ( &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Loire> &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#WhiteWine> ) .</code></pre>|

***
### MinorFail Assertion number 185

[Jump to summary definition](#summary-MinorFail-185)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Class Expression not supported with rdfs:subClassOf|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Wine> a owl:Class ;&#10;rdfs:label "wine"@en,&#10;"vin"@fr ;&#10;rdfs:subClassOf [ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:allValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Winery> ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasMaker> ],&#10;[ a owl:Restriction ;&#10;owl:minCardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#madeFromGrape> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasSugar> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasFlavor> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasBody> ],&#10;[ a owl:Restriction ;&#10;owl:cardinality "1"^^xsd:nonNegativeInteger ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#hasColor> ],&#10;[ a owl:Restriction ;&#10;owl:onProperty &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#locatedIn> ;&#10;owl:someValuesFrom &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#Region> ], &#10; &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/food#PotableLiquid> .</code></pre>|

***
### MinorFail Assertion number 186

[Jump to summary definition](#summary-MinorFail-186)

:exclamation:MinorFail assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Restriction on datatypes|
|Pointer|<pre lang="Turtle"><code>&#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#yearValue> a owl:DatatypeProperty ;&#10;rdfs:domain &#60;http://www.w3.org/TR/2003/PR-owl-guide-20031209/wine#VintageYear> ;&#10;rdfs:range xsd:positiveInteger .</code></pre>|

***

</details>

***


# Pass Assertions

Here is the chapter related to the Pass assertion

:white_check_mark:18 Pass assertions

<details>
<summary>Fold/Unfold the 18 summary and details</summary>

## Pass Assertions Summary

[Jump to statistic summary](#statistic-summary)

:white_check_mark:18 Pass assertions

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-1">1/18</div>|:white_check_mark:*Pass*|`wine`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-assertion-number-1)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-2">2/18</div>|:white_check_mark:*Pass*|`wine`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|Ranges properly defined|[Jump](#pass-assertion-number-2)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-3">3/18</div>|:white_check_mark:*Pass*|`wine`|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|All terms labeled|[Jump](#pass-assertion-number-3)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-4">4/18</div>|:white_check_mark:*Pass*|`wine`|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-assertion-number-4)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-5">5/18</div>|:white_check_mark:*Pass*|`wine`|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|Any term is referenced|[Jump](#pass-assertion-number-5)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-6">6/18</div>|:white_check_mark:*Pass*|`wine`|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-assertion-number-6)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-7">7/18</div>|:white_check_mark:*Pass*|`all-modules`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-assertion-number-7)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-8">8/18</div>|:white_check_mark:*Pass*|`all-modules`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|Ranges properly defined|[Jump](#pass-assertion-number-8)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-9">9/18</div>|:white_check_mark:*Pass*|`all-modules`|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|All terms labeled|[Jump](#pass-assertion-number-9)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-10">10/18</div>|:white_check_mark:*Pass*|`all-modules`|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-assertion-number-10)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-11">11/18</div>|:white_check_mark:*Pass*|`all-modules`|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|Any term is referenced|[Jump](#pass-assertion-number-11)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-12">12/18</div>|:white_check_mark:*Pass*|`all-modules`|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-assertion-number-12)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-13">13/18</div>|:white_check_mark:*Pass*|`all-fragments`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-assertion-number-13)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-14">14/18</div>|:white_check_mark:*Pass*|`all-fragments`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|Ranges properly defined|[Jump](#pass-assertion-number-14)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-15">15/18</div>|:white_check_mark:*Pass*|`all-fragments`|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|All terms labeled|[Jump](#pass-assertion-number-15)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-16">16/18</div>|:white_check_mark:*Pass*|`all-fragments`|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-assertion-number-16)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-17">17/18</div>|:white_check_mark:*Pass*|`all-fragments`|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|Any term is referenced|[Jump](#pass-assertion-number-17)|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-18">18/18</div>|:white_check_mark:*Pass*|`all-fragments`|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-assertion-number-18)|

***

## Pass Assertion Details

This subchapter gives more details to the :white_check_mark:Pass assertions

### Pass Assertion number 1

[Jump to summary definition](#summary-Pass-1)

:white_check_mark:Pass assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Assertion number 2

[Jump to summary definition](#summary-Pass-2)

:white_check_mark:Pass assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Ranges properly defined|
|Description|Each rdfs:range is defined within the fragment|

***
### Pass Assertion number 3

[Jump to summary definition](#summary-Pass-3)

:white_check_mark:Pass assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Assertion number 4

[Jump to summary definition](#summary-Pass-4)

:white_check_mark:Pass assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Assertion number 5

[Jump to summary definition](#summary-Pass-5)

:white_check_mark:Pass assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Assertion number 6

[Jump to summary definition](#summary-Pass-6)

:white_check_mark:Pass assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Assertion number 7

[Jump to summary definition](#summary-Pass-7)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Assertion number 8

[Jump to summary definition](#summary-Pass-8)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Ranges properly defined|
|Description|Each rdfs:range is defined within the fragment|

***
### Pass Assertion number 9

[Jump to summary definition](#summary-Pass-9)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Assertion number 10

[Jump to summary definition](#summary-Pass-10)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Assertion number 11

[Jump to summary definition](#summary-Pass-11)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Assertion number 12

[Jump to summary definition](#summary-Pass-12)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Assertion number 13

[Jump to summary definition](#summary-Pass-13)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Assertion number 14

[Jump to summary definition](#summary-Pass-14)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Ranges properly defined|
|Description|Each rdfs:range is defined within the fragment|

***
### Pass Assertion number 15

[Jump to summary definition](#summary-Pass-15)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Assertion number 16

[Jump to summary definition](#summary-Pass-16)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Assertion number 17

[Jump to summary definition](#summary-Pass-17)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Assertion number 18

[Jump to summary definition](#summary-Pass-18)

:white_check_mark:Pass assertion
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***

</details>

***
