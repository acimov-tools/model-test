# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./query-test-actions.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using actions script|
|Description|Test triggered by &#91;@NicoRobertIn](https://github.com/NicoRobertIn) by actions trigger|
|Script|[suite.py](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/query/suite.py)
|Date|2024-05-13 20:56:46|

***


# Statistic summary

Here is a short overview for this test report

15 Outcomes

:boom:1 MajorFail, :exclamation:2 MinorFail, :warning:1 CannotTell, :grey_question:3 NotTested, :white_check_mark:8 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="6%" height="25px"/><img src="../assets/orange.png" width="13%" height="25px"/><img src="../assets/grey.png" width="6%" height="25px"/><img src="../assets/white.png" width="20%" height="25px"/><img src="../assets/green.png" width="55%" height="25px"/></div>

<br/>

The different status types are an extension of the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary where the nextended terms can be found in the [olivaw-earl dataset](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/olivaw-earl.ttl), each outcome type means:
* :boom: MajorFail: This is an error that is critical and consider as blocking for production
* :exclamation: MinorFail: This is an error that should be fixed, but it is cannot be considered as critical error
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Outcomes

Here is the chapter related to the MajorFail outcome

:boom:1 MajorFail outcomes

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## MajorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:boom:1 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-1">1/1</div>|:boom:*MajorFail*|`question-zedomain-compatEL-q1`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-1)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)

:boom:MajorFail outcome
#### Subject detail
|Name|question-zedomain-compatEL-q1|
|----|----|
|Title|competency question domains/zedomain/compatEL/q1.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q1.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q1.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|Encountered &#34;;&#34; at line 2, column 11.|
|Pointer|<pre lang="Turtle"><code>select * where {&#10;&nbsp;&nbsp;&nbsp;&nbsp;?s ?p ; ?o&#10;}</code></pre>|

***

</details>

***


# MinorFail Outcomes

Here is the chapter related to the MinorFail outcome

:exclamation:2 MinorFail outcomes

<details>
<summary>Fold/Unfold the 2 summary and details</summary>

## MinorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:exclamation:2 MinorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-1">1/2</div>|:exclamation:*MinorFail*|`question-zedomain-compatEL-q3`|[uri-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#uri-validity)|Invalid URI|[Jump](#minorfail-outcome-number-1)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-2">2/2</div>|:exclamation:*MinorFail*|`question-zedomain-compatEL-q2`|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|Unauthorized query type|[Jump](#minorfail-outcome-number-2)|

***

## MinorFail Outcomes Details

This subchapter gives more details to the :exclamation:MinorFail outcomes

### MinorFail Outcome number 1

[Jump to summary definition](#summary-MinorFail-1)

:exclamation:MinorFail outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency question domains/zedomain/compatEL/q3.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q3.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[uri-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#uri-validity)|
|----|----|
|Title|URI validity test|
|Description|A test meant to check if all the URIs of th resource are well-formed|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Invalid URI|
|Description|Expected valid URIs in subject but got: #coucou|

***
### MinorFail Outcome number 2

[Jump to summary definition](#summary-MinorFail-2)

:exclamation:MinorFail outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency question domains/zedomain/compatEL/q2.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q2.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|
|----|----|
|Title|Query type test|
|Description|A test meant to check if the query is indeed of type Select or Ask|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Unauthorized query type|
|Description|The query type was expected to be 'Ask' or 'Select', but got 'Construct'|
|Pointer|<pre lang="Turtle"><code>construct {?s ?p ?o} where {?s ?p ?o}</code></pre>|

***

</details>

***


# CannotTell Outcomes

Here is the chapter related to the CannotTell outcome

:warning:1 CannotTell outcomes

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## CannotTell Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:warning:1 CannotTell outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#cannottell-outcomes-summary)|<div id="summary-CannotTell-1">1/1</div>|:warning:*CannotTell*|`question-zedomain-compatEL-q4`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|Possible prefix typo|[Jump](#cannottell-outcome-number-1)|

***

## CannotTell Outcomes Details

This subchapter gives more details to the :warning:CannotTell outcomes

### CannotTell Outcome number 1

[Jump to summary definition](#summary-CannotTell-1)

:warning:CannotTell outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency question domains/zedomain/compatEL/q4.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q4.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|
|----|----|
|Title|Term validity test|
|Description|A test case checking if all the prefixes are not too close from the most used existing namespaces (according to prefix cc)|

#### Outcome Detail
|Type|:warning:CannotTell|
|----|----|
|Title|Possible prefix typo|
|Description|The prefix http://www.example.org/olivaw/ seems suspicious. Did you mean one of these prefixes?|
|Pointer|<pre lang="Turtle"><code>Prefix usage in the subject file:&#10;@prefix sand: &#60;http://www.example.org/olivaw/> .&#10;select * where {&#10;&nbsp;&nbsp;&nbsp;&nbsp;?s a sand:ClassA .&#10;}</code></pre>|
|Pointer|<pre lang="Turtle"><code>Similar prefix found in file ./use-cases/zeusecase/notrealterm.ttl&#10;Prefix found: https://www.example.org/olivaw/&#10;@prefix owl: &#60;http://www.w3.org/2002/07/owl#> .&#10;@prefix rdf: &#60;http://www.w3.org/1999/02/22-rdf-syntax-ns#> . &#10; &#60;https://www.example.org/zeusecase/zeInstance> rdf:type &#60;https://www.example.org/olivaw/ClasseA> .</code></pre>|

***

</details>

***


# NotTested Outcomes

Here is the chapter related to the NotTested outcome

:grey_question:3 NotTested outcomes

<details>
<summary>Fold/Unfold the 3 summary and details</summary>

## NotTested Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:grey_question:3 NotTested outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-1">1/3</div>|:grey_question:*NotTested*|`question-zedomain-compatEL-q3`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-2">2/3</div>|:grey_question:*NotTested*|`question-zedomain-compatEL-q1`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|Error on custom test |[Jump](#nottested-outcome-number-2)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-3">3/3</div>|:grey_question:*NotTested*|`question-zedomain-compatEL-q1`|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|Error on custom test |[Jump](#nottested-outcome-number-3)|

***

## NotTested Outcomes Details

This subchapter gives more details to the :grey_question:NotTested outcomes

### NotTested Outcome number 1

[Jump to summary definition](#summary-NotTested-1)

:grey_question:NotTested outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency question domains/zedomain/compatEL/q3.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q3.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|
|----|----|
|Title|Term validity test|
|Description|A test case checking if all the prefixes are not too close from the most used existing namespaces (according to prefix cc)|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 2

[Jump to summary definition](#summary-NotTested-2)

:grey_question:NotTested outcome
#### Subject detail
|Name|question-zedomain-compatEL-q1|
|----|----|
|Title|competency question domains/zedomain/compatEL/q1.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q1.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q1.rq.ttl)|

#### Criterion detail
|Identifier|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|
|----|----|
|Title|Term validity test|
|Description|A test case checking if all the prefixes are not too close from the most used existing namespaces (according to prefix cc)|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 3

[Jump to summary definition](#summary-NotTested-3)

:grey_question:NotTested outcome
#### Subject detail
|Name|question-zedomain-compatEL-q1|
|----|----|
|Title|competency question domains/zedomain/compatEL/q1.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q1.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q1.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|
|----|----|
|Title|Query type test|
|Description|A test meant to check if the query is indeed of type Select or Ask|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***

</details>

***


# Pass Outcomes

Here is the chapter related to the Pass outcome

:white_check_mark:8 Pass outcomes

<details>
<summary>Fold/Unfold the 8 summary and details</summary>

## Pass Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:white_check_mark:8 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-1">1/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q4`|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|Accurate query type|[Jump](#pass-outcome-number-1)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-2">2/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q4`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-2)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-3">3/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q4`|[uri-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#uri-validity)|All subject URI valid|[Jump](#pass-outcome-number-3)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-4">4/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q3`|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|Accurate query type|[Jump](#pass-outcome-number-4)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-5">5/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q3`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-5)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-6">6/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q2`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|No prefix typo|[Jump](#pass-outcome-number-6)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-7">7/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q2`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-7)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-8">8/8</div>|:white_check_mark:*Pass*|`question-zedomain-compatEL-q2`|[uri-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#uri-validity)|All subject URI valid|[Jump](#pass-outcome-number-8)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency question domains/zedomain/compatEL/q4.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q4.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|
|----|----|
|Title|Query type test|
|Description|A test meant to check if the query is indeed of type Select or Ask|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Accurate query type|
|Description|The query is of type Select or Ask|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency question domains/zedomain/compatEL/q4.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q4.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Correct syntax|
|Description|Test subject has a correct syntax|

***
### Pass Outcome number 3

[Jump to summary definition](#summary-Pass-3)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency question domains/zedomain/compatEL/q4.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q4.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[uri-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#uri-validity)|
|----|----|
|Title|URI validity test|
|Description|A test meant to check if all the URIs of th resource are well-formed|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All subject URI valid|
|Description|All the URIs of the subject are valid|

***
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency question domains/zedomain/compatEL/q3.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q3.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#query-type)|
|----|----|
|Title|Query type test|
|Description|A test meant to check if the query is indeed of type Select or Ask|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Accurate query type|
|Description|The query is of type Select or Ask|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency question domains/zedomain/compatEL/q3.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q3.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Correct syntax|
|Description|Test subject has a correct syntax|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency question domains/zedomain/compatEL/q2.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q2.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|
|----|----|
|Title|Term validity test|
|Description|A test case checking if all the prefixes are not too close from the most used existing namespaces (according to prefix cc)|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|No prefix typo|
|Description|It seems that none of the subject URIs have prefixes typos|

***
### Pass Outcome number 7

[Jump to summary definition](#summary-Pass-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency question domains/zedomain/compatEL/q2.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q2.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Correct syntax|
|Description|Test subject has a correct syntax|

***
### Pass Outcome number 8

[Jump to summary definition](#summary-Pass-8)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency question domains/zedomain/compatEL/q2.rq from branch refs/heads/main|
|Composition|- [Competency question zedomain/compatEL/q2.rq](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[uri-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#uri-validity)|
|----|----|
|Title|URI validity test|
|Description|A test meant to check if all the URIs of th resource are well-formed|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All subject URI valid|
|Description|All the URIs of the subject are valid|

***

</details>

***
