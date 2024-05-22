# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./model-test-manual-NicoRobertIn-2024-05-22T16-45-32.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using manual script|
|Description|Test triggered by [@NicoRobertIn](https://github.com/NicoRobertIn) by manual trigger|
|Script|[model test suite](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/suite.py)
|Date|2024-05-22 16:45:26|

***


# Statistic summary

Here is a short overview for this test report

342 Outcomes

:boom:47 MajorFail, :exclamation:23 MinorFail, :warning:0 CannotTell, :grey_question:44 NotTested, :white_check_mark:228 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="13%" height="25px"/><img src="../assets/orange.png" width="6%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="12%" height="25px"/><img src="../assets/green.png" width="69%" height="25px"/></div>

<br/>

The different status types are an extension of the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary where the nextended terms can be found in the [olivaw-earl dataset](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/olivaw-earl.ttl), each outcome type means:
* :boom: MajorFail: This is an error that is critical and consider as blocking for production
* :exclamation: MinorFail: This is an error that should be fixed, but it is cannot be considered as critical error
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	Previous section	|	[Next section](#minorfail-outcomes)

Here is the chapter related to the MajorFail outcome

:boom:47 MajorFail outcomes

<details>
<summary>Fold/Unfold the 47 summary and details</summary>

## MajorFail Outcomes Summary

:boom:47 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-1">1/47</div>|:boom:*MajorFail*|`module-src-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-2">2/47</div>|:boom:*MajorFail*|`module-src-unknown-prefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-2)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-3">3/47</div>|:boom:*MajorFail*|`module-src-too-close-terms`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-3)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-4">4/47</div>|:boom:*MajorFail*|`module-src-range-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-4)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-5">5/47</div>|:boom:*MajorFail*|`module-src-not-rl`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-6">6/47</div>|:boom:*MajorFail*|`module-src-not-ql`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-6)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-7">7/47</div>|:boom:*MajorFail*|`module-src-not-el`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-7)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-8">8/47</div>|:boom:*MajorFail*|`module-src-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-8)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-9">9/47</div>|:boom:*MajorFail*|`module-src-inconsistent`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-9)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-10">10/47</div>|:boom:*MajorFail*|`module-src-inconsistent`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-10)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-11">11/47</div>|:boom:*MajorFail*|`module-src-domain-outer`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-11)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-12">12/47</div>|:boom:*MajorFail*|`module-src-domain-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-12)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-13">13/47</div>|:boom:*MajorFail*|`module-src-broken`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-13)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-14">14/47</div>|:boom:*MajorFail*|`modelet-zedomain-syntax`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-14)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-15">15/47</div>|:boom:*MajorFail*|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-15)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-16">16/47</div>|:boom:*MajorFail*|`modelet-zedomain-prefix`|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-16)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-17">17/47</div>|:boom:*MajorFail*|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-17)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-18">18/47</div>|:boom:*MajorFail*|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-18)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-19">19/47</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-19)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-20">20/47</div>|:boom:*MajorFail*|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-20)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-21">21/47</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-21)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-22">22/47</div>|:boom:*MajorFail*|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-22)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-23">23/47</div>|:boom:*MajorFail*|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-23)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-24">24/47</div>|:boom:*MajorFail*|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-24)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-25">25/47</div>|:boom:*MajorFail*|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-25)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-26">26/47</div>|:boom:*MajorFail*|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-26)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-27">27/47</div>|:boom:*MajorFail*|`all-modules`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-27)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-28">28/47</div>|:boom:*MajorFail*|`all-modules`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-28)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-29">29/47</div>|:boom:*MajorFail*|`all-modules`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-29)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-30">30/47</div>|:boom:*MajorFail*|`all-modules`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-30)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-31">31/47</div>|:boom:*MajorFail*|`all-fragments`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-31)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-32">32/47</div>|:boom:*MajorFail*|`all-fragments`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-32)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-33">33/47</div>|:boom:*MajorFail*|`all-fragments`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-33)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-34">34/47</div>|:boom:*MajorFail*|`all-fragments`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-34)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-35">35/47</div>|:boom:*MajorFail*|`-modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-35)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-36">36/47</div>|:boom:*MajorFail*|`-modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-36)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-37">37/47</div>|:boom:*MajorFail*|`-modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-37)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-38">38/47</div>|:boom:*MajorFail*|`-modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-38)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-39">39/47</div>|:boom:*MajorFail*|`-modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-39)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-40">40/47</div>|:boom:*MajorFail*|`-modelet-zedomain-dovrov`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-40)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-41">41/47</div>|:boom:*MajorFail*|`-modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-41)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-42">42/47</div>|:boom:*MajorFail*|`-modelet-zedomain-domainout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-42)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-43">43/47</div>|:boom:*MajorFail*|`-modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-43)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-44">44/47</div>|:boom:*MajorFail*|`-modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-44)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-45">45/47</div>|:boom:*MajorFail*|`-modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-45)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-46">46/47</div>|:boom:*MajorFail*|`-modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-46)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-47">47/47</div>|:boom:*MajorFail*|`-modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-47)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)	|	Previous MajorFail outcome	|	[Next MajorFail outcome](#majorfail-outcome-number-2)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-1)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-1)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-1)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d6f25952-e79b-4882-9ee3-66cb922edb66> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b10778 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)	|	[Previous MajorFail outcome](#majorfail-outcome-number-1)	|	[Next MajorFail outcome](#majorfail-outcome-number-3)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-2)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-2)|Title|Test subject has syntax errors|
|[Section top](#majorfail-outcome-number-2)|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>at line 3 of &#60;>:  &#10;Bad syntax (Prefix &#34;owl:&#34; not bound) at &Hat; in:  &#10;&#34;...b'x : &#60;https://www.example.org/olivaw/> .&#92;r&#92;n&#92;r&#92;n:unknownPrefix a '&Hat;b'owl:Ontology .&#92;r&#92;n&#92;r&#92;n:Unknown a owl:Class ;&#92;r&#92;n&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;Th'...&#34;</code></pre>|

***
### MajorFail Outcome number 3

[Jump to summary definition](#summary-MajorFail-3)	|	[Previous MajorFail outcome](#majorfail-outcome-number-2)	|	[Next MajorFail outcome](#majorfail-outcome-number-4)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-3)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-3)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-3)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:90d77c43-f2f5-4f36-860d-f21f8a606f12> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b9432 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:146da366-d89f-4472-a4ab-d6c622337cc6> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b9432 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)	|	[Previous MajorFail outcome](#majorfail-outcome-number-3)	|	[Next MajorFail outcome](#majorfail-outcome-number-5)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-4)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-4)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-4)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:436e88c8-8e34-4abe-b023-a866e5500aa6> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b8086 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)	|	[Previous MajorFail outcome](#majorfail-outcome-number-4)	|	[Next MajorFail outcome](#majorfail-outcome-number-6)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-5)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-5)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-5)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d93eda38-1c8f-4d23-9514-c6c0c1fa0da8> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b6740 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***
### MajorFail Outcome number 6

[Jump to summary definition](#summary-MajorFail-6)	|	[Previous MajorFail outcome](#majorfail-outcome-number-5)	|	[Next MajorFail outcome](#majorfail-outcome-number-7)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-6)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-6)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-6)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:fe85fb8c-e963-4e50-869b-c3cf6e958af1> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b5394 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 7

[Jump to summary definition](#summary-MajorFail-7)	|	[Previous MajorFail outcome](#majorfail-outcome-number-6)	|	[Next MajorFail outcome](#majorfail-outcome-number-8)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-7)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-7)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-7)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2f6cad65-2bc2-41e5-bca2-5ae1daaa7e0f> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b4048 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***
### MajorFail Outcome number 8

[Jump to summary definition](#summary-MajorFail-8)	|	[Previous MajorFail outcome](#majorfail-outcome-number-7)	|	[Next MajorFail outcome](#majorfail-outcome-number-9)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-8)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-8)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-8)|Description|http://www.w3.org/2002/07/owl#disjointWith  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;  &#10;|

***
### MajorFail Outcome number 9

[Jump to summary definition](#summary-MajorFail-9)	|	[Previous MajorFail outcome](#majorfail-outcome-number-8)	|	[Next MajorFail outcome](#majorfail-outcome-number-10)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-9)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-9)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-9)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;  &#10;|

***
### MajorFail Outcome number 10

[Jump to summary definition](#summary-MajorFail-10)	|	[Previous MajorFail outcome](#majorfail-outcome-number-9)	|	[Next MajorFail outcome](#majorfail-outcome-number-11)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-10)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-10)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-10)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:31b279e9-66eb-47ba-9610-0330db6538bc> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b2702 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:25073b04-2165-44a0-a927-27871cfb9027> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b2702 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent .</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a43479bc-e16d-433f-bead-48437ac10533> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b2702 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|

***
### MajorFail Outcome number 11

[Jump to summary definition](#summary-MajorFail-11)	|	[Previous MajorFail outcome](#majorfail-outcome-number-10)	|	[Next MajorFail outcome](#majorfail-outcome-number-12)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-11)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-11)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-11)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-11)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 12

[Jump to summary definition](#summary-MajorFail-12)	|	[Previous MajorFail outcome](#majorfail-outcome-number-11)	|	[Next MajorFail outcome](#majorfail-outcome-number-13)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-12)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-12)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-12)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:116f7d39-0591-46d0-a821-88b56c2151bf> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b1347 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 13

[Jump to summary definition](#summary-MajorFail-13)	|	[Previous MajorFail outcome](#majorfail-outcome-number-12)	|	[Next MajorFail outcome](#majorfail-outcome-number-14)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-13)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-13)|Title|Test subject has syntax errors|
|[Section top](#majorfail-outcome-number-13)|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|[Section top](#majorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>Encountered &#34;a&#34; at line 9, column 23.</code></pre>|

***
### MajorFail Outcome number 14

[Jump to summary definition](#summary-MajorFail-14)	|	[Previous MajorFail outcome](#majorfail-outcome-number-13)	|	[Next MajorFail outcome](#majorfail-outcome-number-15)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-14)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-14)|Title|Test subject has syntax errors|
|[Section top](#majorfail-outcome-number-14)|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|[Section top](#majorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>Encountered &#34;a&#34; at line 7, column 23.</code></pre>|

***
### MajorFail Outcome number 15

[Jump to summary definition](#summary-MajorFail-15)	|	[Previous MajorFail outcome](#majorfail-outcome-number-14)	|	[Next MajorFail outcome](#majorfail-outcome-number-16)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-15)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-15)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-15)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:1d14538e-80e1-42d2-8d71-ab37ad818381> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b35015 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 16

[Jump to summary definition](#summary-MajorFail-16)	|	[Previous MajorFail outcome](#majorfail-outcome-number-15)	|	[Next MajorFail outcome](#majorfail-outcome-number-17)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[syntax](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-16)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-16)|Title|Test subject has syntax errors|
|[Section top](#majorfail-outcome-number-16)|Description|The subject has turtle syntax errors that makes it unprocessable by an engine|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>at line 3 of &#60;>:  &#10;Bad syntax (Prefix &#34;owl:&#34; not bound) at &Hat; in:  &#10;&#34;...b'x : &#60;https://www.example.org/olivaw/> .&#92;r&#92;n&#92;r&#92;n:unknownPrefix a '&Hat;b'owl:Ontology .&#92;r&#92;n&#92;r&#92;n:Unknown a owl:Class ;&#92;r&#92;n&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;Th'...&#34;</code></pre>|

***
### MajorFail Outcome number 17

[Jump to summary definition](#summary-MajorFail-17)	|	[Previous MajorFail outcome](#majorfail-outcome-number-16)	|	[Next MajorFail outcome](#majorfail-outcome-number-18)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-17)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-17)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-17)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:161ec9c0-6636-4f17-b4f6-1702e391641a> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b32323 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 18

[Jump to summary definition](#summary-MajorFail-18)	|	[Previous MajorFail outcome](#majorfail-outcome-number-17)	|	[Next MajorFail outcome](#majorfail-outcome-number-19)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-18)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-18)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-18)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2886ba02-2fef-4c83-8317-be2aa92b79e0> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b29622 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6cc678ca-6cda-45fe-a47c-4789c08c961f> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b29622 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:3d2a1e93-3dfa-4e82-8275-7db486098b0e> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b29622 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|

***
### MajorFail Outcome number 19

[Jump to summary definition](#summary-MajorFail-19)	|	[Previous MajorFail outcome](#majorfail-outcome-number-18)	|	[Next MajorFail outcome](#majorfail-outcome-number-20)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-19)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-19)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-19)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 20

[Jump to summary definition](#summary-MajorFail-20)	|	[Previous MajorFail outcome](#majorfail-outcome-number-19)	|	[Next MajorFail outcome](#majorfail-outcome-number-21)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-20)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-20)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-20)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:49556651-e0ae-4854-894b-ce005b5ed83e> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b26930 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 21

[Jump to summary definition](#summary-MajorFail-21)	|	[Previous MajorFail outcome](#majorfail-outcome-number-20)	|	[Next MajorFail outcome](#majorfail-outcome-number-22)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-21)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-21)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-21)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-21)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 22

[Jump to summary definition](#summary-MajorFail-22)	|	[Previous MajorFail outcome](#majorfail-outcome-number-21)	|	[Next MajorFail outcome](#majorfail-outcome-number-23)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-22)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-22)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-22)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:23936750-fb2e-4db5-85a9-4c6acbf18187> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b24238 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 23

[Jump to summary definition](#summary-MajorFail-23)	|	[Previous MajorFail outcome](#majorfail-outcome-number-22)	|	[Next MajorFail outcome](#majorfail-outcome-number-24)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-23)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-23)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-23)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a5085a7d-3988-424c-9b96-f4ad1d868d73> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b21546 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:43a0d66e-550b-4990-a7f1-05b7a8878b01> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b21546 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 24

[Jump to summary definition](#summary-MajorFail-24)	|	[Previous MajorFail outcome](#majorfail-outcome-number-23)	|	[Next MajorFail outcome](#majorfail-outcome-number-25)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-24)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-24)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-24)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:d9895291-da8a-45c7-90d1-3d72a58d6a57> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b18854 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***
### MajorFail Outcome number 25

[Jump to summary definition](#summary-MajorFail-25)	|	[Previous MajorFail outcome](#majorfail-outcome-number-24)	|	[Next MajorFail outcome](#majorfail-outcome-number-26)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-25)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-25)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-25)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:8f9dc045-4a27-4c20-b049-808bd1fe960f> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b16162 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 26

[Jump to summary definition](#summary-MajorFail-26)	|	[Previous MajorFail outcome](#majorfail-outcome-number-25)	|	[Next MajorFail outcome](#majorfail-outcome-number-27)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-26)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-26)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-26)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ba1c2c7a-9e55-4a2e-87e5-f4a310ded007> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b13470 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***
### MajorFail Outcome number 27

[Jump to summary definition](#summary-MajorFail-27)	|	[Previous MajorFail outcome](#majorfail-outcome-number-26)	|	[Next MajorFail outcome](#majorfail-outcome-number-28)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-27)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-27)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-27)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-27)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-27)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 28

[Jump to summary definition](#summary-MajorFail-28)	|	[Previous MajorFail outcome](#majorfail-outcome-number-27)	|	[Next MajorFail outcome](#majorfail-outcome-number-29)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-28)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-28)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-28)|Description|http://www.w3.org/2002/07/owl#disjointWith  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;  &#10;|

***
### MajorFail Outcome number 29

[Jump to summary definition](#summary-MajorFail-29)	|	[Previous MajorFail outcome](#majorfail-outcome-number-28)	|	[Next MajorFail outcome](#majorfail-outcome-number-30)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-29)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-29)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-29)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;  &#10;|

***
### MajorFail Outcome number 30

[Jump to summary definition](#summary-MajorFail-30)	|	[Previous MajorFail outcome](#majorfail-outcome-number-29)	|	[Next MajorFail outcome](#majorfail-outcome-number-31)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-30)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-30)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-30)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:7dee88ec-e89a-4cf2-8147-55a6de5dc417> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:e18e0b5e-d5df-468f-b6a9-c10aaaaa30f2> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2ff6c8fe-00ea-414d-adb0-799d3ba30023> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ae26f366-db66-45d4-b6d2-95331d100447> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:e75d0ba8-aaad-43b9-83e8-379851fcae9a> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:498f337b-0841-4886-a87c-3c874f7e6ad3> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:75d79028-5dd0-4569-ad75-7a31b4e3c1a3> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6a943a47-d4cf-45b6-92a3-b4a00bfd5c95> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6d77bcc5-b1af-4a1b-9c81-b3c162a2065d> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:2d2fe6fa-66a2-4d9f-bdc2-0f8d655a7102> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:44e31281-5bc6-4f00-b1dc-a57363fab5aa> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b37716 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 31

[Jump to summary definition](#summary-MajorFail-31)	|	[Previous MajorFail outcome](#majorfail-outcome-number-30)	|	[Next MajorFail outcome](#majorfail-outcome-number-32)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-31)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-31)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-31)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 32

[Jump to summary definition](#summary-MajorFail-32)	|	[Previous MajorFail outcome](#majorfail-outcome-number-31)	|	[Next MajorFail outcome](#majorfail-outcome-number-33)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-32)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-32)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-32)|Description|http://www.w3.org/2002/07/owl#disjointWith  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;  &#10;|

***
### MajorFail Outcome number 33

[Jump to summary definition](#summary-MajorFail-33)	|	[Previous MajorFail outcome](#majorfail-outcome-number-32)	|	[Next MajorFail outcome](#majorfail-outcome-number-34)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-33)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-33)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-33)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;  &#10;|

***
### MajorFail Outcome number 34

[Jump to summary definition](#summary-MajorFail-34)	|	[Previous MajorFail outcome](#majorfail-outcome-number-33)	|	[Next MajorFail outcome](#majorfail-outcome-number-35)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-34)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-34)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-34)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:594bf331-5177-4306-8b4e-2a21506f282c> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:c44335e3-a3b6-4a27-8e31-0c0f4f75f8bb> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:c5e03d01-0294-4e62-ab56-11e021e5c751> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:562f3b0d-9e36-44d0-a411-5abbe6b5c191> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ff89bc13-3caf-4f66-8926-662b68bf4a64> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:7a0705e9-ac9b-47e7-84ba-1363a96d7d67> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:da3fd877-b02f-4807-b892-8f0c51b685e8> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:3309445a-4eb0-446d-a1ba-1f909d8388f2> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:bbc8cb34-dbac-4acb-aacc-03e2a998cb53> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:a1ba4d66-888b-486c-9511-8525f82bc5dd> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:ec63f910-88f2-4de7-bec0-6416cd5b38f1> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b39071 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 35

[Jump to summary definition](#summary-MajorFail-35)	|	[Previous MajorFail outcome](#majorfail-outcome-number-34)	|	[Next MajorFail outcome](#majorfail-outcome-number-36)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-35)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-35)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-35)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-35)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-35)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:4914dd89-bcb6-4cc5-a9c8-7b3b34bc2072> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/rangeReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b36361 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-35)|Pointer|<pre lang="Turtle"><code>sand:rangeReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a range out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:rangeOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:range shacl:NodeShape .</code></pre>|

***
### MajorFail Outcome number 36

[Jump to summary definition](#summary-MajorFail-36)	|	[Previous MajorFail outcome](#majorfail-outcome-number-35)	|	[Next MajorFail outcome](#majorfail-outcome-number-37)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-36)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-36)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-36)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:1b344da3-141c-463d-8255-d4cb0fc096cc> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/unlabeledTerm> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b33669 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MajorFail Outcome number 37

[Jump to summary definition](#summary-MajorFail-37)	|	[Previous MajorFail outcome](#majorfail-outcome-number-36)	|	[Next MajorFail outcome](#majorfail-outcome-number-38)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-37)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-37)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-37)|Description|http://www.w3.org/2002/07/owl#disjointWith  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:disjointWith&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;  &#10;|

***
### MajorFail Outcome number 38

[Jump to summary definition](#summary-MajorFail-38)	|	[Previous MajorFail outcome](#majorfail-outcome-number-37)	|	[Next MajorFail outcome](#majorfail-outcome-number-39)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-38)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-38)|Title|OWL RL Constraint violation|
|[Section top](#majorfail-outcome-number-38)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses  &#10;rdf:type sp:ConstraintViolation  &#10;sp:violationRoot &#60;https://www.example.org/olivaw/BrokenSubclass>  &#10;rdfs:label &#34;Violates owl:AllDisjointClasses&#34;  &#10;sp:arg1 &#60;https://www.example.org/olivaw/DisjointTheFirst>  &#10;sp:arg2 &#60;https://www.example.org/olivaw/DisjointTheSecond>  &#10;  &#10;|

***
### MajorFail Outcome number 39

[Jump to summary definition](#summary-MajorFail-39)	|	[Previous MajorFail outcome](#majorfail-outcome-number-38)	|	[Next MajorFail outcome](#majorfail-outcome-number-40)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-39)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-39)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-39)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:65b2e192-5aeb-4fb0-9423-be745d88a725> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheSecond> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b30977 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheSecond a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This second class is disjoint from the forst one&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheFirst .</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:b2eb2d29-8814-4e10-8395-b7f91f35aafd> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/BrokenSubclass> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b30977 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>sand:BrokenSubclass a owl:Class,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is broken because it is a subclass of disjoint cl...&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subClassOf sand:DisjointTheFirst,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sand:DisjointTheSecond .</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:6b6c9721-23ea-4768-a75c-9acadc9b2676> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/DisjointTheFirst> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b30977 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>sand:DisjointTheFirst a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This first class is disjoint from the other&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:inconsistent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:disjointWith sand:DisjointTheSecond .</code></pre>|

***
### MajorFail Outcome number 40

[Jump to summary definition](#summary-MajorFail-40)	|	[Previous MajorFail outcome](#majorfail-outcome-number-39)	|	[Next MajorFail outcome](#majorfail-outcome-number-41)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-40)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-40)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-40)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-40)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-40)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 41

[Jump to summary definition](#summary-MajorFail-41)	|	[Previous MajorFail outcome](#majorfail-outcome-number-40)	|	[Next MajorFail outcome](#majorfail-outcome-number-42)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-41)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-41)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-41)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-41)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-41)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:e7fd7fb0-ed10-40e9-800a-97461857b3b0> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b28276 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-41)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 42

[Jump to summary definition](#summary-MajorFail-42)	|	[Previous MajorFail outcome](#majorfail-outcome-number-41)	|	[Next MajorFail outcome](#majorfail-outcome-number-43)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-42)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-42)|Title|Domain out of vocabulary|
|[Section top](#majorfail-outcome-number-42)|Description|Some properties have a domain out of the ontology|
|[Section top](#majorfail-outcome-number-42)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:subPropertyOf sand:domainReferencingOut ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;owl:equivalentProperty sand:domainReferencingOut .</code></pre>|
|[Section top](#majorfail-outcome-number-42)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 43

[Jump to summary definition](#summary-MajorFail-43)	|	[Previous MajorFail outcome](#majorfail-outcome-number-42)	|	[Next MajorFail outcome](#majorfail-outcome-number-44)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-43)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-43)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-43)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:4bad9d29-bb72-40ce-831b-baac1f7f7479> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/domainReferencingOut> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b25584 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>sand:domainReferencingOut a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This property has a domain out of vocabulary&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:domain shacl:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:domainOuter .</code></pre>|

***
### MajorFail Outcome number 44

[Jump to summary definition](#summary-MajorFail-44)	|	[Previous MajorFail outcome](#majorfail-outcome-number-43)	|	[Next MajorFail outcome](#majorfail-outcome-number-45)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-44)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-44)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-44)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-44)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-44)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:52d3df5c-2c0c-45bc-ba0e-8a9dcdc363b0> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassA> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b22892 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-44)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#majorfail-outcome-number-44)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:0efad9f3-c7e4-4255-a194-14b850e81879> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/ClassB> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b22892 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-44)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MajorFail Outcome number 45

[Jump to summary definition](#summary-MajorFail-45)	|	[Previous MajorFail outcome](#majorfail-outcome-number-44)	|	[Next MajorFail outcome](#majorfail-outcome-number-46)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-45)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-45)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-45)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-45)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-45)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:4f4d7ba8-9e56-485a-adb0-f92e1e48a722> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notRLTermCauseReflexive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b20200 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-45)|Pointer|<pre lang="Turtle"><code>sand:notRLTermCauseReflexive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ReflexiveObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not RL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notRL .</code></pre>|

***
### MajorFail Outcome number 46

[Jump to summary definition](#summary-MajorFail-46)	|	[Previous MajorFail outcome](#majorfail-outcome-number-45)	|	[Next MajorFail outcome](#majorfail-outcome-number-47)

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-46)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-46)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-46)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-46)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-46)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:bfc9c002-983c-4afb-a607-98213937480b> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notQLTermCauseTransitive> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b17508 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-46)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notQL .</code></pre>|

***
### MajorFail Outcome number 47

[Jump to summary definition](#summary-MajorFail-47)	|	[Previous MajorFail outcome](#majorfail-outcome-number-46)	|	Next MajorFail outcome

:boom:MajorFail outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-47)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-47)|Title|Error on custom test|
|[Section top](#majorfail-outcome-number-47)|Description|Error occured while running custom test|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>&#60;#shape> a sh:NodeShape ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:property &#91; sh:maxCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:minCount 1 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Violation ],  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#91; sh:languageIn ( &#34;en&#34; ) ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:message &#34;Comment not in @en/without line break/ending with full stop&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:path rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:pattern &#34;&Hat;&#91;&Hat;&#92;&#92;n]+&#92;&#92;.$&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sh:severity sh:Warning ] ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:targetSubjectsOf rdfs:isDefinedBy .</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>&#60;urn:uuid:7802e158-dcbf-40c4-bd41-a067a90c7d9d> rdf:type sh:ValidationResult ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:focusNode &#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultMessage &#34;Ontology term should have one and only one rdfs:comment&#34; ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultPath rdfs:comment ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:resultSeverity sh:Violation ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceConstraintComponent sh:MinCountConstraintComponent ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:sourceShape &lowbar;:b14816 ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;sh:value 0 .</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:notEL .</code></pre>|

***

</details>

***


# MinorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#majorfail-outcomes)	|	[Next section](#nottested-outcomes)

Here is the chapter related to the MinorFail outcome

:exclamation:23 MinorFail outcomes

<details>
<summary>Fold/Unfold the 23 summary and details</summary>

## MinorFail Outcomes Summary

:exclamation:23 MinorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-1">1/23</div>|:exclamation:*MinorFail*|`module-src-unreferenced`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-1)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-2">2/23</div>|:exclamation:*MinorFail*|`module-src-unlabeled`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-2)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-3">3/23</div>|:exclamation:*MinorFail*|`module-src-too-close-terms`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-3)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-4">4/23</div>|:exclamation:*MinorFail*|`module-src-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-4)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-5">5/23</div>|:exclamation:*MinorFail*|`module-src-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-5)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-6">6/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-label`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-6)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-7">7/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-differenciation`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-7)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-8">8/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-8)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-9">9/23</div>|:exclamation:*MinorFail*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-9)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-10">10/23</div>|:exclamation:*MinorFail*|`all-modules`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-10)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-11">11/23</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-11)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-12">12/23</div>|:exclamation:*MinorFail*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-12)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-13">13/23</div>|:exclamation:*MinorFail*|`all-modules`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-13)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-14">14/23</div>|:exclamation:*MinorFail*|`all-modules`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-14)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-15">15/23</div>|:exclamation:*MinorFail*|`all-fragments`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-15)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-16">16/23</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-16)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-17">17/23</div>|:exclamation:*MinorFail*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-17)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-18">18/23</div>|:exclamation:*MinorFail*|`all-fragments`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-18)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-19">19/23</div>|:exclamation:*MinorFail*|`all-fragments`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-19)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-20">20/23</div>|:exclamation:*MinorFail*|`-modelet-zedomain-label`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-20)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-21">21/23</div>|:exclamation:*MinorFail*|`-modelet-zedomain-differenciation`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-21)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-22">22/23</div>|:exclamation:*MinorFail*|`-modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-22)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-23">23/23</div>|:exclamation:*MinorFail*|`-modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-23)|

***

## MinorFail Outcomes Details

This subchapter gives more details to the :exclamation:MinorFail outcomes

### MinorFail Outcome number 1

[Jump to summary definition](#summary-MinorFail-1)	|	Previous MinorFail outcome	|	[Next MinorFail outcome](#minorfail-outcome-number-2)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-1)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-1)|Title|Term not referenced to a module|
|[Section top](#minorfail-outcome-number-1)|Description|Subject terms not linked to a module by a rdfs:isDefinedBy property|
|[Section top](#minorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>sand:NotReferencedClass a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is not linked to a module by a rdfs:isDefinedBy p...&#34; .</code></pre>|

***
### MinorFail Outcome number 2

[Jump to summary definition](#summary-MinorFail-2)	|	[Previous MinorFail outcome](#minorfail-outcome-number-1)	|	[Next MinorFail outcome](#minorfail-outcome-number-3)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-2)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-2)|Title|Terms not labeled|
|[Section top](#minorfail-outcome-number-2)|Description|The following terms have no rdfs:label to define it in natural language|
|[Section top](#minorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 3

[Jump to summary definition](#summary-MinorFail-3)	|	[Previous MinorFail outcome](#minorfail-outcome-number-2)	|	[Next MinorFail outcome](#minorfail-outcome-number-4)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-3)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-3)|Title|Too close terms|
|[Section top](#minorfail-outcome-number-3)|Description|Some terms are too similar|
|[Section top](#minorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#minorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 4

[Jump to summary definition](#summary-MinorFail-4)	|	[Previous MinorFail outcome](#minorfail-outcome-number-3)	|	[Next MinorFail outcome](#minorfail-outcome-number-5)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-4)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-4)|Title|OWL QL Profile incompatible|
|[Section top](#minorfail-outcome-number-4)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 5

[Jump to summary definition](#summary-MinorFail-5)	|	[Previous MinorFail outcome](#minorfail-outcome-number-4)	|	[Next MinorFail outcome](#minorfail-outcome-number-6)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-5)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-5)|Title|OWL EL Profile incompatible|
|[Section top](#minorfail-outcome-number-5)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 6

[Jump to summary definition](#summary-MinorFail-6)	|	[Previous MinorFail outcome](#minorfail-outcome-number-5)	|	[Next MinorFail outcome](#minorfail-outcome-number-7)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-6)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-6)|Title|Terms not labeled|
|[Section top](#minorfail-outcome-number-6)|Description|The following terms have no rdfs:label to define it in natural language|
|[Section top](#minorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 7

[Jump to summary definition](#summary-MinorFail-7)	|	[Previous MinorFail outcome](#minorfail-outcome-number-6)	|	[Next MinorFail outcome](#minorfail-outcome-number-8)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-7)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-7)|Title|Too close terms|
|[Section top](#minorfail-outcome-number-7)|Description|Some terms are too similar|
|[Section top](#minorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#minorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 8

[Jump to summary definition](#summary-MinorFail-8)	|	[Previous MinorFail outcome](#minorfail-outcome-number-7)	|	[Next MinorFail outcome](#minorfail-outcome-number-9)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-8)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-8)|Title|OWL QL Profile incompatible|
|[Section top](#minorfail-outcome-number-8)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-8)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 9

[Jump to summary definition](#summary-MinorFail-9)	|	[Previous MinorFail outcome](#minorfail-outcome-number-8)	|	[Next MinorFail outcome](#minorfail-outcome-number-10)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-9)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-9)|Title|OWL EL Profile incompatible|
|[Section top](#minorfail-outcome-number-9)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 10

[Jump to summary definition](#summary-MinorFail-10)	|	[Previous MinorFail outcome](#minorfail-outcome-number-9)	|	[Next MinorFail outcome](#minorfail-outcome-number-11)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-10)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-10)|Title|Terms not labeled|
|[Section top](#minorfail-outcome-number-10)|Description|The following terms have no rdfs:label to define it in natural language|
|[Section top](#minorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 11

[Jump to summary definition](#summary-MinorFail-11)	|	[Previous MinorFail outcome](#minorfail-outcome-number-10)	|	[Next MinorFail outcome](#minorfail-outcome-number-12)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-11)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-11)|Title|OWL QL Profile incompatible|
|[Section top](#minorfail-outcome-number-11)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 12

[Jump to summary definition](#summary-MinorFail-12)	|	[Previous MinorFail outcome](#minorfail-outcome-number-11)	|	[Next MinorFail outcome](#minorfail-outcome-number-13)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-12)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-12)|Title|OWL EL Profile incompatible|
|[Section top](#minorfail-outcome-number-12)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 13

[Jump to summary definition](#summary-MinorFail-13)	|	[Previous MinorFail outcome](#minorfail-outcome-number-12)	|	[Next MinorFail outcome](#minorfail-outcome-number-14)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-13)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-13)|Title|Term not referenced to a module|
|[Section top](#minorfail-outcome-number-13)|Description|Subject terms not linked to a module by a rdfs:isDefinedBy property|
|[Section top](#minorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>sand:NotReferencedClass a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is not linked to a module by a rdfs:isDefinedBy p...&#34; .</code></pre>|

***
### MinorFail Outcome number 14

[Jump to summary definition](#summary-MinorFail-14)	|	[Previous MinorFail outcome](#minorfail-outcome-number-13)	|	[Next MinorFail outcome](#minorfail-outcome-number-15)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-14)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-14)|Title|Too close terms|
|[Section top](#minorfail-outcome-number-14)|Description|Some terms are too similar|
|[Section top](#minorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#minorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 15

[Jump to summary definition](#summary-MinorFail-15)	|	[Previous MinorFail outcome](#minorfail-outcome-number-14)	|	[Next MinorFail outcome](#minorfail-outcome-number-16)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-15)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-15)|Title|Terms not labeled|
|[Section top](#minorfail-outcome-number-15)|Description|The following terms have no rdfs:label to define it in natural language|
|[Section top](#minorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 16

[Jump to summary definition](#summary-MinorFail-16)	|	[Previous MinorFail outcome](#minorfail-outcome-number-15)	|	[Next MinorFail outcome](#minorfail-outcome-number-17)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-16)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-16)|Title|OWL QL Profile incompatible|
|[Section top](#minorfail-outcome-number-16)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 17

[Jump to summary definition](#summary-MinorFail-17)	|	[Previous MinorFail outcome](#minorfail-outcome-number-16)	|	[Next MinorFail outcome](#minorfail-outcome-number-18)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-17)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-17)|Title|OWL EL Profile incompatible|
|[Section top](#minorfail-outcome-number-17)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***
### MinorFail Outcome number 18

[Jump to summary definition](#summary-MinorFail-18)	|	[Previous MinorFail outcome](#minorfail-outcome-number-17)	|	[Next MinorFail outcome](#minorfail-outcome-number-19)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-18)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-18)|Title|Term not referenced to a module|
|[Section top](#minorfail-outcome-number-18)|Description|Subject terms not linked to a module by a rdfs:isDefinedBy property|
|[Section top](#minorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>sand:NotReferencedClass a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class is not linked to a module by a rdfs:isDefinedBy p...&#34; .</code></pre>|

***
### MinorFail Outcome number 19

[Jump to summary definition](#summary-MinorFail-19)	|	[Previous MinorFail outcome](#minorfail-outcome-number-18)	|	[Next MinorFail outcome](#minorfail-outcome-number-20)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-19)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-19)|Title|Too close terms|
|[Section top](#minorfail-outcome-number-19)|Description|Some terms are too similar|
|[Section top](#minorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#minorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 20

[Jump to summary definition](#summary-MinorFail-20)	|	[Previous MinorFail outcome](#minorfail-outcome-number-19)	|	[Next MinorFail outcome](#minorfail-outcome-number-21)

:exclamation:MinorFail outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-20)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-20)|Title|Terms not labeled|
|[Section top](#minorfail-outcome-number-20)|Description|The following terms have no rdfs:label to define it in natural language|
|[Section top](#minorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>sand:unlabeledTerm a owl:Class ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:unlabeled .</code></pre>|

***
### MinorFail Outcome number 21

[Jump to summary definition](#summary-MinorFail-21)	|	[Previous MinorFail outcome](#minorfail-outcome-number-20)	|	[Next MinorFail outcome](#minorfail-outcome-number-22)

:exclamation:MinorFail outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-21)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-21)|Title|Too close terms|
|[Section top](#minorfail-outcome-number-21)|Description|Some terms are too similar|
|[Section top](#minorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>sand:ClassB a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class B&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|
|[Section top](#minorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>sand:ClassA a owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This class has a name too close to class A&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy sand:tooCloseTerms .</code></pre>|

***
### MinorFail Outcome number 22

[Jump to summary definition](#summary-MinorFail-22)	|	[Previous MinorFail outcome](#minorfail-outcome-number-21)	|	[Next MinorFail outcome](#minorfail-outcome-number-23)

:exclamation:MinorFail outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-22)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-22)|Title|OWL QL Profile incompatible|
|[Section top](#minorfail-outcome-number-22)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notQLTermCauseTransitive> a owl:ObjectProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:TransitiveProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not QL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notQL> .</code></pre>|

***
### MinorFail Outcome number 23

[Jump to summary definition](#summary-MinorFail-23)	|	[Previous MinorFail outcome](#minorfail-outcome-number-22)	|	Next MinorFail outcome

:exclamation:MinorFail outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-23)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-23)|Title|OWL EL Profile incompatible|
|[Section top](#minorfail-outcome-number-23)|Description|Statement not supported|
|[Section top](#minorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>&#60;https://www.example.org/olivaw/notELTermCauseAsymmetric> a owl:AsymmetricProperty,  &#10;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;owl:ObjectProperty ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:label &#34;This term has a statement that is not EL compatible&#34;@en ;  &#10;&nbsp;&nbsp;&nbsp;&nbsp;rdfs:isDefinedBy &#60;https://www.example.org/olivaw/notEL> .</code></pre>|

***

</details>

***


# NotTested Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#minorfail-outcomes)	|	[Next section](#pass-outcomes)

Here is the chapter related to the NotTested outcome

:grey_question:44 NotTested outcomes

<details>
<summary>Fold/Unfold the 44 summary and details</summary>

## NotTested Outcomes Summary

:grey_question:44 NotTested outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-1">1/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-2">2/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-2)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-3">3/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-3)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-4">4/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-4)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-5">5/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-5)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-6">6/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-6)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-7">7/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-7)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-8">8/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-8)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-9">9/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-9)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-10">10/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-10)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-11">11/44</div>|:grey_question:*NotTested*|`module-src-unknown-prefix`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-11)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-12">12/44</div>|:grey_question:*NotTested*|`module-src-broken`|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-12)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-13">13/44</div>|:grey_question:*NotTested*|`module-src-broken`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-13)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-14">14/44</div>|:grey_question:*NotTested*|`module-src-broken`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-14)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-15">15/44</div>|:grey_question:*NotTested*|`module-src-broken`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-15)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-16">16/44</div>|:grey_question:*NotTested*|`module-src-broken`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-16)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-17">17/44</div>|:grey_question:*NotTested*|`module-src-broken`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-17)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-18">18/44</div>|:grey_question:*NotTested*|`module-src-broken`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-18)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-19">19/44</div>|:grey_question:*NotTested*|`module-src-broken`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-19)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-20">20/44</div>|:grey_question:*NotTested*|`module-src-broken`|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-20)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-21">21/44</div>|:grey_question:*NotTested*|`module-src-broken`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-21)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-22">22/44</div>|:grey_question:*NotTested*|`module-src-broken`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-22)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-23">23/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-23)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-24">24/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-24)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-25">25/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-25)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-26">26/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-26)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-27">27/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-27)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-28">28/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-28)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-29">29/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-29)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-30">30/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-30)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-31">31/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-31)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-32">32/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-32)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-33">33/44</div>|:grey_question:*NotTested*|`modelet-zedomain-syntax`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-33)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-34">34/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-34)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-35">35/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-35)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-36">36/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Error on custom test |[Jump](#nottested-outcome-number-36)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-37">37/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|Error on custom test |[Jump](#nottested-outcome-number-37)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-38">38/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|Error on custom test |[Jump](#nottested-outcome-number-38)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-39">39/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-39)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-40">40/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-40)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-41">41/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|Error on custom test |[Jump](#nottested-outcome-number-41)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-42">42/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-42)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-43">43/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Error on custom test |[Jump](#nottested-outcome-number-43)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-44">44/44</div>|:grey_question:*NotTested*|`modelet-zedomain-prefix`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Error on custom test |[Jump](#nottested-outcome-number-44)|

***

## NotTested Outcomes Details

This subchapter gives more details to the :grey_question:NotTested outcomes

### NotTested Outcome number 1

[Jump to summary definition](#summary-NotTested-1)	|	Previous NotTested outcome	|	[Next NotTested outcome](#nottested-outcome-number-2)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-1)|Identifier|`None`|
|[Section top](#nottested-outcome-number-1)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-1)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 2

[Jump to summary definition](#summary-NotTested-2)	|	[Previous NotTested outcome](#nottested-outcome-number-1)	|	[Next NotTested outcome](#nottested-outcome-number-3)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-2)|Identifier|`None`|
|[Section top](#nottested-outcome-number-2)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-2)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 3

[Jump to summary definition](#summary-NotTested-3)	|	[Previous NotTested outcome](#nottested-outcome-number-2)	|	[Next NotTested outcome](#nottested-outcome-number-4)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-3)|Identifier|`None`|
|[Section top](#nottested-outcome-number-3)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-3)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 4

[Jump to summary definition](#summary-NotTested-4)	|	[Previous NotTested outcome](#nottested-outcome-number-3)	|	[Next NotTested outcome](#nottested-outcome-number-5)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-4)|Identifier|`None`|
|[Section top](#nottested-outcome-number-4)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-4)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 5

[Jump to summary definition](#summary-NotTested-5)	|	[Previous NotTested outcome](#nottested-outcome-number-4)	|	[Next NotTested outcome](#nottested-outcome-number-6)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-5)|Identifier|`None`|
|[Section top](#nottested-outcome-number-5)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-5)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 6

[Jump to summary definition](#summary-NotTested-6)	|	[Previous NotTested outcome](#nottested-outcome-number-5)	|	[Next NotTested outcome](#nottested-outcome-number-7)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-6)|Identifier|`None`|
|[Section top](#nottested-outcome-number-6)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-6)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 7

[Jump to summary definition](#summary-NotTested-7)	|	[Previous NotTested outcome](#nottested-outcome-number-6)	|	[Next NotTested outcome](#nottested-outcome-number-8)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-7)|Identifier|`None`|
|[Section top](#nottested-outcome-number-7)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-7)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 8

[Jump to summary definition](#summary-NotTested-8)	|	[Previous NotTested outcome](#nottested-outcome-number-7)	|	[Next NotTested outcome](#nottested-outcome-number-9)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-8)|Identifier|`None`|
|[Section top](#nottested-outcome-number-8)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-8)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 9

[Jump to summary definition](#summary-NotTested-9)	|	[Previous NotTested outcome](#nottested-outcome-number-8)	|	[Next NotTested outcome](#nottested-outcome-number-10)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-9)|Identifier|`None`|
|[Section top](#nottested-outcome-number-9)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-9)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 10

[Jump to summary definition](#summary-NotTested-10)	|	[Previous NotTested outcome](#nottested-outcome-number-9)	|	[Next NotTested outcome](#nottested-outcome-number-11)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-10)|Identifier|`None`|
|[Section top](#nottested-outcome-number-10)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-10)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 11

[Jump to summary definition](#summary-NotTested-11)	|	[Previous NotTested outcome](#nottested-outcome-number-10)	|	[Next NotTested outcome](#nottested-outcome-number-12)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone module src/unknown-prefix.ttl from branch main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-11)|Identifier|`None`|
|[Section top](#nottested-outcome-number-11)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-11)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 12

[Jump to summary definition](#summary-NotTested-12)	|	[Previous NotTested outcome](#nottested-outcome-number-11)	|	[Next NotTested outcome](#nottested-outcome-number-13)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-12)|Identifier|`None`|
|[Section top](#nottested-outcome-number-12)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-12)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 13

[Jump to summary definition](#summary-NotTested-13)	|	[Previous NotTested outcome](#nottested-outcome-number-12)	|	[Next NotTested outcome](#nottested-outcome-number-14)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-13)|Identifier|`None`|
|[Section top](#nottested-outcome-number-13)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-13)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 14

[Jump to summary definition](#summary-NotTested-14)	|	[Previous NotTested outcome](#nottested-outcome-number-13)	|	[Next NotTested outcome](#nottested-outcome-number-15)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-14)|Identifier|`None`|
|[Section top](#nottested-outcome-number-14)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-14)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 15

[Jump to summary definition](#summary-NotTested-15)	|	[Previous NotTested outcome](#nottested-outcome-number-14)	|	[Next NotTested outcome](#nottested-outcome-number-16)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-15)|Identifier|`None`|
|[Section top](#nottested-outcome-number-15)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-15)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 16

[Jump to summary definition](#summary-NotTested-16)	|	[Previous NotTested outcome](#nottested-outcome-number-15)	|	[Next NotTested outcome](#nottested-outcome-number-17)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-16)|Identifier|`None`|
|[Section top](#nottested-outcome-number-16)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-16)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 17

[Jump to summary definition](#summary-NotTested-17)	|	[Previous NotTested outcome](#nottested-outcome-number-16)	|	[Next NotTested outcome](#nottested-outcome-number-18)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-17)|Identifier|`None`|
|[Section top](#nottested-outcome-number-17)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-17)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 18

[Jump to summary definition](#summary-NotTested-18)	|	[Previous NotTested outcome](#nottested-outcome-number-17)	|	[Next NotTested outcome](#nottested-outcome-number-19)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-18)|Identifier|`None`|
|[Section top](#nottested-outcome-number-18)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-18)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 19

[Jump to summary definition](#summary-NotTested-19)	|	[Previous NotTested outcome](#nottested-outcome-number-18)	|	[Next NotTested outcome](#nottested-outcome-number-20)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-19)|Identifier|`None`|
|[Section top](#nottested-outcome-number-19)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-19)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 20

[Jump to summary definition](#summary-NotTested-20)	|	[Previous NotTested outcome](#nottested-outcome-number-19)	|	[Next NotTested outcome](#nottested-outcome-number-21)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-20)|Identifier|`None`|
|[Section top](#nottested-outcome-number-20)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-20)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 21

[Jump to summary definition](#summary-NotTested-21)	|	[Previous NotTested outcome](#nottested-outcome-number-20)	|	[Next NotTested outcome](#nottested-outcome-number-22)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-21)|Identifier|`None`|
|[Section top](#nottested-outcome-number-21)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-21)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 22

[Jump to summary definition](#summary-NotTested-22)	|	[Previous NotTested outcome](#nottested-outcome-number-21)	|	[Next NotTested outcome](#nottested-outcome-number-23)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone module src/broken.ttl from branch main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-22)|Identifier|`None`|
|[Section top](#nottested-outcome-number-22)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-22)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 23

[Jump to summary definition](#summary-NotTested-23)	|	[Previous NotTested outcome](#nottested-outcome-number-22)	|	[Next NotTested outcome](#nottested-outcome-number-24)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-23)|Identifier|`None`|
|[Section top](#nottested-outcome-number-23)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-23)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 24

[Jump to summary definition](#summary-NotTested-24)	|	[Previous NotTested outcome](#nottested-outcome-number-23)	|	[Next NotTested outcome](#nottested-outcome-number-25)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-24)|Identifier|`None`|
|[Section top](#nottested-outcome-number-24)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-24)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 25

[Jump to summary definition](#summary-NotTested-25)	|	[Previous NotTested outcome](#nottested-outcome-number-24)	|	[Next NotTested outcome](#nottested-outcome-number-26)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-25)|Identifier|`None`|
|[Section top](#nottested-outcome-number-25)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-25)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 26

[Jump to summary definition](#summary-NotTested-26)	|	[Previous NotTested outcome](#nottested-outcome-number-25)	|	[Next NotTested outcome](#nottested-outcome-number-27)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-26)|Identifier|`None`|
|[Section top](#nottested-outcome-number-26)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-26)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 27

[Jump to summary definition](#summary-NotTested-27)	|	[Previous NotTested outcome](#nottested-outcome-number-26)	|	[Next NotTested outcome](#nottested-outcome-number-28)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-27)|Identifier|`None`|
|[Section top](#nottested-outcome-number-27)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-27)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 28

[Jump to summary definition](#summary-NotTested-28)	|	[Previous NotTested outcome](#nottested-outcome-number-27)	|	[Next NotTested outcome](#nottested-outcome-number-29)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-28)|Identifier|`None`|
|[Section top](#nottested-outcome-number-28)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-28)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 29

[Jump to summary definition](#summary-NotTested-29)	|	[Previous NotTested outcome](#nottested-outcome-number-28)	|	[Next NotTested outcome](#nottested-outcome-number-30)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-29)|Identifier|`None`|
|[Section top](#nottested-outcome-number-29)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-29)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 30

[Jump to summary definition](#summary-NotTested-30)	|	[Previous NotTested outcome](#nottested-outcome-number-29)	|	[Next NotTested outcome](#nottested-outcome-number-31)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-30)|Identifier|`None`|
|[Section top](#nottested-outcome-number-30)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-30)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 31

[Jump to summary definition](#summary-NotTested-31)	|	[Previous NotTested outcome](#nottested-outcome-number-30)	|	[Next NotTested outcome](#nottested-outcome-number-32)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-31)|Identifier|`None`|
|[Section top](#nottested-outcome-number-31)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-31)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 32

[Jump to summary definition](#summary-NotTested-32)	|	[Previous NotTested outcome](#nottested-outcome-number-31)	|	[Next NotTested outcome](#nottested-outcome-number-33)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-32)|Identifier|`None`|
|[Section top](#nottested-outcome-number-32)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-32)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 33

[Jump to summary definition](#summary-NotTested-33)	|	[Previous NotTested outcome](#nottested-outcome-number-32)	|	[Next NotTested outcome](#nottested-outcome-number-34)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone modelet domains/zedomain/syntax/onto.ttl from branch main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-33)|Identifier|`None`|
|[Section top](#nottested-outcome-number-33)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-33)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 34

[Jump to summary definition](#summary-NotTested-34)	|	[Previous NotTested outcome](#nottested-outcome-number-33)	|	[Next NotTested outcome](#nottested-outcome-number-35)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#comment-format)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-34)|Identifier|`None`|
|[Section top](#nottested-outcome-number-34)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-34)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 35

[Jump to summary definition](#summary-NotTested-35)	|	[Previous NotTested outcome](#nottested-outcome-number-34)	|	[Next NotTested outcome](#nottested-outcome-number-36)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-35)|Identifier|`None`|
|[Section top](#nottested-outcome-number-35)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-35)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 36

[Jump to summary definition](#summary-NotTested-36)	|	[Previous NotTested outcome](#nottested-outcome-number-35)	|	[Next NotTested outcome](#nottested-outcome-number-37)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-36)|Identifier|`None`|
|[Section top](#nottested-outcome-number-36)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-36)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 37

[Jump to summary definition](#summary-NotTested-37)	|	[Previous NotTested outcome](#nottested-outcome-number-36)	|	[Next NotTested outcome](#nottested-outcome-number-38)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-37)|Identifier|`None`|
|[Section top](#nottested-outcome-number-37)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-37)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 38

[Jump to summary definition](#summary-NotTested-38)	|	[Previous NotTested outcome](#nottested-outcome-number-37)	|	[Next NotTested outcome](#nottested-outcome-number-39)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-38)|Identifier|`None`|
|[Section top](#nottested-outcome-number-38)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-38)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 39

[Jump to summary definition](#summary-NotTested-39)	|	[Previous NotTested outcome](#nottested-outcome-number-38)	|	[Next NotTested outcome](#nottested-outcome-number-40)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-39)|Identifier|`None`|
|[Section top](#nottested-outcome-number-39)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-39)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 40

[Jump to summary definition](#summary-NotTested-40)	|	[Previous NotTested outcome](#nottested-outcome-number-39)	|	[Next NotTested outcome](#nottested-outcome-number-41)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-40)|Identifier|`None`|
|[Section top](#nottested-outcome-number-40)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-40)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 41

[Jump to summary definition](#summary-NotTested-41)	|	[Previous NotTested outcome](#nottested-outcome-number-40)	|	[Next NotTested outcome](#nottested-outcome-number-42)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-41)|Identifier|`None`|
|[Section top](#nottested-outcome-number-41)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-41)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 42

[Jump to summary definition](#summary-NotTested-42)	|	[Previous NotTested outcome](#nottested-outcome-number-41)	|	[Next NotTested outcome](#nottested-outcome-number-43)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#subclass-cycle)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-42)|Identifier|`None`|
|[Section top](#nottested-outcome-number-42)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-42)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 43

[Jump to summary definition](#summary-NotTested-43)	|	[Previous NotTested outcome](#nottested-outcome-number-42)	|	[Next NotTested outcome](#nottested-outcome-number-44)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-43)|Identifier|`None`|
|[Section top](#nottested-outcome-number-43)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-43)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***
### NotTested Outcome number 44

[Jump to summary definition](#summary-NotTested-44)	|	[Previous NotTested outcome](#nottested-outcome-number-43)	|	Next NotTested outcome

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone modelet domains/zedomain/prefix/onto.ttl from branch main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-44)|Identifier|`None`|
|[Section top](#nottested-outcome-number-44)|Title|Error on custom test|
|[Section top](#nottested-outcome-number-44)|Description|Custom test  could not be run because the subject could not be loaded in the engine|

***

</details>

***


# Pass Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#nottested-outcomes)	|	Next section

Here is the chapter related to the Pass outcome

:white_check_mark:228 Pass outcomes

<details>
<summary>Fold/Unfold the 228 summary and details</summary>

## Pass Outcomes Summary

:white_check_mark:228 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-1">1/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-1)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-2">2/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-2)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-3">3/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-3)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-4">4/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-4)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-5">5/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-5)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-6">6/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-6)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-7">7/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-7)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-8">8/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-8)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-9">9/228</div>|:white_check_mark:*Pass*|`module-src-unreferenced`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-9)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-10">10/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-10)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-11">11/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-11)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-12">12/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-12)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-13">13/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-13)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-14">14/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-14)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-15">15/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-15)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-16">16/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-16)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-17">17/228</div>|:white_check_mark:*Pass*|`module-src-unlabeled`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-17)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-18">18/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-18)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-19">19/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-19)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-20">20/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-20)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-21">21/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-21)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-22">22/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-22)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-23">23/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-23)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-24">24/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-24)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-25">25/228</div>|:white_check_mark:*Pass*|`module-src-too-close-terms`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-25)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-26">26/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-26)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-27">27/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-27)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-28">28/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-28)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-29">29/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-29)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-30">30/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-30)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-31">31/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-31)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-32">32/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-32)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-33">33/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-33)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-34">34/228</div>|:white_check_mark:*Pass*|`module-src-range-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-34)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-35">35/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-35)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-36">36/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-36)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-37">37/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-37)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-38">38/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-38)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-39">39/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-39)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-40">40/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-40)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-41">41/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-41)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-42">42/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-42)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-43">43/228</div>|:white_check_mark:*Pass*|`module-src-not-rl`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-43)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-44">44/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-44)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-45">45/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-45)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-46">46/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-46)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-47">47/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-47)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-48">48/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-48)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-49">49/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-49)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-50">50/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-50)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-51">51/228</div>|:white_check_mark:*Pass*|`module-src-not-ql`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-51)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-52">52/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-52)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-53">53/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-53)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-54">54/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-54)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-55">55/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-55)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-56">56/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-56)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-57">57/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-57)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-58">58/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-58)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-59">59/228</div>|:white_check_mark:*Pass*|`module-src-not-el`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-59)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-60">60/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-60)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-61">61/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-61)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-62">62/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-62)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-63">63/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-63)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-64">64/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-64)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-65">65/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-65)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-66">66/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-66)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-67">67/228</div>|:white_check_mark:*Pass*|`module-src-inconsistent`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-67)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-68">68/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-68)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-69">69/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-69)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-70">70/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-70)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-71">71/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-71)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-72">72/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-72)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-73">73/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-73)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-74">74/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-74)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-75">75/228</div>|:white_check_mark:*Pass*|`module-src-domain-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-75)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-76">76/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-76)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-77">77/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-77)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-78">78/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-78)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-79">79/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-79)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-80">80/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-80)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-81">81/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-81)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-82">82/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-82)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-83">83/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-83)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-84">84/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-84)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-85">85/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-85)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-86">86/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-86)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-87">87/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-87)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-88">88/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-88)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-89">89/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-89)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-90">90/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-90)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-91">91/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-91)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-92">92/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-92)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-93">93/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-93)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-94">94/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-94)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-95">95/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-95)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-96">96/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-96)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-97">97/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-97)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-98">98/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-98)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-99">99/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-99)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-100">100/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-100)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-101">101/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-101)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-102">102/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-102)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-103">103/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-103)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-104">104/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-104)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-105">105/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-105)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-106">106/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-106)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-107">107/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-107)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-108">108/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-108)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-109">109/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-109)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-110">110/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-110)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-111">111/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-111)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-112">112/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-112)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-113">113/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-113)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-114">114/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-114)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-115">115/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-115)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-116">116/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-116)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-117">117/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-117)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-118">118/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-118)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-119">119/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-119)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-120">120/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-120)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-121">121/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-121)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-122">122/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-122)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-123">123/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-123)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-124">124/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-124)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-125">125/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-125)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-126">126/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-126)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-127">127/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-127)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-128">128/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-128)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-129">129/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-129)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-130">130/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-130)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-131">131/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-131)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-132">132/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-132)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-133">133/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-133)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-134">134/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-134)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-135">135/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-135)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-136">136/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-136)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-137">137/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-137)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-138">138/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-138)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-139">139/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-139)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-140">140/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-140)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-141">141/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-141)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-142">142/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-142)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-143">143/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-143)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-144">144/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-144)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-145">145/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-145)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-146">146/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-146)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-147">147/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-147)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-148">148/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-148)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-149">149/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-149)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-150">150/228</div>|:white_check_mark:*Pass*|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-150)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-151">151/228</div>|:white_check_mark:*Pass*|`all-modules`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-151)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-152">152/228</div>|:white_check_mark:*Pass*|`all-modules`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-152)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-153">153/228</div>|:white_check_mark:*Pass*|`all-fragments`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-153)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-154">154/228</div>|:white_check_mark:*Pass*|`all-fragments`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-154)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-155">155/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-155)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-156">156/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-156)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-157">157/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-157)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-158">158/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-158)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-159">159/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-159)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-160">160/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-160)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-161">161/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-161)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-162">162/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-162)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-163">163/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-163)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-164">164/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-164)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-165">165/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-165)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-166">166/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-166)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-167">167/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-167)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-168">168/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-168)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-169">169/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-169)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-170">170/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-170)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-171">171/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-171)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-172">172/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-172)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-173">173/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-173)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-174">174/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-174)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-175">175/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-175)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-176">176/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-176)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-177">177/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-177)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-178">178/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-178)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-179">179/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-179)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-180">180/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-180)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-181">181/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-181)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-182">182/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-182)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-183">183/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-183)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-184">184/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-184)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-185">185/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-185)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-186">186/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-186)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-187">187/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-187)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-188">188/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-188)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-189">189/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-189)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-190">190/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-190)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-191">191/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-191)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-192">192/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-192)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-193">193/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-193)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-194">194/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-194)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-195">195/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-195)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-196">196/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-196)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-197">197/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-197)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-198">198/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-198)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-199">199/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-199)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-200">200/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-200)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-201">201/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-201)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-202">202/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-202)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-203">203/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-203)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-204">204/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-204)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-205">205/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-205)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-206">206/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-206)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-207">207/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-207)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-208">208/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-208)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-209">209/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-209)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-210">210/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-210)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-211">211/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-211)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-212">212/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-212)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-213">213/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-213)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-214">214/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-214)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-215">215/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-215)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-216">216/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-216)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-217">217/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-217)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-218">218/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-218)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-219">219/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-219)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-220">220/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-220)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-221">221/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-221)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-222">222/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-222)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-223">223/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-223)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-224">224/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-224)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-225">225/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-225)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-226">226/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-226)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-227">227/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-227)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-228">228/228</div>|:white_check_mark:*Pass*|`-modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-228)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)	|	Previous Pass outcome	|	[Next Pass outcome](#pass-outcome-number-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-1)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-1)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-1)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)	|	[Previous Pass outcome](#pass-outcome-number-1)	|	[Next Pass outcome](#pass-outcome-number-3)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-2)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-2)|Title|All terms labeled|
|[Section top](#pass-outcome-number-2)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 3

[Jump to summary definition](#summary-Pass-3)	|	[Previous Pass outcome](#pass-outcome-number-2)	|	[Next Pass outcome](#pass-outcome-number-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-3)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-3)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-3)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)	|	[Previous Pass outcome](#pass-outcome-number-3)	|	[Next Pass outcome](#pass-outcome-number-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-4)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-4)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-4)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)	|	[Previous Pass outcome](#pass-outcome-number-4)	|	[Next Pass outcome](#pass-outcome-number-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-5)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-5)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-5)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)	|	[Previous Pass outcome](#pass-outcome-number-5)	|	[Next Pass outcome](#pass-outcome-number-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-6)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-6)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-6)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 7

[Jump to summary definition](#summary-Pass-7)	|	[Previous Pass outcome](#pass-outcome-number-6)	|	[Next Pass outcome](#pass-outcome-number-8)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-7)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-7)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-7)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 8

[Jump to summary definition](#summary-Pass-8)	|	[Previous Pass outcome](#pass-outcome-number-7)	|	[Next Pass outcome](#pass-outcome-number-9)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment format test|
|Description|A test meant to test a comment format|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-8)|Identifier|`comment-format`|
|[Section top](#pass-outcome-number-8)|Title|Test  passed|
|[Section top](#pass-outcome-number-8)|Description|The custom test  passed|

***
### Pass Outcome number 9

[Jump to summary definition](#summary-Pass-9)	|	[Previous Pass outcome](#pass-outcome-number-8)	|	[Next Pass outcome](#pass-outcome-number-10)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone module src/unreferenced.ttl from branch main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-9)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-9)|Title|Test  passed|
|[Section top](#pass-outcome-number-9)|Description|The custom test  passed|

***
### Pass Outcome number 10

[Jump to summary definition](#summary-Pass-10)	|	[Previous Pass outcome](#pass-outcome-number-9)	|	[Next Pass outcome](#pass-outcome-number-11)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-10)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-10)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-10)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)	|	[Previous Pass outcome](#pass-outcome-number-10)	|	[Next Pass outcome](#pass-outcome-number-12)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-11)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-11)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-11)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 12

[Jump to summary definition](#summary-Pass-12)	|	[Previous Pass outcome](#pass-outcome-number-11)	|	[Next Pass outcome](#pass-outcome-number-13)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-12)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-12)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-12)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 13

[Jump to summary definition](#summary-Pass-13)	|	[Previous Pass outcome](#pass-outcome-number-12)	|	[Next Pass outcome](#pass-outcome-number-14)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-13)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-13)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-13)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 14

[Jump to summary definition](#summary-Pass-14)	|	[Previous Pass outcome](#pass-outcome-number-13)	|	[Next Pass outcome](#pass-outcome-number-15)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-14)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-14)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-14)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)	|	[Previous Pass outcome](#pass-outcome-number-14)	|	[Next Pass outcome](#pass-outcome-number-16)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-15)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-15)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-15)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 16

[Jump to summary definition](#summary-Pass-16)	|	[Previous Pass outcome](#pass-outcome-number-15)	|	[Next Pass outcome](#pass-outcome-number-17)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-16)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-16)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-16)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 17

[Jump to summary definition](#summary-Pass-17)	|	[Previous Pass outcome](#pass-outcome-number-16)	|	[Next Pass outcome](#pass-outcome-number-18)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone module src/unlabeled.ttl from branch main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-17)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-17)|Title|Test  passed|
|[Section top](#pass-outcome-number-17)|Description|The custom test  passed|

***
### Pass Outcome number 18

[Jump to summary definition](#summary-Pass-18)	|	[Previous Pass outcome](#pass-outcome-number-17)	|	[Next Pass outcome](#pass-outcome-number-19)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-18)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-18)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-18)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 19

[Jump to summary definition](#summary-Pass-19)	|	[Previous Pass outcome](#pass-outcome-number-18)	|	[Next Pass outcome](#pass-outcome-number-20)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-19)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-19)|Title|All terms labeled|
|[Section top](#pass-outcome-number-19)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 20

[Jump to summary definition](#summary-Pass-20)	|	[Previous Pass outcome](#pass-outcome-number-19)	|	[Next Pass outcome](#pass-outcome-number-21)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-20)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-20)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-20)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 21

[Jump to summary definition](#summary-Pass-21)	|	[Previous Pass outcome](#pass-outcome-number-20)	|	[Next Pass outcome](#pass-outcome-number-22)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-21)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-21)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-21)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 22

[Jump to summary definition](#summary-Pass-22)	|	[Previous Pass outcome](#pass-outcome-number-21)	|	[Next Pass outcome](#pass-outcome-number-23)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-22)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-22)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-22)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 23

[Jump to summary definition](#summary-Pass-23)	|	[Previous Pass outcome](#pass-outcome-number-22)	|	[Next Pass outcome](#pass-outcome-number-24)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-23)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-23)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-23)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 24

[Jump to summary definition](#summary-Pass-24)	|	[Previous Pass outcome](#pass-outcome-number-23)	|	[Next Pass outcome](#pass-outcome-number-25)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-24)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-24)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-24)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 25

[Jump to summary definition](#summary-Pass-25)	|	[Previous Pass outcome](#pass-outcome-number-24)	|	[Next Pass outcome](#pass-outcome-number-26)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone module src/too-close-terms.ttl from branch main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-25)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-25)|Title|Test  passed|
|[Section top](#pass-outcome-number-25)|Description|The custom test  passed|

***
### Pass Outcome number 26

[Jump to summary definition](#summary-Pass-26)	|	[Previous Pass outcome](#pass-outcome-number-25)	|	[Next Pass outcome](#pass-outcome-number-27)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-26)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-26)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-26)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 27

[Jump to summary definition](#summary-Pass-27)	|	[Previous Pass outcome](#pass-outcome-number-26)	|	[Next Pass outcome](#pass-outcome-number-28)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-27)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-27)|Title|All terms labeled|
|[Section top](#pass-outcome-number-27)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 28

[Jump to summary definition](#summary-Pass-28)	|	[Previous Pass outcome](#pass-outcome-number-27)	|	[Next Pass outcome](#pass-outcome-number-29)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-28)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-28)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-28)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 29

[Jump to summary definition](#summary-Pass-29)	|	[Previous Pass outcome](#pass-outcome-number-28)	|	[Next Pass outcome](#pass-outcome-number-30)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-29)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-29)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-29)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 30

[Jump to summary definition](#summary-Pass-30)	|	[Previous Pass outcome](#pass-outcome-number-29)	|	[Next Pass outcome](#pass-outcome-number-31)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-30)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-30)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-30)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 31

[Jump to summary definition](#summary-Pass-31)	|	[Previous Pass outcome](#pass-outcome-number-30)	|	[Next Pass outcome](#pass-outcome-number-32)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-31)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-31)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-31)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 32

[Jump to summary definition](#summary-Pass-32)	|	[Previous Pass outcome](#pass-outcome-number-31)	|	[Next Pass outcome](#pass-outcome-number-33)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-32)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-32)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-32)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 33

[Jump to summary definition](#summary-Pass-33)	|	[Previous Pass outcome](#pass-outcome-number-32)	|	[Next Pass outcome](#pass-outcome-number-34)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-33)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-33)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-33)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 34

[Jump to summary definition](#summary-Pass-34)	|	[Previous Pass outcome](#pass-outcome-number-33)	|	[Next Pass outcome](#pass-outcome-number-35)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone module src/range-outer.ttl from branch main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-34)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-34)|Title|Test  passed|
|[Section top](#pass-outcome-number-34)|Description|The custom test  passed|

***
### Pass Outcome number 35

[Jump to summary definition](#summary-Pass-35)	|	[Previous Pass outcome](#pass-outcome-number-34)	|	[Next Pass outcome](#pass-outcome-number-36)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-35)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-35)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-35)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 36

[Jump to summary definition](#summary-Pass-36)	|	[Previous Pass outcome](#pass-outcome-number-35)	|	[Next Pass outcome](#pass-outcome-number-37)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-36)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-36)|Title|All terms labeled|
|[Section top](#pass-outcome-number-36)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 37

[Jump to summary definition](#summary-Pass-37)	|	[Previous Pass outcome](#pass-outcome-number-36)	|	[Next Pass outcome](#pass-outcome-number-38)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-37)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-37)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-37)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 38

[Jump to summary definition](#summary-Pass-38)	|	[Previous Pass outcome](#pass-outcome-number-37)	|	[Next Pass outcome](#pass-outcome-number-39)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-38)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-38)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-38)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 39

[Jump to summary definition](#summary-Pass-39)	|	[Previous Pass outcome](#pass-outcome-number-38)	|	[Next Pass outcome](#pass-outcome-number-40)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-39)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-39)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-39)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 40

[Jump to summary definition](#summary-Pass-40)	|	[Previous Pass outcome](#pass-outcome-number-39)	|	[Next Pass outcome](#pass-outcome-number-41)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-40)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-40)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-40)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 41

[Jump to summary definition](#summary-Pass-41)	|	[Previous Pass outcome](#pass-outcome-number-40)	|	[Next Pass outcome](#pass-outcome-number-42)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-41)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-41)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-41)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 42

[Jump to summary definition](#summary-Pass-42)	|	[Previous Pass outcome](#pass-outcome-number-41)	|	[Next Pass outcome](#pass-outcome-number-43)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-42)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-42)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-42)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 43

[Jump to summary definition](#summary-Pass-43)	|	[Previous Pass outcome](#pass-outcome-number-42)	|	[Next Pass outcome](#pass-outcome-number-44)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone module src/not-rl.ttl from branch main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-43)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-43)|Title|Test  passed|
|[Section top](#pass-outcome-number-43)|Description|The custom test  passed|

***
### Pass Outcome number 44

[Jump to summary definition](#summary-Pass-44)	|	[Previous Pass outcome](#pass-outcome-number-43)	|	[Next Pass outcome](#pass-outcome-number-45)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-44)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-44)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-44)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 45

[Jump to summary definition](#summary-Pass-45)	|	[Previous Pass outcome](#pass-outcome-number-44)	|	[Next Pass outcome](#pass-outcome-number-46)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-45)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-45)|Title|All terms labeled|
|[Section top](#pass-outcome-number-45)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 46

[Jump to summary definition](#summary-Pass-46)	|	[Previous Pass outcome](#pass-outcome-number-45)	|	[Next Pass outcome](#pass-outcome-number-47)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-46)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-46)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-46)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 47

[Jump to summary definition](#summary-Pass-47)	|	[Previous Pass outcome](#pass-outcome-number-46)	|	[Next Pass outcome](#pass-outcome-number-48)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-47)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-47)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-47)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 48

[Jump to summary definition](#summary-Pass-48)	|	[Previous Pass outcome](#pass-outcome-number-47)	|	[Next Pass outcome](#pass-outcome-number-49)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-48)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-48)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-48)|Description|Statement not supported|

***
### Pass Outcome number 49

[Jump to summary definition](#summary-Pass-49)	|	[Previous Pass outcome](#pass-outcome-number-48)	|	[Next Pass outcome](#pass-outcome-number-50)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-49)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-49)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-49)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 50

[Jump to summary definition](#summary-Pass-50)	|	[Previous Pass outcome](#pass-outcome-number-49)	|	[Next Pass outcome](#pass-outcome-number-51)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-50)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-50)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-50)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 51

[Jump to summary definition](#summary-Pass-51)	|	[Previous Pass outcome](#pass-outcome-number-50)	|	[Next Pass outcome](#pass-outcome-number-52)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone module src/not-ql.ttl from branch main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-51)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-51)|Title|Test  passed|
|[Section top](#pass-outcome-number-51)|Description|The custom test  passed|

***
### Pass Outcome number 52

[Jump to summary definition](#summary-Pass-52)	|	[Previous Pass outcome](#pass-outcome-number-51)	|	[Next Pass outcome](#pass-outcome-number-53)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-52)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-52)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-52)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 53

[Jump to summary definition](#summary-Pass-53)	|	[Previous Pass outcome](#pass-outcome-number-52)	|	[Next Pass outcome](#pass-outcome-number-54)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-53)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-53)|Title|All terms labeled|
|[Section top](#pass-outcome-number-53)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 54

[Jump to summary definition](#summary-Pass-54)	|	[Previous Pass outcome](#pass-outcome-number-53)	|	[Next Pass outcome](#pass-outcome-number-55)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-54)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-54)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-54)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 55

[Jump to summary definition](#summary-Pass-55)	|	[Previous Pass outcome](#pass-outcome-number-54)	|	[Next Pass outcome](#pass-outcome-number-56)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-55)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-55)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-55)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 56

[Jump to summary definition](#summary-Pass-56)	|	[Previous Pass outcome](#pass-outcome-number-55)	|	[Next Pass outcome](#pass-outcome-number-57)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-56)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-56)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-56)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 57

[Jump to summary definition](#summary-Pass-57)	|	[Previous Pass outcome](#pass-outcome-number-56)	|	[Next Pass outcome](#pass-outcome-number-58)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-57)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-57)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-57)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 58

[Jump to summary definition](#summary-Pass-58)	|	[Previous Pass outcome](#pass-outcome-number-57)	|	[Next Pass outcome](#pass-outcome-number-59)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-58)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-58)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-58)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 59

[Jump to summary definition](#summary-Pass-59)	|	[Previous Pass outcome](#pass-outcome-number-58)	|	[Next Pass outcome](#pass-outcome-number-60)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone module src/not-el.ttl from branch main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-59)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-59)|Title|Test  passed|
|[Section top](#pass-outcome-number-59)|Description|The custom test  passed|

***
### Pass Outcome number 60

[Jump to summary definition](#summary-Pass-60)	|	[Previous Pass outcome](#pass-outcome-number-59)	|	[Next Pass outcome](#pass-outcome-number-61)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-60)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-60)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-60)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 61

[Jump to summary definition](#summary-Pass-61)	|	[Previous Pass outcome](#pass-outcome-number-60)	|	[Next Pass outcome](#pass-outcome-number-62)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-61)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-61)|Title|All terms labeled|
|[Section top](#pass-outcome-number-61)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 62

[Jump to summary definition](#summary-Pass-62)	|	[Previous Pass outcome](#pass-outcome-number-61)	|	[Next Pass outcome](#pass-outcome-number-63)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-62)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-62)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-62)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 63

[Jump to summary definition](#summary-Pass-63)	|	[Previous Pass outcome](#pass-outcome-number-62)	|	[Next Pass outcome](#pass-outcome-number-64)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-63)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-63)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-63)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 64

[Jump to summary definition](#summary-Pass-64)	|	[Previous Pass outcome](#pass-outcome-number-63)	|	[Next Pass outcome](#pass-outcome-number-65)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-64)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-64)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-64)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 65

[Jump to summary definition](#summary-Pass-65)	|	[Previous Pass outcome](#pass-outcome-number-64)	|	[Next Pass outcome](#pass-outcome-number-66)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-65)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-65)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-65)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 66

[Jump to summary definition](#summary-Pass-66)	|	[Previous Pass outcome](#pass-outcome-number-65)	|	[Next Pass outcome](#pass-outcome-number-67)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-66)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-66)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-66)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 67

[Jump to summary definition](#summary-Pass-67)	|	[Previous Pass outcome](#pass-outcome-number-66)	|	[Next Pass outcome](#pass-outcome-number-68)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone module src/inconsistent.ttl from branch main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-67)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-67)|Title|Test  passed|
|[Section top](#pass-outcome-number-67)|Description|The custom test  passed|

***
### Pass Outcome number 68

[Jump to summary definition](#summary-Pass-68)	|	[Previous Pass outcome](#pass-outcome-number-67)	|	[Next Pass outcome](#pass-outcome-number-69)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-68)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-68)|Title|All terms labeled|
|[Section top](#pass-outcome-number-68)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 69

[Jump to summary definition](#summary-Pass-69)	|	[Previous Pass outcome](#pass-outcome-number-68)	|	[Next Pass outcome](#pass-outcome-number-70)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-69)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-69)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-69)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 70

[Jump to summary definition](#summary-Pass-70)	|	[Previous Pass outcome](#pass-outcome-number-69)	|	[Next Pass outcome](#pass-outcome-number-71)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-70)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-70)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-70)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 71

[Jump to summary definition](#summary-Pass-71)	|	[Previous Pass outcome](#pass-outcome-number-70)	|	[Next Pass outcome](#pass-outcome-number-72)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-71)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-71)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-71)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 72

[Jump to summary definition](#summary-Pass-72)	|	[Previous Pass outcome](#pass-outcome-number-71)	|	[Next Pass outcome](#pass-outcome-number-73)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-72)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-72)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-72)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 73

[Jump to summary definition](#summary-Pass-73)	|	[Previous Pass outcome](#pass-outcome-number-72)	|	[Next Pass outcome](#pass-outcome-number-74)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-73)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-73)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-73)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 74

[Jump to summary definition](#summary-Pass-74)	|	[Previous Pass outcome](#pass-outcome-number-73)	|	[Next Pass outcome](#pass-outcome-number-75)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-74)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-74)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-74)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 75

[Jump to summary definition](#summary-Pass-75)	|	[Previous Pass outcome](#pass-outcome-number-74)	|	[Next Pass outcome](#pass-outcome-number-76)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone module src/domain-outer.ttl from branch main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-75)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-75)|Title|Test  passed|
|[Section top](#pass-outcome-number-75)|Description|The custom test  passed|

***
### Pass Outcome number 76

[Jump to summary definition](#summary-Pass-76)	|	[Previous Pass outcome](#pass-outcome-number-75)	|	[Next Pass outcome](#pass-outcome-number-77)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-76)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-76)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-76)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 77

[Jump to summary definition](#summary-Pass-77)	|	[Previous Pass outcome](#pass-outcome-number-76)	|	[Next Pass outcome](#pass-outcome-number-78)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-77)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-77)|Title|All terms labeled|
|[Section top](#pass-outcome-number-77)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 78

[Jump to summary definition](#summary-Pass-78)	|	[Previous Pass outcome](#pass-outcome-number-77)	|	[Next Pass outcome](#pass-outcome-number-79)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-78)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-78)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-78)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 79

[Jump to summary definition](#summary-Pass-79)	|	[Previous Pass outcome](#pass-outcome-number-78)	|	[Next Pass outcome](#pass-outcome-number-80)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-79)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-79)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-79)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 80

[Jump to summary definition](#summary-Pass-80)	|	[Previous Pass outcome](#pass-outcome-number-79)	|	[Next Pass outcome](#pass-outcome-number-81)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-80)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-80)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-80)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 81

[Jump to summary definition](#summary-Pass-81)	|	[Previous Pass outcome](#pass-outcome-number-80)	|	[Next Pass outcome](#pass-outcome-number-82)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-81)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-81)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-81)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 82

[Jump to summary definition](#summary-Pass-82)	|	[Previous Pass outcome](#pass-outcome-number-81)	|	[Next Pass outcome](#pass-outcome-number-83)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-82)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-82)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-82)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 83

[Jump to summary definition](#summary-Pass-83)	|	[Previous Pass outcome](#pass-outcome-number-82)	|	[Next Pass outcome](#pass-outcome-number-84)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-83)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-83)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-83)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 84

[Jump to summary definition](#summary-Pass-84)	|	[Previous Pass outcome](#pass-outcome-number-83)	|	[Next Pass outcome](#pass-outcome-number-85)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone modelet domains/zedomain/rangeout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-84)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-84)|Title|Test  passed|
|[Section top](#pass-outcome-number-84)|Description|The custom test  passed|

***
### Pass Outcome number 85

[Jump to summary definition](#summary-Pass-85)	|	[Previous Pass outcome](#pass-outcome-number-84)	|	[Next Pass outcome](#pass-outcome-number-86)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-85)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-85)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-85)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 86

[Jump to summary definition](#summary-Pass-86)	|	[Previous Pass outcome](#pass-outcome-number-85)	|	[Next Pass outcome](#pass-outcome-number-87)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-86)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-86)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-86)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 87

[Jump to summary definition](#summary-Pass-87)	|	[Previous Pass outcome](#pass-outcome-number-86)	|	[Next Pass outcome](#pass-outcome-number-88)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-87)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-87)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-87)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 88

[Jump to summary definition](#summary-Pass-88)	|	[Previous Pass outcome](#pass-outcome-number-87)	|	[Next Pass outcome](#pass-outcome-number-89)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-88)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-88)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-88)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 89

[Jump to summary definition](#summary-Pass-89)	|	[Previous Pass outcome](#pass-outcome-number-88)	|	[Next Pass outcome](#pass-outcome-number-90)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-89)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-89)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-89)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 90

[Jump to summary definition](#summary-Pass-90)	|	[Previous Pass outcome](#pass-outcome-number-89)	|	[Next Pass outcome](#pass-outcome-number-91)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-90)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-90)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-90)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 91

[Jump to summary definition](#summary-Pass-91)	|	[Previous Pass outcome](#pass-outcome-number-90)	|	[Next Pass outcome](#pass-outcome-number-92)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-91)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-91)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-91)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 92

[Jump to summary definition](#summary-Pass-92)	|	[Previous Pass outcome](#pass-outcome-number-91)	|	[Next Pass outcome](#pass-outcome-number-93)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone modelet domains/zedomain/label/onto.ttl from branch main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-92)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-92)|Title|Test  passed|
|[Section top](#pass-outcome-number-92)|Description|The custom test  passed|

***
### Pass Outcome number 93

[Jump to summary definition](#summary-Pass-93)	|	[Previous Pass outcome](#pass-outcome-number-92)	|	[Next Pass outcome](#pass-outcome-number-94)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-93)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-93)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-93)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 94

[Jump to summary definition](#summary-Pass-94)	|	[Previous Pass outcome](#pass-outcome-number-93)	|	[Next Pass outcome](#pass-outcome-number-95)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-94)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-94)|Title|All terms labeled|
|[Section top](#pass-outcome-number-94)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 95

[Jump to summary definition](#summary-Pass-95)	|	[Previous Pass outcome](#pass-outcome-number-94)	|	[Next Pass outcome](#pass-outcome-number-96)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-95)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-95)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-95)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 96

[Jump to summary definition](#summary-Pass-96)	|	[Previous Pass outcome](#pass-outcome-number-95)	|	[Next Pass outcome](#pass-outcome-number-97)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-96)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-96)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-96)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 97

[Jump to summary definition](#summary-Pass-97)	|	[Previous Pass outcome](#pass-outcome-number-96)	|	[Next Pass outcome](#pass-outcome-number-98)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-97)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-97)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-97)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 98

[Jump to summary definition](#summary-Pass-98)	|	[Previous Pass outcome](#pass-outcome-number-97)	|	[Next Pass outcome](#pass-outcome-number-99)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-98)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-98)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-98)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 99

[Jump to summary definition](#summary-Pass-99)	|	[Previous Pass outcome](#pass-outcome-number-98)	|	[Next Pass outcome](#pass-outcome-number-100)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-99)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-99)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-99)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 100

[Jump to summary definition](#summary-Pass-100)	|	[Previous Pass outcome](#pass-outcome-number-99)	|	[Next Pass outcome](#pass-outcome-number-101)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-100)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-100)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-100)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 101

[Jump to summary definition](#summary-Pass-101)	|	[Previous Pass outcome](#pass-outcome-number-100)	|	[Next Pass outcome](#pass-outcome-number-102)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone modelet domains/zedomain/inconsistence/onto.ttl from branch main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-101)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-101)|Title|Test  passed|
|[Section top](#pass-outcome-number-101)|Description|The custom test  passed|

***
### Pass Outcome number 102

[Jump to summary definition](#summary-Pass-102)	|	[Previous Pass outcome](#pass-outcome-number-101)	|	[Next Pass outcome](#pass-outcome-number-103)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-102)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-102)|Title|All terms labeled|
|[Section top](#pass-outcome-number-102)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 103

[Jump to summary definition](#summary-Pass-103)	|	[Previous Pass outcome](#pass-outcome-number-102)	|	[Next Pass outcome](#pass-outcome-number-104)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-103)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-103)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-103)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 104

[Jump to summary definition](#summary-Pass-104)	|	[Previous Pass outcome](#pass-outcome-number-103)	|	[Next Pass outcome](#pass-outcome-number-105)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-104)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-104)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-104)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 105

[Jump to summary definition](#summary-Pass-105)	|	[Previous Pass outcome](#pass-outcome-number-104)	|	[Next Pass outcome](#pass-outcome-number-106)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-105)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-105)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-105)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 106

[Jump to summary definition](#summary-Pass-106)	|	[Previous Pass outcome](#pass-outcome-number-105)	|	[Next Pass outcome](#pass-outcome-number-107)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-106)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-106)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-106)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 107

[Jump to summary definition](#summary-Pass-107)	|	[Previous Pass outcome](#pass-outcome-number-106)	|	[Next Pass outcome](#pass-outcome-number-108)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-107)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-107)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-107)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 108

[Jump to summary definition](#summary-Pass-108)	|	[Previous Pass outcome](#pass-outcome-number-107)	|	[Next Pass outcome](#pass-outcome-number-109)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-108)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-108)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-108)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 109

[Jump to summary definition](#summary-Pass-109)	|	[Previous Pass outcome](#pass-outcome-number-108)	|	[Next Pass outcome](#pass-outcome-number-110)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone modelet domains/zedomain/dovrov/onto.ttl from branch main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-109)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-109)|Title|Test  passed|
|[Section top](#pass-outcome-number-109)|Description|The custom test  passed|

***
### Pass Outcome number 110

[Jump to summary definition](#summary-Pass-110)	|	[Previous Pass outcome](#pass-outcome-number-109)	|	[Next Pass outcome](#pass-outcome-number-111)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-110)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-110)|Title|All terms labeled|
|[Section top](#pass-outcome-number-110)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 111

[Jump to summary definition](#summary-Pass-111)	|	[Previous Pass outcome](#pass-outcome-number-110)	|	[Next Pass outcome](#pass-outcome-number-112)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-111)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-111)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-111)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 112

[Jump to summary definition](#summary-Pass-112)	|	[Previous Pass outcome](#pass-outcome-number-111)	|	[Next Pass outcome](#pass-outcome-number-113)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-112)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-112)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-112)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 113

[Jump to summary definition](#summary-Pass-113)	|	[Previous Pass outcome](#pass-outcome-number-112)	|	[Next Pass outcome](#pass-outcome-number-114)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-113)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-113)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-113)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 114

[Jump to summary definition](#summary-Pass-114)	|	[Previous Pass outcome](#pass-outcome-number-113)	|	[Next Pass outcome](#pass-outcome-number-115)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-114)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-114)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-114)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 115

[Jump to summary definition](#summary-Pass-115)	|	[Previous Pass outcome](#pass-outcome-number-114)	|	[Next Pass outcome](#pass-outcome-number-116)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-115)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-115)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-115)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 116

[Jump to summary definition](#summary-Pass-116)	|	[Previous Pass outcome](#pass-outcome-number-115)	|	[Next Pass outcome](#pass-outcome-number-117)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-116)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-116)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-116)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 117

[Jump to summary definition](#summary-Pass-117)	|	[Previous Pass outcome](#pass-outcome-number-116)	|	[Next Pass outcome](#pass-outcome-number-118)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone modelet domains/zedomain/domainout/onto.ttl from branch main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-117)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-117)|Title|Test  passed|
|[Section top](#pass-outcome-number-117)|Description|The custom test  passed|

***
### Pass Outcome number 118

[Jump to summary definition](#summary-Pass-118)	|	[Previous Pass outcome](#pass-outcome-number-117)	|	[Next Pass outcome](#pass-outcome-number-119)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-118)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-118)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-118)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 119

[Jump to summary definition](#summary-Pass-119)	|	[Previous Pass outcome](#pass-outcome-number-118)	|	[Next Pass outcome](#pass-outcome-number-120)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-119)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-119)|Title|All terms labeled|
|[Section top](#pass-outcome-number-119)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 120

[Jump to summary definition](#summary-Pass-120)	|	[Previous Pass outcome](#pass-outcome-number-119)	|	[Next Pass outcome](#pass-outcome-number-121)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-120)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-120)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-120)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 121

[Jump to summary definition](#summary-Pass-121)	|	[Previous Pass outcome](#pass-outcome-number-120)	|	[Next Pass outcome](#pass-outcome-number-122)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-121)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-121)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-121)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 122

[Jump to summary definition](#summary-Pass-122)	|	[Previous Pass outcome](#pass-outcome-number-121)	|	[Next Pass outcome](#pass-outcome-number-123)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-122)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-122)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-122)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 123

[Jump to summary definition](#summary-Pass-123)	|	[Previous Pass outcome](#pass-outcome-number-122)	|	[Next Pass outcome](#pass-outcome-number-124)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-123)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-123)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-123)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 124

[Jump to summary definition](#summary-Pass-124)	|	[Previous Pass outcome](#pass-outcome-number-123)	|	[Next Pass outcome](#pass-outcome-number-125)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-124)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-124)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-124)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 125

[Jump to summary definition](#summary-Pass-125)	|	[Previous Pass outcome](#pass-outcome-number-124)	|	[Next Pass outcome](#pass-outcome-number-126)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone modelet domains/zedomain/differenciation/onto.ttl from branch main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-125)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-125)|Title|Test  passed|
|[Section top](#pass-outcome-number-125)|Description|The custom test  passed|

***
### Pass Outcome number 126

[Jump to summary definition](#summary-Pass-126)	|	[Previous Pass outcome](#pass-outcome-number-125)	|	[Next Pass outcome](#pass-outcome-number-127)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-126)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-126)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-126)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 127

[Jump to summary definition](#summary-Pass-127)	|	[Previous Pass outcome](#pass-outcome-number-126)	|	[Next Pass outcome](#pass-outcome-number-128)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-127)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-127)|Title|All terms labeled|
|[Section top](#pass-outcome-number-127)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 128

[Jump to summary definition](#summary-Pass-128)	|	[Previous Pass outcome](#pass-outcome-number-127)	|	[Next Pass outcome](#pass-outcome-number-129)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-128)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-128)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-128)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 129

[Jump to summary definition](#summary-Pass-129)	|	[Previous Pass outcome](#pass-outcome-number-128)	|	[Next Pass outcome](#pass-outcome-number-130)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-129)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-129)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-129)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 130

[Jump to summary definition](#summary-Pass-130)	|	[Previous Pass outcome](#pass-outcome-number-129)	|	[Next Pass outcome](#pass-outcome-number-131)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-130)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-130)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-130)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 131

[Jump to summary definition](#summary-Pass-131)	|	[Previous Pass outcome](#pass-outcome-number-130)	|	[Next Pass outcome](#pass-outcome-number-132)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-131)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-131)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-131)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 132

[Jump to summary definition](#summary-Pass-132)	|	[Previous Pass outcome](#pass-outcome-number-131)	|	[Next Pass outcome](#pass-outcome-number-133)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-132)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-132)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-132)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 133

[Jump to summary definition](#summary-Pass-133)	|	[Previous Pass outcome](#pass-outcome-number-132)	|	[Next Pass outcome](#pass-outcome-number-134)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-133)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-133)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-133)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 134

[Jump to summary definition](#summary-Pass-134)	|	[Previous Pass outcome](#pass-outcome-number-133)	|	[Next Pass outcome](#pass-outcome-number-135)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatRL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-134)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-134)|Title|Test  passed|
|[Section top](#pass-outcome-number-134)|Description|The custom test  passed|

***
### Pass Outcome number 135

[Jump to summary definition](#summary-Pass-135)	|	[Previous Pass outcome](#pass-outcome-number-134)	|	[Next Pass outcome](#pass-outcome-number-136)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-135)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-135)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-135)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 136

[Jump to summary definition](#summary-Pass-136)	|	[Previous Pass outcome](#pass-outcome-number-135)	|	[Next Pass outcome](#pass-outcome-number-137)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-136)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-136)|Title|All terms labeled|
|[Section top](#pass-outcome-number-136)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 137

[Jump to summary definition](#summary-Pass-137)	|	[Previous Pass outcome](#pass-outcome-number-136)	|	[Next Pass outcome](#pass-outcome-number-138)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-137)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-137)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-137)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 138

[Jump to summary definition](#summary-Pass-138)	|	[Previous Pass outcome](#pass-outcome-number-137)	|	[Next Pass outcome](#pass-outcome-number-139)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-138)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-138)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-138)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 139

[Jump to summary definition](#summary-Pass-139)	|	[Previous Pass outcome](#pass-outcome-number-138)	|	[Next Pass outcome](#pass-outcome-number-140)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-139)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-139)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-139)|Description|Statement not supported|

***
### Pass Outcome number 140

[Jump to summary definition](#summary-Pass-140)	|	[Previous Pass outcome](#pass-outcome-number-139)	|	[Next Pass outcome](#pass-outcome-number-141)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-140)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-140)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-140)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 141

[Jump to summary definition](#summary-Pass-141)	|	[Previous Pass outcome](#pass-outcome-number-140)	|	[Next Pass outcome](#pass-outcome-number-142)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-141)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-141)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-141)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 142

[Jump to summary definition](#summary-Pass-142)	|	[Previous Pass outcome](#pass-outcome-number-141)	|	[Next Pass outcome](#pass-outcome-number-143)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatQL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-142)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-142)|Title|Test  passed|
|[Section top](#pass-outcome-number-142)|Description|The custom test  passed|

***
### Pass Outcome number 143

[Jump to summary definition](#summary-Pass-143)	|	[Previous Pass outcome](#pass-outcome-number-142)	|	[Next Pass outcome](#pass-outcome-number-144)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-143)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-143)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-143)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 144

[Jump to summary definition](#summary-Pass-144)	|	[Previous Pass outcome](#pass-outcome-number-143)	|	[Next Pass outcome](#pass-outcome-number-145)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-144)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-144)|Title|All terms labeled|
|[Section top](#pass-outcome-number-144)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 145

[Jump to summary definition](#summary-Pass-145)	|	[Previous Pass outcome](#pass-outcome-number-144)	|	[Next Pass outcome](#pass-outcome-number-146)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-145)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-145)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-145)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 146

[Jump to summary definition](#summary-Pass-146)	|	[Previous Pass outcome](#pass-outcome-number-145)	|	[Next Pass outcome](#pass-outcome-number-147)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-146)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-146)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-146)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 147

[Jump to summary definition](#summary-Pass-147)	|	[Previous Pass outcome](#pass-outcome-number-146)	|	[Next Pass outcome](#pass-outcome-number-148)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-147)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-147)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-147)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 148

[Jump to summary definition](#summary-Pass-148)	|	[Previous Pass outcome](#pass-outcome-number-147)	|	[Next Pass outcome](#pass-outcome-number-149)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-148)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-148)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-148)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 149

[Jump to summary definition](#summary-Pass-149)	|	[Previous Pass outcome](#pass-outcome-number-148)	|	[Next Pass outcome](#pass-outcome-number-150)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-149)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-149)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-149)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 150

[Jump to summary definition](#summary-Pass-150)	|	[Previous Pass outcome](#pass-outcome-number-149)	|	[Next Pass outcome](#pass-outcome-number-151)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone modelet domains/zedomain/compatEL/onto.ttl from branch main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-150)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-150)|Title|Test  passed|
|[Section top](#pass-outcome-number-150)|Description|The custom test  passed|

***
### Pass Outcome number 151

[Jump to summary definition](#summary-Pass-151)	|	[Previous Pass outcome](#pass-outcome-number-150)	|	[Next Pass outcome](#pass-outcome-number-152)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-151)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-151)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-151)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 152

[Jump to summary definition](#summary-Pass-152)	|	[Previous Pass outcome](#pass-outcome-number-151)	|	[Next Pass outcome](#pass-outcome-number-153)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All the modules from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-152)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-152)|Title|Test  passed|
|[Section top](#pass-outcome-number-152)|Description|The custom test  passed|

***
### Pass Outcome number 153

[Jump to summary definition](#summary-Pass-153)	|	[Previous Pass outcome](#pass-outcome-number-152)	|	[Next Pass outcome](#pass-outcome-number-154)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-153)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-153)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-153)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 154

[Jump to summary definition](#summary-Pass-154)	|	[Previous Pass outcome](#pass-outcome-number-153)	|	[Next Pass outcome](#pass-outcome-number-155)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All the fragments from branch main that are syntaxically correct as well as their recursive imports|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-154)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-154)|Title|Test  passed|
|[Section top](#pass-outcome-number-154)|Description|The custom test  passed|

***
### Pass Outcome number 155

[Jump to summary definition](#summary-Pass-155)	|	[Previous Pass outcome](#pass-outcome-number-154)	|	[Next Pass outcome](#pass-outcome-number-156)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-155)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-155)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-155)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 156

[Jump to summary definition](#summary-Pass-156)	|	[Previous Pass outcome](#pass-outcome-number-155)	|	[Next Pass outcome](#pass-outcome-number-157)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-156)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-156)|Title|All terms labeled|
|[Section top](#pass-outcome-number-156)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 157

[Jump to summary definition](#summary-Pass-157)	|	[Previous Pass outcome](#pass-outcome-number-156)	|	[Next Pass outcome](#pass-outcome-number-158)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-157)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-157)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-157)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 158

[Jump to summary definition](#summary-Pass-158)	|	[Previous Pass outcome](#pass-outcome-number-157)	|	[Next Pass outcome](#pass-outcome-number-159)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-158)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-158)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-158)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 159

[Jump to summary definition](#summary-Pass-159)	|	[Previous Pass outcome](#pass-outcome-number-158)	|	[Next Pass outcome](#pass-outcome-number-160)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-159)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-159)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-159)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 160

[Jump to summary definition](#summary-Pass-160)	|	[Previous Pass outcome](#pass-outcome-number-159)	|	[Next Pass outcome](#pass-outcome-number-161)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-160)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-160)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-160)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 161

[Jump to summary definition](#summary-Pass-161)	|	[Previous Pass outcome](#pass-outcome-number-160)	|	[Next Pass outcome](#pass-outcome-number-162)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-161)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-161)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-161)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 162

[Jump to summary definition](#summary-Pass-162)	|	[Previous Pass outcome](#pass-outcome-number-161)	|	[Next Pass outcome](#pass-outcome-number-163)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-162)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-162)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-162)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 163

[Jump to summary definition](#summary-Pass-163)	|	[Previous Pass outcome](#pass-outcome-number-162)	|	[Next Pass outcome](#pass-outcome-number-164)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-rangeout|
|----|----|
|Title|Merged use case ../src/range-outer.ttl from branch main with related terms from the fragments domains/zedomain/rangeout/onto.ttl|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-163)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-163)|Title|Test  passed|
|[Section top](#pass-outcome-number-163)|Description|The custom test  passed|

***
### Pass Outcome number 164

[Jump to summary definition](#summary-Pass-164)	|	[Previous Pass outcome](#pass-outcome-number-163)	|	[Next Pass outcome](#pass-outcome-number-165)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-164)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-164)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-164)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 165

[Jump to summary definition](#summary-Pass-165)	|	[Previous Pass outcome](#pass-outcome-number-164)	|	[Next Pass outcome](#pass-outcome-number-166)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-165)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-165)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-165)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 166

[Jump to summary definition](#summary-Pass-166)	|	[Previous Pass outcome](#pass-outcome-number-165)	|	[Next Pass outcome](#pass-outcome-number-167)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-166)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-166)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-166)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 167

[Jump to summary definition](#summary-Pass-167)	|	[Previous Pass outcome](#pass-outcome-number-166)	|	[Next Pass outcome](#pass-outcome-number-168)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-167)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-167)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-167)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 168

[Jump to summary definition](#summary-Pass-168)	|	[Previous Pass outcome](#pass-outcome-number-167)	|	[Next Pass outcome](#pass-outcome-number-169)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-168)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-168)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-168)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 169

[Jump to summary definition](#summary-Pass-169)	|	[Previous Pass outcome](#pass-outcome-number-168)	|	[Next Pass outcome](#pass-outcome-number-170)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-169)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-169)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-169)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 170

[Jump to summary definition](#summary-Pass-170)	|	[Previous Pass outcome](#pass-outcome-number-169)	|	[Next Pass outcome](#pass-outcome-number-171)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-170)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-170)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-170)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 171

[Jump to summary definition](#summary-Pass-171)	|	[Previous Pass outcome](#pass-outcome-number-170)	|	[Next Pass outcome](#pass-outcome-number-172)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-label|
|----|----|
|Title|Merged use case ../src/unlabeled.ttl from branch main with related terms from the fragments domains/zedomain/label/onto.ttl|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-171)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-171)|Title|Test  passed|
|[Section top](#pass-outcome-number-171)|Description|The custom test  passed|

***
### Pass Outcome number 172

[Jump to summary definition](#summary-Pass-172)	|	[Previous Pass outcome](#pass-outcome-number-171)	|	[Next Pass outcome](#pass-outcome-number-173)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-172)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-172)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-172)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 173

[Jump to summary definition](#summary-Pass-173)	|	[Previous Pass outcome](#pass-outcome-number-172)	|	[Next Pass outcome](#pass-outcome-number-174)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-173)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-173)|Title|All terms labeled|
|[Section top](#pass-outcome-number-173)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 174

[Jump to summary definition](#summary-Pass-174)	|	[Previous Pass outcome](#pass-outcome-number-173)	|	[Next Pass outcome](#pass-outcome-number-175)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-174)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-174)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-174)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 175

[Jump to summary definition](#summary-Pass-175)	|	[Previous Pass outcome](#pass-outcome-number-174)	|	[Next Pass outcome](#pass-outcome-number-176)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-175)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-175)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-175)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 176

[Jump to summary definition](#summary-Pass-176)	|	[Previous Pass outcome](#pass-outcome-number-175)	|	[Next Pass outcome](#pass-outcome-number-177)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-176)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-176)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-176)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 177

[Jump to summary definition](#summary-Pass-177)	|	[Previous Pass outcome](#pass-outcome-number-176)	|	[Next Pass outcome](#pass-outcome-number-178)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-177)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-177)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-177)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 178

[Jump to summary definition](#summary-Pass-178)	|	[Previous Pass outcome](#pass-outcome-number-177)	|	[Next Pass outcome](#pass-outcome-number-179)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-178)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-178)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-178)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 179

[Jump to summary definition](#summary-Pass-179)	|	[Previous Pass outcome](#pass-outcome-number-178)	|	[Next Pass outcome](#pass-outcome-number-180)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged use case ../src/inconsistent.ttl from branch main with related terms from the fragments domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-179)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-179)|Title|Test  passed|
|[Section top](#pass-outcome-number-179)|Description|The custom test  passed|

***
### Pass Outcome number 180

[Jump to summary definition](#summary-Pass-180)	|	[Previous Pass outcome](#pass-outcome-number-179)	|	[Next Pass outcome](#pass-outcome-number-181)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-180)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-180)|Title|All terms labeled|
|[Section top](#pass-outcome-number-180)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 181

[Jump to summary definition](#summary-Pass-181)	|	[Previous Pass outcome](#pass-outcome-number-180)	|	[Next Pass outcome](#pass-outcome-number-182)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-181)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-181)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-181)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 182

[Jump to summary definition](#summary-Pass-182)	|	[Previous Pass outcome](#pass-outcome-number-181)	|	[Next Pass outcome](#pass-outcome-number-183)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-182)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-182)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-182)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 183

[Jump to summary definition](#summary-Pass-183)	|	[Previous Pass outcome](#pass-outcome-number-182)	|	[Next Pass outcome](#pass-outcome-number-184)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-183)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-183)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-183)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 184

[Jump to summary definition](#summary-Pass-184)	|	[Previous Pass outcome](#pass-outcome-number-183)	|	[Next Pass outcome](#pass-outcome-number-185)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-184)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-184)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-184)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 185

[Jump to summary definition](#summary-Pass-185)	|	[Previous Pass outcome](#pass-outcome-number-184)	|	[Next Pass outcome](#pass-outcome-number-186)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-185)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-185)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-185)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 186

[Jump to summary definition](#summary-Pass-186)	|	[Previous Pass outcome](#pass-outcome-number-185)	|	[Next Pass outcome](#pass-outcome-number-187)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-186)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-186)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-186)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 187

[Jump to summary definition](#summary-Pass-187)	|	[Previous Pass outcome](#pass-outcome-number-186)	|	[Next Pass outcome](#pass-outcome-number-188)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-dovrov|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/dovrov/onto.ttl|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-187)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-187)|Title|Test  passed|
|[Section top](#pass-outcome-number-187)|Description|The custom test  passed|

***
### Pass Outcome number 188

[Jump to summary definition](#summary-Pass-188)	|	[Previous Pass outcome](#pass-outcome-number-187)	|	[Next Pass outcome](#pass-outcome-number-189)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-188)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-188)|Title|All terms labeled|
|[Section top](#pass-outcome-number-188)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 189

[Jump to summary definition](#summary-Pass-189)	|	[Previous Pass outcome](#pass-outcome-number-188)	|	[Next Pass outcome](#pass-outcome-number-190)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-189)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-189)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-189)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 190

[Jump to summary definition](#summary-Pass-190)	|	[Previous Pass outcome](#pass-outcome-number-189)	|	[Next Pass outcome](#pass-outcome-number-191)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-190)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-190)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-190)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 191

[Jump to summary definition](#summary-Pass-191)	|	[Previous Pass outcome](#pass-outcome-number-190)	|	[Next Pass outcome](#pass-outcome-number-192)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-191)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-191)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-191)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 192

[Jump to summary definition](#summary-Pass-192)	|	[Previous Pass outcome](#pass-outcome-number-191)	|	[Next Pass outcome](#pass-outcome-number-193)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-192)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-192)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-192)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 193

[Jump to summary definition](#summary-Pass-193)	|	[Previous Pass outcome](#pass-outcome-number-192)	|	[Next Pass outcome](#pass-outcome-number-194)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-193)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-193)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-193)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 194

[Jump to summary definition](#summary-Pass-194)	|	[Previous Pass outcome](#pass-outcome-number-193)	|	[Next Pass outcome](#pass-outcome-number-195)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-194)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-194)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-194)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 195

[Jump to summary definition](#summary-Pass-195)	|	[Previous Pass outcome](#pass-outcome-number-194)	|	[Next Pass outcome](#pass-outcome-number-196)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-domainout|
|----|----|
|Title|Merged use case ../src/domain-outer.ttl from branch main with related terms from the fragments domains/zedomain/domainout/onto.ttl|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-195)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-195)|Title|Test  passed|
|[Section top](#pass-outcome-number-195)|Description|The custom test  passed|

***
### Pass Outcome number 196

[Jump to summary definition](#summary-Pass-196)	|	[Previous Pass outcome](#pass-outcome-number-195)	|	[Next Pass outcome](#pass-outcome-number-197)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-196)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-196)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-196)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 197

[Jump to summary definition](#summary-Pass-197)	|	[Previous Pass outcome](#pass-outcome-number-196)	|	[Next Pass outcome](#pass-outcome-number-198)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-197)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-197)|Title|All terms labeled|
|[Section top](#pass-outcome-number-197)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 198

[Jump to summary definition](#summary-Pass-198)	|	[Previous Pass outcome](#pass-outcome-number-197)	|	[Next Pass outcome](#pass-outcome-number-199)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-198)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-198)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-198)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 199

[Jump to summary definition](#summary-Pass-199)	|	[Previous Pass outcome](#pass-outcome-number-198)	|	[Next Pass outcome](#pass-outcome-number-200)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-199)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-199)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-199)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 200

[Jump to summary definition](#summary-Pass-200)	|	[Previous Pass outcome](#pass-outcome-number-199)	|	[Next Pass outcome](#pass-outcome-number-201)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-200)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-200)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-200)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 201

[Jump to summary definition](#summary-Pass-201)	|	[Previous Pass outcome](#pass-outcome-number-200)	|	[Next Pass outcome](#pass-outcome-number-202)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-201)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-201)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-201)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 202

[Jump to summary definition](#summary-Pass-202)	|	[Previous Pass outcome](#pass-outcome-number-201)	|	[Next Pass outcome](#pass-outcome-number-203)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-202)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-202)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-202)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 203

[Jump to summary definition](#summary-Pass-203)	|	[Previous Pass outcome](#pass-outcome-number-202)	|	[Next Pass outcome](#pass-outcome-number-204)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-differenciation|
|----|----|
|Title|Merged use case ../src/too-close-terms.ttl from branch main with related terms from the fragments domains/zedomain/differenciation/onto.ttl|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-203)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-203)|Title|Test  passed|
|[Section top](#pass-outcome-number-203)|Description|The custom test  passed|

***
### Pass Outcome number 204

[Jump to summary definition](#summary-Pass-204)	|	[Previous Pass outcome](#pass-outcome-number-203)	|	[Next Pass outcome](#pass-outcome-number-205)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-204)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-204)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-204)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 205

[Jump to summary definition](#summary-Pass-205)	|	[Previous Pass outcome](#pass-outcome-number-204)	|	[Next Pass outcome](#pass-outcome-number-206)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-205)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-205)|Title|All terms labeled|
|[Section top](#pass-outcome-number-205)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 206

[Jump to summary definition](#summary-Pass-206)	|	[Previous Pass outcome](#pass-outcome-number-205)	|	[Next Pass outcome](#pass-outcome-number-207)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-206)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-206)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-206)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 207

[Jump to summary definition](#summary-Pass-207)	|	[Previous Pass outcome](#pass-outcome-number-206)	|	[Next Pass outcome](#pass-outcome-number-208)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-207)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-207)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-207)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 208

[Jump to summary definition](#summary-Pass-208)	|	[Previous Pass outcome](#pass-outcome-number-207)	|	[Next Pass outcome](#pass-outcome-number-209)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-208)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-208)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-208)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 209

[Jump to summary definition](#summary-Pass-209)	|	[Previous Pass outcome](#pass-outcome-number-208)	|	[Next Pass outcome](#pass-outcome-number-210)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-209)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-209)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-209)|Description|The subject is included in the OWL EL sublanguage|

***
### Pass Outcome number 210

[Jump to summary definition](#summary-Pass-210)	|	[Previous Pass outcome](#pass-outcome-number-209)	|	[Next Pass outcome](#pass-outcome-number-211)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-210)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-210)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-210)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 211

[Jump to summary definition](#summary-Pass-211)	|	[Previous Pass outcome](#pass-outcome-number-210)	|	[Next Pass outcome](#pass-outcome-number-212)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-211)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-211)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-211)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 212

[Jump to summary definition](#summary-Pass-212)	|	[Previous Pass outcome](#pass-outcome-number-211)	|	[Next Pass outcome](#pass-outcome-number-213)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatRL|
|----|----|
|Title|Merged use case ../src/not-rl.ttl from branch main with related terms from the fragments domains/zedomain/compatRL/onto.ttl|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-212)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-212)|Title|Test  passed|
|[Section top](#pass-outcome-number-212)|Description|The custom test  passed|

***
### Pass Outcome number 213

[Jump to summary definition](#summary-Pass-213)	|	[Previous Pass outcome](#pass-outcome-number-212)	|	[Next Pass outcome](#pass-outcome-number-214)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-213)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-213)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-213)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 214

[Jump to summary definition](#summary-Pass-214)	|	[Previous Pass outcome](#pass-outcome-number-213)	|	[Next Pass outcome](#pass-outcome-number-215)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-214)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-214)|Title|All terms labeled|
|[Section top](#pass-outcome-number-214)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 215

[Jump to summary definition](#summary-Pass-215)	|	[Previous Pass outcome](#pass-outcome-number-214)	|	[Next Pass outcome](#pass-outcome-number-216)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-215)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-215)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-215)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 216

[Jump to summary definition](#summary-Pass-216)	|	[Previous Pass outcome](#pass-outcome-number-215)	|	[Next Pass outcome](#pass-outcome-number-217)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-216)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-216)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-216)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 217

[Jump to summary definition](#summary-Pass-217)	|	[Previous Pass outcome](#pass-outcome-number-216)	|	[Next Pass outcome](#pass-outcome-number-218)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-217)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-217)|Title|OWL EL Profile compatible|
|[Section top](#pass-outcome-number-217)|Description|Statement not supported|

***
### Pass Outcome number 218

[Jump to summary definition](#summary-Pass-218)	|	[Previous Pass outcome](#pass-outcome-number-217)	|	[Next Pass outcome](#pass-outcome-number-219)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-218)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-218)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-218)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 219

[Jump to summary definition](#summary-Pass-219)	|	[Previous Pass outcome](#pass-outcome-number-218)	|	[Next Pass outcome](#pass-outcome-number-220)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-219)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-219)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-219)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 220

[Jump to summary definition](#summary-Pass-220)	|	[Previous Pass outcome](#pass-outcome-number-219)	|	[Next Pass outcome](#pass-outcome-number-221)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatQL|
|----|----|
|Title|Merged use case ../src/not-ql.ttl from branch main with related terms from the fragments domains/zedomain/compatQL/onto.ttl|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-220)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-220)|Title|Test  passed|
|[Section top](#pass-outcome-number-220)|Description|The custom test  passed|

***
### Pass Outcome number 221

[Jump to summary definition](#summary-Pass-221)	|	[Previous Pass outcome](#pass-outcome-number-220)	|	[Next Pass outcome](#pass-outcome-number-222)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-221)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-221)|Title|Domains properly defined|
|[Section top](#pass-outcome-number-221)|Description|Each rdfs:domain is defined within the fragment|

***
### Pass Outcome number 222

[Jump to summary definition](#summary-Pass-222)	|	[Previous Pass outcome](#pass-outcome-number-221)	|	[Next Pass outcome](#pass-outcome-number-223)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-222)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-222)|Title|All terms labeled|
|[Section top](#pass-outcome-number-222)|Description|All the terms defined in the subject have a rdfs:label in English|

***
### Pass Outcome number 223

[Jump to summary definition](#summary-Pass-223)	|	[Previous Pass outcome](#pass-outcome-number-222)	|	[Next Pass outcome](#pass-outcome-number-224)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-223)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-223)|Title|OWL RL consistent|
|[Section top](#pass-outcome-number-223)|Description|The provided graph is consistent for any OWL RL constraint|

***
### Pass Outcome number 224

[Jump to summary definition](#summary-Pass-224)	|	[Previous Pass outcome](#pass-outcome-number-223)	|	[Next Pass outcome](#pass-outcome-number-225)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-224)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-224)|Title|OWL RL Profile compatible|
|[Section top](#pass-outcome-number-224)|Description|The subject is included in the OWL RL sublanguage|

***
### Pass Outcome number 225

[Jump to summary definition](#summary-Pass-225)	|	[Previous Pass outcome](#pass-outcome-number-224)	|	[Next Pass outcome](#pass-outcome-number-226)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-225)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-225)|Title|OWL QL Profile compatible|
|[Section top](#pass-outcome-number-225)|Description|The subject is included in the OWL QL sublanguage|

***
### Pass Outcome number 226

[Jump to summary definition](#summary-Pass-226)	|	[Previous Pass outcome](#pass-outcome-number-225)	|	[Next Pass outcome](#pass-outcome-number-227)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-226)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-226)|Title|Any term is referenced|
|[Section top](#pass-outcome-number-226)|Description|Each term of the test subject is linked to a module by a rdfs:isDefinedBy property|

***
### Pass Outcome number 227

[Jump to summary definition](#summary-Pass-227)	|	[Previous Pass outcome](#pass-outcome-number-226)	|	[Next Pass outcome](#pass-outcome-number-228)

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://raw.githubusercontent.com/Wimmics/olivaw/main/olivaw/test/olivaw-earl.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-227)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-227)|Title|Terms differenciated enough|
|[Section top](#pass-outcome-number-227)|Description|All the terms have have a satisfying Levenshtein distance from each other term.|

***
### Pass Outcome number 228

[Jump to summary definition](#summary-Pass-228)	|	[Previous Pass outcome](#pass-outcome-number-227)	|	Next Pass outcome

:white_check_mark:Pass outcome
#### Subject detail
|Name|-modelet-zedomain-compatEL|
|----|----|
|Title|Merged use case ../src/not-el.ttl from branch main with related terms from the fragments domains/zedomain/compatEL/onto.ttl|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass cycle test|
|Description|A test meant to detect rdfs:subclass cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-228)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-228)|Title|Test  passed|
|[Section top](#pass-outcome-number-228)|Description|The custom test  passed|

***

</details>

***
