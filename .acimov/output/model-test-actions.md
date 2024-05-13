# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./model-test-actions.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using actions script|
|Description|Test triggered by &#91;@NicoRobertIn](https://github.com/NicoRobertIn) by actions trigger|
|Script|[suite.py](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/suite.py)
|Date|2024-05-13 20:49:56|

***


# Statistic summary

Here is a short overview for this test report

324 Outcomes

:boom:46 MajorFail, :exclamation:23 MinorFail, :warning:0 CannotTell, :grey_question:36 NotTested, :white_check_mark:219 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="14%" height="25px"/><img src="../assets/orange.png" width="7%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="11%" height="25px"/><img src="../assets/green.png" width="68%" height="25px"/></div>

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

:boom:46 MajorFail outcomes

<details>
<summary>Fold/Unfold the 46 summary and details</summary>

## MajorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:boom:46 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-1">1/46</div>|:boom:*MajorFail*|`module-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-2">2/46</div>|:boom:*MajorFail*|`module-unknown-prefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-2)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-3">3/46</div>|:boom:*MajorFail*|`module-too-close-terms`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-3)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-4">4/46</div>|:boom:*MajorFail*|`module-range-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-4)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-5">5/46</div>|:boom:*MajorFail*|`module-not-ql`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-6">6/46</div>|:boom:*MajorFail*|`module-not-el`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-6)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-7">7/46</div>|:boom:*MajorFail*|`module-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-7)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-8">8/46</div>|:boom:*MajorFail*|`module-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-8)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-9">9/46</div>|:boom:*MajorFail*|`module-inconsistent`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-9)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-10">10/46</div>|:boom:*MajorFail*|`module-domain-outer`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-10)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-11">11/46</div>|:boom:*MajorFail*|`module-domain-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-11)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-12">12/46</div>|:boom:*MajorFail*|`module-broken`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-12)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-13">13/46</div>|:boom:*MajorFail*|`modelet-zedomain-syntax`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-13)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-14">14/46</div>|:boom:*MajorFail*|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-14)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-15">15/46</div>|:boom:*MajorFail*|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-15)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-16">16/46</div>|:boom:*MajorFail*|`modelet-zedomain-prefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-16)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-17">17/46</div>|:boom:*MajorFail*|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-17)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-18">18/46</div>|:boom:*MajorFail*|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-18)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-19">19/46</div>|:boom:*MajorFail*|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-19)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-20">20/46</div>|:boom:*MajorFail*|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-20)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-21">21/46</div>|:boom:*MajorFail*|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-21)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-22">22/46</div>|:boom:*MajorFail*|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-22)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-23">23/46</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-23)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-24">24/46</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-24)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-25">25/46</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-25)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-26">26/46</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-26)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-27">27/46</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-27)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-28">28/46</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-28)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-29">29/46</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-29)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-30">30/46</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-30)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-31">31/46</div>|:boom:*MajorFail*|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-31)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-32">32/46</div>|:boom:*MajorFail*|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-32)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-33">33/46</div>|:boom:*MajorFail*|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-33)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-34">34/46</div>|:boom:*MajorFail*|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-34)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-35">35/46</div>|:boom:*MajorFail*|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-35)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-36">36/46</div>|:boom:*MajorFail*|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-36)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-37">37/46</div>|:boom:*MajorFail*|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-37)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-38">38/46</div>|:boom:*MajorFail*|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-38)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-39">39/46</div>|:boom:*MajorFail*|`all-modules`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-39)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-40">40/46</div>|:boom:*MajorFail*|`all-modules`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-40)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-41">41/46</div>|:boom:*MajorFail*|`all-modules`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-41)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-42">42/46</div>|:boom:*MajorFail*|`all-modules`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-42)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-43">43/46</div>|:boom:*MajorFail*|`all-fragments`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-43)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-44">44/46</div>|:boom:*MajorFail*|`all-fragments`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-44)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-45">45/46</div>|:boom:*MajorFail*|`all-fragments`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-45)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-46">46/46</div>|:boom:*MajorFail*|`all-fragments`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-46)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)

:boom:MajorFail outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:4c6f80d9-dd65-481c-aae4-398afbd73a19> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b2695 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)

:boom:MajorFail outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|Pointer|<pre lang="Turtle"><code>at line 3 of &#60;>:&#10;Bad syntax (Prefix &#34;owl:&#34; not bound) at &Hat; in:&#10;&#34;...b'fix : &#60;https://www.example.org/olivaw/> .&#92;n&#92;n:unknownPrefix a '&Hat;b'owl:Ontology .&#92;n&#92;n:Unknown a owl:Class ;&#92;n&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This '...&#34;</code></pre>|

***
### MajorFail Outcome number 3

[Jump to summary definition](#summary-MajorFail-3)

:boom:MajorFail outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:fa7d47f1-e087-42fa-8832-070afc6a24c4> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b6733 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:9b2c0c94-73b9-4b8f-8d0a-39c417d39944> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b6733 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)

:boom:MajorFail outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:878be711-4e5e-4a36-b0f2-21811eb8c804> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b5387 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)

:boom:MajorFail outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:e903407f-506e-44f0-8e70-106845857595> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b8079 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 6

[Jump to summary definition](#summary-MajorFail-6)

:boom:MajorFail outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ea71928d-02a7-464f-a17e-69a87176612e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b4041 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***
### MajorFail Outcome number 7

[Jump to summary definition](#summary-MajorFail-7)

:boom:MajorFail outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#disjointWith &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10; &#10;|

***
### MajorFail Outcome number 8

[Jump to summary definition](#summary-MajorFail-8)

:boom:MajorFail outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10; &#10;|

***
### MajorFail Outcome number 9

[Jump to summary definition](#summary-MajorFail-9)

:boom:MajorFail outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a81413b0-157e-47ef-a972-494d6f90dd5d> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10780 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ec4d7a93-61fd-4ac4-a27a-c519e1c4a3f5> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10780 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ecd71bb2-8e88-4d81-b93f-f293bb7d3c98> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10780 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent .</code></pre>|

***
### MajorFail Outcome number 10

[Jump to summary definition](#summary-MajorFail-10)

:boom:MajorFail outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 11

[Jump to summary definition](#summary-MajorFail-11)

:boom:MajorFail outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:c2b5911d-56d2-4d57-af3c-f1d55877c30d> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b9425 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 12

[Jump to summary definition](#summary-MajorFail-12)

:boom:MajorFail outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|Pointer|<pre lang="Turtle"><code>Encountered &#34;a&#34; at line 9, column 23.</code></pre>|

***
### MajorFail Outcome number 13

[Jump to summary definition](#summary-MajorFail-13)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|Pointer|<pre lang="Turtle"><code>Encountered &#34;a&#34; at line 7, column 23.</code></pre>|

***
### MajorFail Outcome number 14

[Jump to summary definition](#summary-MajorFail-14)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:5261b664-00da-436d-a47d-69966a952ef3> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b28287 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 15

[Jump to summary definition](#summary-MajorFail-15)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:684f40d4-c6ec-43e7-9e75-8f2babadcbf8> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b29633 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 16

[Jump to summary definition](#summary-MajorFail-16)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|Pointer|<pre lang="Turtle"><code>at line 3 of &#60;>:&#10;Bad syntax (Prefix &#34;owl:&#34; not bound) at &Hat; in:&#10;&#34;...b'fix : &#60;https://www.example.org/olivaw/> .&#92;n&#92;n:unknownPrefix a '&Hat;b'owl:Ontology .&#92;n&#92;n:Unknown a owl:Class ;&#92;n&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This '...&#34;</code></pre>|

***
### MajorFail Outcome number 17

[Jump to summary definition](#summary-MajorFail-17)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d92c9424-771c-498b-b411-ff63649f3476> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b12126 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 18

[Jump to summary definition](#summary-MajorFail-18)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:bfb09fcb-771e-47b2-bb6e-e4fbf66d6b14> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b13472 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 19

[Jump to summary definition](#summary-MajorFail-19)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#disjointWith &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10; &#10;|

***
### MajorFail Outcome number 20

[Jump to summary definition](#summary-MajorFail-20)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10; &#10;|

***
### MajorFail Outcome number 21

[Jump to summary definition](#summary-MajorFail-21)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6caabcea-c65d-4f07-bfc2-86e273e6e7a9> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14818 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:76eddabc-3617-4809-8a25-92d10d76059a> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14818 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d1b952bd-775c-419f-bc1b-00d39259eaf6> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14818 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|

***
### MajorFail Outcome number 22

[Jump to summary definition](#summary-MajorFail-22)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:f62835e5-e1c4-4943-a5f7-425c83af4416> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b16173 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:aa20d34c-02e8-4075-b2f9-148e85fab97f> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b16173 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:17896ee0-1bc8-4dbb-8d67-6216ea459364> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b16173 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|

***
### MajorFail Outcome number 23

[Jump to summary definition](#summary-MajorFail-23)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 24

[Jump to summary definition](#summary-MajorFail-24)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 25

[Jump to summary definition](#summary-MajorFail-25)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d78eed5c-2a79-425b-aaef-06a01d99cf66> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b22903 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 26

[Jump to summary definition](#summary-MajorFail-26)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:99ef07c9-ee23-4a77-a527-95f5367d70fb> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24249 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 27

[Jump to summary definition](#summary-MajorFail-27)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 28

[Jump to summary definition](#summary-MajorFail-28)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 29

[Jump to summary definition](#summary-MajorFail-29)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:7cada05a-90d1-4928-bc2e-bcb89564ddf9> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b33671 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 30

[Jump to summary definition](#summary-MajorFail-30)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:73b73472-0e62-462d-ab1c-9dd1f7d46c46> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b35017 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 31

[Jump to summary definition](#summary-MajorFail-31)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:beabf57e-55a2-4070-8557-dc6835da9be8> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b20211 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:bf44b7d2-6672-4609-b049-f428571c9776> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b20211 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 32

[Jump to summary definition](#summary-MajorFail-32)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:56fc8bc2-aa6c-4e29-8a57-f91f37e867fc> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b21557 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:642959d8-b1d3-4194-bc05-77f6bc4f9aca> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b21557 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 33

[Jump to summary definition](#summary-MajorFail-33)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:56eb29dc-5c8c-4b3a-9b73-afcb0c587047> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b17519 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***
### MajorFail Outcome number 34

[Jump to summary definition](#summary-MajorFail-34)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b7416789-39f1-43ae-8855-fe286ea45228> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b18865 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***
### MajorFail Outcome number 35

[Jump to summary definition](#summary-MajorFail-35)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ea128752-dce5-4503-afed-2439b307089b> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25595 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 36

[Jump to summary definition](#summary-MajorFail-36)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:72258882-645a-4f38-9757-60bc0125998e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b26941 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 37

[Jump to summary definition](#summary-MajorFail-37)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:26be448c-2574-409a-a073-1e276222c2ae> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b30979 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***
### MajorFail Outcome number 38

[Jump to summary definition](#summary-MajorFail-38)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b510ae71-8c1a-4024-846d-e2139b218db1> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b32325 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***
### MajorFail Outcome number 39

[Jump to summary definition](#summary-MajorFail-39)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 40

[Jump to summary definition](#summary-MajorFail-40)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#disjointWith &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10; &#10;|

***
### MajorFail Outcome number 41

[Jump to summary definition](#summary-MajorFail-41)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10; &#10;|

***
### MajorFail Outcome number 42

[Jump to summary definition](#summary-MajorFail-42)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:06a76588-1662-4267-bdbf-829dbeb301d5> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:17b2742c-6b81-41fa-9b91-e210671d56bb> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a376861b-a6a3-4530-9df8-9a3ecf86bdd5> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:421445b7-9c8c-4bf9-aef0-870b4108cb4e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:51f5b742-a8aa-4706-a1aa-7392829e5deb> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:bd582b9f-6ae9-4548-b08e-29174af76b19> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:4b4e5144-ca78-45f3-b9a1-fd9dc9ec484d> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b4130790-5a24-47a4-a8a4-11f624e374e0> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:94b91934-2d49-487e-916d-da41338bcc95> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:7bc59bcb-3644-4ddb-85ee-8096fc53159e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:73667c25-7d05-4a99-b042-cbb0daa0f5fd> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36372 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|

***
### MajorFail Outcome number 43

[Jump to summary definition](#summary-MajorFail-43)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Domain out of vocabulary|
|Description|Some properties have a domain out of the ontology|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 44

[Jump to summary definition](#summary-MajorFail-44)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#disjointWith &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:disjointWith&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10; &#10;|

***
### MajorFail Outcome number 45

[Jump to summary definition](#summary-MajorFail-45)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|OWL RL Constraint violation|
|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses &#10;rdf:type sp:ConstraintViolation &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass> &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34; &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst> &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond> &#10; &#10;|

***
### MajorFail Outcome number 46

[Jump to summary definition](#summary-MajorFail-46)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|
|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ad2676af-912a-4c6d-96ff-82f2ba927f36> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:276b6bcc-5af8-4fa2-b9b1-d268c967a5f4> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:dc060905-4907-4756-bc04-210be7c014b7> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:fd34b33a-dd7e-455a-8c63-e104c513c8f4> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:187bd1e6-1d0a-4c96-a70e-3f9139e431f2> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:8b47601c-78ec-43b4-be3b-6e559b01961b> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:87c8c36f-e46a-4002-bdb8-54693a448d65> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d0a33746-76df-4089-b3bc-05bb77fdca5e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2317cebc-6fc7-49aa-bb18-7073c2477789> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:72901a81-853f-4267-9f66-c5b26f911ff0> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:5d2c4236-7e62-40aa-a475-b7982261e198> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37727 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***

</details>

***


# MinorFail Outcomes

Here is the chapter related to the MinorFail outcome

:exclamation:23 MinorFail outcomes

<details>
<summary>Fold/Unfold the 23 summary and details</summary>

## MinorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:exclamation:23 MinorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-1">1/23</div>|:exclamation:*MinorFail*|`module-unreferenced`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-1)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-2">2/23</div>|:exclamation:*MinorFail*|`module-unlabeled`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-2)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-3">3/23</div>|:exclamation:*MinorFail*|`module-too-close-terms`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-3)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-4">4/23</div>|:exclamation:*MinorFail*|`module-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-4)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-5">5/23</div>|:exclamation:*MinorFail*|`module-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-5)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-6">6/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-label`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-6)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-7">7/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-label`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-7)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-8">8/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-differenciation`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-8)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-9">9/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-differenciation`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-9)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-10">10/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-10)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-11">11/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-11)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-12">12/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-12)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-13">13/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-13)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-14">14/23</div>|:exclamation:*MinorFail*|`all-modules`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-14)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-15">15/23</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-15)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-16">16/23</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-16)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-17">17/23</div>|:exclamation:*MinorFail*|`all-modules`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-17)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-18">18/23</div>|:exclamation:*MinorFail*|`all-modules`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-18)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-19">19/23</div>|:exclamation:*MinorFail*|`all-fragments`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-19)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-20">20/23</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-20)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-21">21/23</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-21)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-22">22/23</div>|:exclamation:*MinorFail*|`all-fragments`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-22)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-23">23/23</div>|:exclamation:*MinorFail*|`all-fragments`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-23)|

***

## MinorFail Outcomes Details

This subchapter gives more details to the :exclamation:MinorFail outcomes

### MinorFail Outcome number 1

[Jump to summary definition](#summary-MinorFail-1)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Term not referenced to a module|
|Description|Subject terms not linked to a module by a rdfs:isDefinedBy property|
|Pointer|<pre lang="Turtle"><code>sand:NotReferencedClass a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is not linked to a module by a rdfs:isDefinedBy p...&#34; .</code></pre>|

***
### MinorFail Outcome number 2

[Jump to summary definition](#summary-MinorFail-2)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Terms not labeled|
|Description|The following terms have no rdfs:label to define it in natural language|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 3

[Jump to summary definition](#summary-MinorFail-3)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Too close terms|
|Description|Some terms are too similar|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 4

[Jump to summary definition](#summary-MinorFail-4)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 5

[Jump to summary definition](#summary-MinorFail-5)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 6

[Jump to summary definition](#summary-MinorFail-6)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Terms not labeled|
|Description|The following terms have no rdfs:label to define it in natural language|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 7

[Jump to summary definition](#summary-MinorFail-7)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Terms not labeled|
|Description|The following terms have no rdfs:label to define it in natural language|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 8

[Jump to summary definition](#summary-MinorFail-8)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Too close terms|
|Description|Some terms are too similar|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 9

[Jump to summary definition](#summary-MinorFail-9)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Too close terms|
|Description|Some terms are too similar|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 10

[Jump to summary definition](#summary-MinorFail-10)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 11

[Jump to summary definition](#summary-MinorFail-11)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 12

[Jump to summary definition](#summary-MinorFail-12)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 13

[Jump to summary definition](#summary-MinorFail-13)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 14

[Jump to summary definition](#summary-MinorFail-14)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Terms not labeled|
|Description|The following terms have no rdfs:label to define it in natural language|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 15

[Jump to summary definition](#summary-MinorFail-15)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 16

[Jump to summary definition](#summary-MinorFail-16)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 17

[Jump to summary definition](#summary-MinorFail-17)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Term not referenced to a module|
|Description|Subject terms not linked to a module by a rdfs:isDefinedBy property|
|Pointer|<pre lang="Turtle"><code>sand:NotReferencedClass a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is not linked to a module by a rdfs:isDefinedBy p...&#34; .</code></pre>|

***
### MinorFail Outcome number 18

[Jump to summary definition](#summary-MinorFail-18)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Too close terms|
|Description|Some terms are too similar|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 19

[Jump to summary definition](#summary-MinorFail-19)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Terms not labeled|
|Description|The following terms have no rdfs:label to define it in natural language|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 20

[Jump to summary definition](#summary-MinorFail-20)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL QL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 21

[Jump to summary definition](#summary-MinorFail-21)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|OWL EL Profile incompatible|
|Description|Statement not supported|
|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 22

[Jump to summary definition](#summary-MinorFail-22)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Term not referenced to a module|
|Description|Subject terms not linked to a module by a rdfs:isDefinedBy property|
|Pointer|<pre lang="Turtle"><code>sand:NotReferencedClass a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is not linked to a module by a rdfs:isDefinedBy p...&#34; .</code></pre>|

***
### MinorFail Outcome number 23

[Jump to summary definition](#summary-MinorFail-23)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:exclamation:MinorFail|
|----|----|
|Title|Too close terms|
|Description|Some terms are too similar|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***

</details>

***


# NotTested Outcomes

Here is the chapter related to the NotTested outcome

:grey_question:36 NotTested outcomes

<details>
<summary>Fold/Unfold the 36 summary and details</summary>

## NotTested Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:grey_question:36 NotTested outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-1">1/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-2">2/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-2)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-3">3/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-3)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-4">4/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-4)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-5">5/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-5)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-6">6/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-6)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-7">7/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-7)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-8">8/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-8)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-9">9/36</div>|:grey_question:*NotTested*|`module-unknown-prefix`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-9)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-10">10/36</div>|:grey_question:*NotTested*|`module-broken`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-10)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-11">11/36</div>|:grey_question:*NotTested*|`module-broken`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-11)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-12">12/36</div>|:grey_question:*NotTested*|`module-broken`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-12)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-13">13/36</div>|:grey_question:*NotTested*|`module-broken`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-13)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-14">14/36</div>|:grey_question:*NotTested*|`module-broken`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-14)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-15">15/36</div>|:grey_question:*NotTested*|`module-broken`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-15)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-16">16/36</div>|:grey_question:*NotTested*|`module-broken`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-16)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-17">17/36</div>|:grey_question:*NotTested*|`module-broken`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-17)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-18">18/36</div>|:grey_question:*NotTested*|`module-broken`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-18)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-19">19/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-19)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-20">20/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-20)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-21">21/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-21)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-22">22/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-22)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-23">23/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-23)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-24">24/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-24)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-25">25/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-25)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-26">26/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-26)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-27">27/36</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-27)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-28">28/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-28)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-29">29/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-29)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-30">30/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-30)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-31">31/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-31)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-32">32/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-32)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-33">33/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-33)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-34">34/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-34)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-35">35/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-35)|
|[Table top](#nottested-outcomes-summary)|<div id="summary-NotTested-36">36/36</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-36)|

***

## NotTested Outcomes Details

This subchapter gives more details to the :grey_question:NotTested outcomes

### NotTested Outcome number 1

[Jump to summary definition](#summary-NotTested-1)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

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
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

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
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

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
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

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
### NotTested Outcome number 5

[Jump to summary definition](#summary-NotTested-5)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 6

[Jump to summary definition](#summary-NotTested-6)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 7

[Jump to summary definition](#summary-NotTested-7)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 8

[Jump to summary definition](#summary-NotTested-8)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 9

[Jump to summary definition](#summary-NotTested-9)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch refs/heads/main|
|Composition|- [Module unknown-prefix.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 10

[Jump to summary definition](#summary-NotTested-10)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 11

[Jump to summary definition](#summary-NotTested-11)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 12

[Jump to summary definition](#summary-NotTested-12)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 13

[Jump to summary definition](#summary-NotTested-13)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

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
### NotTested Outcome number 14

[Jump to summary definition](#summary-NotTested-14)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 15

[Jump to summary definition](#summary-NotTested-15)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 16

[Jump to summary definition](#summary-NotTested-16)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 17

[Jump to summary definition](#summary-NotTested-17)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 18

[Jump to summary definition](#summary-NotTested-18)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch refs/heads/main|
|Composition|- [Module broken.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 19

[Jump to summary definition](#summary-NotTested-19)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 20

[Jump to summary definition](#summary-NotTested-20)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 21

[Jump to summary definition](#summary-NotTested-21)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 22

[Jump to summary definition](#summary-NotTested-22)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

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
### NotTested Outcome number 23

[Jump to summary definition](#summary-NotTested-23)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 24

[Jump to summary definition](#summary-NotTested-24)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 25

[Jump to summary definition](#summary-NotTested-25)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 26

[Jump to summary definition](#summary-NotTested-26)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 27

[Jump to summary definition](#summary-NotTested-27)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/syntax/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 28

[Jump to summary definition](#summary-NotTested-28)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 29

[Jump to summary definition](#summary-NotTested-29)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 30

[Jump to summary definition](#summary-NotTested-30)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 31

[Jump to summary definition](#summary-NotTested-31)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

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
### NotTested Outcome number 32

[Jump to summary definition](#summary-NotTested-32)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 33

[Jump to summary definition](#summary-NotTested-33)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 34

[Jump to summary definition](#summary-NotTested-34)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 35

[Jump to summary definition](#summary-NotTested-35)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|Error on custom test|
|Description|Error occured while running custom test|

***
### NotTested Outcome number 36

[Jump to summary definition](#summary-NotTested-36)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/prefix/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

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

:white_check_mark:219 Pass outcomes

<details>
<summary>Fold/Unfold the 219 summary and details</summary>

## Pass Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:white_check_mark:219 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-1">1/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-1)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-2">2/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-2)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-3">3/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-3)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-4">4/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-4)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-5">5/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-5)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-6">6/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-6)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-7">7/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-7)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-8">8/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-8)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-9">9/219</div>|:white_check_mark:*Pass*|`module-unreferenced`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-9)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-10">10/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-10)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-11">11/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-11)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-12">12/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-12)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-13">13/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-13)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-14">14/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-14)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-15">15/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-15)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-16">16/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-16)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-17">17/219</div>|:white_check_mark:*Pass*|`module-unlabeled`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-17)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-18">18/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-18)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-19">19/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-19)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-20">20/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-20)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-21">21/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-21)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-22">22/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-22)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-23">23/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-23)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-24">24/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-24)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-25">25/219</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-25)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-26">26/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-26)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-27">27/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-27)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-28">28/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-28)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-29">29/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-29)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-30">30/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-30)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-31">31/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-31)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-32">32/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-32)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-33">33/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-33)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-34">34/219</div>|:white_check_mark:*Pass*|`module-range-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-34)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-35">35/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-35)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-36">36/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-36)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-37">37/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-37)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-38">38/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-38)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-39">39/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-39)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-40">40/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-40)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-41">41/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-41)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-42">42/219</div>|:white_check_mark:*Pass*|`module-not-ql`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-42)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-43">43/219</div>|:white_check_mark:*Pass*|`module-not-el`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-43)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-44">44/219</div>|:white_check_mark:*Pass*|`module-not-el`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-44)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-45">45/219</div>|:white_check_mark:*Pass*|`module-not-el`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-45)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-46">46/219</div>|:white_check_mark:*Pass*|`module-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-46)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-47">47/219</div>|:white_check_mark:*Pass*|`module-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-47)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-48">48/219</div>|:white_check_mark:*Pass*|`module-not-el`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-48)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-49">49/219</div>|:white_check_mark:*Pass*|`module-not-el`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-49)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-50">50/219</div>|:white_check_mark:*Pass*|`module-not-el`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-50)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-51">51/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-51)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-52">52/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-52)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-53">53/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-53)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-54">54/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-54)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-55">55/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-55)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-56">56/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-56)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-57">57/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-57)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-58">58/219</div>|:white_check_mark:*Pass*|`module-inconsistent`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-58)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-59">59/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-59)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-60">60/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-60)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-61">61/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-61)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-62">62/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-62)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-63">63/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-63)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-64">64/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-64)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-65">65/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-65)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-66">66/219</div>|:white_check_mark:*Pass*|`module-domain-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-66)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-67">67/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-67)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-68">68/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-68)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-69">69/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-69)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-70">70/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-70)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-71">71/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-71)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-72">72/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-72)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-73">73/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-73)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-74">74/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-74)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-75">75/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-75)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-76">76/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-76)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-77">77/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-77)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-78">78/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-78)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-79">79/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-79)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-80">80/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-80)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-81">81/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-81)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-82">82/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-82)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-83">83/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-83)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-84">84/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-84)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-85">85/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-85)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-86">86/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-86)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-87">87/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-87)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-88">88/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-88)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-89">89/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-89)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-90">90/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-90)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-91">91/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-91)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-92">92/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-92)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-93">93/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-93)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-94">94/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-94)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-95">95/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-95)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-96">96/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-96)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-97">97/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-97)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-98">98/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-98)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-99">99/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-99)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-100">100/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-100)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-101">101/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-101)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-102">102/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-102)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-103">103/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-103)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-104">104/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-104)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-105">105/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-105)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-106">106/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-106)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-107">107/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-107)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-108">108/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-108)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-109">109/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-109)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-110">110/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-110)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-111">111/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-111)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-112">112/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-112)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-113">113/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-113)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-114">114/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-114)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-115">115/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-115)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-116">116/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-116)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-117">117/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-117)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-118">118/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-118)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-119">119/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-119)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-120">120/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-120)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-121">121/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-121)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-122">122/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-122)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-123">123/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-123)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-124">124/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-124)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-125">125/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-125)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-126">126/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-126)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-127">127/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-127)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-128">128/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-128)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-129">129/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-129)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-130">130/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-130)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-131">131/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-131)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-132">132/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-132)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-133">133/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-133)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-134">134/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-134)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-135">135/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-135)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-136">136/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-136)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-137">137/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-137)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-138">138/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-138)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-139">139/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-139)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-140">140/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-140)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-141">141/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-141)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-142">142/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-142)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-143">143/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-143)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-144">144/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-144)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-145">145/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-145)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-146">146/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-146)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-147">147/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-147)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-148">148/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-148)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-149">149/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-149)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-150">150/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-150)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-151">151/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-151)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-152">152/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-152)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-153">153/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-153)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-154">154/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-154)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-155">155/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-155)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-156">156/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-156)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-157">157/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-157)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-158">158/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-158)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-159">159/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-159)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-160">160/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-160)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-161">161/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-161)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-162">162/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-162)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-163">163/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-163)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-164">164/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-164)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-165">165/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-165)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-166">166/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-166)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-167">167/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-167)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-168">168/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-168)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-169">169/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-169)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-170">170/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-170)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-171">171/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-171)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-172">172/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-172)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-173">173/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-173)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-174">174/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-174)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-175">175/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-175)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-176">176/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-176)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-177">177/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-177)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-178">178/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-178)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-179">179/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-179)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-180">180/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-180)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-181">181/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-181)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-182">182/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-182)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-183">183/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-183)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-184">184/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-184)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-185">185/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-185)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-186">186/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-186)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-187">187/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-187)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-188">188/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-188)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-189">189/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-189)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-190">190/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-190)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-191">191/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-191)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-192">192/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-192)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-193">193/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-193)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-194">194/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-194)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-195">195/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-195)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-196">196/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-196)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-197">197/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-197)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-198">198/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-198)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-199">199/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-199)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-200">200/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-200)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-201">201/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-201)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-202">202/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-202)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-203">203/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-203)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-204">204/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-204)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-205">205/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-205)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-206">206/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-206)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-207">207/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-207)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-208">208/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-208)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-209">209/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-209)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-210">210/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-210)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-211">211/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-211)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-212">212/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-212)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-213">213/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-213)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-214">214/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-214)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-215">215/219</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-215)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-216">216/219</div>|:white_check_mark:*Pass*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-216)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-217">217/219</div>|:white_check_mark:*Pass*|`all-modules`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-217)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-218">218/219</div>|:white_check_mark:*Pass*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-218)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-219">219/219</div>|:white_check_mark:*Pass*|`all-fragments`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-219)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 3

[Jump to summary definition](#summary-Pass-3)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

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
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 7

[Jump to summary definition](#summary-Pass-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 8

[Jump to summary definition](#summary-Pass-8)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 9

[Jump to summary definition](#summary-Pass-9)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch refs/heads/main|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

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
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

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
### Pass Outcome number 12

[Jump to summary definition](#summary-Pass-12)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 13

[Jump to summary definition](#summary-Pass-13)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 14

[Jump to summary definition](#summary-Pass-14)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 16

[Jump to summary definition](#summary-Pass-16)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 17

[Jump to summary definition](#summary-Pass-17)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch refs/heads/main|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 18

[Jump to summary definition](#summary-Pass-18)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 19

[Jump to summary definition](#summary-Pass-19)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 20

[Jump to summary definition](#summary-Pass-20)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

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
### Pass Outcome number 21

[Jump to summary definition](#summary-Pass-21)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 22

[Jump to summary definition](#summary-Pass-22)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 23

[Jump to summary definition](#summary-Pass-23)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 24

[Jump to summary definition](#summary-Pass-24)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 25

[Jump to summary definition](#summary-Pass-25)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch refs/heads/main|
|Composition|- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 26

[Jump to summary definition](#summary-Pass-26)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 27

[Jump to summary definition](#summary-Pass-27)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 28

[Jump to summary definition](#summary-Pass-28)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

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
### Pass Outcome number 29

[Jump to summary definition](#summary-Pass-29)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 30

[Jump to summary definition](#summary-Pass-30)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 31

[Jump to summary definition](#summary-Pass-31)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 32

[Jump to summary definition](#summary-Pass-32)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 33

[Jump to summary definition](#summary-Pass-33)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 34

[Jump to summary definition](#summary-Pass-34)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch refs/heads/main|
|Composition|- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 35

[Jump to summary definition](#summary-Pass-35)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 36

[Jump to summary definition](#summary-Pass-36)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 37

[Jump to summary definition](#summary-Pass-37)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

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
### Pass Outcome number 38

[Jump to summary definition](#summary-Pass-38)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 39

[Jump to summary definition](#summary-Pass-39)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|Statement not supported|

***
### Pass Outcome number 40

[Jump to summary definition](#summary-Pass-40)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 41

[Jump to summary definition](#summary-Pass-41)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 42

[Jump to summary definition](#summary-Pass-42)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch refs/heads/main|
|Composition|- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 43

[Jump to summary definition](#summary-Pass-43)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 44

[Jump to summary definition](#summary-Pass-44)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 45

[Jump to summary definition](#summary-Pass-45)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

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
### Pass Outcome number 46

[Jump to summary definition](#summary-Pass-46)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 47

[Jump to summary definition](#summary-Pass-47)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 48

[Jump to summary definition](#summary-Pass-48)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 49

[Jump to summary definition](#summary-Pass-49)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 50

[Jump to summary definition](#summary-Pass-50)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch refs/heads/main|
|Composition|- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 51

[Jump to summary definition](#summary-Pass-51)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 52

[Jump to summary definition](#summary-Pass-52)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 53

[Jump to summary definition](#summary-Pass-53)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 54

[Jump to summary definition](#summary-Pass-54)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 55

[Jump to summary definition](#summary-Pass-55)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 56

[Jump to summary definition](#summary-Pass-56)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 57

[Jump to summary definition](#summary-Pass-57)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 58

[Jump to summary definition](#summary-Pass-58)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch refs/heads/main|
|Composition|- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 59

[Jump to summary definition](#summary-Pass-59)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 60

[Jump to summary definition](#summary-Pass-60)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

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
### Pass Outcome number 61

[Jump to summary definition](#summary-Pass-61)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 62

[Jump to summary definition](#summary-Pass-62)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 63

[Jump to summary definition](#summary-Pass-63)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 64

[Jump to summary definition](#summary-Pass-64)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 65

[Jump to summary definition](#summary-Pass-65)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 66

[Jump to summary definition](#summary-Pass-66)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch refs/heads/main|
|Composition|- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 67

[Jump to summary definition](#summary-Pass-67)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 68

[Jump to summary definition](#summary-Pass-68)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 69

[Jump to summary definition](#summary-Pass-69)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 70

[Jump to summary definition](#summary-Pass-70)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 71

[Jump to summary definition](#summary-Pass-71)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

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
### Pass Outcome number 72

[Jump to summary definition](#summary-Pass-72)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

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
### Pass Outcome number 73

[Jump to summary definition](#summary-Pass-73)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 74

[Jump to summary definition](#summary-Pass-74)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 75

[Jump to summary definition](#summary-Pass-75)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 76

[Jump to summary definition](#summary-Pass-76)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 77

[Jump to summary definition](#summary-Pass-77)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 78

[Jump to summary definition](#summary-Pass-78)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 79

[Jump to summary definition](#summary-Pass-79)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 80

[Jump to summary definition](#summary-Pass-80)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 81

[Jump to summary definition](#summary-Pass-81)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 82

[Jump to summary definition](#summary-Pass-82)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 83

[Jump to summary definition](#summary-Pass-83)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 84

[Jump to summary definition](#summary-Pass-84)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 85

[Jump to summary definition](#summary-Pass-85)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 86

[Jump to summary definition](#summary-Pass-86)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 87

[Jump to summary definition](#summary-Pass-87)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

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
### Pass Outcome number 88

[Jump to summary definition](#summary-Pass-88)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

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
### Pass Outcome number 89

[Jump to summary definition](#summary-Pass-89)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 90

[Jump to summary definition](#summary-Pass-90)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 91

[Jump to summary definition](#summary-Pass-91)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 92

[Jump to summary definition](#summary-Pass-92)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 93

[Jump to summary definition](#summary-Pass-93)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 94

[Jump to summary definition](#summary-Pass-94)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 95

[Jump to summary definition](#summary-Pass-95)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 96

[Jump to summary definition](#summary-Pass-96)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 97

[Jump to summary definition](#summary-Pass-97)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 98

[Jump to summary definition](#summary-Pass-98)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 99

[Jump to summary definition](#summary-Pass-99)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 100

[Jump to summary definition](#summary-Pass-100)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 101

[Jump to summary definition](#summary-Pass-101)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 102

[Jump to summary definition](#summary-Pass-102)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 103

[Jump to summary definition](#summary-Pass-103)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 104

[Jump to summary definition](#summary-Pass-104)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 105

[Jump to summary definition](#summary-Pass-105)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

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
### Pass Outcome number 106

[Jump to summary definition](#summary-Pass-106)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 107

[Jump to summary definition](#summary-Pass-107)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 108

[Jump to summary definition](#summary-Pass-108)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 109

[Jump to summary definition](#summary-Pass-109)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 110

[Jump to summary definition](#summary-Pass-110)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 111

[Jump to summary definition](#summary-Pass-111)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 112

[Jump to summary definition](#summary-Pass-112)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 113

[Jump to summary definition](#summary-Pass-113)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 114

[Jump to summary definition](#summary-Pass-114)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 115

[Jump to summary definition](#summary-Pass-115)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 116

[Jump to summary definition](#summary-Pass-116)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 117

[Jump to summary definition](#summary-Pass-117)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 118

[Jump to summary definition](#summary-Pass-118)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 119

[Jump to summary definition](#summary-Pass-119)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 120

[Jump to summary definition](#summary-Pass-120)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

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
### Pass Outcome number 121

[Jump to summary definition](#summary-Pass-121)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

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
### Pass Outcome number 122

[Jump to summary definition](#summary-Pass-122)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 123

[Jump to summary definition](#summary-Pass-123)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 124

[Jump to summary definition](#summary-Pass-124)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 125

[Jump to summary definition](#summary-Pass-125)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 126

[Jump to summary definition](#summary-Pass-126)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 127

[Jump to summary definition](#summary-Pass-127)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 128

[Jump to summary definition](#summary-Pass-128)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 129

[Jump to summary definition](#summary-Pass-129)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 130

[Jump to summary definition](#summary-Pass-130)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 131

[Jump to summary definition](#summary-Pass-131)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 132

[Jump to summary definition](#summary-Pass-132)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 133

[Jump to summary definition](#summary-Pass-133)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 134

[Jump to summary definition](#summary-Pass-134)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 135

[Jump to summary definition](#summary-Pass-135)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 136

[Jump to summary definition](#summary-Pass-136)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

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
### Pass Outcome number 137

[Jump to summary definition](#summary-Pass-137)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

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
### Pass Outcome number 138

[Jump to summary definition](#summary-Pass-138)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 139

[Jump to summary definition](#summary-Pass-139)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 140

[Jump to summary definition](#summary-Pass-140)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 141

[Jump to summary definition](#summary-Pass-141)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 142

[Jump to summary definition](#summary-Pass-142)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 143

[Jump to summary definition](#summary-Pass-143)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 144

[Jump to summary definition](#summary-Pass-144)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 145

[Jump to summary definition](#summary-Pass-145)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 146

[Jump to summary definition](#summary-Pass-146)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 147

[Jump to summary definition](#summary-Pass-147)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 148

[Jump to summary definition](#summary-Pass-148)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 149

[Jump to summary definition](#summary-Pass-149)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 150

[Jump to summary definition](#summary-Pass-150)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 151

[Jump to summary definition](#summary-Pass-151)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 152

[Jump to summary definition](#summary-Pass-152)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 153

[Jump to summary definition](#summary-Pass-153)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 154

[Jump to summary definition](#summary-Pass-154)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### Pass Outcome number 155

[Jump to summary definition](#summary-Pass-155)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### Pass Outcome number 156

[Jump to summary definition](#summary-Pass-156)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 157

[Jump to summary definition](#summary-Pass-157)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 158

[Jump to summary definition](#summary-Pass-158)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 159

[Jump to summary definition](#summary-Pass-159)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 160

[Jump to summary definition](#summary-Pass-160)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 161

[Jump to summary definition](#summary-Pass-161)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 162

[Jump to summary definition](#summary-Pass-162)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 163

[Jump to summary definition](#summary-Pass-163)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 164

[Jump to summary definition](#summary-Pass-164)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 165

[Jump to summary definition](#summary-Pass-165)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 166

[Jump to summary definition](#summary-Pass-166)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 167

[Jump to summary definition](#summary-Pass-167)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 168

[Jump to summary definition](#summary-Pass-168)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 169

[Jump to summary definition](#summary-Pass-169)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 170

[Jump to summary definition](#summary-Pass-170)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

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
### Pass Outcome number 171

[Jump to summary definition](#summary-Pass-171)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

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
### Pass Outcome number 172

[Jump to summary definition](#summary-Pass-172)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 173

[Jump to summary definition](#summary-Pass-173)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 174

[Jump to summary definition](#summary-Pass-174)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 175

[Jump to summary definition](#summary-Pass-175)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 176

[Jump to summary definition](#summary-Pass-176)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 177

[Jump to summary definition](#summary-Pass-177)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 178

[Jump to summary definition](#summary-Pass-178)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 179

[Jump to summary definition](#summary-Pass-179)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 180

[Jump to summary definition](#summary-Pass-180)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 181

[Jump to summary definition](#summary-Pass-181)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 182

[Jump to summary definition](#summary-Pass-182)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 183

[Jump to summary definition](#summary-Pass-183)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 184

[Jump to summary definition](#summary-Pass-184)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 185

[Jump to summary definition](#summary-Pass-185)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 186

[Jump to summary definition](#summary-Pass-186)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 187

[Jump to summary definition](#summary-Pass-187)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 188

[Jump to summary definition](#summary-Pass-188)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

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
### Pass Outcome number 189

[Jump to summary definition](#summary-Pass-189)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

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
### Pass Outcome number 190

[Jump to summary definition](#summary-Pass-190)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 191

[Jump to summary definition](#summary-Pass-191)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|Statement not supported|

***
### Pass Outcome number 192

[Jump to summary definition](#summary-Pass-192)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 193

[Jump to summary definition](#summary-Pass-193)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL EL Profile compatible|
|Description|Statement not supported|

***
### Pass Outcome number 194

[Jump to summary definition](#summary-Pass-194)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 195

[Jump to summary definition](#summary-Pass-195)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 196

[Jump to summary definition](#summary-Pass-196)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 197

[Jump to summary definition](#summary-Pass-197)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 198

[Jump to summary definition](#summary-Pass-198)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 199

[Jump to summary definition](#summary-Pass-199)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 200

[Jump to summary definition](#summary-Pass-200)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 201

[Jump to summary definition](#summary-Pass-201)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Domains properly defined|
|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 202

[Jump to summary definition](#summary-Pass-202)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 203

[Jump to summary definition](#summary-Pass-203)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|All terms labeled|
|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 204

[Jump to summary definition](#summary-Pass-204)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

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
### Pass Outcome number 205

[Jump to summary definition](#summary-Pass-205)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

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
### Pass Outcome number 206

[Jump to summary definition](#summary-Pass-206)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 207

[Jump to summary definition](#summary-Pass-207)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 208

[Jump to summary definition](#summary-Pass-208)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 209

[Jump to summary definition](#summary-Pass-209)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL QL Profile compatible|
|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 210

[Jump to summary definition](#summary-Pass-210)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 211

[Jump to summary definition](#summary-Pass-211)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Any term is referenced|
|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 212

[Jump to summary definition](#summary-Pass-212)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 213

[Jump to summary definition](#summary-Pass-213)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Terms differenciated enough|
|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 214

[Jump to summary definition](#summary-Pass-214)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 215

[Jump to summary definition](#summary-Pass-215)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch refs/heads/main|
|Composition|- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 216

[Jump to summary definition](#summary-Pass-216)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 217

[Jump to summary definition](#summary-Pass-217)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***
### Pass Outcome number 218

[Jump to summary definition](#summary-Pass-218)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|OWL RL Profile compatible|
|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 219

[Jump to summary definition](#summary-Pass-219)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Type|:white_check_mark:Pass|
|----|----|
|Title|Test  passed|
|Description|The custom test  passed|

***

</details>

***
