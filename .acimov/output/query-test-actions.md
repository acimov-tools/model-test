# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./query-test-actions.ttl).

# Test Activity

Here is some information about the testing activity that led to this report

|Title|Query&#32;tests&#32;of&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|--|--|
|Description|[NicoRobertIn](https://github.com/NicoRobertIn)&#32;launch&#32;actions&#32;run&#32;of&#32;query&#32;tests&#32;against&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|Tester|[NicoRobertIn](https://github.com/NicoRobertIn)|
|Ontology|[acimov-tools/model-test](https://github.com/acimov-tools/model-test)|
|Ontology version|[1e31ef4c4a02f94c32b6076f05ad9578a3185acf](https://github.com/acimov-tools/model-test/tree/1e31ef4c4a02f94c32b6076f05ad9578a3185acf)|
|Ontology branch|[main](https://github.com/acimov-tools/model-test/tree/main)|
|Olivaw suite|[olivaw query test suite](https://github.com/Wimmics/olivaw/blob/v0.0.6/olivaw/test/query/suite.py)|
|Olivaw version|[v0.0.6](https://github.com/Wimmics/olivaw)|
|Generated turtle|[Turtle report](./query-test-actions.ttl)|
|Generated Markdown|[Markdown report](./query-test-actions.md)|

# Statistic summary

Here is a short overview for this test report

12 Outcomes

:boom:1 MajorFail, :exclamation:2 MinorFail, :warning:1 CannotTell, :grey_question:0 NotTested, :white_check_mark:8 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="8%" height="25px"/><img src="../assets/orange.png" width="16%" height="25px"/><img src="../assets/grey.png" width="8%" height="25px"/><img src="../assets/white.png" width="0%" height="25px"/><img src="../assets/green.png" width="68%" height="25px"/></div>

<br/>

The different status types are an extension of the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary where the nextended terms can be found in the [olivaw ontology](https://ns.inria.fr/olivaw#), each outcome type means:
* :boom: MajorFail: This is an error that is critical and consider as blocking for production
* :exclamation: MinorFail: This is an error that should be fixed, but it is cannot be considered as critical error
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	Previous section	|	[Next section](#minorfail-outcomes)

Here is the chapter related to the MajorFail outcome

:boom:1 MajorFail outcomes

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## MajorFail Outcomes Summary

:boom:1 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-1">1/1</div>|:boom:MajorFail|`question-zedomain-compatEL-q1`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-1)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)	|	Previous MajorFail outcome	|	Next MajorFail outcome

:boom:MajorFail outcome
#### Subject detail
|Name|question-zedomain-compatEL-q1|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q1.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q1](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q1.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-1)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-1)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-1)|Description|Encountered&#32; &#34;;&#34; &#32;at&#32;line&#32;2,&#32;column&#32;11.|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>select&#32;*&#32;where&#32;{  &#10; &#32; &#32;&#32; &#32;?s&#32;?p&#32;;&#32;?o  &#10;}</code></pre>|

***

</details>

***


# MinorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#majorfail-outcomes)	|	[Next section](#cannottell-outcomes)

Here is the chapter related to the MinorFail outcome

:exclamation:2 MinorFail outcomes

<details>
<summary>Fold/Unfold the 2 summary and details</summary>

## MinorFail Outcomes Summary

:exclamation:2 MinorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-1">1/2</div>|:exclamation:MinorFail|`question-zedomain-compatEL-q3`|[uri-validity](https://ns.inria.fr/olivaw#uri-validity)|Invalid URI|[Jump](#minorfail-outcome-number-1)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-2">2/2</div>|:exclamation:MinorFail|`question-zedomain-compatEL-q2`|[query-type](https://ns.inria.fr/olivaw#query-type)|Unauthorized query type|[Jump](#minorfail-outcome-number-2)|

***

## MinorFail Outcomes Details

This subchapter gives more details to the :exclamation:MinorFail outcomes

### MinorFail Outcome number 1

[Jump to summary definition](#summary-MinorFail-1)	|	Previous MinorFail outcome	|	[Next MinorFail outcome](#minorfail-outcome-number-2)

:exclamation:MinorFail outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q3.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q3](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[uri-validity](https://ns.inria.fr/olivaw#uri-validity)|
|----|----|
|Title|URI&#32;validity&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;if&#32;all&#32;the&#32;URIs&#32;of&#32;the&#32;resource&#32;are&#32;well-formed|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-1)|Identifier|`invalid-uri`|
|[Section top](#minorfail-outcome-number-1)|Title|Invalid&#32;URI|
|[Section top](#minorfail-outcome-number-1)|Description|Expected&#32;valid&#32;URIs&#32;in&#32;subject&#32;but&#32;got:&#32;#coucou|
|[Section top](#minorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>select&#32;*&#32;where&#32;{?s&#32;a&#32; &#60;#coucou>}</code></pre>|

***
### MinorFail Outcome number 2

[Jump to summary definition](#summary-MinorFail-2)	|	[Previous MinorFail outcome](#minorfail-outcome-number-1)	|	Next MinorFail outcome

:exclamation:MinorFail outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q2.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q2](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://ns.inria.fr/olivaw#query-type)|
|----|----|
|Title|Query&#32;type&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;if&#32;the&#32;query&#32;is&#32;indeed&#32;of&#32;type&#32;Select&#32;or&#32;Ask|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-2)|Identifier|`wrong-query-type`|
|[Section top](#minorfail-outcome-number-2)|Title|Unauthorized&#32;query&#32;type|
|[Section top](#minorfail-outcome-number-2)|Description|The&#32;query&#32;type&#32;was&#32;expected&#32;to&#32;be&#32;'Ask'&#32;or&#32;'Select',&#32;but&#32;got&#32;'Construct'|
|[Section top](#minorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>construct&#32;{?s&#32;?p&#32;?o}&#32;where&#32;{?s&#32;?p&#32;?o}</code></pre>|

***

</details>

***


# CannotTell Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#minorfail-outcomes)	|	[Next section](#pass-outcomes)

Here is the chapter related to the CannotTell outcome

:warning:1 CannotTell outcomes

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## CannotTell Outcomes Summary

:warning:1 CannotTell outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#cannottell-outcomes)|<div id="summary-CannotTell-1">1/1</div>|:warning:CannotTell|`question-zedomain-compatEL-q4`|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|Possible namespace typo|[Jump](#cannottell-outcome-number-1)|

***

## CannotTell Outcomes Details

This subchapter gives more details to the :warning:CannotTell outcomes

### CannotTell Outcome number 1

[Jump to summary definition](#summary-CannotTell-1)	|	Previous CannotTell outcome	|	Next CannotTell outcome

:warning:CannotTell outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q4.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q4](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|
|----|----|
|Title|Prefix&#32;validity&#32;test|
|Description|A&#32;test&#32;case&#32;checking&#32;if&#32;all&#32;the&#32;prefixes&#32;are&#32;not&#32;too&#32;close&#32;from&#32;the&#32;most&#32;used&#32;existing&#32;namespaces&#32;(according&#32;to&#32;prefix&#32;cc)&#32;or&#32;an&#32;ontology&#32;namespace|

#### Outcome Detail
|Jump|Type|:warning:CannotTell|
|----|----|----|
|[Section top](#cannottell-outcome-number-1)|Identifier|`namespace-typo`|
|[Section top](#cannottell-outcome-number-1)|Title|Possible&#32;namespace&#32;typo|
|[Section top](#cannottell-outcome-number-1)|Description|The&#32;following&#32;namespace&#32;seems&#32;suspicious:  &#10; &#32;http://www.example.org/olivaw/&#32;  &#10;Was&#32;it&#32;supposed&#32;to&#32;correspond&#32;to&#32;one&#32;of&#32;these&#32;namespaces?|
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>Namespace&#32;usage&#32;in&#32;the&#32;subject&#32;file:</code></pre>|
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>@prefix&#32;sand:&#32; &#60;http://www.example.org/olivaw/> &#32;.  &#10;select&#32;*&#32;where&#32;{  &#10; &#32; &#32;&#32; &#32;?s&#32;a&#32;sand:ClassA&#32;.  &#10;}</code></pre>|
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>Similar&#32;namespace&#32;found&#32;in&#32;file:  &#10;./use-cases/zeusecase/notrealterm.ttl&#32;  &#10;Namespace&#32;found:  &#10;https://www.example.org/olivaw/</code></pre>|
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/zeusecase/zeInstance> &#32;a&#32;similar-namespace:ClasseA&#32;.</code></pre>|

***

</details>

***


# Pass Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#cannottell-outcomes)	|	Next section

Here is the chapter related to the Pass outcome

:white_check_mark:8 Pass outcomes

<details>
<summary>Fold/Unfold the 8 summary and details</summary>

## Pass Outcomes Summary

:white_check_mark:8 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-1">1/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q4`|[query-type](https://ns.inria.fr/olivaw#query-type)|Accurate query type|[Jump](#pass-outcome-number-1)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-2">2/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q4`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-2)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-3">3/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q4`|[uri-validity](https://ns.inria.fr/olivaw#uri-validity)|All subject URI valid|[Jump](#pass-outcome-number-3)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-4">4/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q3`|[query-type](https://ns.inria.fr/olivaw#query-type)|Accurate query type|[Jump](#pass-outcome-number-4)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-5">5/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q3`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-5)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-6">6/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q2`|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|No namespace typo|[Jump](#pass-outcome-number-6)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-7">7/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q2`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-7)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-8">8/8</div>|:white_check_mark:Pass|`question-zedomain-compatEL-q2`|[uri-validity](https://ns.inria.fr/olivaw#uri-validity)|All subject URI valid|[Jump](#pass-outcome-number-8)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)	|	Previous Pass outcome	|	[Next Pass outcome](#pass-outcome-number-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q4.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q4](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://ns.inria.fr/olivaw#query-type)|
|----|----|
|Title|Query&#32;type&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;if&#32;the&#32;query&#32;is&#32;indeed&#32;of&#32;type&#32;Select&#32;or&#32;Ask|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-1)|Identifier|`wrong-query-type`|
|[Section top](#pass-outcome-number-1)|Title|Accurate&#32;query&#32;type|
|[Section top](#pass-outcome-number-1)|Description|The&#32;query&#32;is&#32;of&#32;type&#32;Select&#32;or&#32;Ask|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)	|	[Previous Pass outcome](#pass-outcome-number-1)	|	[Next Pass outcome](#pass-outcome-number-3)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q4.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q4](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-2)|Identifier|`syntax-error`|
|[Section top](#pass-outcome-number-2)|Title|Correct&#32;syntax|
|[Section top](#pass-outcome-number-2)|Description|All&#32;the&#32;subject&#32;URIs&#32;should&#32;be&#32;well-formed|

***
### Pass Outcome number 3

[Jump to summary definition](#summary-Pass-3)	|	[Previous Pass outcome](#pass-outcome-number-2)	|	[Next Pass outcome](#pass-outcome-number-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q4|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q4.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q4](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q4.rq.ttl)|

#### Criterion detail
|Identifier|[uri-validity](https://ns.inria.fr/olivaw#uri-validity)|
|----|----|
|Title|URI&#32;validity&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;if&#32;all&#32;the&#32;URIs&#32;of&#32;the&#32;resource&#32;are&#32;well-formed|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-3)|Identifier|`invalid-uri`|
|[Section top](#pass-outcome-number-3)|Title|All&#32;subject&#32;URI&#32;valid|
|[Section top](#pass-outcome-number-3)|Description|All&#32;the&#32;URIs&#32;of&#32;the&#32;subject&#32;are&#32;valid|

***
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)	|	[Previous Pass outcome](#pass-outcome-number-3)	|	[Next Pass outcome](#pass-outcome-number-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q3.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q3](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[query-type](https://ns.inria.fr/olivaw#query-type)|
|----|----|
|Title|Query&#32;type&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;if&#32;the&#32;query&#32;is&#32;indeed&#32;of&#32;type&#32;Select&#32;or&#32;Ask|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-4)|Identifier|`wrong-query-type`|
|[Section top](#pass-outcome-number-4)|Title|Accurate&#32;query&#32;type|
|[Section top](#pass-outcome-number-4)|Description|The&#32;query&#32;is&#32;of&#32;type&#32;Select&#32;or&#32;Ask|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)	|	[Previous Pass outcome](#pass-outcome-number-4)	|	[Next Pass outcome](#pass-outcome-number-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q3|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q3.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q3](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q3.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-5)|Identifier|`syntax-error`|
|[Section top](#pass-outcome-number-5)|Title|Correct&#32;syntax|
|[Section top](#pass-outcome-number-5)|Description|Test&#32;subject&#32;has&#32;a&#32;correct&#32;syntax|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)	|	[Previous Pass outcome](#pass-outcome-number-5)	|	[Next Pass outcome](#pass-outcome-number-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q2.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q2](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|
|----|----|
|Title|Prefix&#32;validity&#32;test|
|Description|A&#32;test&#32;case&#32;checking&#32;if&#32;all&#32;the&#32;prefixes&#32;are&#32;not&#32;too&#32;close&#32;from&#32;the&#32;most&#32;used&#32;existing&#32;namespaces&#32;(according&#32;to&#32;prefix&#32;cc)&#32;or&#32;an&#32;ontology&#32;namespace|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-6)|Identifier|`namespace-typo`|
|[Section top](#pass-outcome-number-6)|Title|No&#32;namespace&#32;typo|
|[Section top](#pass-outcome-number-6)|Description|It&#32;seems&#32;that&#32;none&#32;of&#32;the&#32;subject&#32;URIs&#32;have&#32;namespaces&#32;typos|

***
### Pass Outcome number 7

[Jump to summary definition](#summary-Pass-7)	|	[Previous Pass outcome](#pass-outcome-number-6)	|	[Next Pass outcome](#pass-outcome-number-8)

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q2.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q2](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-7)|Identifier|`syntax-error`|
|[Section top](#pass-outcome-number-7)|Title|Correct&#32;syntax|
|[Section top](#pass-outcome-number-7)|Description|Test&#32;subject&#32;has&#32;a&#32;correct&#32;syntax|

***
### Pass Outcome number 8

[Jump to summary definition](#summary-Pass-8)	|	[Previous Pass outcome](#pass-outcome-number-7)	|	Next Pass outcome

:white_check_mark:Pass outcome
#### Subject detail
|Name|question-zedomain-compatEL-q2|
|----|----|
|Title|competency&#32;question&#32;domains/zedomain/compatEL/q2.rq&#32;from&#32;branch&#32;main|
|Composition|- [Competency question zedomain/compatEL/q2](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/q2.rq.ttl)|

#### Criterion detail
|Identifier|[uri-validity](https://ns.inria.fr/olivaw#uri-validity)|
|----|----|
|Title|URI&#32;validity&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;if&#32;all&#32;the&#32;URIs&#32;of&#32;the&#32;resource&#32;are&#32;well-formed|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-8)|Identifier|`invalid-uri`|
|[Section top](#pass-outcome-number-8)|Title|All&#32;subject&#32;URI&#32;valid|
|[Section top](#pass-outcome-number-8)|Description|All&#32;the&#32;URIs&#32;of&#32;the&#32;subject&#32;are&#32;valid|

***

</details>

***
