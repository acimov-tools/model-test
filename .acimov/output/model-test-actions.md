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
|Date|2024-05-21 14:30:48|

***


# Statistic summary

Here is a short overview for this test report

233 Outcomes

:boom:33 MajorFail, :exclamation:19 MinorFail, :warning:0 CannotTell, :grey_question:36 NotTested, :white_check_mark:145 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="14%" height="25px"/><img src="../assets/orange.png" width="8%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="15%" height="25px"/><img src="../assets/green.png" width="63%" height="25px"/></div>

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

:boom:33 MajorFail outcomes

<details>
<summary>Fold/Unfold the 33 summary and details</summary>

## MajorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:boom:33 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-1">1/33</div>|:boom:*MajorFail*|`module-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-2">2/33</div>|:boom:*MajorFail*|`module-unknown-prefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-2)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-3">3/33</div>|:boom:*MajorFail*|`module-too-close-terms`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-3)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-4">4/33</div>|:boom:*MajorFail*|`module-range-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-4)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-5">5/33</div>|:boom:*MajorFail*|`module-not-ql`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-6">6/33</div>|:boom:*MajorFail*|`module-not-el`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-6)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-7">7/33</div>|:boom:*MajorFail*|`module-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-7)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-8">8/33</div>|:boom:*MajorFail*|`module-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-8)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-9">9/33</div>|:boom:*MajorFail*|`module-inconsistent`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-9)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-10">10/33</div>|:boom:*MajorFail*|`module-domain-outer`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-10)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-11">11/33</div>|:boom:*MajorFail*|`module-domain-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-11)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-12">12/33</div>|:boom:*MajorFail*|`module-broken`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-12)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-13">13/33</div>|:boom:*MajorFail*|`modelet-zedomain-syntax`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-13)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-14">14/33</div>|:boom:*MajorFail*|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-14)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-15">15/33</div>|:boom:*MajorFail*|`modelet-zedomain-prefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-15)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-16">16/33</div>|:boom:*MajorFail*|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-16)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-17">17/33</div>|:boom:*MajorFail*|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-17)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-18">18/33</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-18)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-19">19/33</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-19)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-20">20/33</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-20)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-21">21/33</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-21)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-22">22/33</div>|:boom:*MajorFail*|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-22)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-23">23/33</div>|:boom:*MajorFail*|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-23)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-24">24/33</div>|:boom:*MajorFail*|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-24)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-25">25/33</div>|:boom:*MajorFail*|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-25)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-26">26/33</div>|:boom:*MajorFail*|`all-modules`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-26)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-27">27/33</div>|:boom:*MajorFail*|`all-modules`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-27)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-28">28/33</div>|:boom:*MajorFail*|`all-modules`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-28)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-29">29/33</div>|:boom:*MajorFail*|`all-modules`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-29)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-30">30/33</div>|:boom:*MajorFail*|`all-fragments`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-30)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-31">31/33</div>|:boom:*MajorFail*|`all-fragments`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-31)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-32">32/33</div>|:boom:*MajorFail*|`all-fragments`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-32)|
|[Table top](#majorfail-outcomes-summary)|<div id="summary-MajorFail-33">33/33</div>|:boom:*MajorFail*|`all-fragments`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-33)|

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:5651f6f9-dff5-40ee-8103-02c23bb45e06> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b1347 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:e9e87962-23c3-454c-8579-00d342f98eb1> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b2693 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b17bffca-eef5-4c85-a2ba-a2b772e3c704> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b2693 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b185f998-646c-473a-bc65-1edd09774515> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b6731 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:83c6cf84-b14a-4b40-8cf0-f68533be1caf> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b9423 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:f0cffa76-3467-4674-b05f-b370183c4a91> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b5385 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ca0ae8f7-a6a7-4c1a-996b-3a949b9e68da> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10778 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:166c47a3-fadb-4fad-8fca-1743227be300> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10778 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:743324da-04b2-4f23-b1ac-bab4c05cef8f> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10778 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:8b483aa7-16ba-472d-9354-37bd46c46944> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b4039 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:62bebe51-d965-48f6-96bf-fb72cdda1118> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b12124 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 15

[Jump to summary definition](#summary-MajorFail-15)

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
### MajorFail Outcome number 16

[Jump to summary definition](#summary-MajorFail-16)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:50f01916-c583-47d0-90eb-776b74d8fa84> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b21546 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 17

[Jump to summary definition](#summary-MajorFail-17)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b985b4b5-d192-4a4f-95b5-26a2b4fe88e2> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14816 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:0487ec92-1689-481e-9181-b8b08fc2681d> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14816 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d339b2f0-6c95-4baa-843b-c6b6b6d74d35> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14816 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|

***
### MajorFail Outcome number 18

[Jump to summary definition](#summary-MajorFail-18)

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
### MajorFail Outcome number 19

[Jump to summary definition](#summary-MajorFail-19)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:23c4b751-e1c9-4d41-bf21-0a8cb0b6d50e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b18854 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 20

[Jump to summary definition](#summary-MajorFail-20)

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
### MajorFail Outcome number 21

[Jump to summary definition](#summary-MajorFail-21)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a0c8d8d3-8240-4dc3-b8e4-81970f872a15> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b13470 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 22

[Jump to summary definition](#summary-MajorFail-22)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:92ca2d77-c28d-42e0-9dae-964838542d38> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b22892 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:f0ff2afa-027b-4217-87e1-eb1664600361> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b22892 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 23

[Jump to summary definition](#summary-MajorFail-23)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6f20c93e-bdf5-421c-9694-f0a1bcd3a8fe> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b17508 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***
### MajorFail Outcome number 24

[Jump to summary definition](#summary-MajorFail-24)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d6d371ff-0f0e-472a-a146-59a59c7bb5aa> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b16162 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 25

[Jump to summary definition](#summary-MajorFail-25)

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2b2db02d-67db-49ea-9dc0-f45a5228c057> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b20200 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***
### MajorFail Outcome number 26

[Jump to summary definition](#summary-MajorFail-26)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### MajorFail Outcome number 27

[Jump to summary definition](#summary-MajorFail-27)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### MajorFail Outcome number 28

[Jump to summary definition](#summary-MajorFail-28)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### MajorFail Outcome number 29

[Jump to summary definition](#summary-MajorFail-29)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:9fdc928c-6e3e-456a-aef3-2a6af99e142c> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:967f65e6-c57b-484f-9b05-9ee8f438de25> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:151fe766-c6e3-4dd9-bc5d-d337feb8d684> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6b480861-78be-42c2-b54f-952d612b2e53> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:788a1bb2-4ef5-4732-a41f-541af4f16b7a> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:385d335f-f029-47fa-aa7d-6aace779386f> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:00e6bd4e-6eb4-4288-a1e2-351547717202> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6114c2f9-f9c1-4fb6-affc-c32b2114ef2a> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a3b816d8-e039-4fc5-bfa9-d00cb600f320> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:3a198ca9-5e43-4c91-8d17-1eed4b9237cb> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:4ebdcf02-5a82-4cbc-9de9-07a6544aded7> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24247 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|

***
### MajorFail Outcome number 30

[Jump to summary definition](#summary-MajorFail-30)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MajorFail Outcome number 31

[Jump to summary definition](#summary-MajorFail-31)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MajorFail Outcome number 32

[Jump to summary definition](#summary-MajorFail-32)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MajorFail Outcome number 33

[Jump to summary definition](#summary-MajorFail-33)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:675085e8-85c2-4086-b606-e2ddf941a26a> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6a7efe8a-0f8b-40a5-9be9-d593a9c6fb45> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a8f549b4-cf0e-4ad7-a165-adaf537e8d8f> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:25005caa-ab3b-4d6c-b663-6714cb439daa> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b366b8f5-b958-40c2-947f-6a666a4b1861> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:41c243da-c2ad-4919-b67a-2a7c6f770a38> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a125ff5b-d281-4a7f-ae97-45d8457e9837> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:8dd996ed-5559-4137-aada-b9cab1c92772> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:9d47d939-2e74-48db-a311-aa1458f2b3e0> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2ed183c1-914f-426a-b66b-8809f29d9a12> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|
|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:c539ff15-c281-417b-99bc-5bee6d479d2e> rdf:type sh:ValidationResult ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25602 ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,&#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;&#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***

</details>

***


# MinorFail Outcomes

Here is the chapter related to the MinorFail outcome

:exclamation:19 MinorFail outcomes

<details>
<summary>Fold/Unfold the 19 summary and details</summary>

## MinorFail Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:exclamation:19 MinorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-1">1/19</div>|:exclamation:*MinorFail*|`module-unreferenced`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-1)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-2">2/19</div>|:exclamation:*MinorFail*|`module-unlabeled`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-2)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-3">3/19</div>|:exclamation:*MinorFail*|`module-too-close-terms`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-3)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-4">4/19</div>|:exclamation:*MinorFail*|`module-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-4)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-5">5/19</div>|:exclamation:*MinorFail*|`module-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-5)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-6">6/19</div>|:exclamation:*MinorFail*|`modelet-zedomain-label`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-6)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-7">7/19</div>|:exclamation:*MinorFail*|`modelet-zedomain-differenciation`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-7)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-8">8/19</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-8)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-9">9/19</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-9)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-10">10/19</div>|:exclamation:*MinorFail*|`all-modules`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-10)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-11">11/19</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-11)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-12">12/19</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-12)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-13">13/19</div>|:exclamation:*MinorFail*|`all-modules`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-13)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-14">14/19</div>|:exclamation:*MinorFail*|`all-modules`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-14)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-15">15/19</div>|:exclamation:*MinorFail*|`all-fragments`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-15)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-16">16/19</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-16)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-17">17/19</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-17)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-18">18/19</div>|:exclamation:*MinorFail*|`all-fragments`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-18)|
|[Table top](#minorfail-outcomes-summary)|<div id="summary-MinorFail-19">19/19</div>|:exclamation:*MinorFail*|`all-fragments`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-19)|

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
### MinorFail Outcome number 8

[Jump to summary definition](#summary-MinorFail-8)

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
### MinorFail Outcome number 9

[Jump to summary definition](#summary-MinorFail-9)

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
### MinorFail Outcome number 10

[Jump to summary definition](#summary-MinorFail-10)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### MinorFail Outcome number 11

[Jump to summary definition](#summary-MinorFail-11)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### MinorFail Outcome number 14

[Jump to summary definition](#summary-MinorFail-14)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### MinorFail Outcome number 15

[Jump to summary definition](#summary-MinorFail-15)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MinorFail Outcome number 16

[Jump to summary definition](#summary-MinorFail-16)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MinorFail Outcome number 17

[Jump to summary definition](#summary-MinorFail-17)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MinorFail Outcome number 18

[Jump to summary definition](#summary-MinorFail-18)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### MinorFail Outcome number 19

[Jump to summary definition](#summary-MinorFail-19)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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

:white_check_mark:145 Pass outcomes

<details>
<summary>Fold/Unfold the 145 summary and details</summary>

## Pass Outcomes Summary

[Jump to statistic summary](#statistic-summary)

:white_check_mark:145 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-1">1/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-1)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-2">2/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-2)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-3">3/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-3)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-4">4/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-4)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-5">5/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-5)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-6">6/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-6)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-7">7/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-7)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-8">8/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-8)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-9">9/145</div>|:white_check_mark:*Pass*|`module-unreferenced`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-9)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-10">10/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-10)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-11">11/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-11)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-12">12/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-12)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-13">13/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-13)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-14">14/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-14)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-15">15/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-15)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-16">16/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-16)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-17">17/145</div>|:white_check_mark:*Pass*|`module-unlabeled`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-17)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-18">18/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-18)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-19">19/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-19)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-20">20/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-20)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-21">21/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-21)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-22">22/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-22)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-23">23/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-23)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-24">24/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-24)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-25">25/145</div>|:white_check_mark:*Pass*|`module-too-close-terms`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-25)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-26">26/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-26)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-27">27/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-27)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-28">28/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-28)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-29">29/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-29)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-30">30/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-30)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-31">31/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-31)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-32">32/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-32)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-33">33/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-33)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-34">34/145</div>|:white_check_mark:*Pass*|`module-range-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-34)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-35">35/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-35)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-36">36/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-36)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-37">37/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-37)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-38">38/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-38)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-39">39/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-39)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-40">40/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-40)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-41">41/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-41)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-42">42/145</div>|:white_check_mark:*Pass*|`module-not-ql`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-42)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-43">43/145</div>|:white_check_mark:*Pass*|`module-not-el`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-43)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-44">44/145</div>|:white_check_mark:*Pass*|`module-not-el`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-44)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-45">45/145</div>|:white_check_mark:*Pass*|`module-not-el`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-45)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-46">46/145</div>|:white_check_mark:*Pass*|`module-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-46)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-47">47/145</div>|:white_check_mark:*Pass*|`module-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-47)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-48">48/145</div>|:white_check_mark:*Pass*|`module-not-el`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-48)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-49">49/145</div>|:white_check_mark:*Pass*|`module-not-el`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-49)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-50">50/145</div>|:white_check_mark:*Pass*|`module-not-el`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-50)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-51">51/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-51)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-52">52/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-52)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-53">53/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-53)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-54">54/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-54)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-55">55/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-55)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-56">56/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-56)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-57">57/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-57)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-58">58/145</div>|:white_check_mark:*Pass*|`module-inconsistent`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-58)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-59">59/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-59)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-60">60/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-60)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-61">61/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-61)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-62">62/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-62)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-63">63/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-63)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-64">64/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-64)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-65">65/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-65)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-66">66/145</div>|:white_check_mark:*Pass*|`module-domain-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-66)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-67">67/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-67)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-68">68/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-68)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-69">69/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-69)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-70">70/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-70)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-71">71/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-71)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-72">72/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-72)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-73">73/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-73)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-74">74/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-74)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-75">75/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-75)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-76">76/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-76)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-77">77/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-77)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-78">78/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-78)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-79">79/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-79)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-80">80/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-80)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-81">81/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-81)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-82">82/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-82)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-83">83/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-83)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-84">84/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-84)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-85">85/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-85)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-86">86/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-86)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-87">87/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-87)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-88">88/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-88)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-89">89/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-89)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-90">90/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-90)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-91">91/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-91)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-92">92/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-92)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-93">93/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-93)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-94">94/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-94)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-95">95/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-95)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-96">96/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-96)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-97">97/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-97)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-98">98/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-98)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-99">99/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-99)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-100">100/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-100)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-101">101/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-101)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-102">102/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-102)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-103">103/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-103)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-104">104/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-104)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-105">105/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-105)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-106">106/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-106)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-107">107/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-107)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-108">108/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-108)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-109">109/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-109)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-110">110/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-110)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-111">111/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-111)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-112">112/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-112)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-113">113/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-113)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-114">114/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-114)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-115">115/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-115)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-116">116/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-116)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-117">117/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-117)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-118">118/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-118)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-119">119/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-119)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-120">120/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-120)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-121">121/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-121)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-122">122/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-122)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-123">123/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-123)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-124">124/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-124)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-125">125/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-125)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-126">126/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-126)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-127">127/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-127)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-128">128/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-128)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-129">129/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-129)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-130">130/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-130)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-131">131/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-131)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-132">132/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-132)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-133">133/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-133)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-134">134/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-134)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-135">135/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-135)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-136">136/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-136)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-137">137/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-137)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-138">138/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-138)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-139">139/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-139)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-140">140/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-140)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-141">141/145</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-141)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-142">142/145</div>|:white_check_mark:*Pass*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-142)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-143">143/145</div>|:white_check_mark:*Pass*|`all-modules`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-143)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-144">144/145</div>|:white_check_mark:*Pass*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-144)|
|[Table top](#pass-outcomes-summary)|<div id="summary-Pass-145">145/145</div>|:white_check_mark:*Pass*|`all-fragments`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/refs/heads/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-145)|

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
### Pass Outcome number 69

[Jump to summary definition](#summary-Pass-69)

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
### Pass Outcome number 70

[Jump to summary definition](#summary-Pass-70)

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
### Pass Outcome number 71

[Jump to summary definition](#summary-Pass-71)

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
### Pass Outcome number 72

[Jump to summary definition](#summary-Pass-72)

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
### Pass Outcome number 73

[Jump to summary definition](#summary-Pass-73)

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
### Pass Outcome number 74

[Jump to summary definition](#summary-Pass-74)

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
### Pass Outcome number 75

[Jump to summary definition](#summary-Pass-75)

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
### Pass Outcome number 76

[Jump to summary definition](#summary-Pass-76)

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
### Pass Outcome number 77

[Jump to summary definition](#summary-Pass-77)

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
### Pass Outcome number 78

[Jump to summary definition](#summary-Pass-78)

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
### Pass Outcome number 79

[Jump to summary definition](#summary-Pass-79)

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
### Pass Outcome number 80

[Jump to summary definition](#summary-Pass-80)

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
### Pass Outcome number 81

[Jump to summary definition](#summary-Pass-81)

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
### Pass Outcome number 82

[Jump to summary definition](#summary-Pass-82)

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
### Pass Outcome number 83

[Jump to summary definition](#summary-Pass-83)

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
### Pass Outcome number 84

[Jump to summary definition](#summary-Pass-84)

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
### Pass Outcome number 85

[Jump to summary definition](#summary-Pass-85)

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
### Pass Outcome number 86

[Jump to summary definition](#summary-Pass-86)

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
### Pass Outcome number 87

[Jump to summary definition](#summary-Pass-87)

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
### Pass Outcome number 88

[Jump to summary definition](#summary-Pass-88)

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
### Pass Outcome number 89

[Jump to summary definition](#summary-Pass-89)

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
### Pass Outcome number 90

[Jump to summary definition](#summary-Pass-90)

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
### Pass Outcome number 91

[Jump to summary definition](#summary-Pass-91)

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
### Pass Outcome number 92

[Jump to summary definition](#summary-Pass-92)

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
### Pass Outcome number 93

[Jump to summary definition](#summary-Pass-93)

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
### Pass Outcome number 94

[Jump to summary definition](#summary-Pass-94)

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
### Pass Outcome number 95

[Jump to summary definition](#summary-Pass-95)

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
### Pass Outcome number 96

[Jump to summary definition](#summary-Pass-96)

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
### Pass Outcome number 97

[Jump to summary definition](#summary-Pass-97)

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
### Pass Outcome number 98

[Jump to summary definition](#summary-Pass-98)

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
### Pass Outcome number 99

[Jump to summary definition](#summary-Pass-99)

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
### Pass Outcome number 100

[Jump to summary definition](#summary-Pass-100)

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
### Pass Outcome number 101

[Jump to summary definition](#summary-Pass-101)

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
### Pass Outcome number 102

[Jump to summary definition](#summary-Pass-102)

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
### Pass Outcome number 103

[Jump to summary definition](#summary-Pass-103)

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
### Pass Outcome number 104

[Jump to summary definition](#summary-Pass-104)

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
### Pass Outcome number 105

[Jump to summary definition](#summary-Pass-105)

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
### Pass Outcome number 106

[Jump to summary definition](#summary-Pass-106)

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
### Pass Outcome number 107

[Jump to summary definition](#summary-Pass-107)

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
### Pass Outcome number 108

[Jump to summary definition](#summary-Pass-108)

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
### Pass Outcome number 109

[Jump to summary definition](#summary-Pass-109)

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
### Pass Outcome number 110

[Jump to summary definition](#summary-Pass-110)

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
### Pass Outcome number 111

[Jump to summary definition](#summary-Pass-111)

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
### Pass Outcome number 112

[Jump to summary definition](#summary-Pass-112)

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
### Pass Outcome number 113

[Jump to summary definition](#summary-Pass-113)

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
### Pass Outcome number 114

[Jump to summary definition](#summary-Pass-114)

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
### Pass Outcome number 115

[Jump to summary definition](#summary-Pass-115)

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
### Pass Outcome number 116

[Jump to summary definition](#summary-Pass-116)

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
### Pass Outcome number 117

[Jump to summary definition](#summary-Pass-117)

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
### Pass Outcome number 118

[Jump to summary definition](#summary-Pass-118)

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
### Pass Outcome number 119

[Jump to summary definition](#summary-Pass-119)

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
### Pass Outcome number 120

[Jump to summary definition](#summary-Pass-120)

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
### Pass Outcome number 121

[Jump to summary definition](#summary-Pass-121)

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
### Pass Outcome number 122

[Jump to summary definition](#summary-Pass-122)

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
### Pass Outcome number 123

[Jump to summary definition](#summary-Pass-123)

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
### Pass Outcome number 124

[Jump to summary definition](#summary-Pass-124)

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
### Pass Outcome number 125

[Jump to summary definition](#summary-Pass-125)

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
### Pass Outcome number 126

[Jump to summary definition](#summary-Pass-126)

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
### Pass Outcome number 127

[Jump to summary definition](#summary-Pass-127)

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
### Pass Outcome number 128

[Jump to summary definition](#summary-Pass-128)

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
### Pass Outcome number 129

[Jump to summary definition](#summary-Pass-129)

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
### Pass Outcome number 130

[Jump to summary definition](#summary-Pass-130)

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
### Pass Outcome number 131

[Jump to summary definition](#summary-Pass-131)

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
### Pass Outcome number 132

[Jump to summary definition](#summary-Pass-132)

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
### Pass Outcome number 133

[Jump to summary definition](#summary-Pass-133)

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
### Pass Outcome number 134

[Jump to summary definition](#summary-Pass-134)

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
### Pass Outcome number 135

[Jump to summary definition](#summary-Pass-135)

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
### Pass Outcome number 136

[Jump to summary definition](#summary-Pass-136)

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
### Pass Outcome number 137

[Jump to summary definition](#summary-Pass-137)

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
### Pass Outcome number 138

[Jump to summary definition](#summary-Pass-138)

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
### Pass Outcome number 139

[Jump to summary definition](#summary-Pass-139)

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
### Pass Outcome number 140

[Jump to summary definition](#summary-Pass-140)

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
### Pass Outcome number 141

[Jump to summary definition](#summary-Pass-141)

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
### Pass Outcome number 142

[Jump to summary definition](#summary-Pass-142)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### Pass Outcome number 143

[Jump to summary definition](#summary-Pass-143)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)|

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
### Pass Outcome number 144

[Jump to summary definition](#summary-Pass-144)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
### Pass Outcome number 145

[Jump to summary definition](#summary-Pass-145)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch refs/heads/main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module unlabeled.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unlabeled.ttl)<br/>- [Module too-close-terms.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/too-close-terms.ttl)<br/>- [Module domain-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/domain-outer.ttl)<br/>- [Module not-rl.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-rl.ttl)<br/>- [Module not-el.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-el.ttl)<br/>- [Module range-outer.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/range-outer.ttl)<br/>- [Module unreferenced.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/unreferenced.ttl)<br/>- [Module not-ql.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/not-ql.ttl)<br/>- [Module inconsistent.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/rangeout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/domainout/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatQL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/label/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/differenciation/onto.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/domains/zedomain/differenciation/onto.ttl)|

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
