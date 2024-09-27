# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./data-test-actions.ttl).

# Test Activity

Here is some information about the testing activity that led to this report

|Title|Data&#32;tests&#32;of&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|--|--|
|Description|[NicoRobertIn](https://github.com/NicoRobertIn)&#32;launch&#32;actions&#32;run&#32;of&#32;data&#32;tests&#32;against&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|Tester|[NicoRobertIn](https://github.com/NicoRobertIn)|
|Ontology|[acimov-tools/model-test](https://github.com/acimov-tools/model-test)|
|Ontology version|[b02cfda816c8805663b73d674c4b6036469ad121](https://github.com/acimov-tools/model-test/tree/b02cfda816c8805663b73d674c4b6036469ad121)|
|Ontology branch|[main](https://github.com/acimov-tools/model-test/tree/main)|
|Olivaw suite|[olivaw data test suite](https://github.com/Wimmics/olivaw/blob/v0.0.6/olivaw/test/data/suite.py)|
|Olivaw version|[v0.0.6](https://github.com/Wimmics/olivaw)|
|Generated turtle|[Turtle report](./https://github.com/acimov-tools/model-test/blob/b02cfda816c8805663b73d674c4b6036469ad121/.acimov/output/data-test-actions.ttl)|
|Generated Markdown|[Markdown report](./https://github.com/acimov-tools/model-test/blob/b02cfda816c8805663b73d674c4b6036469ad121/.acimov/output/data-test-actions.md)|

# Statistic summary

Here is a short overview for this test report

25 Outcomes

:boom:7 MajorFail, :exclamation:0 MinorFail, :warning:1 CannotTell, :grey_question:2 NotTested, :white_check_mark:15 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="28%" height="25px"/><img src="../assets/orange.png" width="0%" height="25px"/><img src="../assets/grey.png" width="4%" height="25px"/><img src="../assets/white.png" width="8%" height="25px"/><img src="../assets/green.png" width="60%" height="25px"/></div>

<br/>

The different status types are an extension of the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary where the nextended terms can be found in the [olivaw ontology](https://ns.inria.fr/olivaw#), each outcome type means:
* :boom: MajorFail: This is an error that is critical and consider as blocking for production
* :exclamation: MinorFail: This is an error that should be fixed, but it is cannot be considered as critical error
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	Previous section	|	[Next section](#cannottell-outcomes)

Here is the chapter related to the MajorFail outcome

:boom:7 MajorFail outcomes

<details>
<summary>Fold/Unfold the 7 summary and details</summary>

## MajorFail Outcomes Summary

:boom:7 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-1">1/7</div>|:boom:MajorFail|`usecase-zeusecase-wronguncommonprefix`|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/richness.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-2">2/7</div>|:boom:MajorFail|`usecase-zeusecase-wrongcommonprefix`|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/richness.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-2)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-3">3/7</div>|:boom:MajorFail|`usecase-zeusecase-syntax`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-3)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-4">4/7</div>|:boom:MajorFail|`usecase-zeusecase-notrealterm`|[term-recognition](https://ns.inria.fr/olivaw#term-recognition)|Unknown ontology term|[Jump](#majorfail-outcome-number-4)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-5">5/7</div>|:boom:MajorFail|`usecase-zeusecase-notrealterm`|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/richness.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-6">6/7</div>|:boom:MajorFail|`usecase-zeusecase-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-6)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-7">7/7</div>|:boom:MajorFail|`dataset-domain1-scenario1`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-7)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)	|	Previous MajorFail outcome	|	[Next MajorFail outcome](#majorfail-outcome-number-2)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wronguncommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wronguncommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/richness.shacl#criterion)|
|----|----|
|Title|The&#32;vocabulary&#32;is&#32;linked&#32;to&#32;by&#32;other&#32;vocabularies|
|Description|Each&#32;node&#32;should&#32;have&#32;predicates&#32;other&#32;than&#32;rdf:type|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-1)|Identifier|`data-richness`|
|[Section top](#majorfail-outcome-number-1)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-1)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Some&#32;subjects&#32;only&#32;have&#32;a&#32;rdf:type&#32;property&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sparql&#32; &#91;&#32;sh:select&#32; &#34; &#34; &#34;  &#10;select&#32;?this&#32;where&#32;{  &#10; &#32; &#32;?this&#32;?p&#32;?o&#32;.  &#10; &#32; &#32; &#32;filter&#32;(?p&#32;!=&#32;rdf:t...&#34; &#34; &#34; &#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdf:type&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>violation:610e732d-6a93-4ac3-b45b-349fe762f7a3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32; &#60;https://www.example.org/zeusecase/zeInstance> &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Some&#32;subjects&#32;only&#32;have&#32;a&#32;rdf:type&#32;property&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;sh:sparql&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Warning&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:sparqlCount&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32;data-richness:shape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:zeInstance&#32;a&#32; &#60;http://www.example.org/olivaw/ClassA> &#32;.</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)	|	[Previous MajorFail outcome](#majorfail-outcome-number-1)	|	[Next MajorFail outcome](#majorfail-outcome-number-3)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wrongcommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wrongcommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/richness.shacl#criterion)|
|----|----|
|Title|The&#32;vocabulary&#32;is&#32;linked&#32;to&#32;by&#32;other&#32;vocabularies|
|Description|Each&#32;node&#32;should&#32;have&#32;predicates&#32;other&#32;than&#32;rdf:type|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-2)|Identifier|`data-richness`|
|[Section top](#majorfail-outcome-number-2)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-2)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Some&#32;subjects&#32;only&#32;have&#32;a&#32;rdf:type&#32;property&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sparql&#32; &#91;&#32;sh:select&#32; &#34; &#34; &#34;  &#10;select&#32;?this&#32;where&#32;{  &#10; &#32; &#32;?this&#32;?p&#32;?o&#32;.  &#10; &#32; &#32; &#32;filter&#32;(?p&#32;!=&#32;rdf:t...&#34; &#34; &#34; &#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdf:type&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>violation:1fe4b55d-0f4f-4268-99bc-c3c58b3de3f2&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32; &#60;https://www.example.org/zeusecase/zeInstance> &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Some&#32;subjects&#32;only&#32;have&#32;a&#32;rdf:type&#32;property&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;sh:sparql&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Warning&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:sparqlCount&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32;data-richness:shape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>:zeInstance&#32;a&#32;sand:ClassA&#32;.</code></pre>|

***
### MajorFail Outcome number 3

[Jump to summary definition](#summary-MajorFail-3)	|	[Previous MajorFail outcome](#majorfail-outcome-number-2)	|	[Next MajorFail outcome](#majorfail-outcome-number-4)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-syntax|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/syntax.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/syntax](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/syntax.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-3)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-3)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-3)|Description|Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;6,&#32;column&#32;27.|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)	|	[Previous MajorFail outcome](#majorfail-outcome-number-3)	|	[Next MajorFail outcome](#majorfail-outcome-number-5)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/notrealterm.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/notrealterm](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://ns.inria.fr/olivaw#term-recognition)|
|----|----|
|Title|Term&#32;recognition&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;if&#32;all&#32;the&#32;terms&#32;from&#32;the&#32;subject&#32;that&#32;are&#32;from&#32;the&#32;ontology&#32;namespace&#32;are&#32;indeed&#32;defined&#32;in&#32;the&#32;ontology|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-4)|Identifier|`unknown-term`|
|[Section top](#majorfail-outcome-number-4)|Title|Unknown&#32;ontology&#32;term|
|[Section top](#majorfail-outcome-number-4)|Description|Some&#32;fragment&#32;terms&#32;are&#32;in&#32;ontology&#32;namespace&#32;but&#32;not&#32;defined&#32;in&#32;ontology|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>Term&#32;not&#32;recognized:&#32; &#60;https://www.example.org/olivaw/ClasseA></code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/zeusecase/zeInstance> &#32;a&#32;:ClasseA&#32;.</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)	|	[Previous MajorFail outcome](#majorfail-outcome-number-4)	|	[Next MajorFail outcome](#majorfail-outcome-number-6)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/notrealterm.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/notrealterm](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/richness.shacl#criterion)|
|----|----|
|Title|The&#32;vocabulary&#32;is&#32;linked&#32;to&#32;by&#32;other&#32;vocabularies|
|Description|Each&#32;node&#32;should&#32;have&#32;predicates&#32;other&#32;than&#32;rdf:type|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-5)|Identifier|`data-richness`|
|[Section top](#majorfail-outcome-number-5)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-5)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Some&#32;subjects&#32;only&#32;have&#32;a&#32;rdf:type&#32;property&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sparql&#32; &#91;&#32;sh:select&#32; &#34; &#34; &#34;  &#10;select&#32;?this&#32;where&#32;{  &#10; &#32; &#32;?this&#32;?p&#32;?o&#32;.  &#10; &#32; &#32; &#32;filter&#32;(?p&#32;!=&#32;rdf:t...&#34; &#34; &#34; &#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdf:type&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>violation:5952e86b-f043-473c-822d-5735295e29b3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32; &#60;https://www.example.org/zeusecase/zeInstance> &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Some&#32;subjects&#32;only&#32;have&#32;a&#32;rdf:type&#32;property&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;sh:sparql&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Warning&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:sparqlCount&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32;data-richness:shape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:zeInstance&#32;a&#32;sand:ClasseA&#32;.</code></pre>|

***
### MajorFail Outcome number 6

[Jump to summary definition](#summary-MajorFail-6)	|	[Previous MajorFail outcome](#majorfail-outcome-number-5)	|	[Next MajorFail outcome](#majorfail-outcome-number-7)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-inconsistent|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/inconsistent](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-6)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-6)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-6)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/zeusecase/zeInstance> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/zeusecase/zeClassA> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/zeusecase/zeClassB> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 7

[Jump to summary definition](#summary-MajorFail-7)	|	[Previous MajorFail outcome](#majorfail-outcome-number-6)	|	Next MajorFail outcome

:boom:MajorFail outcome
#### Subject detail
|Name|dataset-domain1-scenario1|
|----|----|
|Title|Standalone&#32;dataset&#32;domains/domain1/scenario1/dataset.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Dataset domain1/scenario1](https://github.com/acimov-tools/model-test/blob/main/domains/domain1/scenario1/dataset.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-7)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-7)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-7)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;http://stardog.com/tutorial/The&lowbar;Beatles> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/A> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/B> &#32; &#10; &#32; &#10;|

***

</details>

***


# CannotTell Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#majorfail-outcomes)	|	[Next section](#nottested-outcomes)

Here is the chapter related to the CannotTell outcome

:warning:1 CannotTell outcomes

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## CannotTell Outcomes Summary

:warning:1 CannotTell outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#cannottell-outcomes)|<div id="summary-CannotTell-1">1/1</div>|:warning:CannotTell|`usecase-zeusecase-wronguncommonprefix`|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|Possible namespace typo|[Jump](#cannottell-outcome-number-1)|

***

## CannotTell Outcomes Details

This subchapter gives more details to the :warning:CannotTell outcomes

### CannotTell Outcome number 1

[Jump to summary definition](#summary-CannotTell-1)	|	Previous CannotTell outcome	|	Next CannotTell outcome

:warning:CannotTell outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wronguncommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wronguncommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

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
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/zeusecase/zeInstance> &#32;a&#32; &#60;http://www.example.org/olivaw/ClassA> &#32;.</code></pre>|
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>Similar&#32;namespace&#32;found&#32;in&#32;file:  &#10;./use-cases/zeusecase/notrealterm.ttl&#32;  &#10;Namespace&#32;found:  &#10;https://www.example.org/olivaw/</code></pre>|
|[Section top](#cannottell-outcome-number-1)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/zeusecase/zeInstance> &#32;a&#32;similar-namespace:ClasseA&#32;.</code></pre>|

***

</details>

***


# NotTested Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#cannottell-outcomes)	|	[Next section](#pass-outcomes)

Here is the chapter related to the NotTested outcome

:grey_question:2 NotTested outcomes

<details>
<summary>Fold/Unfold the 2 summary and details</summary>

## NotTested Outcomes Summary

:grey_question:2 NotTested outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-1">1/2</div>|:grey_question:NotTested|`usecase-zeusecase-syntax`|[data-richness](https://ns.inria.fr/olivaw#data-richness)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-2">2/2</div>|:grey_question:NotTested|`usecase-zeusecase-syntax`|[node-with-class](https://ns.inria.fr/olivaw#node-with-class)|Error on custom test |[Jump](#nottested-outcome-number-2)|

***

## NotTested Outcomes Details

This subchapter gives more details to the :grey_question:NotTested outcomes

### NotTested Outcome number 1

[Jump to summary definition](#summary-NotTested-1)	|	Previous NotTested outcome	|	[Next NotTested outcome](#nottested-outcome-number-2)

:grey_question:NotTested outcome
#### Subject detail
|Name|usecase-zeusecase-syntax|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/syntax.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/syntax](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/syntax.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://ns.inria.fr/olivaw#data-richness)|
|----|----|
|Title|The&#32;vocabulary&#32;is&#32;linked&#32;to&#32;by&#32;other&#32;vocabularies|
|Description|Each&#32;node&#32;should&#32;have&#32;predicates&#32;other&#32;than&#32;rdf:type|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-1)|Identifier|`data-richness`|
|[Section top](#nottested-outcome-number-1)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-1)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 2

[Jump to summary definition](#summary-NotTested-2)	|	[Previous NotTested outcome](#nottested-outcome-number-1)	|	Next NotTested outcome

:grey_question:NotTested outcome
#### Subject detail
|Name|usecase-zeusecase-syntax|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/syntax.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/syntax](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/syntax.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://ns.inria.fr/olivaw#node-with-class)|
|----|----|
|Title|Classed&#32;node&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;if&#32;each&#32;node&#32;has&#32;a&#32;rdf:type&#32;property|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-2)|Identifier|`node-with-class`|
|[Section top](#nottested-outcome-number-2)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-2)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***

</details>

***


# Pass Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#nottested-outcomes)	|	Next section

Here is the chapter related to the Pass outcome

:white_check_mark:15 Pass outcomes

<details>
<summary>Fold/Unfold the 15 summary and details</summary>

## Pass Outcomes Summary

:white_check_mark:15 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-1">1/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wronguncommonprefix`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-1)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-2">2/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wronguncommonprefix`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-2)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-3">3/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wronguncommonprefix`|[term-recognition](https://ns.inria.fr/olivaw#term-recognition)|Every term exists|[Jump](#pass-outcome-number-3)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-4">4/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wronguncommonprefix`|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-4)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-5">5/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wrongcommonprefix`|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|No namespace typo|[Jump](#pass-outcome-number-5)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-6">6/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wrongcommonprefix`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-6)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-7">7/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wrongcommonprefix`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-7)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-8">8/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wrongcommonprefix`|[term-recognition](https://ns.inria.fr/olivaw#term-recognition)|Every term exists|[Jump](#pass-outcome-number-8)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-9">9/15</div>|:white_check_mark:Pass|`usecase-zeusecase-wrongcommonprefix`|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-9)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-10">10/15</div>|:white_check_mark:Pass|`usecase-zeusecase-notrealterm`|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|No namespace typo|[Jump](#pass-outcome-number-10)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-11">11/15</div>|:white_check_mark:Pass|`usecase-zeusecase-notrealterm`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-11)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-12">12/15</div>|:white_check_mark:Pass|`usecase-zeusecase-notrealterm`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-12)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-13">13/15</div>|:white_check_mark:Pass|`usecase-zeusecase-notrealterm`|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-13)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-14">14/15</div>|:white_check_mark:Pass|`usecase-zeusecase-inconsistent`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-14)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-15">15/15</div>|:white_check_mark:Pass|`dataset-domain1-scenario1`|[syntax](https://ns.inria.fr/olivaw#syntax)|Correct syntax|[Jump](#pass-outcome-number-15)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)	|	Previous Pass outcome	|	[Next Pass outcome](#pass-outcome-number-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wronguncommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wronguncommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-1)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-1)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-1)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)	|	[Previous Pass outcome](#pass-outcome-number-1)	|	[Next Pass outcome](#pass-outcome-number-3)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wronguncommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wronguncommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

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
|[Section top](#pass-outcome-number-2)|Description|Test&#32;subject&#32;has&#32;a&#32;correct&#32;syntax|

***
### Pass Outcome number 3

[Jump to summary definition](#summary-Pass-3)	|	[Previous Pass outcome](#pass-outcome-number-2)	|	[Next Pass outcome](#pass-outcome-number-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wronguncommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wronguncommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://ns.inria.fr/olivaw#term-recognition)|
|----|----|
|Title|Term&#32;recognition&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;if&#32;all&#32;the&#32;terms&#32;from&#32;the&#32;subject&#32;that&#32;are&#32;from&#32;the&#32;ontology&#32;namespace&#32;are&#32;indeed&#32;defined&#32;in&#32;the&#32;ontology|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-3)|Identifier|`unknown-term`|
|[Section top](#pass-outcome-number-3)|Title|Every&#32;term&#32;exists|
|[Section top](#pass-outcome-number-3)|Description|All&#32;the&#32;ontologic&#32;terms&#32;in&#32;the&#32;subject&#32;are&#32;defined&#32;in&#32;the&#32;ontology|

***
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)	|	[Previous Pass outcome](#pass-outcome-number-3)	|	[Next Pass outcome](#pass-outcome-number-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wronguncommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wronguncommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|
|----|----|
|Title|Classed&#32;node&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;if&#32;each&#32;node&#32;has&#32;a&#32;rdf:type&#32;property|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-4)|Identifier|`node-with-class`|
|[Section top](#pass-outcome-number-4)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-4)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)	|	[Previous Pass outcome](#pass-outcome-number-4)	|	[Next Pass outcome](#pass-outcome-number-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wrongcommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wrongcommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|
|----|----|
|Title|Prefix&#32;validity&#32;test|
|Description|A&#32;test&#32;case&#32;checking&#32;if&#32;all&#32;the&#32;prefixes&#32;are&#32;not&#32;too&#32;close&#32;from&#32;the&#32;most&#32;used&#32;existing&#32;namespaces&#32;(according&#32;to&#32;prefix&#32;cc)&#32;or&#32;an&#32;ontology&#32;namespace|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-5)|Identifier|`namespace-typo`|
|[Section top](#pass-outcome-number-5)|Title|No&#32;namespace&#32;typo|
|[Section top](#pass-outcome-number-5)|Description|It&#32;seems&#32;that&#32;none&#32;of&#32;the&#32;subject&#32;URIs&#32;have&#32;namespaces&#32;typos|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)	|	[Previous Pass outcome](#pass-outcome-number-5)	|	[Next Pass outcome](#pass-outcome-number-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wrongcommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wrongcommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-6)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-6)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-6)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 7

[Jump to summary definition](#summary-Pass-7)	|	[Previous Pass outcome](#pass-outcome-number-6)	|	[Next Pass outcome](#pass-outcome-number-8)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wrongcommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wrongcommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

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

[Jump to summary definition](#summary-Pass-8)	|	[Previous Pass outcome](#pass-outcome-number-7)	|	[Next Pass outcome](#pass-outcome-number-9)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wrongcommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wrongcommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://ns.inria.fr/olivaw#term-recognition)|
|----|----|
|Title|Term&#32;recognition&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;if&#32;all&#32;the&#32;terms&#32;from&#32;the&#32;subject&#32;that&#32;are&#32;from&#32;the&#32;ontology&#32;namespace&#32;are&#32;indeed&#32;defined&#32;in&#32;the&#32;ontology|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-8)|Identifier|`unknown-term`|
|[Section top](#pass-outcome-number-8)|Title|Every&#32;term&#32;exists|
|[Section top](#pass-outcome-number-8)|Description|All&#32;the&#32;ontologic&#32;terms&#32;in&#32;the&#32;subject&#32;are&#32;defined&#32;in&#32;the&#32;ontology|

***
### Pass Outcome number 9

[Jump to summary definition](#summary-Pass-9)	|	[Previous Pass outcome](#pass-outcome-number-8)	|	[Next Pass outcome](#pass-outcome-number-10)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/wrongcommonprefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/wrongcommonprefix](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|
|----|----|
|Title|Classed&#32;node&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;if&#32;each&#32;node&#32;has&#32;a&#32;rdf:type&#32;property|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-9)|Identifier|`node-with-class`|
|[Section top](#pass-outcome-number-9)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-9)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 10

[Jump to summary definition](#summary-Pass-10)	|	[Previous Pass outcome](#pass-outcome-number-9)	|	[Next Pass outcome](#pass-outcome-number-11)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/notrealterm.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/notrealterm](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[namespace-validity](https://ns.inria.fr/olivaw#namespace-validity)|
|----|----|
|Title|Prefix&#32;validity&#32;test|
|Description|A&#32;test&#32;case&#32;checking&#32;if&#32;all&#32;the&#32;prefixes&#32;are&#32;not&#32;too&#32;close&#32;from&#32;the&#32;most&#32;used&#32;existing&#32;namespaces&#32;(according&#32;to&#32;prefix&#32;cc)&#32;or&#32;an&#32;ontology&#32;namespace|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-10)|Identifier|`namespace-typo`|
|[Section top](#pass-outcome-number-10)|Title|No&#32;namespace&#32;typo|
|[Section top](#pass-outcome-number-10)|Description|It&#32;seems&#32;that&#32;none&#32;of&#32;the&#32;subject&#32;URIs&#32;have&#32;namespaces&#32;typos|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)	|	[Previous Pass outcome](#pass-outcome-number-10)	|	[Next Pass outcome](#pass-outcome-number-12)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/notrealterm.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/notrealterm](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-11)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-11)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-11)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 12

[Jump to summary definition](#summary-Pass-12)	|	[Previous Pass outcome](#pass-outcome-number-11)	|	[Next Pass outcome](#pass-outcome-number-13)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/notrealterm.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/notrealterm](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-12)|Identifier|`syntax-error`|
|[Section top](#pass-outcome-number-12)|Title|Correct&#32;syntax|
|[Section top](#pass-outcome-number-12)|Description|Test&#32;subject&#32;has&#32;a&#32;correct&#32;syntax|

***
### Pass Outcome number 13

[Jump to summary definition](#summary-Pass-13)	|	[Previous Pass outcome](#pass-outcome-number-12)	|	[Next Pass outcome](#pass-outcome-number-14)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/notrealterm.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/notrealterm](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|
|----|----|
|Title|Classed&#32;node&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;if&#32;each&#32;node&#32;has&#32;a&#32;rdf:type&#32;property|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-13)|Identifier|`node-with-class`|
|[Section top](#pass-outcome-number-13)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-13)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 14

[Jump to summary definition](#summary-Pass-14)	|	[Previous Pass outcome](#pass-outcome-number-13)	|	[Next Pass outcome](#pass-outcome-number-15)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-inconsistent|
|----|----|
|Title|Standalone&#32;use&#32;case&#32;use-cases/zeusecase/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Use case zeusecase/inconsistent](https://github.com/acimov-tools/model-test/blob/main/use-cases/zeusecase/inconsistent.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-14)|Identifier|`syntax-error`|
|[Section top](#pass-outcome-number-14)|Title|Correct&#32;syntax|
|[Section top](#pass-outcome-number-14)|Description|Test&#32;subject&#32;has&#32;a&#32;correct&#32;syntax|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)	|	[Previous Pass outcome](#pass-outcome-number-14)	|	Next Pass outcome

:white_check_mark:Pass outcome
#### Subject detail
|Name|dataset-domain1-scenario1|
|----|----|
|Title|Standalone&#32;dataset&#32;domains/domain1/scenario1/dataset.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Dataset domain1/scenario1](https://github.com/acimov-tools/model-test/blob/main/domains/domain1/scenario1/dataset.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-15)|Identifier|`syntax-error`|
|[Section top](#pass-outcome-number-15)|Title|Correct&#32;syntax|
|[Section top](#pass-outcome-number-15)|Description|Test&#32;subject&#32;has&#32;a&#32;correct&#32;syntax|

***

</details>

***
