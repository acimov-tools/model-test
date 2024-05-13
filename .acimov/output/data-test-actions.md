# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./data-test-actions.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using actions script|
|Description|Test triggered by &#91;@NicoRobertIn](https://github.com/NicoRobertIn) by actions trigger|
|Script|[suite.py](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/data/suite.py)
|Date|2024-05-13 14:54:46|

***


# Statistic summary

Here is a short overview for this test report

27 Outcomes

:boom:5 MajorFail, :exclamation:0 MinorFail, :warning:1 CannotTell, :grey_question:4 NotTested, :white_check_mark:17 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="18%" height="25px"/><img src="../assets/orange.png" width="0%" height="25px"/><img src="../assets/grey.png" width="3%" height="25px"/><img src="../assets/white.png" width="14%" height="25px"/><img src="../assets/green.png" width="65%" height="25px"/></div>

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

:boom:5 MajorFail outcomes

<details>
<summary>Fold/Unfold the 5 summary and details</summary>

## MajorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:boom:5 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-1">1/5</div>|:boom:*MajorFail*|`usecase-zeusecase-wronguncommonprefix`|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/richness.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-2">2/5</div>|:boom:*MajorFail*|`usecase-zeusecase-wrongcommonprefix`|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/richness.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-2)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-3">3/5</div>|:boom:*MajorFail*|`usecase-zeusecase-syntax`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-3)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-4">4/5</div>|:boom:*MajorFail*|`usecase-zeusecase-notrealterm`|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|Unknown ontology term|[Jump](#majorfail-outcome-number-4)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-5">5/5</div>|:boom:*MajorFail*|`usecase-zeusecase-notrealterm`|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/richness.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wronguncommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wronguncommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/richness.shacl#criterion)|
|----|----|
|Title|The vocabulary is linked to by other vocabularies|
|Description|Each node should have predicates other than rdf:type|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Some subjects only have a rdf:type property&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sparql &#91; sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:select &#34;&#34;&#34;&#10;select ?this where {&#10;?this ?p ?o .&#10;filter (?p != rdf:type)&#10;}&#10;values ($ontology&lowbar;url) { (&#34;https://www.example.org/olivaw/&#34;) }&#34;&#34;&#34; ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdf:type .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:1722e86f-7ed4-47e9-9382-f8b31cdbc157> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/zeusecase/zeInstance> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Some subjects only have a rdf:type property&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath sh:sparql ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Warning ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:sparqlCount ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &#60;#shape> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>:zeInstance a &#60;http://www.example.org/olivaw/ClassA> .</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wrongcommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wrongcommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/richness.shacl#criterion)|
|----|----|
|Title|The vocabulary is linked to by other vocabularies|
|Description|Each node should have predicates other than rdf:type|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Some subjects only have a rdf:type property&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sparql &#91; sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:select &#34;&#34;&#34;&#10;select ?this where {&#10;?this ?p ?o .&#10;filter (?p != rdf:type)&#10;}&#10;values ($ontology&lowbar;url) { (&#34;https://www.example.org/olivaw/&#34;) }&#34;&#34;&#34; ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdf:type .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:9a2c2417-50d6-4e81-8fd2-23418e4eee63> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/zeusecase/zeInstance> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Some subjects only have a rdf:type property&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath sh:sparql ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Warning ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:sparqlCount ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &#60;#shape> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>:zeInstance a sand:ClassA .</code></pre>|

***
### MajorFail Outcome number 3

[Jump to summary definition](#summary-MajorFail-3)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-syntax|
|----|----|
|Title|Standalone use case use-cases/zeusecase/syntax.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/syntax.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/syntax.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|Encountered &#34;a&#34; at line 6, column 27.|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone use case use-cases/zeusecase/notrealterm.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/notrealterm.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|
|----|----|
|Title|Term recognition test|
|Description|A test meant to detect if all the terms from the subject that are from the ontology namespace are indeed defined in the ontology|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Unknown ontology term|
|Description|Some fragment terms are in ontology namespace but not defined in ontology|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/zeusecase/zeInstance> rdf:type &#60;https://www.example.org/olivaw/ClasseA> .</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)

:boom:MajorFail outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone use case use-cases/zeusecase/notrealterm.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/notrealterm.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[data-richness](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/richness.shacl#criterion)|
|----|----|
|Title|The vocabulary is linked to by other vocabularies|
|Description|Each node should have predicates other than rdf:type|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Some subjects only have a rdf:type property&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sparql &#91; sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:select &#34;&#34;&#34;&#10;select ?this where {&#10;?this ?p ?o .&#10;filter (?p != rdf:type)&#10;}&#10;values ($ontology&lowbar;url) { (&#34;https://www.example.org/olivaw/&#34;) }&#34;&#34;&#34; ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdf:type .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:bedc253c-08c2-4fb1-a636-8ad94d5bef2e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/zeusecase/zeInstance> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Some subjects only have a rdf:type property&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath sh:sparql ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Warning ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:sparqlCount ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &#60;#shape> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>:zeInstance a sand:ClasseA .</code></pre>|

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
|[Table top](#cannottell-outcomes-summary)|<div id="summary-CannotTell-1">1/1</div>|:warning:*CannotTell*|`usecase-zeusecase-wronguncommonprefix`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|Possible prefix typo|[Jump](#cannottell-outcome-number-1)|

***

## CannotTell Outcomes Details

This subchapter gives more details to the :warning:CannotTell outcomes

### CannotTell Outcome number 1

[Jump to summary definition](#summary-CannotTell-1)

:warning:CannotTell outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wronguncommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wronguncommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

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
|Pointer|<pre lang="Turtle"><code>Prefix usage in the subject file:&#10;@prefix owl: &#60;http://www.w3.org/2002/07/owl#> .&#10;@prefix rdf: &#60;http://www.w3.org/1999/02/22-rdf-syntax-ns#> . &#10; &#60;https://www.example.org/zeusecase/zeInstance> rdf:type &#60;http://www.example.org/olivaw/ClassA> .</code></pre>|
|Pointer|<pre lang="Turtle"><code>Similar prefix found in file ./use-cases/zeusecase/notrealterm.ttl&#10;Prefix found: https://www.example.org/olivaw/&#10;@prefix owl: &#60;http://www.w3.org/2002/07/owl#> .&#10;@prefix rdf: &#60;http://www.w3.org/1999/02/22-rdf-syntax-ns#> . &#10; &#60;https://www.example.org/zeusecase/zeInstance> rdf:type &#60;https://www.example.org/olivaw/ClasseA> .</code></pre>|

***

</details>

***


# NotTested Outcomes

Here is the chapter related to the NotTested outcome

:grey_question:4 NotTested outcomes

<details>
<summary>Fold/Unfold the 4 summary and details</summary>

## NotTested Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:grey_question:4 NotTested outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-1">1/4</div>|:grey_question:*NotTested*|`usecase-zeusecase-syntax`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-2">2/4</div>|:grey_question:*NotTested*|`usecase-zeusecase-syntax`|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|Error on custom test |[Jump](#nottested-outcome-number-2)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-3">3/4</div>|:grey_question:*NotTested*|`usecase-zeusecase-inconsistent`|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|Error on custom test |[Jump](#nottested-outcome-number-3)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-4">4/4</div>|:grey_question:*NotTested*|`dataset-domain1-scenario1`|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|Error on custom test |[Jump](#nottested-outcome-number-4)|

***

## NotTested Outcomes Details

This subchapter gives more details to the :grey_question:NotTested outcomes

### NotTested Outcome number 1

[Jump to summary definition](#summary-NotTested-1)

:grey_question:NotTested outcome
#### Subject detail
|Name|usecase-zeusecase-syntax|
|----|----|
|Title|Standalone use case use-cases/zeusecase/syntax.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/syntax.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/syntax.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

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
|Name|usecase-zeusecase-syntax|
|----|----|
|Title|Standalone use case use-cases/zeusecase/syntax.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/syntax.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/syntax.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|
|----|----|
|Title|Term recognition test|
|Description|A test meant to detect if all the terms from the subject that are from the ontology namespace are indeed defined in the ontology|

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
|Name|usecase-zeusecase-inconsistent|
|----|----|
|Title|Standalone use case use-cases/zeusecase/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/inconsistent.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|
|----|----|
|Title|Term recognition test|
|Description|A test meant to detect if all the terms from the subject that are from the ontology namespace are indeed defined in the ontology|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 4

[Jump to summary definition](#summary-NotTested-4)

:grey_question:NotTested outcome
#### Subject detail
|Name|dataset-domain1-scenario1|
|----|----|
|Title|Standalone dataset domains/domain1/scenario1/dataset.ttl from branch refs/heads/main|
|Composition|- [Dataset domain1/scenario1/dataset.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/domain1/scenario1/dataset.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|
|----|----|
|Title|Term recognition test|
|Description|A test meant to detect if all the terms from the subject that are from the ontology namespace are indeed defined in the ontology|

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

:white_check_mark:17 Pass outcomes

<details>
<summary>Fold/Unfold the 17 summary and details</summary>

## Pass Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:white_check_mark:17 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-1">1/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wronguncommonprefix`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-1)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-2">2/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wronguncommonprefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-2)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-3">3/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wronguncommonprefix`|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|Every term exists|[Jump](#pass-outcome-number-3)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-4">4/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wronguncommonprefix`|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-4)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-5">5/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wrongcommonprefix`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-5)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-6">6/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wrongcommonprefix`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|No prefix typo|[Jump](#pass-outcome-number-6)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-7">7/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wrongcommonprefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-7)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-8">8/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wrongcommonprefix`|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|Every term exists|[Jump](#pass-outcome-number-8)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-9">9/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-wrongcommonprefix`|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-9)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-10">10/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-notrealterm`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-10)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-11">11/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-notrealterm`|[prefix-validity](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#prefix-validity)|No prefix typo|[Jump](#pass-outcome-number-11)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-12">12/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-notrealterm`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-12)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-13">13/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-notrealterm`|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-13)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-14">14/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-14)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-15">15/17</div>|:white_check_mark:*Pass*|`usecase-zeusecase-inconsistent`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-15)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-16">16/17</div>|:white_check_mark:*Pass*|`dataset-domain1-scenario1`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-16)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-17">17/17</div>|:white_check_mark:*Pass*|`dataset-domain1-scenario1`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Correct syntax|[Jump](#pass-outcome-number-17)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wronguncommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wronguncommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wronguncommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wronguncommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

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
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wronguncommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wronguncommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|
|----|----|
|Title|Term recognition test|
|Description|A test meant to detect if all the terms from the subject that are from the ontology namespace are indeed defined in the ontology|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Every term exists|
|Description|All the ontologic terms in the subject are defined in the ontology|

***
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wronguncommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wronguncommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wronguncommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wronguncommonprefix.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|
|----|----|
|Title|Classed node test|
|Description|A test meant to test if each node has a rdf:type property|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wrongcommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wrongcommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wrongcommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wrongcommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

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
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wrongcommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wrongcommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

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
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wrongcommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wrongcommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[term-recognition](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-recognition)|
|----|----|
|Title|Term recognition test|
|Description|A test meant to detect if all the terms from the subject that are from the ontology namespace are indeed defined in the ontology|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Every term exists|
|Description|All the ontologic terms in the subject are defined in the ontology|

***
### Pass Outcome number 9

[Jump to summary definition](#summary-Pass-9)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-wrongcommonprefix|
|----|----|
|Title|Standalone use case use-cases/zeusecase/wrongcommonprefix.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/wrongcommonprefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/wrongcommonprefix.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|
|----|----|
|Title|Classed node test|
|Description|A test meant to test if each node has a rdf:type property|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 10

[Jump to summary definition](#summary-Pass-10)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone use case use-cases/zeusecase/notrealterm.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/notrealterm.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone use case use-cases/zeusecase/notrealterm.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/notrealterm.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/notrealterm.ttl)|

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
### Pass Outcome number 12

[Jump to summary definition](#summary-Pass-12)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone use case use-cases/zeusecase/notrealterm.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/notrealterm.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/notrealterm.ttl)|

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
### Pass Outcome number 13

[Jump to summary definition](#summary-Pass-13)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-notrealterm|
|----|----|
|Title|Standalone use case use-cases/zeusecase/notrealterm.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/notrealterm.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/notrealterm.ttl)|

#### Criterion detail
|Identifier|[node-with-class](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/data/node-with-class.shacl#criterion)|
|----|----|
|Title|Classed node test|
|Description|A test meant to test if each node has a rdf:type property|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 14

[Jump to summary definition](#summary-Pass-14)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-inconsistent|
|----|----|
|Title|Standalone use case use-cases/zeusecase/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)

:white_check_mark:Pass outcome
#### Subject detail
|Name|usecase-zeusecase-inconsistent|
|----|----|
|Title|Standalone use case use-cases/zeusecase/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Use case zeusecase/inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/use-cases/zeusecase/inconsistent.ttl)|

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
### Pass Outcome number 16

[Jump to summary definition](#summary-Pass-16)

:white_check_mark:Pass outcome
#### Subject detail
|Name|dataset-domain1-scenario1|
|----|----|
|Title|Standalone dataset domains/domain1/scenario1/dataset.ttl from branch refs/heads/main|
|Composition|- [Dataset domain1/scenario1/dataset.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/domain1/scenario1/dataset.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL consistent|
|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 17

[Jump to summary definition](#summary-Pass-17)

:white_check_mark:Pass outcome
#### Subject detail
|Name|dataset-domain1-scenario1|
|----|----|
|Title|Standalone dataset domains/domain1/scenario1/dataset.ttl from branch refs/heads/main|
|Composition|- [Dataset domain1/scenario1/dataset.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/domain1/scenario1/dataset.ttl)|

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

</details>

***
