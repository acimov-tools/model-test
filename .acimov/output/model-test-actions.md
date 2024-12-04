# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./model-test-actions.ttl).

# Test Activity

Here is some information about the testing activity that led to this report

|Title|Model&#32;tests&#32;of&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|--|--|
|Description|[NicoRobertIn](https://github.com/NicoRobertIn)&#32;launch&#32;actions&#32;run&#32;of&#32;model&#32;tests&#32;against&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|Tester|[NicoRobertIn](https://github.com/NicoRobertIn)|
|Ontology|[acimov-tools/model-test](https://github.com/acimov-tools/model-test)|
|Ontology version|[182b88769b6cbec7599fcf80d761d592b9776321](https://github.com/acimov-tools/model-test/tree/182b88769b6cbec7599fcf80d761d592b9776321)|
|Ontology branch|[main](https://github.com/acimov-tools/model-test/tree/main)|
|Olivaw suite|[olivaw model test suite](https://github.com/Wimmics/olivaw/blob/v0.0.6/olivaw/test/model/suite.py)|
|Olivaw version|[v0.0.6](https://pypi.org/project/olivaw/0.0.6)|
|Generated turtle|[Turtle report](https://github.com/acimov-tools/model-test/blob/182b88769b6cbec7599fcf80d761d592b9776321/.acimov/output/model-test-actions.ttl)|
|Generated Markdown|[Markdown report](https://github.com/acimov-tools/model-test/blob/182b88769b6cbec7599fcf80d761d592b9776321/.acimov/output/model-test-actions.md)|

# Statistic summary

Here is a short overview for this test report

422 Outcomes

:boom:47 MajorFail, :exclamation:23 MinorFail, :warning:0 CannotTell, :grey_question:8 NotTested, :white_check_mark:344 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="11%" height="25px"/><img src="../assets/orange.png" width="5%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="1%" height="25px"/><img src="../assets/green.png" width="83%" height="25px"/></div>

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

:boom:47 MajorFail outcomes

<details>
<summary>Fold/Unfold the 47 summary and details</summary>

## MajorFail Outcomes Summary

:boom:47 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-1">1/47</div>|:boom:MajorFail|`module-src-unlabeled-modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-2">2/47</div>|:boom:MajorFail|`module-src-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-2)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-3">3/47</div>|:boom:MajorFail|`module-src-unknown-prefix`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-3)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-4">4/47</div>|:boom:MajorFail|`module-src-too-close-terms-modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-4)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-5">5/47</div>|:boom:MajorFail|`module-src-too-close-terms`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-6">6/47</div>|:boom:MajorFail|`module-src-range-outer-modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-6)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-7">7/47</div>|:boom:MajorFail|`module-src-range-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-7)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-8">8/47</div>|:boom:MajorFail|`module-src-not-rl-modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-8)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-9">9/47</div>|:boom:MajorFail|`module-src-not-rl`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-9)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-10">10/47</div>|:boom:MajorFail|`module-src-not-ql-modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-10)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-11">11/47</div>|:boom:MajorFail|`module-src-not-ql`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-11)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-12">12/47</div>|:boom:MajorFail|`module-src-not-el-modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-12)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-13">13/47</div>|:boom:MajorFail|`module-src-not-el`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-13)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-14">14/47</div>|:boom:MajorFail|`module-src-inconsistent-modelet-zedomain-inconsistence`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-14)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-15">15/47</div>|:boom:MajorFail|`module-src-inconsistent-modelet-zedomain-inconsistence`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-15)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-16">16/47</div>|:boom:MajorFail|`module-src-inconsistent-modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-16)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-17">17/47</div>|:boom:MajorFail|`module-src-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-17)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-18">18/47</div>|:boom:MajorFail|`module-src-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-18)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-19">19/47</div>|:boom:MajorFail|`module-src-inconsistent`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-19)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-20">20/47</div>|:boom:MajorFail|`module-src-domain-outer-modelet-zedomain-dovrov`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-20)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-21">21/47</div>|:boom:MajorFail|`module-src-domain-outer-modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-21)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-22">22/47</div>|:boom:MajorFail|`module-src-domain-outer-modelet-zedomain-domainout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-22)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-23">23/47</div>|:boom:MajorFail|`module-src-domain-outer-modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-23)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-24">24/47</div>|:boom:MajorFail|`module-src-domain-outer`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-24)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-25">25/47</div>|:boom:MajorFail|`module-src-domain-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-25)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-26">26/47</div>|:boom:MajorFail|`module-src-broken`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-26)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-27">27/47</div>|:boom:MajorFail|`modelet-zedomain-syntax`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-27)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-28">28/47</div>|:boom:MajorFail|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-28)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-29">29/47</div>|:boom:MajorFail|`modelet-zedomain-prefix`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-29)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-30">30/47</div>|:boom:MajorFail|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-30)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-31">31/47</div>|:boom:MajorFail|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-31)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-32">32/47</div>|:boom:MajorFail|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-32)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-33">33/47</div>|:boom:MajorFail|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-33)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-34">34/47</div>|:boom:MajorFail|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-34)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-35">35/47</div>|:boom:MajorFail|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-35)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-36">36/47</div>|:boom:MajorFail|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-36)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-37">37/47</div>|:boom:MajorFail|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-37)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-38">38/47</div>|:boom:MajorFail|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-38)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-39">39/47</div>|:boom:MajorFail|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-39)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-40">40/47</div>|:boom:MajorFail|`all-modules`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-40)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-41">41/47</div>|:boom:MajorFail|`all-modules`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-41)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-42">42/47</div>|:boom:MajorFail|`all-modules`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-42)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-43">43/47</div>|:boom:MajorFail|`all-modules`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-43)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-44">44/47</div>|:boom:MajorFail|`all-fragments`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-44)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-45">45/47</div>|:boom:MajorFail|`all-fragments`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-45)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-46">46/47</div>|:boom:MajorFail|`all-fragments`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-46)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-47">47/47</div>|:boom:MajorFail|`all-fragments`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-47)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)	|	Previous MajorFail outcome	|	[Next MajorFail outcome](#majorfail-outcome-number-2)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-1)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-1)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-1)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>violation:ac3bb2d3-0318-4c03-ba05-beb71b9b2bd2&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)	|	[Previous MajorFail outcome](#majorfail-outcome-number-1)	|	[Next MajorFail outcome](#majorfail-outcome-number-3)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-2)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-2)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-2)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>violation:31944ec4-9f8e-4c06-a2c5-4a011a36c134&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 3

[Jump to summary definition](#summary-MajorFail-3)	|	[Previous MajorFail outcome](#majorfail-outcome-number-2)	|	[Next MajorFail outcome](#majorfail-outcome-number-4)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

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
|[Section top](#majorfail-outcome-number-3)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>at&#32;line&#32;3&#32;of&#32; &#60;>:  &#10;Bad&#32;syntax&#32;(Prefix&#32; &#34;owl:&#34; &#32;not&#32;bound)&#32;at&#32;&Hat;&#32;in:  &#10; &#34;...b'fix&#32;:&#32; &#60;https://www.example.org/olivaw/> &#32;.&#92;n&#92;n:unknownPrefix&#32;a&#32;'&Hat;b'owl:Ontology&#32;.&#92;n&#92;n:Unknown&#32;a&#32;owl:Class&#32;;&#92;n&#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;'...&#34;</code></pre>|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)	|	[Previous MajorFail outcome](#majorfail-outcome-number-3)	|	[Next MajorFail outcome](#majorfail-outcome-number-5)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-4)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-4)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-4)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>violation:50156956-e2c8-43ac-9967-c64a1106358b&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>violation:9f9f7f6c-60a4-4530-9904-733724ebdb56&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)	|	[Previous MajorFail outcome](#majorfail-outcome-number-4)	|	[Next MajorFail outcome](#majorfail-outcome-number-6)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-5)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-5)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-5)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>violation:70176c1c-9613-4484-935a-d5e7c23d8e71&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>violation:0eb59d81-08f5-4c82-9c5e-963290b84ef3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 6

[Jump to summary definition](#summary-MajorFail-6)	|	[Previous MajorFail outcome](#majorfail-outcome-number-5)	|	[Next MajorFail outcome](#majorfail-outcome-number-7)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-6)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-6)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-6)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>violation:715e695d-e0f0-4bc3-9f61-73530a8fb2a9&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 7

[Jump to summary definition](#summary-MajorFail-7)	|	[Previous MajorFail outcome](#majorfail-outcome-number-6)	|	[Next MajorFail outcome](#majorfail-outcome-number-8)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-7)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-7)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-7)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>violation:a92f3de7-8718-4a8d-8703-7722eb3e8694&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 8

[Jump to summary definition](#summary-MajorFail-8)	|	[Previous MajorFail outcome](#majorfail-outcome-number-7)	|	[Next MajorFail outcome](#majorfail-outcome-number-9)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-8)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-8)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-8)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-8)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-8)|Pointer|<pre lang="Turtle"><code>violation:8adf46d9-1bf5-450a-9039-447b00f94889&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-8)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|

***
### MajorFail Outcome number 9

[Jump to summary definition](#summary-MajorFail-9)	|	[Previous MajorFail outcome](#majorfail-outcome-number-8)	|	[Next MajorFail outcome](#majorfail-outcome-number-10)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-9)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-9)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-9)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>violation:30447824-6946-4b01-bfca-38106ffe8c16&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|

***
### MajorFail Outcome number 10

[Jump to summary definition](#summary-MajorFail-10)	|	[Previous MajorFail outcome](#majorfail-outcome-number-9)	|	[Next MajorFail outcome](#majorfail-outcome-number-11)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-10)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-10)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-10)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>violation:4bd7ca66-8a92-425e-aca6-631ed034fe93&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 11

[Jump to summary definition](#summary-MajorFail-11)	|	[Previous MajorFail outcome](#majorfail-outcome-number-10)	|	[Next MajorFail outcome](#majorfail-outcome-number-12)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-11)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-11)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-11)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>violation:4203cb2c-0a4c-4a87-863e-9f593cd9c787&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 12

[Jump to summary definition](#summary-MajorFail-12)	|	[Previous MajorFail outcome](#majorfail-outcome-number-11)	|	[Next MajorFail outcome](#majorfail-outcome-number-13)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-12)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-12)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-12)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>violation:fdb21d01-233d-4f60-972d-a6336714a5e3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 13

[Jump to summary definition](#summary-MajorFail-13)	|	[Previous MajorFail outcome](#majorfail-outcome-number-12)	|	[Next MajorFail outcome](#majorfail-outcome-number-14)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-13)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-13)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-13)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>violation:9f91a50b-6876-4b69-ba21-a0ba805b1af4&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 14

[Jump to summary definition](#summary-MajorFail-14)	|	[Previous MajorFail outcome](#majorfail-outcome-number-13)	|	[Next MajorFail outcome](#majorfail-outcome-number-15)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-14)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-14)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-14)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 15

[Jump to summary definition](#summary-MajorFail-15)	|	[Previous MajorFail outcome](#majorfail-outcome-number-14)	|	[Next MajorFail outcome](#majorfail-outcome-number-16)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-15)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-15)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-15)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 16

[Jump to summary definition](#summary-MajorFail-16)	|	[Previous MajorFail outcome](#majorfail-outcome-number-15)	|	[Next MajorFail outcome](#majorfail-outcome-number-17)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-16)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-16)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-16)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>violation:6b31d856-acb9-4f38-8d0c-b97e362a5e21&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>violation:10106f8c-0273-4355-b731-12e66ab82fa4&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>violation:15ca91d4-1a27-479a-92af-d4efe6f45eb6&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|

***
### MajorFail Outcome number 17

[Jump to summary definition](#summary-MajorFail-17)	|	[Previous MajorFail outcome](#majorfail-outcome-number-16)	|	[Next MajorFail outcome](#majorfail-outcome-number-18)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-17)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-17)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-17)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 18

[Jump to summary definition](#summary-MajorFail-18)	|	[Previous MajorFail outcome](#majorfail-outcome-number-17)	|	[Next MajorFail outcome](#majorfail-outcome-number-19)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-18)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-18)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-18)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 19

[Jump to summary definition](#summary-MajorFail-19)	|	[Previous MajorFail outcome](#majorfail-outcome-number-18)	|	[Next MajorFail outcome](#majorfail-outcome-number-20)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-19)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-19)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-19)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>violation:a6768a68-9bc4-4f1e-839c-cdd2d7c5d3cb&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>violation:1a5cd258-a4e0-4b45-8e4e-af3817d68480&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>violation:8b36949e-6e96-4760-8d72-3332aed3fdab&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|

***
### MajorFail Outcome number 20

[Jump to summary definition](#summary-MajorFail-20)	|	[Previous MajorFail outcome](#majorfail-outcome-number-19)	|	[Next MajorFail outcome](#majorfail-outcome-number-21)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-20)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-20)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-20)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-20)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 21

[Jump to summary definition](#summary-MajorFail-21)	|	[Previous MajorFail outcome](#majorfail-outcome-number-20)	|	[Next MajorFail outcome](#majorfail-outcome-number-22)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-21)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-21)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-21)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>violation:a5a69056-a321-49d9-a6e6-ecbc8ef48190&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 22

[Jump to summary definition](#summary-MajorFail-22)	|	[Previous MajorFail outcome](#majorfail-outcome-number-21)	|	[Next MajorFail outcome](#majorfail-outcome-number-23)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-22)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-22)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-22)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 23

[Jump to summary definition](#summary-MajorFail-23)	|	[Previous MajorFail outcome](#majorfail-outcome-number-22)	|	[Next MajorFail outcome](#majorfail-outcome-number-24)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-23)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-23)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-23)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>violation:5f923923-6429-4f63-82d9-ff97cd30096a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 24

[Jump to summary definition](#summary-MajorFail-24)	|	[Previous MajorFail outcome](#majorfail-outcome-number-23)	|	[Next MajorFail outcome](#majorfail-outcome-number-25)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-24)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-24)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-24)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-24)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 25

[Jump to summary definition](#summary-MajorFail-25)	|	[Previous MajorFail outcome](#majorfail-outcome-number-24)	|	[Next MajorFail outcome](#majorfail-outcome-number-26)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-25)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-25)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-25)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>violation:f703003d-e2a5-4773-b875-641056551ff2&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 26

[Jump to summary definition](#summary-MajorFail-26)	|	[Previous MajorFail outcome](#majorfail-outcome-number-25)	|	[Next MajorFail outcome](#majorfail-outcome-number-27)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone&#32;module&#32;src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-26)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-26)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-26)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;9,&#32;column&#32;23.</code></pre>|

***
### MajorFail Outcome number 27

[Jump to summary definition](#summary-MajorFail-27)	|	[Previous MajorFail outcome](#majorfail-outcome-number-26)	|	[Next MajorFail outcome](#majorfail-outcome-number-28)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-27)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-27)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-27)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-27)|Pointer|<pre lang="Turtle"><code>Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;7,&#32;column&#32;23.</code></pre>|

***
### MajorFail Outcome number 28

[Jump to summary definition](#summary-MajorFail-28)	|	[Previous MajorFail outcome](#majorfail-outcome-number-27)	|	[Next MajorFail outcome](#majorfail-outcome-number-29)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-28)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-28)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-28)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-28)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-28)|Pointer|<pre lang="Turtle"><code>violation:f9f0e498-a0e8-45dd-8fe8-00d5b824dc8e&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-28)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 29

[Jump to summary definition](#summary-MajorFail-29)	|	[Previous MajorFail outcome](#majorfail-outcome-number-28)	|	[Next MajorFail outcome](#majorfail-outcome-number-30)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-29)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-29)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-29)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>at&#32;line&#32;3&#32;of&#32; &#60;>:  &#10;Bad&#32;syntax&#32;(Prefix&#32; &#34;owl:&#34; &#32;not&#32;bound)&#32;at&#32;&Hat;&#32;in:  &#10; &#34;...b'fix&#32;:&#32; &#60;https://www.example.org/olivaw/> &#32;.&#92;n&#92;n:unknownPrefix&#32;a&#32;'&Hat;b'owl:Ontology&#32;.&#92;n&#92;n:Unknown&#32;a&#32;owl:Class&#32;;&#92;n&#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;'...&#34;</code></pre>|

***
### MajorFail Outcome number 30

[Jump to summary definition](#summary-MajorFail-30)	|	[Previous MajorFail outcome](#majorfail-outcome-number-29)	|	[Next MajorFail outcome](#majorfail-outcome-number-31)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-30)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-30)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-30)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:11995eaa-7f77-4ae5-92a6-73710b206346&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 31

[Jump to summary definition](#summary-MajorFail-31)	|	[Previous MajorFail outcome](#majorfail-outcome-number-30)	|	[Next MajorFail outcome](#majorfail-outcome-number-32)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-31)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-31)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-31)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>violation:4fe75329-ee82-4958-8049-642e3fb395c7&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>violation:a53fa3c7-a4ce-42a2-bfa0-28df682e390c&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>violation:4e72630c-378a-4aa5-b24f-3509a8e032c0&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|

***
### MajorFail Outcome number 32

[Jump to summary definition](#summary-MajorFail-32)	|	[Previous MajorFail outcome](#majorfail-outcome-number-31)	|	[Next MajorFail outcome](#majorfail-outcome-number-33)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-32)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-32)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-32)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-32)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-32)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 33

[Jump to summary definition](#summary-MajorFail-33)	|	[Previous MajorFail outcome](#majorfail-outcome-number-32)	|	[Next MajorFail outcome](#majorfail-outcome-number-34)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-33)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-33)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-33)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:6b364dee-7a2f-4dbb-95e7-220175acfa0a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 34

[Jump to summary definition](#summary-MajorFail-34)	|	[Previous MajorFail outcome](#majorfail-outcome-number-33)	|	[Next MajorFail outcome](#majorfail-outcome-number-35)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-34)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-34)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-34)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 35

[Jump to summary definition](#summary-MajorFail-35)	|	[Previous MajorFail outcome](#majorfail-outcome-number-34)	|	[Next MajorFail outcome](#majorfail-outcome-number-36)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-35)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-35)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-35)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-35)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-35)|Pointer|<pre lang="Turtle"><code>violation:23ad6b90-0626-42b8-bc20-a9e65584ab62&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-35)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 36

[Jump to summary definition](#summary-MajorFail-36)	|	[Previous MajorFail outcome](#majorfail-outcome-number-35)	|	[Next MajorFail outcome](#majorfail-outcome-number-37)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-36)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-36)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-36)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>violation:9ef52d53-c14c-402b-a38e-2666bb2a6dc4&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>violation:48f97ff3-4a49-4504-8595-824f7e544fa1&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-36)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 37

[Jump to summary definition](#summary-MajorFail-37)	|	[Previous MajorFail outcome](#majorfail-outcome-number-36)	|	[Next MajorFail outcome](#majorfail-outcome-number-38)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-37)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-37)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-37)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-37)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-37)|Pointer|<pre lang="Turtle"><code>violation:3c825fc2-1048-444f-9b42-4173429193ba&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-37)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|

***
### MajorFail Outcome number 38

[Jump to summary definition](#summary-MajorFail-38)	|	[Previous MajorFail outcome](#majorfail-outcome-number-37)	|	[Next MajorFail outcome](#majorfail-outcome-number-39)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-38)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-38)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-38)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-38)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-38)|Pointer|<pre lang="Turtle"><code>violation:83236044-e3d5-4747-971d-dfd0db03fd88&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-38)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 39

[Jump to summary definition](#summary-MajorFail-39)	|	[Previous MajorFail outcome](#majorfail-outcome-number-38)	|	[Next MajorFail outcome](#majorfail-outcome-number-40)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-39)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-39)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-39)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>violation:d11084ce-8c3f-4ca4-99e1-2676e19fe77a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-39)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 40

[Jump to summary definition](#summary-MajorFail-40)	|	[Previous MajorFail outcome](#majorfail-outcome-number-39)	|	[Next MajorFail outcome](#majorfail-outcome-number-41)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-40)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-40)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-40)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-40)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-40)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 41

[Jump to summary definition](#summary-MajorFail-41)	|	[Previous MajorFail outcome](#majorfail-outcome-number-40)	|	[Next MajorFail outcome](#majorfail-outcome-number-42)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-41)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-41)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-41)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 42

[Jump to summary definition](#summary-MajorFail-42)	|	[Previous MajorFail outcome](#majorfail-outcome-number-41)	|	[Next MajorFail outcome](#majorfail-outcome-number-43)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-42)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-42)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-42)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 43

[Jump to summary definition](#summary-MajorFail-43)	|	[Previous MajorFail outcome](#majorfail-outcome-number-42)	|	[Next MajorFail outcome](#majorfail-outcome-number-44)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-43)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-43)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-43)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:323930b3-a3ff-473f-811d-fae0fa0bbb13&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:adf26828-bdc2-42a6-aec0-a0da0e0f4d32&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:89e9aa7c-1abe-4e7a-9d9e-2fd55325dfa3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:e9fb0971-62d5-44e4-94ba-5cd5eadae5c0&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:167ae38a-dc18-4234-9cbb-235b2aae2e9a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:3a9e4a96-2481-4a33-b227-af3b60022bb7&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:e8223206-2282-43d6-bc59-ae6cc69ef28e&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:8c05aee9-fbc4-473d-b595-3f5086d8db64&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:cc250d41-b5e8-4731-a743-05d3445c5215&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:19c98502-b743-4183-bab8-4433f32c44ab&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>violation:855a6d9d-33e7-4cd7-8ed7-fb31d4d3d360&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-43)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|

***
### MajorFail Outcome number 44

[Jump to summary definition](#summary-MajorFail-44)	|	[Previous MajorFail outcome](#majorfail-outcome-number-43)	|	[Next MajorFail outcome](#majorfail-outcome-number-45)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-44)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-44)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-44)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-44)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-44)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 45

[Jump to summary definition](#summary-MajorFail-45)	|	[Previous MajorFail outcome](#majorfail-outcome-number-44)	|	[Next MajorFail outcome](#majorfail-outcome-number-46)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-45)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-45)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-45)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 46

[Jump to summary definition](#summary-MajorFail-46)	|	[Previous MajorFail outcome](#majorfail-outcome-number-45)	|	[Next MajorFail outcome](#majorfail-outcome-number-47)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-46)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-46)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-46)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 47

[Jump to summary definition](#summary-MajorFail-47)	|	[Previous MajorFail outcome](#majorfail-outcome-number-46)	|	Next MajorFail outcome

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-47)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-47)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-47)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:dc78312a-6aad-4779-917e-4b5a06c56f31&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:63532789-4437-44e2-b06f-0544b0dcfd45&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:be0c0ec8-208a-4da1-8d19-f1a1140d17f3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:bfa9722d-44f3-4d83-a77e-e36fdbe4d8fe&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:e7c905ac-a01d-4827-8185-447c7d77880d&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:74ab3e7b-0bd0-4ab3-9ec7-2325e2b89f39&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:04d96fb2-0d2f-4c71-8914-2dc3b9035af9&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:1a1dd34c-2362-4fd4-906a-0b5d0e3c04b0&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:8779a0d3-aac7-4793-bd20-597f83148859&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:b6f03648-8f0a-4fbc-ac2e-1792f9093d4e&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>violation:019204a7-db74-44e3-901f-65809bc4cf35&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-47)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

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
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-1">1/23</div>|:exclamation:MinorFail|`module-src-unreferenced`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-1)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-2">2/23</div>|:exclamation:MinorFail|`module-src-unlabeled-modelet-zedomain-label`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-2)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-3">3/23</div>|:exclamation:MinorFail|`module-src-unlabeled`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-3)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-4">4/23</div>|:exclamation:MinorFail|`module-src-too-close-terms-modelet-zedomain-differenciation`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-4)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-5">5/23</div>|:exclamation:MinorFail|`module-src-too-close-terms`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-5)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-6">6/23</div>|:exclamation:MinorFail|`module-src-not-ql-modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-6)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-7">7/23</div>|:exclamation:MinorFail|`module-src-not-ql`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-7)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-8">8/23</div>|:exclamation:MinorFail|`module-src-not-el-modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-8)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-9">9/23</div>|:exclamation:MinorFail|`module-src-not-el`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-9)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-10">10/23</div>|:exclamation:MinorFail|`modelet-zedomain-label`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-10)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-11">11/23</div>|:exclamation:MinorFail|`modelet-zedomain-differenciation`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-11)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-12">12/23</div>|:exclamation:MinorFail|`modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-12)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-13">13/23</div>|:exclamation:MinorFail|`modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-13)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-14">14/23</div>|:exclamation:MinorFail|`all-modules`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-14)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-15">15/23</div>|:exclamation:MinorFail|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-15)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-16">16/23</div>|:exclamation:MinorFail|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-16)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-17">17/23</div>|:exclamation:MinorFail|`all-modules`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-17)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-18">18/23</div>|:exclamation:MinorFail|`all-modules`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-18)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-19">19/23</div>|:exclamation:MinorFail|`all-fragments`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-19)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-20">20/23</div>|:exclamation:MinorFail|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-20)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-21">21/23</div>|:exclamation:MinorFail|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-21)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-22">22/23</div>|:exclamation:MinorFail|`all-fragments`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-22)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-23">23/23</div>|:exclamation:MinorFail|`all-fragments`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-23)|

***

## MinorFail Outcomes Details

This subchapter gives more details to the :exclamation:MinorFail outcomes

### MinorFail Outcome number 1

[Jump to summary definition](#summary-MinorFail-1)	|	Previous MinorFail outcome	|	[Next MinorFail outcome](#minorfail-outcome-number-2)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-1)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-1)|Title|Term&#32;not&#32;referenced&#32;to&#32;a&#32;module|
|[Section top](#minorfail-outcome-number-1)|Description|Subject&#32;terms&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|
|[Section top](#minorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:NotReferencedClass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;p...&#34; &#32;.</code></pre>|

***
### MinorFail Outcome number 2

[Jump to summary definition](#summary-MinorFail-2)	|	[Previous MinorFail outcome](#minorfail-outcome-number-1)	|	[Next MinorFail outcome](#minorfail-outcome-number-3)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-2)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-2)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-2)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 3

[Jump to summary definition](#summary-MinorFail-3)	|	[Previous MinorFail outcome](#minorfail-outcome-number-2)	|	[Next MinorFail outcome](#minorfail-outcome-number-4)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-3)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-3)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-3)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 4

[Jump to summary definition](#summary-MinorFail-4)	|	[Previous MinorFail outcome](#minorfail-outcome-number-3)	|	[Next MinorFail outcome](#minorfail-outcome-number-5)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-4)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-4)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-4)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 5

[Jump to summary definition](#summary-MinorFail-5)	|	[Previous MinorFail outcome](#minorfail-outcome-number-4)	|	[Next MinorFail outcome](#minorfail-outcome-number-6)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-5)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-5)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-5)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 6

[Jump to summary definition](#summary-MinorFail-6)	|	[Previous MinorFail outcome](#minorfail-outcome-number-5)	|	[Next MinorFail outcome](#minorfail-outcome-number-7)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-6)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-6)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-6)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 7

[Jump to summary definition](#summary-MinorFail-7)	|	[Previous MinorFail outcome](#minorfail-outcome-number-6)	|	[Next MinorFail outcome](#minorfail-outcome-number-8)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-7)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-7)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-7)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 8

[Jump to summary definition](#summary-MinorFail-8)	|	[Previous MinorFail outcome](#minorfail-outcome-number-7)	|	[Next MinorFail outcome](#minorfail-outcome-number-9)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-8)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-8)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-8)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-8)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 9

[Jump to summary definition](#summary-MinorFail-9)	|	[Previous MinorFail outcome](#minorfail-outcome-number-8)	|	[Next MinorFail outcome](#minorfail-outcome-number-10)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-9)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-9)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-9)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 10

[Jump to summary definition](#summary-MinorFail-10)	|	[Previous MinorFail outcome](#minorfail-outcome-number-9)	|	[Next MinorFail outcome](#minorfail-outcome-number-11)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-10)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-10)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-10)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 11

[Jump to summary definition](#summary-MinorFail-11)	|	[Previous MinorFail outcome](#minorfail-outcome-number-10)	|	[Next MinorFail outcome](#minorfail-outcome-number-12)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-11)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-11)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-11)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 12

[Jump to summary definition](#summary-MinorFail-12)	|	[Previous MinorFail outcome](#minorfail-outcome-number-11)	|	[Next MinorFail outcome](#minorfail-outcome-number-13)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-12)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-12)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-12)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 13

[Jump to summary definition](#summary-MinorFail-13)	|	[Previous MinorFail outcome](#minorfail-outcome-number-12)	|	[Next MinorFail outcome](#minorfail-outcome-number-14)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-13)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-13)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-13)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 14

[Jump to summary definition](#summary-MinorFail-14)	|	[Previous MinorFail outcome](#minorfail-outcome-number-13)	|	[Next MinorFail outcome](#minorfail-outcome-number-15)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-14)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-14)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-14)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 15

[Jump to summary definition](#summary-MinorFail-15)	|	[Previous MinorFail outcome](#minorfail-outcome-number-14)	|	[Next MinorFail outcome](#minorfail-outcome-number-16)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-15)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-15)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-15)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 16

[Jump to summary definition](#summary-MinorFail-16)	|	[Previous MinorFail outcome](#minorfail-outcome-number-15)	|	[Next MinorFail outcome](#minorfail-outcome-number-17)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-16)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-16)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-16)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 17

[Jump to summary definition](#summary-MinorFail-17)	|	[Previous MinorFail outcome](#minorfail-outcome-number-16)	|	[Next MinorFail outcome](#minorfail-outcome-number-18)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-17)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-17)|Title|Term&#32;not&#32;referenced&#32;to&#32;a&#32;module|
|[Section top](#minorfail-outcome-number-17)|Description|Subject&#32;terms&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|
|[Section top](#minorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>:NotReferencedClass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;p...&#34; &#32;.</code></pre>|

***
### MinorFail Outcome number 18

[Jump to summary definition](#summary-MinorFail-18)	|	[Previous MinorFail outcome](#minorfail-outcome-number-17)	|	[Next MinorFail outcome](#minorfail-outcome-number-19)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-18)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-18)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-18)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 19

[Jump to summary definition](#summary-MinorFail-19)	|	[Previous MinorFail outcome](#minorfail-outcome-number-18)	|	[Next MinorFail outcome](#minorfail-outcome-number-20)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-19)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-19)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-19)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 20

[Jump to summary definition](#summary-MinorFail-20)	|	[Previous MinorFail outcome](#minorfail-outcome-number-19)	|	[Next MinorFail outcome](#minorfail-outcome-number-21)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-20)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-20)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-20)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 21

[Jump to summary definition](#summary-MinorFail-21)	|	[Previous MinorFail outcome](#minorfail-outcome-number-20)	|	[Next MinorFail outcome](#minorfail-outcome-number-22)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-21)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-21)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-21)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 22

[Jump to summary definition](#summary-MinorFail-22)	|	[Previous MinorFail outcome](#minorfail-outcome-number-21)	|	[Next MinorFail outcome](#minorfail-outcome-number-23)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-22)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-22)|Title|Term&#32;not&#32;referenced&#32;to&#32;a&#32;module|
|[Section top](#minorfail-outcome-number-22)|Description|Subject&#32;terms&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|
|[Section top](#minorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>:NotReferencedClass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;p...&#34; &#32;.</code></pre>|

***
### MinorFail Outcome number 23

[Jump to summary definition](#summary-MinorFail-23)	|	[Previous MinorFail outcome](#minorfail-outcome-number-22)	|	Next MinorFail outcome

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-23)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-23)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-23)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***

</details>

***


# NotTested Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#minorfail-outcomes)	|	[Next section](#pass-outcomes)

Here is the chapter related to the NotTested outcome

:grey_question:8 NotTested outcomes

<details>
<summary>Fold/Unfold the 8 summary and details</summary>

## NotTested Outcomes Summary

:grey_question:8 NotTested outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-1">1/8</div>|:grey_question:NotTested|`module-src-unknown-prefix`|[comment-format](https://ns.inria.fr/olivaw#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-2">2/8</div>|:grey_question:NotTested|`module-src-unknown-prefix`|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-2)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-3">3/8</div>|:grey_question:NotTested|`module-src-broken`|[comment-format](https://ns.inria.fr/olivaw#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-3)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-4">4/8</div>|:grey_question:NotTested|`module-src-broken`|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-4)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-5">5/8</div>|:grey_question:NotTested|`modelet-zedomain-syntax`|[comment-format](https://ns.inria.fr/olivaw#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-5)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-6">6/8</div>|:grey_question:NotTested|`modelet-zedomain-syntax`|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-6)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-7">7/8</div>|:grey_question:NotTested|`modelet-zedomain-prefix`|[comment-format](https://ns.inria.fr/olivaw#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-7)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-8">8/8</div>|:grey_question:NotTested|`modelet-zedomain-prefix`|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-8)|

***

## NotTested Outcomes Details

This subchapter gives more details to the :grey_question:NotTested outcomes

### NotTested Outcome number 1

[Jump to summary definition](#summary-NotTested-1)	|	Previous NotTested outcome	|	[Next NotTested outcome](#nottested-outcome-number-2)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://ns.inria.fr/olivaw#comment-format)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-1)|Identifier|`comment-format`|
|[Section top](#nottested-outcome-number-1)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-1)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 2

[Jump to summary definition](#summary-NotTested-2)	|	[Previous NotTested outcome](#nottested-outcome-number-1)	|	[Next NotTested outcome](#nottested-outcome-number-3)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-2)|Identifier|`subclass-cycle`|
|[Section top](#nottested-outcome-number-2)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-2)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 3

[Jump to summary definition](#summary-NotTested-3)	|	[Previous NotTested outcome](#nottested-outcome-number-2)	|	[Next NotTested outcome](#nottested-outcome-number-4)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone&#32;module&#32;src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://ns.inria.fr/olivaw#comment-format)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-3)|Identifier|`comment-format`|
|[Section top](#nottested-outcome-number-3)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-3)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 4

[Jump to summary definition](#summary-NotTested-4)	|	[Previous NotTested outcome](#nottested-outcome-number-3)	|	[Next NotTested outcome](#nottested-outcome-number-5)

:grey_question:NotTested outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone&#32;module&#32;src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-4)|Identifier|`subclass-cycle`|
|[Section top](#nottested-outcome-number-4)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-4)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 5

[Jump to summary definition](#summary-NotTested-5)	|	[Previous NotTested outcome](#nottested-outcome-number-4)	|	[Next NotTested outcome](#nottested-outcome-number-6)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://ns.inria.fr/olivaw#comment-format)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-5)|Identifier|`comment-format`|
|[Section top](#nottested-outcome-number-5)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-5)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 6

[Jump to summary definition](#summary-NotTested-6)	|	[Previous NotTested outcome](#nottested-outcome-number-5)	|	[Next NotTested outcome](#nottested-outcome-number-7)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-6)|Identifier|`subclass-cycle`|
|[Section top](#nottested-outcome-number-6)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-6)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 7

[Jump to summary definition](#summary-NotTested-7)	|	[Previous NotTested outcome](#nottested-outcome-number-6)	|	[Next NotTested outcome](#nottested-outcome-number-8)

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://ns.inria.fr/olivaw#comment-format)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-7)|Identifier|`comment-format`|
|[Section top](#nottested-outcome-number-7)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-7)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***
### NotTested Outcome number 8

[Jump to summary definition](#summary-NotTested-8)	|	[Previous NotTested outcome](#nottested-outcome-number-7)	|	Next NotTested outcome

:grey_question:NotTested outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:grey_question:NotTested|
|----|----|----|
|[Section top](#nottested-outcome-number-8)|Identifier|`subclass-cycle`|
|[Section top](#nottested-outcome-number-8)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#nottested-outcome-number-8)|Description|Custom&#32;test&#32; &#32;could&#32;not&#32;be&#32;run&#32;because&#32;the&#32;subject&#32;could&#32;not&#32;be&#32;loaded&#32;in&#32;the&#32;engine|

***

</details>

***


# Pass Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#nottested-outcomes)	|	Next section

Here is the chapter related to the Pass outcome

:white_check_mark:344 Pass outcomes

<details>
<summary>Fold/Unfold the 344 summary and details</summary>

## Pass Outcomes Summary

:white_check_mark:344 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-1">1/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-1)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-2">2/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-2)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-3">3/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-3)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-4">4/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-4)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-5">5/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-5)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-6">6/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-6)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-7">7/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-7)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-8">8/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-8)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-9">9/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-9)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-10">10/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-10)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-11">11/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-11)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-12">12/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-12)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-13">13/344</div>|:white_check_mark:Pass|`module-src-unreferenced`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-13)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-14">14/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-14)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-15">15/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-15)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-16">16/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-16)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-17">17/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-17)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-18">18/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-18)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-19">19/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-19)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-20">20/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-20)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-21">21/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-21)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-22">22/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-22)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-23">23/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-23)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-24">24/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-24)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-25">25/344</div>|:white_check_mark:Pass|`module-src-unlabeled-modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-25)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-26">26/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-26)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-27">27/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-27)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-28">28/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-28)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-29">29/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-29)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-30">30/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-30)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-31">31/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-31)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-32">32/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-32)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-33">33/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-33)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-34">34/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-34)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-35">35/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-35)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-36">36/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-36)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-37">37/344</div>|:white_check_mark:Pass|`module-src-unlabeled`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-37)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-38">38/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-38)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-39">39/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-39)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-40">40/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-40)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-41">41/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-41)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-42">42/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-42)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-43">43/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-43)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-44">44/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-44)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-45">45/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-45)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-46">46/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-46)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-47">47/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-47)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-48">48/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-48)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-49">49/344</div>|:white_check_mark:Pass|`module-src-too-close-terms-modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-49)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-50">50/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-50)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-51">51/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-51)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-52">52/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-52)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-53">53/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-53)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-54">54/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-54)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-55">55/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-55)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-56">56/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-56)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-57">57/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-57)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-58">58/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-58)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-59">59/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-59)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-60">60/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-60)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-61">61/344</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-61)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-62">62/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-62)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-63">63/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-63)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-64">64/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-64)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-65">65/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-65)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-66">66/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-66)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-67">67/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-67)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-68">68/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-68)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-69">69/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-69)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-70">70/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-70)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-71">71/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-71)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-72">72/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-72)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-73">73/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-73)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-74">74/344</div>|:white_check_mark:Pass|`module-src-range-outer-modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-74)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-75">75/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-75)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-76">76/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-76)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-77">77/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-77)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-78">78/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-78)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-79">79/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-79)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-80">80/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-80)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-81">81/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-81)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-82">82/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-82)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-83">83/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-83)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-84">84/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-84)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-85">85/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-85)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-86">86/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-86)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-87">87/344</div>|:white_check_mark:Pass|`module-src-range-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-87)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-88">88/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-88)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-89">89/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-89)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-90">90/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-90)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-91">91/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-91)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-92">92/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-92)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-93">93/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-93)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-94">94/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-94)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-95">95/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-95)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-96">96/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-96)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-97">97/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-97)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-98">98/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-98)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-99">99/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-99)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-100">100/344</div>|:white_check_mark:Pass|`module-src-not-rl-modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-100)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-101">101/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-101)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-102">102/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-102)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-103">103/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-103)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-104">104/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-104)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-105">105/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-105)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-106">106/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-106)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-107">107/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-107)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-108">108/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-108)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-109">109/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-109)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-110">110/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-110)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-111">111/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-111)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-112">112/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-112)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-113">113/344</div>|:white_check_mark:Pass|`module-src-not-rl`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-113)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-114">114/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-114)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-115">115/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-115)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-116">116/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-116)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-117">117/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-117)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-118">118/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-118)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-119">119/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-119)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-120">120/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-120)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-121">121/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-121)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-122">122/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-122)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-123">123/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-123)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-124">124/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-124)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-125">125/344</div>|:white_check_mark:Pass|`module-src-not-ql-modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-125)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-126">126/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-126)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-127">127/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-127)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-128">128/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-128)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-129">129/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-129)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-130">130/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-130)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-131">131/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-131)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-132">132/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-132)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-133">133/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-133)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-134">134/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-134)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-135">135/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-135)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-136">136/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-136)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-137">137/344</div>|:white_check_mark:Pass|`module-src-not-ql`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-137)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-138">138/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-138)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-139">139/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-139)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-140">140/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-140)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-141">141/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-141)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-142">142/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-142)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-143">143/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-143)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-144">144/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-144)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-145">145/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-145)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-146">146/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-146)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-147">147/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-147)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-148">148/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-148)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-149">149/344</div>|:white_check_mark:Pass|`module-src-not-el-modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-149)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-150">150/344</div>|:white_check_mark:Pass|`module-src-not-el`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-150)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-151">151/344</div>|:white_check_mark:Pass|`module-src-not-el`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-151)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-152">152/344</div>|:white_check_mark:Pass|`module-src-not-el`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-152)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-153">153/344</div>|:white_check_mark:Pass|`module-src-not-el`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-153)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-154">154/344</div>|:white_check_mark:Pass|`module-src-not-el`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-154)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-155">155/344</div>|:white_check_mark:Pass|`module-src-not-el`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-155)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-156">156/344</div>|:white_check_mark:Pass|`module-src-not-el`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-156)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-157">157/344</div>|:white_check_mark:Pass|`module-src-not-el`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-157)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-158">158/344</div>|:white_check_mark:Pass|`module-src-not-el`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-158)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-159">159/344</div>|:white_check_mark:Pass|`module-src-not-el`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-159)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-160">160/344</div>|:white_check_mark:Pass|`module-src-not-el`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-160)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-161">161/344</div>|:white_check_mark:Pass|`module-src-not-el`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-161)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-162">162/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-162)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-163">163/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-163)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-164">164/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-164)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-165">165/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-165)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-166">166/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-166)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-167">167/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-167)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-168">168/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-168)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-169">169/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-169)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-170">170/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-170)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-171">171/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-171)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-172">172/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-172)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-173">173/344</div>|:white_check_mark:Pass|`module-src-inconsistent-modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-173)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-174">174/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-174)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-175">175/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-175)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-176">176/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-176)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-177">177/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-177)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-178">178/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-178)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-179">179/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-179)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-180">180/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-180)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-181">181/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-181)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-182">182/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-182)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-183">183/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-183)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-184">184/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-184)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-185">185/344</div>|:white_check_mark:Pass|`module-src-inconsistent`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-185)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-186">186/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-186)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-187">187/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-187)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-188">188/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-188)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-189">189/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-189)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-190">190/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-190)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-191">191/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-191)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-192">192/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-192)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-193">193/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-193)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-194">194/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-194)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-195">195/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-195)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-196">196/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-196)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-197">197/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-197)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-198">198/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-198)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-199">199/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-199)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-200">200/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-200)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-201">201/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-201)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-202">202/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-202)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-203">203/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-203)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-204">204/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-204)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-205">205/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-205)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-206">206/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-206)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-207">207/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-207)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-208">208/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-208)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-209">209/344</div>|:white_check_mark:Pass|`module-src-domain-outer-modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-209)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-210">210/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-210)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-211">211/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-211)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-212">212/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-212)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-213">213/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-213)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-214">214/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-214)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-215">215/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-215)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-216">216/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-216)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-217">217/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-217)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-218">218/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-218)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-219">219/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-219)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-220">220/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-220)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-221">221/344</div>|:white_check_mark:Pass|`module-src-domain-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-221)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-222">222/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-222)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-223">223/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-223)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-224">224/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-224)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-225">225/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-225)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-226">226/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-226)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-227">227/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-227)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-228">228/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-228)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-229">229/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-229)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-230">230/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-230)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-231">231/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-231)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-232">232/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-232)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-233">233/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-233)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-234">234/344</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-234)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-235">235/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-235)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-236">236/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-236)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-237">237/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-237)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-238">238/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-238)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-239">239/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-239)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-240">240/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-240)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-241">241/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-241)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-242">242/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-242)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-243">243/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-243)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-244">244/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-244)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-245">245/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-245)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-246">246/344</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-246)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-247">247/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-247)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-248">248/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-248)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-249">249/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-249)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-250">250/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-250)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-251">251/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-251)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-252">252/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-252)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-253">253/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-253)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-254">254/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-254)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-255">255/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-255)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-256">256/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-256)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-257">257/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-257)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-258">258/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-258)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-259">259/344</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-259)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-260">260/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-260)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-261">261/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-261)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-262">262/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-262)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-263">263/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-263)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-264">264/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-264)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-265">265/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-265)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-266">266/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-266)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-267">267/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-267)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-268">268/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-268)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-269">269/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-269)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-270">270/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-270)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-271">271/344</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-271)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-272">272/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-272)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-273">273/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-273)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-274">274/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-274)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-275">275/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-275)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-276">276/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-276)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-277">277/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-277)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-278">278/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-278)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-279">279/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-279)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-280">280/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-280)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-281">281/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-281)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-282">282/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-282)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-283">283/344</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-283)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-284">284/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-284)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-285">285/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-285)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-286">286/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-286)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-287">287/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-287)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-288">288/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-288)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-289">289/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-289)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-290">290/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-290)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-291">291/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-291)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-292">292/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-292)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-293">293/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-293)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-294">294/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-294)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-295">295/344</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-295)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-296">296/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-296)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-297">297/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-297)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-298">298/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-298)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-299">299/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-299)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-300">300/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-300)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-301">301/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-301)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-302">302/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-302)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-303">303/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-303)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-304">304/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-304)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-305">305/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-305)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-306">306/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-306)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-307">307/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-307)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-308">308/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-308)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-309">309/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-309)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-310">310/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-310)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-311">311/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-311)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-312">312/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-312)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-313">313/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-313)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-314">314/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-314)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-315">315/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-315)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-316">316/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-316)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-317">317/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-317)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-318">318/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-318)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-319">319/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-319)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-320">320/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-320)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-321">321/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-321)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-322">322/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-322)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-323">323/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-323)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-324">324/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-324)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-325">325/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-325)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-326">326/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-326)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-327">327/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-327)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-328">328/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-328)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-329">329/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-329)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-330">330/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-330)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-331">331/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-331)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-332">332/344</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-332)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-333">333/344</div>|:white_check_mark:Pass|`all-modules`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-333)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-334">334/344</div>|:white_check_mark:Pass|`all-modules`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-334)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-335">335/344</div>|:white_check_mark:Pass|`all-modules`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-335)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-336">336/344</div>|:white_check_mark:Pass|`all-modules`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-336)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-337">337/344</div>|:white_check_mark:Pass|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-337)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-338">338/344</div>|:white_check_mark:Pass|`all-modules`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-338)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-339">339/344</div>|:white_check_mark:Pass|`all-fragments`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subclass of property|[Jump](#pass-outcome-number-339)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-340">340/344</div>|:white_check_mark:Pass|`all-fragments`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No subproperty of class|[Jump](#pass-outcome-number-340)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-341">341/344</div>|:white_check_mark:Pass|`all-fragments`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No class subproperty|[Jump](#pass-outcome-number-341)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-342">342/344</div>|:white_check_mark:Pass|`all-fragments`|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|No property subclass|[Jump](#pass-outcome-number-342)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-343">343/344</div>|:white_check_mark:Pass|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-343)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-344">344/344</div>|:white_check_mark:Pass|`all-fragments`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-344)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)	|	Previous Pass outcome	|	[Next Pass outcome](#pass-outcome-number-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-1)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-1)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-1)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 2

[Jump to summary definition](#summary-Pass-2)	|	[Previous Pass outcome](#pass-outcome-number-1)	|	[Next Pass outcome](#pass-outcome-number-3)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-2)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-2)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-2)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 3

[Jump to summary definition](#summary-Pass-3)	|	[Previous Pass outcome](#pass-outcome-number-2)	|	[Next Pass outcome](#pass-outcome-number-4)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-3)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-3)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-3)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 4

[Jump to summary definition](#summary-Pass-4)	|	[Previous Pass outcome](#pass-outcome-number-3)	|	[Next Pass outcome](#pass-outcome-number-5)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-4)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-4)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-4)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)	|	[Previous Pass outcome](#pass-outcome-number-4)	|	[Next Pass outcome](#pass-outcome-number-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-5)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-5)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-5)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)	|	[Previous Pass outcome](#pass-outcome-number-5)	|	[Next Pass outcome](#pass-outcome-number-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-6)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-6)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-6)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 7

[Jump to summary definition](#summary-Pass-7)	|	[Previous Pass outcome](#pass-outcome-number-6)	|	[Next Pass outcome](#pass-outcome-number-8)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-7)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-7)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-7)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 8

[Jump to summary definition](#summary-Pass-8)	|	[Previous Pass outcome](#pass-outcome-number-7)	|	[Next Pass outcome](#pass-outcome-number-9)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-8)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-8)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-8)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 9

[Jump to summary definition](#summary-Pass-9)	|	[Previous Pass outcome](#pass-outcome-number-8)	|	[Next Pass outcome](#pass-outcome-number-10)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-9)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-9)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-9)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 10

[Jump to summary definition](#summary-Pass-10)	|	[Previous Pass outcome](#pass-outcome-number-9)	|	[Next Pass outcome](#pass-outcome-number-11)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-10)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-10)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-10)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)	|	[Previous Pass outcome](#pass-outcome-number-10)	|	[Next Pass outcome](#pass-outcome-number-12)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-11)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-11)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-11)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 12

[Jump to summary definition](#summary-Pass-12)	|	[Previous Pass outcome](#pass-outcome-number-11)	|	[Next Pass outcome](#pass-outcome-number-13)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-12)|Identifier|`comment-format`|
|[Section top](#pass-outcome-number-12)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-12)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 13

[Jump to summary definition](#summary-Pass-13)	|	[Previous Pass outcome](#pass-outcome-number-12)	|	[Next Pass outcome](#pass-outcome-number-14)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-13)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-13)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-13)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 14

[Jump to summary definition](#summary-Pass-14)	|	[Previous Pass outcome](#pass-outcome-number-13)	|	[Next Pass outcome](#pass-outcome-number-15)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-14)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-14)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-14)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)	|	[Previous Pass outcome](#pass-outcome-number-14)	|	[Next Pass outcome](#pass-outcome-number-16)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-15)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-15)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-15)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 16

[Jump to summary definition](#summary-Pass-16)	|	[Previous Pass outcome](#pass-outcome-number-15)	|	[Next Pass outcome](#pass-outcome-number-17)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-16)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-16)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-16)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 17

[Jump to summary definition](#summary-Pass-17)	|	[Previous Pass outcome](#pass-outcome-number-16)	|	[Next Pass outcome](#pass-outcome-number-18)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-17)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-17)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-17)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 18

[Jump to summary definition](#summary-Pass-18)	|	[Previous Pass outcome](#pass-outcome-number-17)	|	[Next Pass outcome](#pass-outcome-number-19)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-18)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-18)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-18)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 19

[Jump to summary definition](#summary-Pass-19)	|	[Previous Pass outcome](#pass-outcome-number-18)	|	[Next Pass outcome](#pass-outcome-number-20)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-19)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-19)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-19)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 20

[Jump to summary definition](#summary-Pass-20)	|	[Previous Pass outcome](#pass-outcome-number-19)	|	[Next Pass outcome](#pass-outcome-number-21)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-20)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-20)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-20)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 21

[Jump to summary definition](#summary-Pass-21)	|	[Previous Pass outcome](#pass-outcome-number-20)	|	[Next Pass outcome](#pass-outcome-number-22)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-21)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-21)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-21)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 22

[Jump to summary definition](#summary-Pass-22)	|	[Previous Pass outcome](#pass-outcome-number-21)	|	[Next Pass outcome](#pass-outcome-number-23)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-22)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-22)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-22)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 23

[Jump to summary definition](#summary-Pass-23)	|	[Previous Pass outcome](#pass-outcome-number-22)	|	[Next Pass outcome](#pass-outcome-number-24)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-23)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-23)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-23)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 24

[Jump to summary definition](#summary-Pass-24)	|	[Previous Pass outcome](#pass-outcome-number-23)	|	[Next Pass outcome](#pass-outcome-number-25)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-24)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-24)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-24)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 25

[Jump to summary definition](#summary-Pass-25)	|	[Previous Pass outcome](#pass-outcome-number-24)	|	[Next Pass outcome](#pass-outcome-number-26)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled-modelet-zedomain-label|
|----|----|
|Title|Merged&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/label/onto.ttl|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-25)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-25)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-25)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 26

[Jump to summary definition](#summary-Pass-26)	|	[Previous Pass outcome](#pass-outcome-number-25)	|	[Next Pass outcome](#pass-outcome-number-27)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-26)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-26)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-26)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 27

[Jump to summary definition](#summary-Pass-27)	|	[Previous Pass outcome](#pass-outcome-number-26)	|	[Next Pass outcome](#pass-outcome-number-28)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-27)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-27)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-27)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 28

[Jump to summary definition](#summary-Pass-28)	|	[Previous Pass outcome](#pass-outcome-number-27)	|	[Next Pass outcome](#pass-outcome-number-29)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-28)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-28)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-28)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 29

[Jump to summary definition](#summary-Pass-29)	|	[Previous Pass outcome](#pass-outcome-number-28)	|	[Next Pass outcome](#pass-outcome-number-30)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-29)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-29)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-29)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 30

[Jump to summary definition](#summary-Pass-30)	|	[Previous Pass outcome](#pass-outcome-number-29)	|	[Next Pass outcome](#pass-outcome-number-31)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-30)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-30)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-30)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 31

[Jump to summary definition](#summary-Pass-31)	|	[Previous Pass outcome](#pass-outcome-number-30)	|	[Next Pass outcome](#pass-outcome-number-32)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-31)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-31)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-31)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 32

[Jump to summary definition](#summary-Pass-32)	|	[Previous Pass outcome](#pass-outcome-number-31)	|	[Next Pass outcome](#pass-outcome-number-33)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-32)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-32)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-32)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 33

[Jump to summary definition](#summary-Pass-33)	|	[Previous Pass outcome](#pass-outcome-number-32)	|	[Next Pass outcome](#pass-outcome-number-34)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-33)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-33)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-33)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 34

[Jump to summary definition](#summary-Pass-34)	|	[Previous Pass outcome](#pass-outcome-number-33)	|	[Next Pass outcome](#pass-outcome-number-35)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-34)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-34)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-34)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 35

[Jump to summary definition](#summary-Pass-35)	|	[Previous Pass outcome](#pass-outcome-number-34)	|	[Next Pass outcome](#pass-outcome-number-36)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-35)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-35)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-35)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 36

[Jump to summary definition](#summary-Pass-36)	|	[Previous Pass outcome](#pass-outcome-number-35)	|	[Next Pass outcome](#pass-outcome-number-37)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-36)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-36)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-36)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 37

[Jump to summary definition](#summary-Pass-37)	|	[Previous Pass outcome](#pass-outcome-number-36)	|	[Next Pass outcome](#pass-outcome-number-38)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-37)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-37)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-37)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 38

[Jump to summary definition](#summary-Pass-38)	|	[Previous Pass outcome](#pass-outcome-number-37)	|	[Next Pass outcome](#pass-outcome-number-39)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-38)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-38)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-38)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 39

[Jump to summary definition](#summary-Pass-39)	|	[Previous Pass outcome](#pass-outcome-number-38)	|	[Next Pass outcome](#pass-outcome-number-40)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-39)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-39)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-39)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 40

[Jump to summary definition](#summary-Pass-40)	|	[Previous Pass outcome](#pass-outcome-number-39)	|	[Next Pass outcome](#pass-outcome-number-41)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-40)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-40)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-40)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 41

[Jump to summary definition](#summary-Pass-41)	|	[Previous Pass outcome](#pass-outcome-number-40)	|	[Next Pass outcome](#pass-outcome-number-42)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-41)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-41)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-41)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 42

[Jump to summary definition](#summary-Pass-42)	|	[Previous Pass outcome](#pass-outcome-number-41)	|	[Next Pass outcome](#pass-outcome-number-43)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-42)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-42)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-42)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 43

[Jump to summary definition](#summary-Pass-43)	|	[Previous Pass outcome](#pass-outcome-number-42)	|	[Next Pass outcome](#pass-outcome-number-44)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-43)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-43)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-43)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 44

[Jump to summary definition](#summary-Pass-44)	|	[Previous Pass outcome](#pass-outcome-number-43)	|	[Next Pass outcome](#pass-outcome-number-45)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-44)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-44)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-44)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 45

[Jump to summary definition](#summary-Pass-45)	|	[Previous Pass outcome](#pass-outcome-number-44)	|	[Next Pass outcome](#pass-outcome-number-46)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-45)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-45)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-45)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 46

[Jump to summary definition](#summary-Pass-46)	|	[Previous Pass outcome](#pass-outcome-number-45)	|	[Next Pass outcome](#pass-outcome-number-47)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-46)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-46)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-46)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 47

[Jump to summary definition](#summary-Pass-47)	|	[Previous Pass outcome](#pass-outcome-number-46)	|	[Next Pass outcome](#pass-outcome-number-48)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-47)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-47)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-47)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 48

[Jump to summary definition](#summary-Pass-48)	|	[Previous Pass outcome](#pass-outcome-number-47)	|	[Next Pass outcome](#pass-outcome-number-49)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-48)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-48)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-48)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 49

[Jump to summary definition](#summary-Pass-49)	|	[Previous Pass outcome](#pass-outcome-number-48)	|	[Next Pass outcome](#pass-outcome-number-50)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms-modelet-zedomain-differenciation|
|----|----|
|Title|Merged&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/differenciation/onto.ttl|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-49)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-49)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-49)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 50

[Jump to summary definition](#summary-Pass-50)	|	[Previous Pass outcome](#pass-outcome-number-49)	|	[Next Pass outcome](#pass-outcome-number-51)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-50)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-50)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-50)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 51

[Jump to summary definition](#summary-Pass-51)	|	[Previous Pass outcome](#pass-outcome-number-50)	|	[Next Pass outcome](#pass-outcome-number-52)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-51)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-51)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-51)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 52

[Jump to summary definition](#summary-Pass-52)	|	[Previous Pass outcome](#pass-outcome-number-51)	|	[Next Pass outcome](#pass-outcome-number-53)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-52)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-52)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-52)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 53

[Jump to summary definition](#summary-Pass-53)	|	[Previous Pass outcome](#pass-outcome-number-52)	|	[Next Pass outcome](#pass-outcome-number-54)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-53)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-53)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-53)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 54

[Jump to summary definition](#summary-Pass-54)	|	[Previous Pass outcome](#pass-outcome-number-53)	|	[Next Pass outcome](#pass-outcome-number-55)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-54)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-54)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-54)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 55

[Jump to summary definition](#summary-Pass-55)	|	[Previous Pass outcome](#pass-outcome-number-54)	|	[Next Pass outcome](#pass-outcome-number-56)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-55)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-55)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-55)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 56

[Jump to summary definition](#summary-Pass-56)	|	[Previous Pass outcome](#pass-outcome-number-55)	|	[Next Pass outcome](#pass-outcome-number-57)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-56)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-56)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-56)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 57

[Jump to summary definition](#summary-Pass-57)	|	[Previous Pass outcome](#pass-outcome-number-56)	|	[Next Pass outcome](#pass-outcome-number-58)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-57)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-57)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-57)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 58

[Jump to summary definition](#summary-Pass-58)	|	[Previous Pass outcome](#pass-outcome-number-57)	|	[Next Pass outcome](#pass-outcome-number-59)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-58)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-58)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-58)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 59

[Jump to summary definition](#summary-Pass-59)	|	[Previous Pass outcome](#pass-outcome-number-58)	|	[Next Pass outcome](#pass-outcome-number-60)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-59)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-59)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-59)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 60

[Jump to summary definition](#summary-Pass-60)	|	[Previous Pass outcome](#pass-outcome-number-59)	|	[Next Pass outcome](#pass-outcome-number-61)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-60)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-60)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-60)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 61

[Jump to summary definition](#summary-Pass-61)	|	[Previous Pass outcome](#pass-outcome-number-60)	|	[Next Pass outcome](#pass-outcome-number-62)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-61)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-61)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-61)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 62

[Jump to summary definition](#summary-Pass-62)	|	[Previous Pass outcome](#pass-outcome-number-61)	|	[Next Pass outcome](#pass-outcome-number-63)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-62)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-62)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-62)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 63

[Jump to summary definition](#summary-Pass-63)	|	[Previous Pass outcome](#pass-outcome-number-62)	|	[Next Pass outcome](#pass-outcome-number-64)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-63)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-63)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-63)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 64

[Jump to summary definition](#summary-Pass-64)	|	[Previous Pass outcome](#pass-outcome-number-63)	|	[Next Pass outcome](#pass-outcome-number-65)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-64)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-64)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-64)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 65

[Jump to summary definition](#summary-Pass-65)	|	[Previous Pass outcome](#pass-outcome-number-64)	|	[Next Pass outcome](#pass-outcome-number-66)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-65)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-65)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-65)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 66

[Jump to summary definition](#summary-Pass-66)	|	[Previous Pass outcome](#pass-outcome-number-65)	|	[Next Pass outcome](#pass-outcome-number-67)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-66)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-66)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-66)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 67

[Jump to summary definition](#summary-Pass-67)	|	[Previous Pass outcome](#pass-outcome-number-66)	|	[Next Pass outcome](#pass-outcome-number-68)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-67)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-67)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-67)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 68

[Jump to summary definition](#summary-Pass-68)	|	[Previous Pass outcome](#pass-outcome-number-67)	|	[Next Pass outcome](#pass-outcome-number-69)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-68)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-68)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-68)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 69

[Jump to summary definition](#summary-Pass-69)	|	[Previous Pass outcome](#pass-outcome-number-68)	|	[Next Pass outcome](#pass-outcome-number-70)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-69)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-69)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-69)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 70

[Jump to summary definition](#summary-Pass-70)	|	[Previous Pass outcome](#pass-outcome-number-69)	|	[Next Pass outcome](#pass-outcome-number-71)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-70)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-70)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-70)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 71

[Jump to summary definition](#summary-Pass-71)	|	[Previous Pass outcome](#pass-outcome-number-70)	|	[Next Pass outcome](#pass-outcome-number-72)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-71)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-71)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-71)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 72

[Jump to summary definition](#summary-Pass-72)	|	[Previous Pass outcome](#pass-outcome-number-71)	|	[Next Pass outcome](#pass-outcome-number-73)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-72)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-72)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-72)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 73

[Jump to summary definition](#summary-Pass-73)	|	[Previous Pass outcome](#pass-outcome-number-72)	|	[Next Pass outcome](#pass-outcome-number-74)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-73)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-73)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-73)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 74

[Jump to summary definition](#summary-Pass-74)	|	[Previous Pass outcome](#pass-outcome-number-73)	|	[Next Pass outcome](#pass-outcome-number-75)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer-modelet-zedomain-rangeout|
|----|----|
|Title|Merged&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/rangeout/onto.ttl|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-74)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-74)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-74)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 75

[Jump to summary definition](#summary-Pass-75)	|	[Previous Pass outcome](#pass-outcome-number-74)	|	[Next Pass outcome](#pass-outcome-number-76)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-75)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-75)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-75)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 76

[Jump to summary definition](#summary-Pass-76)	|	[Previous Pass outcome](#pass-outcome-number-75)	|	[Next Pass outcome](#pass-outcome-number-77)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-76)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-76)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-76)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 77

[Jump to summary definition](#summary-Pass-77)	|	[Previous Pass outcome](#pass-outcome-number-76)	|	[Next Pass outcome](#pass-outcome-number-78)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-77)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-77)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-77)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 78

[Jump to summary definition](#summary-Pass-78)	|	[Previous Pass outcome](#pass-outcome-number-77)	|	[Next Pass outcome](#pass-outcome-number-79)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-78)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-78)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-78)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 79

[Jump to summary definition](#summary-Pass-79)	|	[Previous Pass outcome](#pass-outcome-number-78)	|	[Next Pass outcome](#pass-outcome-number-80)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-79)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-79)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-79)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 80

[Jump to summary definition](#summary-Pass-80)	|	[Previous Pass outcome](#pass-outcome-number-79)	|	[Next Pass outcome](#pass-outcome-number-81)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-80)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-80)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-80)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 81

[Jump to summary definition](#summary-Pass-81)	|	[Previous Pass outcome](#pass-outcome-number-80)	|	[Next Pass outcome](#pass-outcome-number-82)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-81)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-81)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-81)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 82

[Jump to summary definition](#summary-Pass-82)	|	[Previous Pass outcome](#pass-outcome-number-81)	|	[Next Pass outcome](#pass-outcome-number-83)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-82)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-82)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-82)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 83

[Jump to summary definition](#summary-Pass-83)	|	[Previous Pass outcome](#pass-outcome-number-82)	|	[Next Pass outcome](#pass-outcome-number-84)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-83)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-83)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-83)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 84

[Jump to summary definition](#summary-Pass-84)	|	[Previous Pass outcome](#pass-outcome-number-83)	|	[Next Pass outcome](#pass-outcome-number-85)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-84)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-84)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-84)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 85

[Jump to summary definition](#summary-Pass-85)	|	[Previous Pass outcome](#pass-outcome-number-84)	|	[Next Pass outcome](#pass-outcome-number-86)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-85)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-85)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-85)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 86

[Jump to summary definition](#summary-Pass-86)	|	[Previous Pass outcome](#pass-outcome-number-85)	|	[Next Pass outcome](#pass-outcome-number-87)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-86)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-86)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-86)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 87

[Jump to summary definition](#summary-Pass-87)	|	[Previous Pass outcome](#pass-outcome-number-86)	|	[Next Pass outcome](#pass-outcome-number-88)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-87)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-87)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-87)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 88

[Jump to summary definition](#summary-Pass-88)	|	[Previous Pass outcome](#pass-outcome-number-87)	|	[Next Pass outcome](#pass-outcome-number-89)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-88)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-88)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-88)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 89

[Jump to summary definition](#summary-Pass-89)	|	[Previous Pass outcome](#pass-outcome-number-88)	|	[Next Pass outcome](#pass-outcome-number-90)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-89)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-89)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-89)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 90

[Jump to summary definition](#summary-Pass-90)	|	[Previous Pass outcome](#pass-outcome-number-89)	|	[Next Pass outcome](#pass-outcome-number-91)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-90)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-90)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-90)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 91

[Jump to summary definition](#summary-Pass-91)	|	[Previous Pass outcome](#pass-outcome-number-90)	|	[Next Pass outcome](#pass-outcome-number-92)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-91)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-91)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-91)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 92

[Jump to summary definition](#summary-Pass-92)	|	[Previous Pass outcome](#pass-outcome-number-91)	|	[Next Pass outcome](#pass-outcome-number-93)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-92)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-92)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-92)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 93

[Jump to summary definition](#summary-Pass-93)	|	[Previous Pass outcome](#pass-outcome-number-92)	|	[Next Pass outcome](#pass-outcome-number-94)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-93)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-93)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-93)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 94

[Jump to summary definition](#summary-Pass-94)	|	[Previous Pass outcome](#pass-outcome-number-93)	|	[Next Pass outcome](#pass-outcome-number-95)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-94)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-94)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-94)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 95

[Jump to summary definition](#summary-Pass-95)	|	[Previous Pass outcome](#pass-outcome-number-94)	|	[Next Pass outcome](#pass-outcome-number-96)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-95)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-95)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-95)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 96

[Jump to summary definition](#summary-Pass-96)	|	[Previous Pass outcome](#pass-outcome-number-95)	|	[Next Pass outcome](#pass-outcome-number-97)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-96)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-96)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-96)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 97

[Jump to summary definition](#summary-Pass-97)	|	[Previous Pass outcome](#pass-outcome-number-96)	|	[Next Pass outcome](#pass-outcome-number-98)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-97)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-97)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-97)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 98

[Jump to summary definition](#summary-Pass-98)	|	[Previous Pass outcome](#pass-outcome-number-97)	|	[Next Pass outcome](#pass-outcome-number-99)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-98)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-98)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-98)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 99

[Jump to summary definition](#summary-Pass-99)	|	[Previous Pass outcome](#pass-outcome-number-98)	|	[Next Pass outcome](#pass-outcome-number-100)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-99)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-99)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-99)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 100

[Jump to summary definition](#summary-Pass-100)	|	[Previous Pass outcome](#pass-outcome-number-99)	|	[Next Pass outcome](#pass-outcome-number-101)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl-modelet-zedomain-compatRL|
|----|----|
|Title|Merged&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatRL/onto.ttl|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-100)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-100)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-100)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 101

[Jump to summary definition](#summary-Pass-101)	|	[Previous Pass outcome](#pass-outcome-number-100)	|	[Next Pass outcome](#pass-outcome-number-102)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-101)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-101)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-101)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 102

[Jump to summary definition](#summary-Pass-102)	|	[Previous Pass outcome](#pass-outcome-number-101)	|	[Next Pass outcome](#pass-outcome-number-103)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-102)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-102)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-102)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 103

[Jump to summary definition](#summary-Pass-103)	|	[Previous Pass outcome](#pass-outcome-number-102)	|	[Next Pass outcome](#pass-outcome-number-104)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-103)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-103)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-103)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 104

[Jump to summary definition](#summary-Pass-104)	|	[Previous Pass outcome](#pass-outcome-number-103)	|	[Next Pass outcome](#pass-outcome-number-105)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-104)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-104)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-104)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 105

[Jump to summary definition](#summary-Pass-105)	|	[Previous Pass outcome](#pass-outcome-number-104)	|	[Next Pass outcome](#pass-outcome-number-106)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-105)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-105)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-105)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 106

[Jump to summary definition](#summary-Pass-106)	|	[Previous Pass outcome](#pass-outcome-number-105)	|	[Next Pass outcome](#pass-outcome-number-107)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-106)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-106)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-106)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 107

[Jump to summary definition](#summary-Pass-107)	|	[Previous Pass outcome](#pass-outcome-number-106)	|	[Next Pass outcome](#pass-outcome-number-108)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-107)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-107)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-107)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 108

[Jump to summary definition](#summary-Pass-108)	|	[Previous Pass outcome](#pass-outcome-number-107)	|	[Next Pass outcome](#pass-outcome-number-109)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-108)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-108)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-108)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 109

[Jump to summary definition](#summary-Pass-109)	|	[Previous Pass outcome](#pass-outcome-number-108)	|	[Next Pass outcome](#pass-outcome-number-110)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-109)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-109)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-109)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 110

[Jump to summary definition](#summary-Pass-110)	|	[Previous Pass outcome](#pass-outcome-number-109)	|	[Next Pass outcome](#pass-outcome-number-111)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-110)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-110)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-110)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 111

[Jump to summary definition](#summary-Pass-111)	|	[Previous Pass outcome](#pass-outcome-number-110)	|	[Next Pass outcome](#pass-outcome-number-112)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-111)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-111)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-111)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 112

[Jump to summary definition](#summary-Pass-112)	|	[Previous Pass outcome](#pass-outcome-number-111)	|	[Next Pass outcome](#pass-outcome-number-113)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-112)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-112)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-112)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 113

[Jump to summary definition](#summary-Pass-113)	|	[Previous Pass outcome](#pass-outcome-number-112)	|	[Next Pass outcome](#pass-outcome-number-114)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-113)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-113)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-113)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 114

[Jump to summary definition](#summary-Pass-114)	|	[Previous Pass outcome](#pass-outcome-number-113)	|	[Next Pass outcome](#pass-outcome-number-115)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-114)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-114)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-114)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 115

[Jump to summary definition](#summary-Pass-115)	|	[Previous Pass outcome](#pass-outcome-number-114)	|	[Next Pass outcome](#pass-outcome-number-116)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-115)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-115)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-115)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 116

[Jump to summary definition](#summary-Pass-116)	|	[Previous Pass outcome](#pass-outcome-number-115)	|	[Next Pass outcome](#pass-outcome-number-117)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-116)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-116)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-116)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 117

[Jump to summary definition](#summary-Pass-117)	|	[Previous Pass outcome](#pass-outcome-number-116)	|	[Next Pass outcome](#pass-outcome-number-118)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-117)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-117)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-117)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 118

[Jump to summary definition](#summary-Pass-118)	|	[Previous Pass outcome](#pass-outcome-number-117)	|	[Next Pass outcome](#pass-outcome-number-119)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-118)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-118)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-118)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 119

[Jump to summary definition](#summary-Pass-119)	|	[Previous Pass outcome](#pass-outcome-number-118)	|	[Next Pass outcome](#pass-outcome-number-120)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-119)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-119)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-119)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 120

[Jump to summary definition](#summary-Pass-120)	|	[Previous Pass outcome](#pass-outcome-number-119)	|	[Next Pass outcome](#pass-outcome-number-121)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-120)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-120)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-120)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 121

[Jump to summary definition](#summary-Pass-121)	|	[Previous Pass outcome](#pass-outcome-number-120)	|	[Next Pass outcome](#pass-outcome-number-122)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-121)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-121)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-121)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 122

[Jump to summary definition](#summary-Pass-122)	|	[Previous Pass outcome](#pass-outcome-number-121)	|	[Next Pass outcome](#pass-outcome-number-123)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-122)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-122)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-122)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 123

[Jump to summary definition](#summary-Pass-123)	|	[Previous Pass outcome](#pass-outcome-number-122)	|	[Next Pass outcome](#pass-outcome-number-124)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-123)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-123)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-123)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 124

[Jump to summary definition](#summary-Pass-124)	|	[Previous Pass outcome](#pass-outcome-number-123)	|	[Next Pass outcome](#pass-outcome-number-125)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-124)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-124)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-124)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 125

[Jump to summary definition](#summary-Pass-125)	|	[Previous Pass outcome](#pass-outcome-number-124)	|	[Next Pass outcome](#pass-outcome-number-126)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql-modelet-zedomain-compatQL|
|----|----|
|Title|Merged&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatQL/onto.ttl|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-125)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-125)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-125)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 126

[Jump to summary definition](#summary-Pass-126)	|	[Previous Pass outcome](#pass-outcome-number-125)	|	[Next Pass outcome](#pass-outcome-number-127)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-126)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-126)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-126)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 127

[Jump to summary definition](#summary-Pass-127)	|	[Previous Pass outcome](#pass-outcome-number-126)	|	[Next Pass outcome](#pass-outcome-number-128)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-127)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-127)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-127)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 128

[Jump to summary definition](#summary-Pass-128)	|	[Previous Pass outcome](#pass-outcome-number-127)	|	[Next Pass outcome](#pass-outcome-number-129)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-128)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-128)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-128)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 129

[Jump to summary definition](#summary-Pass-129)	|	[Previous Pass outcome](#pass-outcome-number-128)	|	[Next Pass outcome](#pass-outcome-number-130)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-129)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-129)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-129)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 130

[Jump to summary definition](#summary-Pass-130)	|	[Previous Pass outcome](#pass-outcome-number-129)	|	[Next Pass outcome](#pass-outcome-number-131)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-130)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-130)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-130)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 131

[Jump to summary definition](#summary-Pass-131)	|	[Previous Pass outcome](#pass-outcome-number-130)	|	[Next Pass outcome](#pass-outcome-number-132)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-131)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-131)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-131)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 132

[Jump to summary definition](#summary-Pass-132)	|	[Previous Pass outcome](#pass-outcome-number-131)	|	[Next Pass outcome](#pass-outcome-number-133)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-132)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-132)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-132)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 133

[Jump to summary definition](#summary-Pass-133)	|	[Previous Pass outcome](#pass-outcome-number-132)	|	[Next Pass outcome](#pass-outcome-number-134)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-133)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-133)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-133)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 134

[Jump to summary definition](#summary-Pass-134)	|	[Previous Pass outcome](#pass-outcome-number-133)	|	[Next Pass outcome](#pass-outcome-number-135)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-134)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-134)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-134)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 135

[Jump to summary definition](#summary-Pass-135)	|	[Previous Pass outcome](#pass-outcome-number-134)	|	[Next Pass outcome](#pass-outcome-number-136)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-135)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-135)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-135)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 136

[Jump to summary definition](#summary-Pass-136)	|	[Previous Pass outcome](#pass-outcome-number-135)	|	[Next Pass outcome](#pass-outcome-number-137)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-136)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-136)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-136)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 137

[Jump to summary definition](#summary-Pass-137)	|	[Previous Pass outcome](#pass-outcome-number-136)	|	[Next Pass outcome](#pass-outcome-number-138)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-137)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-137)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-137)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 138

[Jump to summary definition](#summary-Pass-138)	|	[Previous Pass outcome](#pass-outcome-number-137)	|	[Next Pass outcome](#pass-outcome-number-139)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-138)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-138)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-138)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 139

[Jump to summary definition](#summary-Pass-139)	|	[Previous Pass outcome](#pass-outcome-number-138)	|	[Next Pass outcome](#pass-outcome-number-140)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-139)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-139)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-139)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 140

[Jump to summary definition](#summary-Pass-140)	|	[Previous Pass outcome](#pass-outcome-number-139)	|	[Next Pass outcome](#pass-outcome-number-141)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-140)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-140)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-140)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 141

[Jump to summary definition](#summary-Pass-141)	|	[Previous Pass outcome](#pass-outcome-number-140)	|	[Next Pass outcome](#pass-outcome-number-142)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-141)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-141)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-141)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 142

[Jump to summary definition](#summary-Pass-142)	|	[Previous Pass outcome](#pass-outcome-number-141)	|	[Next Pass outcome](#pass-outcome-number-143)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-142)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-142)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-142)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 143

[Jump to summary definition](#summary-Pass-143)	|	[Previous Pass outcome](#pass-outcome-number-142)	|	[Next Pass outcome](#pass-outcome-number-144)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-143)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-143)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-143)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 144

[Jump to summary definition](#summary-Pass-144)	|	[Previous Pass outcome](#pass-outcome-number-143)	|	[Next Pass outcome](#pass-outcome-number-145)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-144)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-144)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-144)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 145

[Jump to summary definition](#summary-Pass-145)	|	[Previous Pass outcome](#pass-outcome-number-144)	|	[Next Pass outcome](#pass-outcome-number-146)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-145)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-145)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-145)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 146

[Jump to summary definition](#summary-Pass-146)	|	[Previous Pass outcome](#pass-outcome-number-145)	|	[Next Pass outcome](#pass-outcome-number-147)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-146)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-146)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-146)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 147

[Jump to summary definition](#summary-Pass-147)	|	[Previous Pass outcome](#pass-outcome-number-146)	|	[Next Pass outcome](#pass-outcome-number-148)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-147)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-147)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-147)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 148

[Jump to summary definition](#summary-Pass-148)	|	[Previous Pass outcome](#pass-outcome-number-147)	|	[Next Pass outcome](#pass-outcome-number-149)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-148)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-148)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-148)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 149

[Jump to summary definition](#summary-Pass-149)	|	[Previous Pass outcome](#pass-outcome-number-148)	|	[Next Pass outcome](#pass-outcome-number-150)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el-modelet-zedomain-compatEL|
|----|----|
|Title|Merged&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/compatEL/onto.ttl|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-149)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-149)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-149)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 150

[Jump to summary definition](#summary-Pass-150)	|	[Previous Pass outcome](#pass-outcome-number-149)	|	[Next Pass outcome](#pass-outcome-number-151)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-150)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-150)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-150)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 151

[Jump to summary definition](#summary-Pass-151)	|	[Previous Pass outcome](#pass-outcome-number-150)	|	[Next Pass outcome](#pass-outcome-number-152)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-151)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-151)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-151)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 152

[Jump to summary definition](#summary-Pass-152)	|	[Previous Pass outcome](#pass-outcome-number-151)	|	[Next Pass outcome](#pass-outcome-number-153)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-152)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-152)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-152)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 153

[Jump to summary definition](#summary-Pass-153)	|	[Previous Pass outcome](#pass-outcome-number-152)	|	[Next Pass outcome](#pass-outcome-number-154)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-153)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-153)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-153)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 154

[Jump to summary definition](#summary-Pass-154)	|	[Previous Pass outcome](#pass-outcome-number-153)	|	[Next Pass outcome](#pass-outcome-number-155)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-154)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-154)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-154)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 155

[Jump to summary definition](#summary-Pass-155)	|	[Previous Pass outcome](#pass-outcome-number-154)	|	[Next Pass outcome](#pass-outcome-number-156)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-155)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-155)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-155)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 156

[Jump to summary definition](#summary-Pass-156)	|	[Previous Pass outcome](#pass-outcome-number-155)	|	[Next Pass outcome](#pass-outcome-number-157)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-156)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-156)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-156)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 157

[Jump to summary definition](#summary-Pass-157)	|	[Previous Pass outcome](#pass-outcome-number-156)	|	[Next Pass outcome](#pass-outcome-number-158)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-157)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-157)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-157)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 158

[Jump to summary definition](#summary-Pass-158)	|	[Previous Pass outcome](#pass-outcome-number-157)	|	[Next Pass outcome](#pass-outcome-number-159)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-158)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-158)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-158)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 159

[Jump to summary definition](#summary-Pass-159)	|	[Previous Pass outcome](#pass-outcome-number-158)	|	[Next Pass outcome](#pass-outcome-number-160)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-159)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-159)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-159)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 160

[Jump to summary definition](#summary-Pass-160)	|	[Previous Pass outcome](#pass-outcome-number-159)	|	[Next Pass outcome](#pass-outcome-number-161)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-160)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-160)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-160)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 161

[Jump to summary definition](#summary-Pass-161)	|	[Previous Pass outcome](#pass-outcome-number-160)	|	[Next Pass outcome](#pass-outcome-number-162)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-161)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-161)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-161)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 162

[Jump to summary definition](#summary-Pass-162)	|	[Previous Pass outcome](#pass-outcome-number-161)	|	[Next Pass outcome](#pass-outcome-number-163)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-162)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-162)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-162)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 163

[Jump to summary definition](#summary-Pass-163)	|	[Previous Pass outcome](#pass-outcome-number-162)	|	[Next Pass outcome](#pass-outcome-number-164)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-163)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-163)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-163)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 164

[Jump to summary definition](#summary-Pass-164)	|	[Previous Pass outcome](#pass-outcome-number-163)	|	[Next Pass outcome](#pass-outcome-number-165)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-164)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-164)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-164)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 165

[Jump to summary definition](#summary-Pass-165)	|	[Previous Pass outcome](#pass-outcome-number-164)	|	[Next Pass outcome](#pass-outcome-number-166)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-165)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-165)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-165)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 166

[Jump to summary definition](#summary-Pass-166)	|	[Previous Pass outcome](#pass-outcome-number-165)	|	[Next Pass outcome](#pass-outcome-number-167)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-166)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-166)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-166)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 167

[Jump to summary definition](#summary-Pass-167)	|	[Previous Pass outcome](#pass-outcome-number-166)	|	[Next Pass outcome](#pass-outcome-number-168)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-167)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-167)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-167)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 168

[Jump to summary definition](#summary-Pass-168)	|	[Previous Pass outcome](#pass-outcome-number-167)	|	[Next Pass outcome](#pass-outcome-number-169)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-168)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-168)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-168)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 169

[Jump to summary definition](#summary-Pass-169)	|	[Previous Pass outcome](#pass-outcome-number-168)	|	[Next Pass outcome](#pass-outcome-number-170)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-169)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-169)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-169)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 170

[Jump to summary definition](#summary-Pass-170)	|	[Previous Pass outcome](#pass-outcome-number-169)	|	[Next Pass outcome](#pass-outcome-number-171)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-170)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-170)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-170)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 171

[Jump to summary definition](#summary-Pass-171)	|	[Previous Pass outcome](#pass-outcome-number-170)	|	[Next Pass outcome](#pass-outcome-number-172)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-171)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-171)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-171)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 172

[Jump to summary definition](#summary-Pass-172)	|	[Previous Pass outcome](#pass-outcome-number-171)	|	[Next Pass outcome](#pass-outcome-number-173)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-172)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-172)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-172)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 173

[Jump to summary definition](#summary-Pass-173)	|	[Previous Pass outcome](#pass-outcome-number-172)	|	[Next Pass outcome](#pass-outcome-number-174)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent-modelet-zedomain-inconsistence|
|----|----|
|Title|Merged&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/inconsistence/onto.ttl|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-173)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-173)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-173)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 174

[Jump to summary definition](#summary-Pass-174)	|	[Previous Pass outcome](#pass-outcome-number-173)	|	[Next Pass outcome](#pass-outcome-number-175)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-174)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-174)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-174)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 175

[Jump to summary definition](#summary-Pass-175)	|	[Previous Pass outcome](#pass-outcome-number-174)	|	[Next Pass outcome](#pass-outcome-number-176)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-175)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-175)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-175)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 176

[Jump to summary definition](#summary-Pass-176)	|	[Previous Pass outcome](#pass-outcome-number-175)	|	[Next Pass outcome](#pass-outcome-number-177)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-176)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-176)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-176)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 177

[Jump to summary definition](#summary-Pass-177)	|	[Previous Pass outcome](#pass-outcome-number-176)	|	[Next Pass outcome](#pass-outcome-number-178)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-177)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-177)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-177)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 178

[Jump to summary definition](#summary-Pass-178)	|	[Previous Pass outcome](#pass-outcome-number-177)	|	[Next Pass outcome](#pass-outcome-number-179)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-178)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-178)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-178)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 179

[Jump to summary definition](#summary-Pass-179)	|	[Previous Pass outcome](#pass-outcome-number-178)	|	[Next Pass outcome](#pass-outcome-number-180)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-179)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-179)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-179)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 180

[Jump to summary definition](#summary-Pass-180)	|	[Previous Pass outcome](#pass-outcome-number-179)	|	[Next Pass outcome](#pass-outcome-number-181)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-180)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-180)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-180)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 181

[Jump to summary definition](#summary-Pass-181)	|	[Previous Pass outcome](#pass-outcome-number-180)	|	[Next Pass outcome](#pass-outcome-number-182)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-181)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-181)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-181)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 182

[Jump to summary definition](#summary-Pass-182)	|	[Previous Pass outcome](#pass-outcome-number-181)	|	[Next Pass outcome](#pass-outcome-number-183)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-182)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-182)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-182)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 183

[Jump to summary definition](#summary-Pass-183)	|	[Previous Pass outcome](#pass-outcome-number-182)	|	[Next Pass outcome](#pass-outcome-number-184)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-183)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-183)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-183)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 184

[Jump to summary definition](#summary-Pass-184)	|	[Previous Pass outcome](#pass-outcome-number-183)	|	[Next Pass outcome](#pass-outcome-number-185)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-184)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-184)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-184)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 185

[Jump to summary definition](#summary-Pass-185)	|	[Previous Pass outcome](#pass-outcome-number-184)	|	[Next Pass outcome](#pass-outcome-number-186)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-185)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-185)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-185)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 186

[Jump to summary definition](#summary-Pass-186)	|	[Previous Pass outcome](#pass-outcome-number-185)	|	[Next Pass outcome](#pass-outcome-number-187)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-186)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-186)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-186)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 187

[Jump to summary definition](#summary-Pass-187)	|	[Previous Pass outcome](#pass-outcome-number-186)	|	[Next Pass outcome](#pass-outcome-number-188)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-187)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-187)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-187)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 188

[Jump to summary definition](#summary-Pass-188)	|	[Previous Pass outcome](#pass-outcome-number-187)	|	[Next Pass outcome](#pass-outcome-number-189)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-188)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-188)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-188)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 189

[Jump to summary definition](#summary-Pass-189)	|	[Previous Pass outcome](#pass-outcome-number-188)	|	[Next Pass outcome](#pass-outcome-number-190)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-189)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-189)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-189)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 190

[Jump to summary definition](#summary-Pass-190)	|	[Previous Pass outcome](#pass-outcome-number-189)	|	[Next Pass outcome](#pass-outcome-number-191)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-190)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-190)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-190)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 191

[Jump to summary definition](#summary-Pass-191)	|	[Previous Pass outcome](#pass-outcome-number-190)	|	[Next Pass outcome](#pass-outcome-number-192)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-191)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-191)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-191)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 192

[Jump to summary definition](#summary-Pass-192)	|	[Previous Pass outcome](#pass-outcome-number-191)	|	[Next Pass outcome](#pass-outcome-number-193)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-192)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-192)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-192)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 193

[Jump to summary definition](#summary-Pass-193)	|	[Previous Pass outcome](#pass-outcome-number-192)	|	[Next Pass outcome](#pass-outcome-number-194)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-193)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-193)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-193)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 194

[Jump to summary definition](#summary-Pass-194)	|	[Previous Pass outcome](#pass-outcome-number-193)	|	[Next Pass outcome](#pass-outcome-number-195)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-194)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-194)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-194)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 195

[Jump to summary definition](#summary-Pass-195)	|	[Previous Pass outcome](#pass-outcome-number-194)	|	[Next Pass outcome](#pass-outcome-number-196)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-195)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-195)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-195)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 196

[Jump to summary definition](#summary-Pass-196)	|	[Previous Pass outcome](#pass-outcome-number-195)	|	[Next Pass outcome](#pass-outcome-number-197)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-196)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-196)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-196)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 197

[Jump to summary definition](#summary-Pass-197)	|	[Previous Pass outcome](#pass-outcome-number-196)	|	[Next Pass outcome](#pass-outcome-number-198)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-dovrov|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/dovrov/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-197)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-197)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-197)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 198

[Jump to summary definition](#summary-Pass-198)	|	[Previous Pass outcome](#pass-outcome-number-197)	|	[Next Pass outcome](#pass-outcome-number-199)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-198)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-198)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-198)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 199

[Jump to summary definition](#summary-Pass-199)	|	[Previous Pass outcome](#pass-outcome-number-198)	|	[Next Pass outcome](#pass-outcome-number-200)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-199)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-199)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-199)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 200

[Jump to summary definition](#summary-Pass-200)	|	[Previous Pass outcome](#pass-outcome-number-199)	|	[Next Pass outcome](#pass-outcome-number-201)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-200)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-200)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-200)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 201

[Jump to summary definition](#summary-Pass-201)	|	[Previous Pass outcome](#pass-outcome-number-200)	|	[Next Pass outcome](#pass-outcome-number-202)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-201)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-201)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-201)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 202

[Jump to summary definition](#summary-Pass-202)	|	[Previous Pass outcome](#pass-outcome-number-201)	|	[Next Pass outcome](#pass-outcome-number-203)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-202)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-202)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-202)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 203

[Jump to summary definition](#summary-Pass-203)	|	[Previous Pass outcome](#pass-outcome-number-202)	|	[Next Pass outcome](#pass-outcome-number-204)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-203)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-203)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-203)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 204

[Jump to summary definition](#summary-Pass-204)	|	[Previous Pass outcome](#pass-outcome-number-203)	|	[Next Pass outcome](#pass-outcome-number-205)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-204)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-204)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-204)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 205

[Jump to summary definition](#summary-Pass-205)	|	[Previous Pass outcome](#pass-outcome-number-204)	|	[Next Pass outcome](#pass-outcome-number-206)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-205)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-205)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-205)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 206

[Jump to summary definition](#summary-Pass-206)	|	[Previous Pass outcome](#pass-outcome-number-205)	|	[Next Pass outcome](#pass-outcome-number-207)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-206)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-206)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-206)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 207

[Jump to summary definition](#summary-Pass-207)	|	[Previous Pass outcome](#pass-outcome-number-206)	|	[Next Pass outcome](#pass-outcome-number-208)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-207)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-207)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-207)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 208

[Jump to summary definition](#summary-Pass-208)	|	[Previous Pass outcome](#pass-outcome-number-207)	|	[Next Pass outcome](#pass-outcome-number-209)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-208)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-208)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-208)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 209

[Jump to summary definition](#summary-Pass-209)	|	[Previous Pass outcome](#pass-outcome-number-208)	|	[Next Pass outcome](#pass-outcome-number-210)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer-modelet-zedomain-domainout|
|----|----|
|Title|Merged&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main&#32;with&#32;related&#32;terms&#32;from&#32;the&#32;fragments&#32;domains/zedomain/domainout/onto.ttl|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-209)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-209)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-209)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 210

[Jump to summary definition](#summary-Pass-210)	|	[Previous Pass outcome](#pass-outcome-number-209)	|	[Next Pass outcome](#pass-outcome-number-211)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-210)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-210)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-210)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 211

[Jump to summary definition](#summary-Pass-211)	|	[Previous Pass outcome](#pass-outcome-number-210)	|	[Next Pass outcome](#pass-outcome-number-212)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-211)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-211)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-211)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 212

[Jump to summary definition](#summary-Pass-212)	|	[Previous Pass outcome](#pass-outcome-number-211)	|	[Next Pass outcome](#pass-outcome-number-213)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-212)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-212)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-212)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 213

[Jump to summary definition](#summary-Pass-213)	|	[Previous Pass outcome](#pass-outcome-number-212)	|	[Next Pass outcome](#pass-outcome-number-214)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-213)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-213)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-213)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 214

[Jump to summary definition](#summary-Pass-214)	|	[Previous Pass outcome](#pass-outcome-number-213)	|	[Next Pass outcome](#pass-outcome-number-215)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-214)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-214)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-214)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 215

[Jump to summary definition](#summary-Pass-215)	|	[Previous Pass outcome](#pass-outcome-number-214)	|	[Next Pass outcome](#pass-outcome-number-216)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-215)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-215)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-215)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 216

[Jump to summary definition](#summary-Pass-216)	|	[Previous Pass outcome](#pass-outcome-number-215)	|	[Next Pass outcome](#pass-outcome-number-217)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-216)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-216)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-216)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 217

[Jump to summary definition](#summary-Pass-217)	|	[Previous Pass outcome](#pass-outcome-number-216)	|	[Next Pass outcome](#pass-outcome-number-218)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-217)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-217)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-217)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 218

[Jump to summary definition](#summary-Pass-218)	|	[Previous Pass outcome](#pass-outcome-number-217)	|	[Next Pass outcome](#pass-outcome-number-219)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-218)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-218)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-218)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 219

[Jump to summary definition](#summary-Pass-219)	|	[Previous Pass outcome](#pass-outcome-number-218)	|	[Next Pass outcome](#pass-outcome-number-220)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-219)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-219)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-219)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 220

[Jump to summary definition](#summary-Pass-220)	|	[Previous Pass outcome](#pass-outcome-number-219)	|	[Next Pass outcome](#pass-outcome-number-221)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-220)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-220)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-220)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 221

[Jump to summary definition](#summary-Pass-221)	|	[Previous Pass outcome](#pass-outcome-number-220)	|	[Next Pass outcome](#pass-outcome-number-222)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-221)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-221)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-221)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 222

[Jump to summary definition](#summary-Pass-222)	|	[Previous Pass outcome](#pass-outcome-number-221)	|	[Next Pass outcome](#pass-outcome-number-223)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-222)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-222)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-222)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 223

[Jump to summary definition](#summary-Pass-223)	|	[Previous Pass outcome](#pass-outcome-number-222)	|	[Next Pass outcome](#pass-outcome-number-224)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-223)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-223)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-223)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 224

[Jump to summary definition](#summary-Pass-224)	|	[Previous Pass outcome](#pass-outcome-number-223)	|	[Next Pass outcome](#pass-outcome-number-225)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-224)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-224)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-224)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 225

[Jump to summary definition](#summary-Pass-225)	|	[Previous Pass outcome](#pass-outcome-number-224)	|	[Next Pass outcome](#pass-outcome-number-226)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-225)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-225)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-225)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 226

[Jump to summary definition](#summary-Pass-226)	|	[Previous Pass outcome](#pass-outcome-number-225)	|	[Next Pass outcome](#pass-outcome-number-227)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-226)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-226)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-226)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 227

[Jump to summary definition](#summary-Pass-227)	|	[Previous Pass outcome](#pass-outcome-number-226)	|	[Next Pass outcome](#pass-outcome-number-228)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-227)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-227)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-227)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 228

[Jump to summary definition](#summary-Pass-228)	|	[Previous Pass outcome](#pass-outcome-number-227)	|	[Next Pass outcome](#pass-outcome-number-229)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-228)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-228)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-228)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 229

[Jump to summary definition](#summary-Pass-229)	|	[Previous Pass outcome](#pass-outcome-number-228)	|	[Next Pass outcome](#pass-outcome-number-230)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-229)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-229)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-229)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 230

[Jump to summary definition](#summary-Pass-230)	|	[Previous Pass outcome](#pass-outcome-number-229)	|	[Next Pass outcome](#pass-outcome-number-231)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-230)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-230)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-230)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 231

[Jump to summary definition](#summary-Pass-231)	|	[Previous Pass outcome](#pass-outcome-number-230)	|	[Next Pass outcome](#pass-outcome-number-232)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-231)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-231)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-231)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 232

[Jump to summary definition](#summary-Pass-232)	|	[Previous Pass outcome](#pass-outcome-number-231)	|	[Next Pass outcome](#pass-outcome-number-233)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-232)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-232)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-232)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 233

[Jump to summary definition](#summary-Pass-233)	|	[Previous Pass outcome](#pass-outcome-number-232)	|	[Next Pass outcome](#pass-outcome-number-234)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-233)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-233)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-233)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 234

[Jump to summary definition](#summary-Pass-234)	|	[Previous Pass outcome](#pass-outcome-number-233)	|	[Next Pass outcome](#pass-outcome-number-235)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-234)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-234)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-234)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 235

[Jump to summary definition](#summary-Pass-235)	|	[Previous Pass outcome](#pass-outcome-number-234)	|	[Next Pass outcome](#pass-outcome-number-236)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-235)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-235)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-235)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 236

[Jump to summary definition](#summary-Pass-236)	|	[Previous Pass outcome](#pass-outcome-number-235)	|	[Next Pass outcome](#pass-outcome-number-237)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-236)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-236)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-236)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 237

[Jump to summary definition](#summary-Pass-237)	|	[Previous Pass outcome](#pass-outcome-number-236)	|	[Next Pass outcome](#pass-outcome-number-238)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-237)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-237)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-237)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 238

[Jump to summary definition](#summary-Pass-238)	|	[Previous Pass outcome](#pass-outcome-number-237)	|	[Next Pass outcome](#pass-outcome-number-239)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-238)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-238)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-238)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 239

[Jump to summary definition](#summary-Pass-239)	|	[Previous Pass outcome](#pass-outcome-number-238)	|	[Next Pass outcome](#pass-outcome-number-240)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-239)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-239)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-239)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 240

[Jump to summary definition](#summary-Pass-240)	|	[Previous Pass outcome](#pass-outcome-number-239)	|	[Next Pass outcome](#pass-outcome-number-241)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-240)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-240)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-240)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 241

[Jump to summary definition](#summary-Pass-241)	|	[Previous Pass outcome](#pass-outcome-number-240)	|	[Next Pass outcome](#pass-outcome-number-242)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-241)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-241)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-241)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 242

[Jump to summary definition](#summary-Pass-242)	|	[Previous Pass outcome](#pass-outcome-number-241)	|	[Next Pass outcome](#pass-outcome-number-243)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-242)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-242)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-242)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 243

[Jump to summary definition](#summary-Pass-243)	|	[Previous Pass outcome](#pass-outcome-number-242)	|	[Next Pass outcome](#pass-outcome-number-244)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-243)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-243)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-243)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 244

[Jump to summary definition](#summary-Pass-244)	|	[Previous Pass outcome](#pass-outcome-number-243)	|	[Next Pass outcome](#pass-outcome-number-245)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-244)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-244)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-244)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 245

[Jump to summary definition](#summary-Pass-245)	|	[Previous Pass outcome](#pass-outcome-number-244)	|	[Next Pass outcome](#pass-outcome-number-246)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-245)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-245)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-245)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 246

[Jump to summary definition](#summary-Pass-246)	|	[Previous Pass outcome](#pass-outcome-number-245)	|	[Next Pass outcome](#pass-outcome-number-247)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-246)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-246)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-246)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 247

[Jump to summary definition](#summary-Pass-247)	|	[Previous Pass outcome](#pass-outcome-number-246)	|	[Next Pass outcome](#pass-outcome-number-248)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-247)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-247)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-247)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 248

[Jump to summary definition](#summary-Pass-248)	|	[Previous Pass outcome](#pass-outcome-number-247)	|	[Next Pass outcome](#pass-outcome-number-249)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-248)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-248)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-248)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 249

[Jump to summary definition](#summary-Pass-249)	|	[Previous Pass outcome](#pass-outcome-number-248)	|	[Next Pass outcome](#pass-outcome-number-250)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-249)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-249)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-249)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 250

[Jump to summary definition](#summary-Pass-250)	|	[Previous Pass outcome](#pass-outcome-number-249)	|	[Next Pass outcome](#pass-outcome-number-251)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-250)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-250)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-250)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 251

[Jump to summary definition](#summary-Pass-251)	|	[Previous Pass outcome](#pass-outcome-number-250)	|	[Next Pass outcome](#pass-outcome-number-252)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-251)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-251)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-251)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 252

[Jump to summary definition](#summary-Pass-252)	|	[Previous Pass outcome](#pass-outcome-number-251)	|	[Next Pass outcome](#pass-outcome-number-253)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-252)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-252)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-252)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 253

[Jump to summary definition](#summary-Pass-253)	|	[Previous Pass outcome](#pass-outcome-number-252)	|	[Next Pass outcome](#pass-outcome-number-254)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-253)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-253)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-253)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 254

[Jump to summary definition](#summary-Pass-254)	|	[Previous Pass outcome](#pass-outcome-number-253)	|	[Next Pass outcome](#pass-outcome-number-255)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-254)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-254)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-254)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 255

[Jump to summary definition](#summary-Pass-255)	|	[Previous Pass outcome](#pass-outcome-number-254)	|	[Next Pass outcome](#pass-outcome-number-256)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-255)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-255)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-255)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 256

[Jump to summary definition](#summary-Pass-256)	|	[Previous Pass outcome](#pass-outcome-number-255)	|	[Next Pass outcome](#pass-outcome-number-257)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-256)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-256)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-256)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 257

[Jump to summary definition](#summary-Pass-257)	|	[Previous Pass outcome](#pass-outcome-number-256)	|	[Next Pass outcome](#pass-outcome-number-258)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-257)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-257)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-257)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 258

[Jump to summary definition](#summary-Pass-258)	|	[Previous Pass outcome](#pass-outcome-number-257)	|	[Next Pass outcome](#pass-outcome-number-259)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-258)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-258)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-258)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 259

[Jump to summary definition](#summary-Pass-259)	|	[Previous Pass outcome](#pass-outcome-number-258)	|	[Next Pass outcome](#pass-outcome-number-260)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-259)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-259)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-259)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 260

[Jump to summary definition](#summary-Pass-260)	|	[Previous Pass outcome](#pass-outcome-number-259)	|	[Next Pass outcome](#pass-outcome-number-261)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-260)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-260)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-260)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 261

[Jump to summary definition](#summary-Pass-261)	|	[Previous Pass outcome](#pass-outcome-number-260)	|	[Next Pass outcome](#pass-outcome-number-262)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-261)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-261)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-261)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 262

[Jump to summary definition](#summary-Pass-262)	|	[Previous Pass outcome](#pass-outcome-number-261)	|	[Next Pass outcome](#pass-outcome-number-263)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-262)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-262)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-262)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 263

[Jump to summary definition](#summary-Pass-263)	|	[Previous Pass outcome](#pass-outcome-number-262)	|	[Next Pass outcome](#pass-outcome-number-264)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-263)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-263)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-263)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 264

[Jump to summary definition](#summary-Pass-264)	|	[Previous Pass outcome](#pass-outcome-number-263)	|	[Next Pass outcome](#pass-outcome-number-265)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-264)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-264)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-264)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 265

[Jump to summary definition](#summary-Pass-265)	|	[Previous Pass outcome](#pass-outcome-number-264)	|	[Next Pass outcome](#pass-outcome-number-266)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-265)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-265)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-265)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 266

[Jump to summary definition](#summary-Pass-266)	|	[Previous Pass outcome](#pass-outcome-number-265)	|	[Next Pass outcome](#pass-outcome-number-267)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-266)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-266)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-266)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 267

[Jump to summary definition](#summary-Pass-267)	|	[Previous Pass outcome](#pass-outcome-number-266)	|	[Next Pass outcome](#pass-outcome-number-268)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-267)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-267)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-267)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 268

[Jump to summary definition](#summary-Pass-268)	|	[Previous Pass outcome](#pass-outcome-number-267)	|	[Next Pass outcome](#pass-outcome-number-269)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-268)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-268)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-268)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 269

[Jump to summary definition](#summary-Pass-269)	|	[Previous Pass outcome](#pass-outcome-number-268)	|	[Next Pass outcome](#pass-outcome-number-270)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-269)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-269)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-269)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 270

[Jump to summary definition](#summary-Pass-270)	|	[Previous Pass outcome](#pass-outcome-number-269)	|	[Next Pass outcome](#pass-outcome-number-271)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-270)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-270)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-270)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 271

[Jump to summary definition](#summary-Pass-271)	|	[Previous Pass outcome](#pass-outcome-number-270)	|	[Next Pass outcome](#pass-outcome-number-272)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-271)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-271)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-271)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 272

[Jump to summary definition](#summary-Pass-272)	|	[Previous Pass outcome](#pass-outcome-number-271)	|	[Next Pass outcome](#pass-outcome-number-273)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-272)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-272)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-272)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 273

[Jump to summary definition](#summary-Pass-273)	|	[Previous Pass outcome](#pass-outcome-number-272)	|	[Next Pass outcome](#pass-outcome-number-274)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-273)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-273)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-273)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 274

[Jump to summary definition](#summary-Pass-274)	|	[Previous Pass outcome](#pass-outcome-number-273)	|	[Next Pass outcome](#pass-outcome-number-275)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-274)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-274)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-274)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 275

[Jump to summary definition](#summary-Pass-275)	|	[Previous Pass outcome](#pass-outcome-number-274)	|	[Next Pass outcome](#pass-outcome-number-276)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-275)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-275)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-275)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 276

[Jump to summary definition](#summary-Pass-276)	|	[Previous Pass outcome](#pass-outcome-number-275)	|	[Next Pass outcome](#pass-outcome-number-277)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-276)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-276)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-276)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 277

[Jump to summary definition](#summary-Pass-277)	|	[Previous Pass outcome](#pass-outcome-number-276)	|	[Next Pass outcome](#pass-outcome-number-278)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-277)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-277)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-277)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 278

[Jump to summary definition](#summary-Pass-278)	|	[Previous Pass outcome](#pass-outcome-number-277)	|	[Next Pass outcome](#pass-outcome-number-279)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-278)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-278)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-278)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 279

[Jump to summary definition](#summary-Pass-279)	|	[Previous Pass outcome](#pass-outcome-number-278)	|	[Next Pass outcome](#pass-outcome-number-280)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-279)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-279)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-279)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 280

[Jump to summary definition](#summary-Pass-280)	|	[Previous Pass outcome](#pass-outcome-number-279)	|	[Next Pass outcome](#pass-outcome-number-281)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-280)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-280)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-280)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 281

[Jump to summary definition](#summary-Pass-281)	|	[Previous Pass outcome](#pass-outcome-number-280)	|	[Next Pass outcome](#pass-outcome-number-282)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-281)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-281)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-281)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 282

[Jump to summary definition](#summary-Pass-282)	|	[Previous Pass outcome](#pass-outcome-number-281)	|	[Next Pass outcome](#pass-outcome-number-283)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-282)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-282)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-282)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 283

[Jump to summary definition](#summary-Pass-283)	|	[Previous Pass outcome](#pass-outcome-number-282)	|	[Next Pass outcome](#pass-outcome-number-284)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-283)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-283)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-283)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 284

[Jump to summary definition](#summary-Pass-284)	|	[Previous Pass outcome](#pass-outcome-number-283)	|	[Next Pass outcome](#pass-outcome-number-285)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-284)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-284)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-284)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 285

[Jump to summary definition](#summary-Pass-285)	|	[Previous Pass outcome](#pass-outcome-number-284)	|	[Next Pass outcome](#pass-outcome-number-286)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-285)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-285)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-285)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 286

[Jump to summary definition](#summary-Pass-286)	|	[Previous Pass outcome](#pass-outcome-number-285)	|	[Next Pass outcome](#pass-outcome-number-287)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-286)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-286)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-286)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 287

[Jump to summary definition](#summary-Pass-287)	|	[Previous Pass outcome](#pass-outcome-number-286)	|	[Next Pass outcome](#pass-outcome-number-288)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-287)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-287)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-287)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 288

[Jump to summary definition](#summary-Pass-288)	|	[Previous Pass outcome](#pass-outcome-number-287)	|	[Next Pass outcome](#pass-outcome-number-289)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-288)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-288)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-288)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 289

[Jump to summary definition](#summary-Pass-289)	|	[Previous Pass outcome](#pass-outcome-number-288)	|	[Next Pass outcome](#pass-outcome-number-290)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-289)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-289)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-289)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 290

[Jump to summary definition](#summary-Pass-290)	|	[Previous Pass outcome](#pass-outcome-number-289)	|	[Next Pass outcome](#pass-outcome-number-291)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-290)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-290)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-290)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 291

[Jump to summary definition](#summary-Pass-291)	|	[Previous Pass outcome](#pass-outcome-number-290)	|	[Next Pass outcome](#pass-outcome-number-292)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-291)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-291)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-291)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 292

[Jump to summary definition](#summary-Pass-292)	|	[Previous Pass outcome](#pass-outcome-number-291)	|	[Next Pass outcome](#pass-outcome-number-293)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-292)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-292)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-292)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 293

[Jump to summary definition](#summary-Pass-293)	|	[Previous Pass outcome](#pass-outcome-number-292)	|	[Next Pass outcome](#pass-outcome-number-294)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-293)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-293)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-293)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 294

[Jump to summary definition](#summary-Pass-294)	|	[Previous Pass outcome](#pass-outcome-number-293)	|	[Next Pass outcome](#pass-outcome-number-295)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-294)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-294)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-294)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 295

[Jump to summary definition](#summary-Pass-295)	|	[Previous Pass outcome](#pass-outcome-number-294)	|	[Next Pass outcome](#pass-outcome-number-296)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-295)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-295)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-295)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 296

[Jump to summary definition](#summary-Pass-296)	|	[Previous Pass outcome](#pass-outcome-number-295)	|	[Next Pass outcome](#pass-outcome-number-297)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-296)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-296)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-296)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 297

[Jump to summary definition](#summary-Pass-297)	|	[Previous Pass outcome](#pass-outcome-number-296)	|	[Next Pass outcome](#pass-outcome-number-298)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-297)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-297)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-297)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 298

[Jump to summary definition](#summary-Pass-298)	|	[Previous Pass outcome](#pass-outcome-number-297)	|	[Next Pass outcome](#pass-outcome-number-299)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-298)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-298)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-298)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 299

[Jump to summary definition](#summary-Pass-299)	|	[Previous Pass outcome](#pass-outcome-number-298)	|	[Next Pass outcome](#pass-outcome-number-300)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-299)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-299)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-299)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 300

[Jump to summary definition](#summary-Pass-300)	|	[Previous Pass outcome](#pass-outcome-number-299)	|	[Next Pass outcome](#pass-outcome-number-301)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-300)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-300)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-300)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 301

[Jump to summary definition](#summary-Pass-301)	|	[Previous Pass outcome](#pass-outcome-number-300)	|	[Next Pass outcome](#pass-outcome-number-302)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-301)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-301)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-301)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 302

[Jump to summary definition](#summary-Pass-302)	|	[Previous Pass outcome](#pass-outcome-number-301)	|	[Next Pass outcome](#pass-outcome-number-303)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-302)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-302)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-302)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 303

[Jump to summary definition](#summary-Pass-303)	|	[Previous Pass outcome](#pass-outcome-number-302)	|	[Next Pass outcome](#pass-outcome-number-304)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-303)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-303)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-303)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 304

[Jump to summary definition](#summary-Pass-304)	|	[Previous Pass outcome](#pass-outcome-number-303)	|	[Next Pass outcome](#pass-outcome-number-305)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-304)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-304)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-304)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 305

[Jump to summary definition](#summary-Pass-305)	|	[Previous Pass outcome](#pass-outcome-number-304)	|	[Next Pass outcome](#pass-outcome-number-306)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-305)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-305)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-305)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 306

[Jump to summary definition](#summary-Pass-306)	|	[Previous Pass outcome](#pass-outcome-number-305)	|	[Next Pass outcome](#pass-outcome-number-307)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-306)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-306)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-306)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 307

[Jump to summary definition](#summary-Pass-307)	|	[Previous Pass outcome](#pass-outcome-number-306)	|	[Next Pass outcome](#pass-outcome-number-308)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-307)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-307)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-307)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 308

[Jump to summary definition](#summary-Pass-308)	|	[Previous Pass outcome](#pass-outcome-number-307)	|	[Next Pass outcome](#pass-outcome-number-309)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-308)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-308)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-308)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 309

[Jump to summary definition](#summary-Pass-309)	|	[Previous Pass outcome](#pass-outcome-number-308)	|	[Next Pass outcome](#pass-outcome-number-310)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-309)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-309)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-309)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 310

[Jump to summary definition](#summary-Pass-310)	|	[Previous Pass outcome](#pass-outcome-number-309)	|	[Next Pass outcome](#pass-outcome-number-311)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-310)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-310)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-310)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 311

[Jump to summary definition](#summary-Pass-311)	|	[Previous Pass outcome](#pass-outcome-number-310)	|	[Next Pass outcome](#pass-outcome-number-312)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-311)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-311)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-311)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 312

[Jump to summary definition](#summary-Pass-312)	|	[Previous Pass outcome](#pass-outcome-number-311)	|	[Next Pass outcome](#pass-outcome-number-313)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-312)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-312)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-312)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 313

[Jump to summary definition](#summary-Pass-313)	|	[Previous Pass outcome](#pass-outcome-number-312)	|	[Next Pass outcome](#pass-outcome-number-314)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-313)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-313)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-313)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 314

[Jump to summary definition](#summary-Pass-314)	|	[Previous Pass outcome](#pass-outcome-number-313)	|	[Next Pass outcome](#pass-outcome-number-315)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-314)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-314)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-314)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 315

[Jump to summary definition](#summary-Pass-315)	|	[Previous Pass outcome](#pass-outcome-number-314)	|	[Next Pass outcome](#pass-outcome-number-316)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-315)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-315)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-315)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 316

[Jump to summary definition](#summary-Pass-316)	|	[Previous Pass outcome](#pass-outcome-number-315)	|	[Next Pass outcome](#pass-outcome-number-317)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-316)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-316)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-316)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 317

[Jump to summary definition](#summary-Pass-317)	|	[Previous Pass outcome](#pass-outcome-number-316)	|	[Next Pass outcome](#pass-outcome-number-318)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-317)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-317)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-317)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 318

[Jump to summary definition](#summary-Pass-318)	|	[Previous Pass outcome](#pass-outcome-number-317)	|	[Next Pass outcome](#pass-outcome-number-319)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-318)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-318)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-318)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 319

[Jump to summary definition](#summary-Pass-319)	|	[Previous Pass outcome](#pass-outcome-number-318)	|	[Next Pass outcome](#pass-outcome-number-320)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-319)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-319)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-319)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 320

[Jump to summary definition](#summary-Pass-320)	|	[Previous Pass outcome](#pass-outcome-number-319)	|	[Next Pass outcome](#pass-outcome-number-321)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-320)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-320)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-320)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 321

[Jump to summary definition](#summary-Pass-321)	|	[Previous Pass outcome](#pass-outcome-number-320)	|	[Next Pass outcome](#pass-outcome-number-322)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-321)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-321)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-321)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 322

[Jump to summary definition](#summary-Pass-322)	|	[Previous Pass outcome](#pass-outcome-number-321)	|	[Next Pass outcome](#pass-outcome-number-323)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-322)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-322)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-322)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 323

[Jump to summary definition](#summary-Pass-323)	|	[Previous Pass outcome](#pass-outcome-number-322)	|	[Next Pass outcome](#pass-outcome-number-324)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-323)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-323)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-323)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 324

[Jump to summary definition](#summary-Pass-324)	|	[Previous Pass outcome](#pass-outcome-number-323)	|	[Next Pass outcome](#pass-outcome-number-325)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-324)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-324)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-324)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 325

[Jump to summary definition](#summary-Pass-325)	|	[Previous Pass outcome](#pass-outcome-number-324)	|	[Next Pass outcome](#pass-outcome-number-326)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-325)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-325)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-325)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 326

[Jump to summary definition](#summary-Pass-326)	|	[Previous Pass outcome](#pass-outcome-number-325)	|	[Next Pass outcome](#pass-outcome-number-327)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-326)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-326)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-326)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 327

[Jump to summary definition](#summary-Pass-327)	|	[Previous Pass outcome](#pass-outcome-number-326)	|	[Next Pass outcome](#pass-outcome-number-328)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-327)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-327)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-327)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 328

[Jump to summary definition](#summary-Pass-328)	|	[Previous Pass outcome](#pass-outcome-number-327)	|	[Next Pass outcome](#pass-outcome-number-329)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-328)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-328)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-328)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 329

[Jump to summary definition](#summary-Pass-329)	|	[Previous Pass outcome](#pass-outcome-number-328)	|	[Next Pass outcome](#pass-outcome-number-330)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-329)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-329)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-329)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 330

[Jump to summary definition](#summary-Pass-330)	|	[Previous Pass outcome](#pass-outcome-number-329)	|	[Next Pass outcome](#pass-outcome-number-331)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-330)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-330)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-330)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 331

[Jump to summary definition](#summary-Pass-331)	|	[Previous Pass outcome](#pass-outcome-number-330)	|	[Next Pass outcome](#pass-outcome-number-332)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-331)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-331)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-331)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 332

[Jump to summary definition](#summary-Pass-332)	|	[Previous Pass outcome](#pass-outcome-number-331)	|	[Next Pass outcome](#pass-outcome-number-333)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-332)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-332)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-332)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 333

[Jump to summary definition](#summary-Pass-333)	|	[Previous Pass outcome](#pass-outcome-number-332)	|	[Next Pass outcome](#pass-outcome-number-334)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-333)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-333)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-333)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 334

[Jump to summary definition](#summary-Pass-334)	|	[Previous Pass outcome](#pass-outcome-number-333)	|	[Next Pass outcome](#pass-outcome-number-335)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-334)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-334)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-334)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 335

[Jump to summary definition](#summary-Pass-335)	|	[Previous Pass outcome](#pass-outcome-number-334)	|	[Next Pass outcome](#pass-outcome-number-336)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-335)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-335)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-335)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 336

[Jump to summary definition](#summary-Pass-336)	|	[Previous Pass outcome](#pass-outcome-number-335)	|	[Next Pass outcome](#pass-outcome-number-337)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-336)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-336)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-336)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 337

[Jump to summary definition](#summary-Pass-337)	|	[Previous Pass outcome](#pass-outcome-number-336)	|	[Next Pass outcome](#pass-outcome-number-338)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-337)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-337)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-337)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 338

[Jump to summary definition](#summary-Pass-338)	|	[Previous Pass outcome](#pass-outcome-number-337)	|	[Next Pass outcome](#pass-outcome-number-339)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-338)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-338)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-338)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 339

[Jump to summary definition](#summary-Pass-339)	|	[Previous Pass outcome](#pass-outcome-number-338)	|	[Next Pass outcome](#pass-outcome-number-340)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-339)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-339)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-339)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 340

[Jump to summary definition](#summary-Pass-340)	|	[Previous Pass outcome](#pass-outcome-number-339)	|	[Next Pass outcome](#pass-outcome-number-341)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-340)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-340)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-340)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 341

[Jump to summary definition](#summary-Pass-341)	|	[Previous Pass outcome](#pass-outcome-number-340)	|	[Next Pass outcome](#pass-outcome-number-342)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-341)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-341)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-341)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 342

[Jump to summary definition](#summary-Pass-342)	|	[Previous Pass outcome](#pass-outcome-number-341)	|	[Next Pass outcome](#pass-outcome-number-343)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[bad-extension-property](https://ns.inria.fr/olivaw#bad-extension-property)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-342)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-342)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-342)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 343

[Jump to summary definition](#summary-Pass-343)	|	[Previous Pass outcome](#pass-outcome-number-342)	|	[Next Pass outcome](#pass-outcome-number-344)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-343)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-343)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-343)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 344

[Jump to summary definition](#summary-Pass-344)	|	[Previous Pass outcome](#pass-outcome-number-343)	|	Next Pass outcome

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-344)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-344)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-344)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***

</details>

***
