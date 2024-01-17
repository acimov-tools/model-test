# Test Report Markdown export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./data-test-actions.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using actions script|
|Description|Test triggered by [@NicoRobertIn](https://github.com/NicoRobertIn) by actions trigger|
|Script|[suite.py](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/data/suite.py)
|Date|2024-01-17 13:12:25|

***


# Statistic summary

Here is a short overview for this test report

2 Assertions

:boom:1 MajorFail, :exclamation:0 MinorFail, :warning:0 CannotTell, :grey_question:0 NotTested, :white_check_mark:1 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="50%" height="25px"/><img src="../assets/orange.png" width="0%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="0%" height="25px"/><img src="../assets/green.png" width="50%" height="25px"/></div>

<br/>

According to the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary, each outcome type means:
* :x: Fail: The subject failed the test. 
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Assertions

Here is the chapter related to the MajorFail assertion

:boom:1 MajorFail assertions

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## MajorFail Assertions Summary

[Jump to statistic summary](#statistic-summary)

:boom:1 MajorFail assertions

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#majorfail-assertions-summary)|<div id="summary-MajorFail-1">1/1</div>|:boom:*MajorFail*|`domain1-scenario1`|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-assertion-number-1)|

***

## MajorFail Assertion Details

This subchapter gives more details to the :boom:MajorFail assertions

### MajorFail Assertion number 1

[Jump to summary definition](#summary-MajorFail-1)

:boom:MajorFail assertion
#### Subject detail
|Name|domain1-scenario1|
|----|----|
|Title|Standalone dataset domains/domain1/scenario1/dataset.ttl from branch refs/heads/main|
|Composition|- [Dataset domain1/scenario1/dataset.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/domain1/scenario1/dataset.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;http://stardog.com/tutorial/The_Beatles> &#10;rdfs:label "Violates owl:AllDisjointClasses" &#10;sp:arg1 &#60;https://www.example.org/A> &#10;sp:arg2 &#60;https://www.example.org/B> &#10; &#10;|

***

</details>

***


# Pass Assertions

Here is the chapter related to the Pass assertion

:white_check_mark:1 Pass assertions

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## Pass Assertions Summary

[Jump to statistic summary](#statistic-summary)

:white_check_mark:1 Pass assertions

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#pass-assertions-summary)|<div id="summary-Pass-1">1/1</div>|:white_check_mark:*Pass*|`domain1-scenario1`|[syntax](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#syntax)|Correct syntax|[Jump](#pass-assertion-number-1)|

***

## Pass Assertion Details

This subchapter gives more details to the :white_check_mark:Pass assertions

### Pass Assertion number 1

[Jump to summary definition](#summary-Pass-1)

:white_check_mark:Pass assertion
#### Subject detail
|Name|domain1-scenario1|
|----|----|
|Title|Standalone dataset domains/domain1/scenario1/dataset.ttl from branch refs/heads/main|
|Composition|- [Dataset domain1/scenario1/dataset.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/domain1/scenario1/dataset.ttl)|

#### Criterion detail
|Identifier|[syntax](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Correct syntax|
|Description|Test subject has a correct syntax|

***

</details>

***
