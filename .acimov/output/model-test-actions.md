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
|Ontology version|[87eef5eee7e5b0dfcc0264136d579196a32e07fb](https://github.com/acimov-tools/model-test/tree/87eef5eee7e5b0dfcc0264136d579196a32e07fb)|
|Ontology branch|[main](https://github.com/acimov-tools/model-test/tree/main)|
|Olivaw suite|[olivaw model test suite](https://github.com/Wimmics/olivaw/blob/v0.0.6/olivaw/test/model/suite.py)|
|Olivaw version|[v0.0.6](https://github.com/Wimmics/olivaw)|
|Generated turtle|[Turtle report](./model-test-actions.ttl)|
|Generated Markdown|[Markdown report](./model-test-actions.md)|

# Statistic summary

Here is a short overview for this test report

215 Outcomes

:boom:34 MajorFail, :exclamation:19 MinorFail, :warning:0 CannotTell, :grey_question:8 NotTested, :white_check_mark:154 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="15%" height="25px"/><img src="../assets/orange.png" width="8%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="3%" height="25px"/><img src="../assets/green.png" width="74%" height="25px"/></div>

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

:boom:34 MajorFail outcomes

<details>
<summary>Fold/Unfold the 34 summary and details</summary>

## MajorFail Outcomes Summary

:boom:34 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-1">1/34</div>|:boom:MajorFail|`module-src-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-2">2/34</div>|:boom:MajorFail|`module-src-unknown-prefix`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-2)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-3">3/34</div>|:boom:MajorFail|`module-src-too-close-terms`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-3)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-4">4/34</div>|:boom:MajorFail|`module-src-range-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-4)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-5">5/34</div>|:boom:MajorFail|`module-src-not-rl`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-6">6/34</div>|:boom:MajorFail|`module-src-not-ql`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-6)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-7">7/34</div>|:boom:MajorFail|`module-src-not-el`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-7)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-8">8/34</div>|:boom:MajorFail|`module-src-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-8)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-9">9/34</div>|:boom:MajorFail|`module-src-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-9)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-10">10/34</div>|:boom:MajorFail|`module-src-inconsistent`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-10)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-11">11/34</div>|:boom:MajorFail|`module-src-domain-outer`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-11)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-12">12/34</div>|:boom:MajorFail|`module-src-domain-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-12)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-13">13/34</div>|:boom:MajorFail|`module-src-broken`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-13)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-14">14/34</div>|:boom:MajorFail|`modelet-zedomain-syntax`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-14)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-15">15/34</div>|:boom:MajorFail|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-15)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-16">16/34</div>|:boom:MajorFail|`modelet-zedomain-prefix`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-16)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-17">17/34</div>|:boom:MajorFail|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-17)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-18">18/34</div>|:boom:MajorFail|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-18)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-19">19/34</div>|:boom:MajorFail|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-19)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-20">20/34</div>|:boom:MajorFail|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-20)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-21">21/34</div>|:boom:MajorFail|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-21)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-22">22/34</div>|:boom:MajorFail|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-22)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-23">23/34</div>|:boom:MajorFail|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-23)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-24">24/34</div>|:boom:MajorFail|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-24)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-25">25/34</div>|:boom:MajorFail|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-25)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-26">26/34</div>|:boom:MajorFail|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-26)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-27">27/34</div>|:boom:MajorFail|`all-modules`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-27)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-28">28/34</div>|:boom:MajorFail|`all-modules`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-28)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-29">29/34</div>|:boom:MajorFail|`all-modules`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-29)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-30">30/34</div>|:boom:MajorFail|`all-modules`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-30)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-31">31/34</div>|:boom:MajorFail|`all-fragments`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-31)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-32">32/34</div>|:boom:MajorFail|`all-fragments`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-32)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-33">33/34</div>|:boom:MajorFail|`all-fragments`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-33)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-34">34/34</div>|:boom:MajorFail|`all-fragments`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-34)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)	|	Previous MajorFail outcome	|	[Next MajorFail outcome](#majorfail-outcome-number-2)

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
|[Section top](#majorfail-outcome-number-1)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-1)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-1)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>violation:38629e11-c562-4557-891c-53f5810cff57&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)	|	[Previous MajorFail outcome](#majorfail-outcome-number-1)	|	[Next MajorFail outcome](#majorfail-outcome-number-3)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module unknown-prefix](https://github.com/acimov-tools/model-test/blob/main/src/unknown-prefix.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-2)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-2)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-2)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>at&#32;line&#32;3&#32;of&#32; &#60;>:  &#10;Bad&#32;syntax&#32;(Prefix&#32; &#34;owl:&#34; &#32;not&#32;bound)&#32;at&#32;&Hat;&#32;in:  &#10; &#34;...b'fix&#32;:&#32; &#60;https://www.example.org/olivaw/> &#32;.&#92;n&#92;n:unknownPrefix&#32;a&#32;'&Hat;b'owl:Ontology&#32;.&#92;n&#92;n:Unknown&#32;a&#32;owl:Class&#32;;&#92;n&#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;'...&#34;</code></pre>|

***
### MajorFail Outcome number 3

[Jump to summary definition](#summary-MajorFail-3)	|	[Previous MajorFail outcome](#majorfail-outcome-number-2)	|	[Next MajorFail outcome](#majorfail-outcome-number-4)

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
|[Section top](#majorfail-outcome-number-3)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-3)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-3)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>violation:7632e8aa-8ab5-4094-b7df-6e470f7c87a8&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>violation:3144aff7-c0ae-4ada-886b-5da59eab678e&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)	|	[Previous MajorFail outcome](#majorfail-outcome-number-3)	|	[Next MajorFail outcome](#majorfail-outcome-number-5)

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
|[Section top](#majorfail-outcome-number-4)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-4)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-4)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>violation:c20e8996-9ffa-4b13-ab97-62a19662946b&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)	|	[Previous MajorFail outcome](#majorfail-outcome-number-4)	|	[Next MajorFail outcome](#majorfail-outcome-number-6)

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
|[Section top](#majorfail-outcome-number-5)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-5)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-5)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>violation:f2d3168d-b0f2-439c-bf29-69e70c386ffb&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|

***
### MajorFail Outcome number 6

[Jump to summary definition](#summary-MajorFail-6)	|	[Previous MajorFail outcome](#majorfail-outcome-number-5)	|	[Next MajorFail outcome](#majorfail-outcome-number-7)

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
|[Section top](#majorfail-outcome-number-6)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-6)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-6)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>violation:7f8fc81f-39a9-4202-8410-7c7a3c6c4ae1&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 7

[Jump to summary definition](#summary-MajorFail-7)	|	[Previous MajorFail outcome](#majorfail-outcome-number-6)	|	[Next MajorFail outcome](#majorfail-outcome-number-8)

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
|[Section top](#majorfail-outcome-number-7)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-7)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-7)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>violation:3f282151-3619-4c98-90bc-6a51aee656ae&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 8

[Jump to summary definition](#summary-MajorFail-8)	|	[Previous MajorFail outcome](#majorfail-outcome-number-7)	|	[Next MajorFail outcome](#majorfail-outcome-number-9)

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
|[Section top](#majorfail-outcome-number-8)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-8)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-8)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 9

[Jump to summary definition](#summary-MajorFail-9)	|	[Previous MajorFail outcome](#majorfail-outcome-number-8)	|	[Next MajorFail outcome](#majorfail-outcome-number-10)

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
|[Section top](#majorfail-outcome-number-9)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-9)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-9)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 10

[Jump to summary definition](#summary-MajorFail-10)	|	[Previous MajorFail outcome](#majorfail-outcome-number-9)	|	[Next MajorFail outcome](#majorfail-outcome-number-11)

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
|[Section top](#majorfail-outcome-number-10)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-10)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-10)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>violation:88dbf753-ab91-4d88-b3d7-2170e49bc076&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>violation:c90db51d-b3f5-4f1c-a45c-7fccafc2b3a0&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>violation:87910217-bc3e-44a7-9a54-e2f74f76a7da&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|

***
### MajorFail Outcome number 11

[Jump to summary definition](#summary-MajorFail-11)	|	[Previous MajorFail outcome](#majorfail-outcome-number-10)	|	[Next MajorFail outcome](#majorfail-outcome-number-12)

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
|[Section top](#majorfail-outcome-number-11)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-11)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-11)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-11)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 12

[Jump to summary definition](#summary-MajorFail-12)	|	[Previous MajorFail outcome](#majorfail-outcome-number-11)	|	[Next MajorFail outcome](#majorfail-outcome-number-13)

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
|[Section top](#majorfail-outcome-number-12)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-12)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-12)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>violation:34020672-5f69-4d10-bba1-a640a760bace&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 13

[Jump to summary definition](#summary-MajorFail-13)	|	[Previous MajorFail outcome](#majorfail-outcome-number-12)	|	[Next MajorFail outcome](#majorfail-outcome-number-14)

:boom:MajorFail outcome
#### Subject detail
|Name|module-src-broken|
|----|----|
|Title|Standalone&#32;module&#32;src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module broken](https://github.com/acimov-tools/model-test/blob/main/src/broken.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-13)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-13)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-13)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;9,&#32;column&#32;23.</code></pre>|

***
### MajorFail Outcome number 14

[Jump to summary definition](#summary-MajorFail-14)	|	[Previous MajorFail outcome](#majorfail-outcome-number-13)	|	[Next MajorFail outcome](#majorfail-outcome-number-15)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/syntax](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/syntax/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-14)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-14)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-14)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;7,&#32;column&#32;23.</code></pre>|

***
### MajorFail Outcome number 15

[Jump to summary definition](#summary-MajorFail-15)	|	[Previous MajorFail outcome](#majorfail-outcome-number-14)	|	[Next MajorFail outcome](#majorfail-outcome-number-16)

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
|[Section top](#majorfail-outcome-number-15)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-15)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-15)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>violation:9ad9a9ee-1f0d-4bbd-833f-2c9a5b3be9fe&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 16

[Jump to summary definition](#summary-MajorFail-16)	|	[Previous MajorFail outcome](#majorfail-outcome-number-15)	|	[Next MajorFail outcome](#majorfail-outcome-number-17)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/prefix](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/prefix/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-16)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-16)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-16)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>at&#32;line&#32;3&#32;of&#32; &#60;>:  &#10;Bad&#32;syntax&#32;(Prefix&#32; &#34;owl:&#34; &#32;not&#32;bound)&#32;at&#32;&Hat;&#32;in:  &#10; &#34;...b'fix&#32;:&#32; &#60;https://www.example.org/olivaw/> &#32;.&#92;n&#92;n:unknownPrefix&#32;a&#32;'&Hat;b'owl:Ontology&#32;.&#92;n&#92;n:Unknown&#32;a&#32;owl:Class&#32;;&#92;n&#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;'...&#34;</code></pre>|

***
### MajorFail Outcome number 17

[Jump to summary definition](#summary-MajorFail-17)	|	[Previous MajorFail outcome](#majorfail-outcome-number-16)	|	[Next MajorFail outcome](#majorfail-outcome-number-18)

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
|[Section top](#majorfail-outcome-number-17)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-17)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-17)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>violation:935b2b1c-5d3c-4e14-854a-1128bcfd7d42&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 18

[Jump to summary definition](#summary-MajorFail-18)	|	[Previous MajorFail outcome](#majorfail-outcome-number-17)	|	[Next MajorFail outcome](#majorfail-outcome-number-19)

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
|[Section top](#majorfail-outcome-number-18)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-18)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-18)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>violation:4e41b752-cc8d-42b2-9ce3-c62e630273ef&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>violation:3ddafd9d-fe72-405b-823e-687fcfbb359b&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>violation:d8fccc98-0d4a-425c-ad2b-0fbece7ec56a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|

***
### MajorFail Outcome number 19

[Jump to summary definition](#summary-MajorFail-19)	|	[Previous MajorFail outcome](#majorfail-outcome-number-18)	|	[Next MajorFail outcome](#majorfail-outcome-number-20)

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
|[Section top](#majorfail-outcome-number-19)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-19)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-19)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 20

[Jump to summary definition](#summary-MajorFail-20)	|	[Previous MajorFail outcome](#majorfail-outcome-number-19)	|	[Next MajorFail outcome](#majorfail-outcome-number-21)

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
|[Section top](#majorfail-outcome-number-20)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-20)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-20)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>violation:f006ee60-159f-41da-8b16-7d21a60371d0&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 21

[Jump to summary definition](#summary-MajorFail-21)	|	[Previous MajorFail outcome](#majorfail-outcome-number-20)	|	[Next MajorFail outcome](#majorfail-outcome-number-22)

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
|[Section top](#majorfail-outcome-number-21)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-21)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-21)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-21)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 22

[Jump to summary definition](#summary-MajorFail-22)	|	[Previous MajorFail outcome](#majorfail-outcome-number-21)	|	[Next MajorFail outcome](#majorfail-outcome-number-23)

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
|[Section top](#majorfail-outcome-number-22)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-22)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-22)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>violation:6e8c6b98-9ab4-4e0a-accd-dd818b449820&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 23

[Jump to summary definition](#summary-MajorFail-23)	|	[Previous MajorFail outcome](#majorfail-outcome-number-22)	|	[Next MajorFail outcome](#majorfail-outcome-number-24)

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
|[Section top](#majorfail-outcome-number-23)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-23)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-23)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>violation:33e25779-1a6b-4ae0-8578-bfe22ab9336d&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>violation:bc918950-8f06-446d-b3b4-a3acc6f1bca4&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 24

[Jump to summary definition](#summary-MajorFail-24)	|	[Previous MajorFail outcome](#majorfail-outcome-number-23)	|	[Next MajorFail outcome](#majorfail-outcome-number-25)

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
|[Section top](#majorfail-outcome-number-24)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-24)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-24)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>violation:91173f60-458b-4617-a3f8-8537a17c6be4&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|

***
### MajorFail Outcome number 25

[Jump to summary definition](#summary-MajorFail-25)	|	[Previous MajorFail outcome](#majorfail-outcome-number-24)	|	[Next MajorFail outcome](#majorfail-outcome-number-26)

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
|[Section top](#majorfail-outcome-number-25)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-25)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-25)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>violation:692ffe4a-d435-45a3-8016-e2609090a70d&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 26

[Jump to summary definition](#summary-MajorFail-26)	|	[Previous MajorFail outcome](#majorfail-outcome-number-25)	|	[Next MajorFail outcome](#majorfail-outcome-number-27)

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
|[Section top](#majorfail-outcome-number-26)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-26)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-26)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>violation:d0f5da8f-27f7-4309-859c-9eb5df336045&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 27

[Jump to summary definition](#summary-MajorFail-27)	|	[Previous MajorFail outcome](#majorfail-outcome-number-26)	|	[Next MajorFail outcome](#majorfail-outcome-number-28)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-27)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-27)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-27)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-27)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-27)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 28

[Jump to summary definition](#summary-MajorFail-28)	|	[Previous MajorFail outcome](#majorfail-outcome-number-27)	|	[Next MajorFail outcome](#majorfail-outcome-number-29)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-28)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-28)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-28)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 29

[Jump to summary definition](#summary-MajorFail-29)	|	[Previous MajorFail outcome](#majorfail-outcome-number-28)	|	[Next MajorFail outcome](#majorfail-outcome-number-30)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-29)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-29)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-29)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 30

[Jump to summary definition](#summary-MajorFail-30)	|	[Previous MajorFail outcome](#majorfail-outcome-number-29)	|	[Next MajorFail outcome](#majorfail-outcome-number-31)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

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
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:4f01846a-126d-4b9c-b9bb-3e80cdc39d55&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:27ceea0d-21c8-42ad-801e-e649a1e488dc&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:f97f57fd-de2e-43fc-89b8-0bd61aa19364&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:27249045-9e4a-4a39-8650-c3c120b12f09&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:0fbb80f0-84bb-4fdc-a870-eb1bb9845477&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:d131b784-518b-41e5-b519-fb433265c1c2&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:d3685a84-9924-49cd-af40-286c6104aa9a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:9aadc070-566c-41e9-a903-da6ca6da6dda&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:17d4f247-9413-4e54-817e-2962a66110db&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:ea164681-82ee-4234-b031-d322fe1313cd&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>violation:1257e130-9d31-4902-9b19-7f5d5a469d7f&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|

***
### MajorFail Outcome number 31

[Jump to summary definition](#summary-MajorFail-31)	|	[Previous MajorFail outcome](#majorfail-outcome-number-30)	|	[Next MajorFail outcome](#majorfail-outcome-number-32)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-31)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-31)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-31)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-31)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subPropertyOf&#32;:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;owl:equivalentProperty&#32;:domainReferencingOut&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-31)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 32

[Jump to summary definition](#summary-MajorFail-32)	|	[Previous MajorFail outcome](#majorfail-outcome-number-31)	|	[Next MajorFail outcome](#majorfail-outcome-number-33)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-32)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-32)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-32)|Description|http://www.w3.org/2002/07/owl#disjointWith&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:disjointWith&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 33

[Jump to summary definition](#summary-MajorFail-33)	|	[Previous MajorFail outcome](#majorfail-outcome-number-32)	|	[Next MajorFail outcome](#majorfail-outcome-number-34)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-33)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-33)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-33)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 34

[Jump to summary definition](#summary-MajorFail-34)	|	[Previous MajorFail outcome](#majorfail-outcome-number-33)	|	Next MajorFail outcome

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-34)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-34)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-34)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:7ea8a3c6-357b-4f35-87d7-0aaef0467a0c&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:dd96165c-c26e-44e3-8ffb-b1c0d259cc5b&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:13a39635-40d1-4e13-ad0d-5bf8d42a72ec&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:6b02071c-5b6c-42ef-a462-ba21cf5731c6&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:e4003788-7713-4165-a4de-74c58fa7d6bf&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:bc473aa5-a9d6-47ff-befa-b3dac991ef85&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:909ce747-b9a3-4a1d-9856-c32d8e2b1c4a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:dde42db4-483b-43c9-aa42-153365d5efee&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:5763ef56-bc45-4e33-9df4-be5e8072a273&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:8fb9e99e-3f39-4263-856f-61f6423bd232&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>violation:bf503023-267a-43b4-a86b-34040111ebb4&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-34)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|

***

</details>

***


# MinorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	[Previous section](#majorfail-outcomes)	|	[Next section](#nottested-outcomes)

Here is the chapter related to the MinorFail outcome

:exclamation:19 MinorFail outcomes

<details>
<summary>Fold/Unfold the 19 summary and details</summary>

## MinorFail Outcomes Summary

:exclamation:19 MinorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-1">1/19</div>|:exclamation:MinorFail|`module-src-unreferenced`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-1)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-2">2/19</div>|:exclamation:MinorFail|`module-src-unlabeled`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-2)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-3">3/19</div>|:exclamation:MinorFail|`module-src-too-close-terms`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-3)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-4">4/19</div>|:exclamation:MinorFail|`module-src-not-ql`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-4)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-5">5/19</div>|:exclamation:MinorFail|`module-src-not-el`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-5)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-6">6/19</div>|:exclamation:MinorFail|`modelet-zedomain-label`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-6)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-7">7/19</div>|:exclamation:MinorFail|`modelet-zedomain-differenciation`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-7)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-8">8/19</div>|:exclamation:MinorFail|`modelet-zedomain-compatQL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-8)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-9">9/19</div>|:exclamation:MinorFail|`modelet-zedomain-compatEL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-9)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-10">10/19</div>|:exclamation:MinorFail|`all-modules`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-10)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-11">11/19</div>|:exclamation:MinorFail|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-11)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-12">12/19</div>|:exclamation:MinorFail|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-12)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-13">13/19</div>|:exclamation:MinorFail|`all-modules`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-13)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-14">14/19</div>|:exclamation:MinorFail|`all-modules`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-14)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-15">15/19</div>|:exclamation:MinorFail|`all-fragments`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-15)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-16">16/19</div>|:exclamation:MinorFail|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-16)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-17">17/19</div>|:exclamation:MinorFail|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-17)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-18">18/19</div>|:exclamation:MinorFail|`all-fragments`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-18)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-19">19/19</div>|:exclamation:MinorFail|`all-fragments`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-19)|

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
|[Section top](#minorfail-outcome-number-2)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-2)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-2)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-2)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 3

[Jump to summary definition](#summary-MinorFail-3)	|	[Previous MinorFail outcome](#minorfail-outcome-number-2)	|	[Next MinorFail outcome](#minorfail-outcome-number-4)

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
|[Section top](#minorfail-outcome-number-3)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-3)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-3)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 4

[Jump to summary definition](#summary-MinorFail-4)	|	[Previous MinorFail outcome](#minorfail-outcome-number-3)	|	[Next MinorFail outcome](#minorfail-outcome-number-5)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-4)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-4)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-4)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 5

[Jump to summary definition](#summary-MinorFail-5)	|	[Previous MinorFail outcome](#minorfail-outcome-number-4)	|	[Next MinorFail outcome](#minorfail-outcome-number-6)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-5)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-5)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-5)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 6

[Jump to summary definition](#summary-MinorFail-6)	|	[Previous MinorFail outcome](#minorfail-outcome-number-5)	|	[Next MinorFail outcome](#minorfail-outcome-number-7)

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
|[Section top](#minorfail-outcome-number-6)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-6)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-6)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 7

[Jump to summary definition](#summary-MinorFail-7)	|	[Previous MinorFail outcome](#minorfail-outcome-number-6)	|	[Next MinorFail outcome](#minorfail-outcome-number-8)

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
|[Section top](#minorfail-outcome-number-7)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-7)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-7)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-7)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 8

[Jump to summary definition](#summary-MinorFail-8)	|	[Previous MinorFail outcome](#minorfail-outcome-number-7)	|	[Next MinorFail outcome](#minorfail-outcome-number-9)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-8)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-8)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-8)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-8)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 9

[Jump to summary definition](#summary-MinorFail-9)	|	[Previous MinorFail outcome](#minorfail-outcome-number-8)	|	[Next MinorFail outcome](#minorfail-outcome-number-10)

:exclamation:MinorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

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
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

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
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-11)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-11)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-11)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 12

[Jump to summary definition](#summary-MinorFail-12)	|	[Previous MinorFail outcome](#minorfail-outcome-number-11)	|	[Next MinorFail outcome](#minorfail-outcome-number-13)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-12)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-12)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-12)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 13

[Jump to summary definition](#summary-MinorFail-13)	|	[Previous MinorFail outcome](#minorfail-outcome-number-12)	|	[Next MinorFail outcome](#minorfail-outcome-number-14)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-13)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-13)|Title|Term&#32;not&#32;referenced&#32;to&#32;a&#32;module|
|[Section top](#minorfail-outcome-number-13)|Description|Subject&#32;terms&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|
|[Section top](#minorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>:NotReferencedClass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;p...&#34; &#32;.</code></pre>|

***
### MinorFail Outcome number 14

[Jump to summary definition](#summary-MinorFail-14)	|	[Previous MinorFail outcome](#minorfail-outcome-number-13)	|	[Next MinorFail outcome](#minorfail-outcome-number-15)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-14)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-14)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-14)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MinorFail Outcome number 15

[Jump to summary definition](#summary-MinorFail-15)	|	[Previous MinorFail outcome](#minorfail-outcome-number-14)	|	[Next MinorFail outcome](#minorfail-outcome-number-16)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-15)|Identifier|`not-labeled-term`|
|[Section top](#minorfail-outcome-number-15)|Title|Terms&#32;not&#32;labeled|
|[Section top](#minorfail-outcome-number-15)|Description|The&#32;following&#32;terms&#32;have&#32;no&#32;rdfs:label&#32;to&#32;define&#32;it&#32;in&#32;natural&#32;language|
|[Section top](#minorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MinorFail Outcome number 16

[Jump to summary definition](#summary-MinorFail-16)	|	[Previous MinorFail outcome](#minorfail-outcome-number-15)	|	[Next MinorFail outcome](#minorfail-outcome-number-17)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-16)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-16)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-16)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 17

[Jump to summary definition](#summary-MinorFail-17)	|	[Previous MinorFail outcome](#minorfail-outcome-number-16)	|	[Next MinorFail outcome](#minorfail-outcome-number-18)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-17)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-17)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-17)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 18

[Jump to summary definition](#summary-MinorFail-18)	|	[Previous MinorFail outcome](#minorfail-outcome-number-17)	|	[Next MinorFail outcome](#minorfail-outcome-number-19)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-18)|Identifier|`no-reference-module`|
|[Section top](#minorfail-outcome-number-18)|Title|Term&#32;not&#32;referenced&#32;to&#32;a&#32;module|
|[Section top](#minorfail-outcome-number-18)|Description|Subject&#32;terms&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|
|[Section top](#minorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:NotReferencedClass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;not&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;p...&#34; &#32;.</code></pre>|

***
### MinorFail Outcome number 19

[Jump to summary definition](#summary-MinorFail-19)	|	[Previous MinorFail outcome](#minorfail-outcome-number-18)	|	Next MinorFail outcome

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-19)|Identifier|`too-close-terms`|
|[Section top](#minorfail-outcome-number-19)|Title|Too&#32;close&#32;terms|
|[Section top](#minorfail-outcome-number-19)|Description|Some&#32;terms&#32;are&#32;too&#32;similar|
|[Section top](#minorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#minorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

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

:white_check_mark:154 Pass outcomes

<details>
<summary>Fold/Unfold the 154 summary and details</summary>

## Pass Outcomes Summary

:white_check_mark:154 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-1">1/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-1)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-2">2/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-2)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-3">3/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-3)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-4">4/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-4)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-5">5/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-5)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-6">6/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-6)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-7">7/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-7)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-8">8/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-8)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-9">9/154</div>|:white_check_mark:Pass|`module-src-unreferenced`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-9)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-10">10/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-10)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-11">11/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-11)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-12">12/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-12)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-13">13/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-13)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-14">14/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-14)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-15">15/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-15)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-16">16/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-16)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-17">17/154</div>|:white_check_mark:Pass|`module-src-unlabeled`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-17)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-18">18/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-18)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-19">19/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-19)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-20">20/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-20)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-21">21/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-21)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-22">22/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-22)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-23">23/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-23)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-24">24/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-24)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-25">25/154</div>|:white_check_mark:Pass|`module-src-too-close-terms`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-25)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-26">26/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-26)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-27">27/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-27)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-28">28/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-28)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-29">29/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-29)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-30">30/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-30)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-31">31/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-31)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-32">32/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-32)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-33">33/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-33)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-34">34/154</div>|:white_check_mark:Pass|`module-src-range-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-34)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-35">35/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-35)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-36">36/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-36)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-37">37/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-37)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-38">38/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-38)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-39">39/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-39)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-40">40/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-40)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-41">41/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-41)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-42">42/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-42)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-43">43/154</div>|:white_check_mark:Pass|`module-src-not-rl`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-43)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-44">44/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-44)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-45">45/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-45)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-46">46/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-46)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-47">47/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-47)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-48">48/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-48)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-49">49/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-49)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-50">50/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-50)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-51">51/154</div>|:white_check_mark:Pass|`module-src-not-ql`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-51)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-52">52/154</div>|:white_check_mark:Pass|`module-src-not-el`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-52)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-53">53/154</div>|:white_check_mark:Pass|`module-src-not-el`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-53)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-54">54/154</div>|:white_check_mark:Pass|`module-src-not-el`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-54)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-55">55/154</div>|:white_check_mark:Pass|`module-src-not-el`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-55)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-56">56/154</div>|:white_check_mark:Pass|`module-src-not-el`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-56)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-57">57/154</div>|:white_check_mark:Pass|`module-src-not-el`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-57)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-58">58/154</div>|:white_check_mark:Pass|`module-src-not-el`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-58)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-59">59/154</div>|:white_check_mark:Pass|`module-src-not-el`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-59)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-60">60/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-60)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-61">61/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-61)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-62">62/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-62)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-63">63/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-63)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-64">64/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-64)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-65">65/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-65)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-66">66/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-66)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-67">67/154</div>|:white_check_mark:Pass|`module-src-inconsistent`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-67)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-68">68/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-68)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-69">69/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-69)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-70">70/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-70)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-71">71/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-71)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-72">72/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-72)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-73">73/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-73)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-74">74/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-74)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-75">75/154</div>|:white_check_mark:Pass|`module-src-domain-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-75)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-76">76/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-76)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-77">77/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-77)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-78">78/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-78)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-79">79/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-79)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-80">80/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-80)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-81">81/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-81)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-82">82/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-82)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-83">83/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-83)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-84">84/154</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-84)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-85">85/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-85)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-86">86/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-86)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-87">87/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-87)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-88">88/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-88)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-89">89/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-89)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-90">90/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-90)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-91">91/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-91)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-92">92/154</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-92)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-93">93/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-93)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-94">94/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-94)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-95">95/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-95)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-96">96/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-96)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-97">97/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-97)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-98">98/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-98)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-99">99/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-99)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-100">100/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-100)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-101">101/154</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-101)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-102">102/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-102)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-103">103/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-103)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-104">104/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-104)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-105">105/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-105)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-106">106/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-106)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-107">107/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-107)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-108">108/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-108)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-109">109/154</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-109)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-110">110/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-110)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-111">111/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-111)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-112">112/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-112)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-113">113/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-113)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-114">114/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-114)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-115">115/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-115)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-116">116/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-116)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-117">117/154</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-117)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-118">118/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-118)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-119">119/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-119)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-120">120/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-120)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-121">121/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-121)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-122">122/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-122)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-123">123/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-123)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-124">124/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-124)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-125">125/154</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-125)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-126">126/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-126)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-127">127/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-127)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-128">128/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-128)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-129">129/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-129)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-130">130/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-130)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-131">131/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-131)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-132">132/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-132)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-133">133/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-133)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-134">134/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-134)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-135">135/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-135)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-136">136/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-136)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-137">137/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-137)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-138">138/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-138)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-139">139/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-139)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-140">140/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-140)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-141">141/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-141)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-142">142/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-142)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-143">143/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-143)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-144">144/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-144)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-145">145/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-145)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-146">146/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-146)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-147">147/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-147)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-148">148/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-148)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-149">149/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-149)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-150">150/154</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-150)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-151">151/154</div>|:white_check_mark:Pass|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-151)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-152">152/154</div>|:white_check_mark:Pass|`all-modules`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-152)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-153">153/154</div>|:white_check_mark:Pass|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-153)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-154">154/154</div>|:white_check_mark:Pass|`all-fragments`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-154)|

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
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-1)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-1)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-1)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

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
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-2)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-2)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-2)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

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
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-3)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-3)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-3)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

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
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-4)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-4)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-4)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

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
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-5)|Identifier|`comment-format`|
|[Section top](#pass-outcome-number-5)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-5)|Description|The&#32;custom&#32;test&#32; &#32;passed|

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
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-6)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-6)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-6)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

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
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-7)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-7)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-7)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

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
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-8)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-8)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-8)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

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
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-9)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-9)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-9)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 10

[Jump to summary definition](#summary-Pass-10)	|	[Previous Pass outcome](#pass-outcome-number-9)	|	[Next Pass outcome](#pass-outcome-number-11)

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
|[Section top](#pass-outcome-number-10)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-10)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-10)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)	|	[Previous Pass outcome](#pass-outcome-number-10)	|	[Next Pass outcome](#pass-outcome-number-12)

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
|[Section top](#pass-outcome-number-11)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-11)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-11)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 12

[Jump to summary definition](#summary-Pass-12)	|	[Previous Pass outcome](#pass-outcome-number-11)	|	[Next Pass outcome](#pass-outcome-number-13)

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
|[Section top](#pass-outcome-number-12)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-12)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-12)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 13

[Jump to summary definition](#summary-Pass-13)	|	[Previous Pass outcome](#pass-outcome-number-12)	|	[Next Pass outcome](#pass-outcome-number-14)

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
|[Section top](#pass-outcome-number-13)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-13)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-13)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 14

[Jump to summary definition](#summary-Pass-14)	|	[Previous Pass outcome](#pass-outcome-number-13)	|	[Next Pass outcome](#pass-outcome-number-15)

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
|[Section top](#pass-outcome-number-14)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-14)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-14)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)	|	[Previous Pass outcome](#pass-outcome-number-14)	|	[Next Pass outcome](#pass-outcome-number-16)

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
|[Section top](#pass-outcome-number-15)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-15)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-15)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 16

[Jump to summary definition](#summary-Pass-16)	|	[Previous Pass outcome](#pass-outcome-number-15)	|	[Next Pass outcome](#pass-outcome-number-17)

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
|[Section top](#pass-outcome-number-16)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-16)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-16)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 17

[Jump to summary definition](#summary-Pass-17)	|	[Previous Pass outcome](#pass-outcome-number-16)	|	[Next Pass outcome](#pass-outcome-number-18)

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
|[Section top](#pass-outcome-number-17)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-17)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-17)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 18

[Jump to summary definition](#summary-Pass-18)	|	[Previous Pass outcome](#pass-outcome-number-17)	|	[Next Pass outcome](#pass-outcome-number-19)

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
|[Section top](#pass-outcome-number-18)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-18)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-18)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 19

[Jump to summary definition](#summary-Pass-19)	|	[Previous Pass outcome](#pass-outcome-number-18)	|	[Next Pass outcome](#pass-outcome-number-20)

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
|[Section top](#pass-outcome-number-19)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-19)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-19)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 20

[Jump to summary definition](#summary-Pass-20)	|	[Previous Pass outcome](#pass-outcome-number-19)	|	[Next Pass outcome](#pass-outcome-number-21)

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
|[Section top](#pass-outcome-number-20)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-20)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-20)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 21

[Jump to summary definition](#summary-Pass-21)	|	[Previous Pass outcome](#pass-outcome-number-20)	|	[Next Pass outcome](#pass-outcome-number-22)

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
|[Section top](#pass-outcome-number-21)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-21)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-21)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 22

[Jump to summary definition](#summary-Pass-22)	|	[Previous Pass outcome](#pass-outcome-number-21)	|	[Next Pass outcome](#pass-outcome-number-23)

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
|[Section top](#pass-outcome-number-22)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-22)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-22)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 23

[Jump to summary definition](#summary-Pass-23)	|	[Previous Pass outcome](#pass-outcome-number-22)	|	[Next Pass outcome](#pass-outcome-number-24)

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
|[Section top](#pass-outcome-number-23)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-23)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-23)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 24

[Jump to summary definition](#summary-Pass-24)	|	[Previous Pass outcome](#pass-outcome-number-23)	|	[Next Pass outcome](#pass-outcome-number-25)

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
|[Section top](#pass-outcome-number-24)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-24)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-24)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 25

[Jump to summary definition](#summary-Pass-25)	|	[Previous Pass outcome](#pass-outcome-number-24)	|	[Next Pass outcome](#pass-outcome-number-26)

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
|[Section top](#pass-outcome-number-25)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-25)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-25)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 26

[Jump to summary definition](#summary-Pass-26)	|	[Previous Pass outcome](#pass-outcome-number-25)	|	[Next Pass outcome](#pass-outcome-number-27)

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
|[Section top](#pass-outcome-number-26)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-26)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-26)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 27

[Jump to summary definition](#summary-Pass-27)	|	[Previous Pass outcome](#pass-outcome-number-26)	|	[Next Pass outcome](#pass-outcome-number-28)

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
|[Section top](#pass-outcome-number-27)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-27)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-27)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 28

[Jump to summary definition](#summary-Pass-28)	|	[Previous Pass outcome](#pass-outcome-number-27)	|	[Next Pass outcome](#pass-outcome-number-29)

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
|[Section top](#pass-outcome-number-28)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-28)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-28)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 29

[Jump to summary definition](#summary-Pass-29)	|	[Previous Pass outcome](#pass-outcome-number-28)	|	[Next Pass outcome](#pass-outcome-number-30)

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
|[Section top](#pass-outcome-number-29)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-29)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-29)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 30

[Jump to summary definition](#summary-Pass-30)	|	[Previous Pass outcome](#pass-outcome-number-29)	|	[Next Pass outcome](#pass-outcome-number-31)

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
|[Section top](#pass-outcome-number-30)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-30)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-30)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 31

[Jump to summary definition](#summary-Pass-31)	|	[Previous Pass outcome](#pass-outcome-number-30)	|	[Next Pass outcome](#pass-outcome-number-32)

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
|[Section top](#pass-outcome-number-31)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-31)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-31)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 32

[Jump to summary definition](#summary-Pass-32)	|	[Previous Pass outcome](#pass-outcome-number-31)	|	[Next Pass outcome](#pass-outcome-number-33)

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
|[Section top](#pass-outcome-number-32)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-32)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-32)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 33

[Jump to summary definition](#summary-Pass-33)	|	[Previous Pass outcome](#pass-outcome-number-32)	|	[Next Pass outcome](#pass-outcome-number-34)

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
|[Section top](#pass-outcome-number-33)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-33)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-33)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 34

[Jump to summary definition](#summary-Pass-34)	|	[Previous Pass outcome](#pass-outcome-number-33)	|	[Next Pass outcome](#pass-outcome-number-35)

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
|[Section top](#pass-outcome-number-34)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-34)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-34)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 35

[Jump to summary definition](#summary-Pass-35)	|	[Previous Pass outcome](#pass-outcome-number-34)	|	[Next Pass outcome](#pass-outcome-number-36)

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
|[Section top](#pass-outcome-number-35)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-35)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-35)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 36

[Jump to summary definition](#summary-Pass-36)	|	[Previous Pass outcome](#pass-outcome-number-35)	|	[Next Pass outcome](#pass-outcome-number-37)

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
|[Section top](#pass-outcome-number-36)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-36)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-36)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 37

[Jump to summary definition](#summary-Pass-37)	|	[Previous Pass outcome](#pass-outcome-number-36)	|	[Next Pass outcome](#pass-outcome-number-38)

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
|[Section top](#pass-outcome-number-37)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-37)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-37)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 38

[Jump to summary definition](#summary-Pass-38)	|	[Previous Pass outcome](#pass-outcome-number-37)	|	[Next Pass outcome](#pass-outcome-number-39)

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
|[Section top](#pass-outcome-number-38)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-38)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-38)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 39

[Jump to summary definition](#summary-Pass-39)	|	[Previous Pass outcome](#pass-outcome-number-38)	|	[Next Pass outcome](#pass-outcome-number-40)

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
|[Section top](#pass-outcome-number-39)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-39)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-39)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 40

[Jump to summary definition](#summary-Pass-40)	|	[Previous Pass outcome](#pass-outcome-number-39)	|	[Next Pass outcome](#pass-outcome-number-41)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-40)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-40)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-40)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 41

[Jump to summary definition](#summary-Pass-41)	|	[Previous Pass outcome](#pass-outcome-number-40)	|	[Next Pass outcome](#pass-outcome-number-42)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-41)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-41)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-41)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 42

[Jump to summary definition](#summary-Pass-42)	|	[Previous Pass outcome](#pass-outcome-number-41)	|	[Next Pass outcome](#pass-outcome-number-43)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-rl|
|----|----|
|Title|Standalone&#32;module&#32;src/not-rl.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-42)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-42)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-42)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 43

[Jump to summary definition](#summary-Pass-43)	|	[Previous Pass outcome](#pass-outcome-number-42)	|	[Next Pass outcome](#pass-outcome-number-44)

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
|[Section top](#pass-outcome-number-43)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-43)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-43)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 44

[Jump to summary definition](#summary-Pass-44)	|	[Previous Pass outcome](#pass-outcome-number-43)	|	[Next Pass outcome](#pass-outcome-number-45)

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
|[Section top](#pass-outcome-number-44)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-44)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-44)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 45

[Jump to summary definition](#summary-Pass-45)	|	[Previous Pass outcome](#pass-outcome-number-44)	|	[Next Pass outcome](#pass-outcome-number-46)

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
|[Section top](#pass-outcome-number-45)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-45)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-45)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 46

[Jump to summary definition](#summary-Pass-46)	|	[Previous Pass outcome](#pass-outcome-number-45)	|	[Next Pass outcome](#pass-outcome-number-47)

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
|[Section top](#pass-outcome-number-46)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-46)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-46)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 47

[Jump to summary definition](#summary-Pass-47)	|	[Previous Pass outcome](#pass-outcome-number-46)	|	[Next Pass outcome](#pass-outcome-number-48)

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
|[Section top](#pass-outcome-number-47)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-47)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-47)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 48

[Jump to summary definition](#summary-Pass-48)	|	[Previous Pass outcome](#pass-outcome-number-47)	|	[Next Pass outcome](#pass-outcome-number-49)

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
|[Section top](#pass-outcome-number-48)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-48)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-48)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 49

[Jump to summary definition](#summary-Pass-49)	|	[Previous Pass outcome](#pass-outcome-number-48)	|	[Next Pass outcome](#pass-outcome-number-50)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-49)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-49)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-49)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 50

[Jump to summary definition](#summary-Pass-50)	|	[Previous Pass outcome](#pass-outcome-number-49)	|	[Next Pass outcome](#pass-outcome-number-51)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-50)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-50)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-50)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 51

[Jump to summary definition](#summary-Pass-51)	|	[Previous Pass outcome](#pass-outcome-number-50)	|	[Next Pass outcome](#pass-outcome-number-52)

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
|[Section top](#pass-outcome-number-51)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-51)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-51)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 52

[Jump to summary definition](#summary-Pass-52)	|	[Previous Pass outcome](#pass-outcome-number-51)	|	[Next Pass outcome](#pass-outcome-number-53)

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
|[Section top](#pass-outcome-number-52)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-52)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-52)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 53

[Jump to summary definition](#summary-Pass-53)	|	[Previous Pass outcome](#pass-outcome-number-52)	|	[Next Pass outcome](#pass-outcome-number-54)

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
|[Section top](#pass-outcome-number-53)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-53)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-53)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 54

[Jump to summary definition](#summary-Pass-54)	|	[Previous Pass outcome](#pass-outcome-number-53)	|	[Next Pass outcome](#pass-outcome-number-55)

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
|[Section top](#pass-outcome-number-54)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-54)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-54)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 55

[Jump to summary definition](#summary-Pass-55)	|	[Previous Pass outcome](#pass-outcome-number-54)	|	[Next Pass outcome](#pass-outcome-number-56)

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
|[Section top](#pass-outcome-number-55)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-55)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-55)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 56

[Jump to summary definition](#summary-Pass-56)	|	[Previous Pass outcome](#pass-outcome-number-55)	|	[Next Pass outcome](#pass-outcome-number-57)

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
|[Section top](#pass-outcome-number-56)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-56)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-56)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 57

[Jump to summary definition](#summary-Pass-57)	|	[Previous Pass outcome](#pass-outcome-number-56)	|	[Next Pass outcome](#pass-outcome-number-58)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

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
|Name|module-src-not-el|
|----|----|
|Title|Standalone&#32;module&#32;src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

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
|[Section top](#pass-outcome-number-59)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-59)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-59)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 60

[Jump to summary definition](#summary-Pass-60)	|	[Previous Pass outcome](#pass-outcome-number-59)	|	[Next Pass outcome](#pass-outcome-number-61)

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
|[Section top](#pass-outcome-number-60)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-60)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-60)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 61

[Jump to summary definition](#summary-Pass-61)	|	[Previous Pass outcome](#pass-outcome-number-60)	|	[Next Pass outcome](#pass-outcome-number-62)

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
|[Section top](#pass-outcome-number-61)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-61)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-61)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 62

[Jump to summary definition](#summary-Pass-62)	|	[Previous Pass outcome](#pass-outcome-number-61)	|	[Next Pass outcome](#pass-outcome-number-63)

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
|[Section top](#pass-outcome-number-62)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-62)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-62)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 63

[Jump to summary definition](#summary-Pass-63)	|	[Previous Pass outcome](#pass-outcome-number-62)	|	[Next Pass outcome](#pass-outcome-number-64)

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
|[Section top](#pass-outcome-number-63)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-63)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-63)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 64

[Jump to summary definition](#summary-Pass-64)	|	[Previous Pass outcome](#pass-outcome-number-63)	|	[Next Pass outcome](#pass-outcome-number-65)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-64)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-64)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-64)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 65

[Jump to summary definition](#summary-Pass-65)	|	[Previous Pass outcome](#pass-outcome-number-64)	|	[Next Pass outcome](#pass-outcome-number-66)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-65)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-65)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-65)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 66

[Jump to summary definition](#summary-Pass-66)	|	[Previous Pass outcome](#pass-outcome-number-65)	|	[Next Pass outcome](#pass-outcome-number-67)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-66)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-66)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-66)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 67

[Jump to summary definition](#summary-Pass-67)	|	[Previous Pass outcome](#pass-outcome-number-66)	|	[Next Pass outcome](#pass-outcome-number-68)

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
|[Section top](#pass-outcome-number-67)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-67)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-67)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 68

[Jump to summary definition](#summary-Pass-68)	|	[Previous Pass outcome](#pass-outcome-number-67)	|	[Next Pass outcome](#pass-outcome-number-69)

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
|[Section top](#pass-outcome-number-68)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-68)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-68)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 69

[Jump to summary definition](#summary-Pass-69)	|	[Previous Pass outcome](#pass-outcome-number-68)	|	[Next Pass outcome](#pass-outcome-number-70)

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
|[Section top](#pass-outcome-number-69)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-69)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-69)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 70

[Jump to summary definition](#summary-Pass-70)	|	[Previous Pass outcome](#pass-outcome-number-69)	|	[Next Pass outcome](#pass-outcome-number-71)

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
|[Section top](#pass-outcome-number-70)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-70)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-70)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 71

[Jump to summary definition](#summary-Pass-71)	|	[Previous Pass outcome](#pass-outcome-number-70)	|	[Next Pass outcome](#pass-outcome-number-72)

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
|[Section top](#pass-outcome-number-71)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-71)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-71)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 72

[Jump to summary definition](#summary-Pass-72)	|	[Previous Pass outcome](#pass-outcome-number-71)	|	[Next Pass outcome](#pass-outcome-number-73)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-72)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-72)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-72)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 73

[Jump to summary definition](#summary-Pass-73)	|	[Previous Pass outcome](#pass-outcome-number-72)	|	[Next Pass outcome](#pass-outcome-number-74)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-73)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-73)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-73)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 74

[Jump to summary definition](#summary-Pass-74)	|	[Previous Pass outcome](#pass-outcome-number-73)	|	[Next Pass outcome](#pass-outcome-number-75)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-src-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-74)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-74)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-74)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 75

[Jump to summary definition](#summary-Pass-75)	|	[Previous Pass outcome](#pass-outcome-number-74)	|	[Next Pass outcome](#pass-outcome-number-76)

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
|[Section top](#pass-outcome-number-75)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-75)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-75)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 76

[Jump to summary definition](#summary-Pass-76)	|	[Previous Pass outcome](#pass-outcome-number-75)	|	[Next Pass outcome](#pass-outcome-number-77)

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
|[Section top](#pass-outcome-number-76)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-76)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-76)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 77

[Jump to summary definition](#summary-Pass-77)	|	[Previous Pass outcome](#pass-outcome-number-76)	|	[Next Pass outcome](#pass-outcome-number-78)

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
|[Section top](#pass-outcome-number-77)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-77)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-77)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 78

[Jump to summary definition](#summary-Pass-78)	|	[Previous Pass outcome](#pass-outcome-number-77)	|	[Next Pass outcome](#pass-outcome-number-79)

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
|[Section top](#pass-outcome-number-78)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-78)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-78)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 79

[Jump to summary definition](#summary-Pass-79)	|	[Previous Pass outcome](#pass-outcome-number-78)	|	[Next Pass outcome](#pass-outcome-number-80)

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
|[Section top](#pass-outcome-number-79)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-79)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-79)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 80

[Jump to summary definition](#summary-Pass-80)	|	[Previous Pass outcome](#pass-outcome-number-79)	|	[Next Pass outcome](#pass-outcome-number-81)

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
|[Section top](#pass-outcome-number-80)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-80)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-80)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 81

[Jump to summary definition](#summary-Pass-81)	|	[Previous Pass outcome](#pass-outcome-number-80)	|	[Next Pass outcome](#pass-outcome-number-82)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-81)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-81)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-81)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 82

[Jump to summary definition](#summary-Pass-82)	|	[Previous Pass outcome](#pass-outcome-number-81)	|	[Next Pass outcome](#pass-outcome-number-83)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-82)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-82)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-82)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 83

[Jump to summary definition](#summary-Pass-83)	|	[Previous Pass outcome](#pass-outcome-number-82)	|	[Next Pass outcome](#pass-outcome-number-84)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-83)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-83)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-83)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 84

[Jump to summary definition](#summary-Pass-84)	|	[Previous Pass outcome](#pass-outcome-number-83)	|	[Next Pass outcome](#pass-outcome-number-85)

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
|[Section top](#pass-outcome-number-84)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-84)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-84)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 85

[Jump to summary definition](#summary-Pass-85)	|	[Previous Pass outcome](#pass-outcome-number-84)	|	[Next Pass outcome](#pass-outcome-number-86)

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
|[Section top](#pass-outcome-number-85)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-85)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-85)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 86

[Jump to summary definition](#summary-Pass-86)	|	[Previous Pass outcome](#pass-outcome-number-85)	|	[Next Pass outcome](#pass-outcome-number-87)

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
|[Section top](#pass-outcome-number-86)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-86)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-86)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 87

[Jump to summary definition](#summary-Pass-87)	|	[Previous Pass outcome](#pass-outcome-number-86)	|	[Next Pass outcome](#pass-outcome-number-88)

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
|[Section top](#pass-outcome-number-87)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-87)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-87)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 88

[Jump to summary definition](#summary-Pass-88)	|	[Previous Pass outcome](#pass-outcome-number-87)	|	[Next Pass outcome](#pass-outcome-number-89)

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
|[Section top](#pass-outcome-number-88)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-88)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-88)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 89

[Jump to summary definition](#summary-Pass-89)	|	[Previous Pass outcome](#pass-outcome-number-88)	|	[Next Pass outcome](#pass-outcome-number-90)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-89)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-89)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-89)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 90

[Jump to summary definition](#summary-Pass-90)	|	[Previous Pass outcome](#pass-outcome-number-89)	|	[Next Pass outcome](#pass-outcome-number-91)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-90)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-90)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-90)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 91

[Jump to summary definition](#summary-Pass-91)	|	[Previous Pass outcome](#pass-outcome-number-90)	|	[Next Pass outcome](#pass-outcome-number-92)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-91)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-91)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-91)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 92

[Jump to summary definition](#summary-Pass-92)	|	[Previous Pass outcome](#pass-outcome-number-91)	|	[Next Pass outcome](#pass-outcome-number-93)

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
|[Section top](#pass-outcome-number-92)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-92)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-92)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 93

[Jump to summary definition](#summary-Pass-93)	|	[Previous Pass outcome](#pass-outcome-number-92)	|	[Next Pass outcome](#pass-outcome-number-94)

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
|[Section top](#pass-outcome-number-93)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-93)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-93)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 94

[Jump to summary definition](#summary-Pass-94)	|	[Previous Pass outcome](#pass-outcome-number-93)	|	[Next Pass outcome](#pass-outcome-number-95)

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
|[Section top](#pass-outcome-number-94)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-94)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-94)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 95

[Jump to summary definition](#summary-Pass-95)	|	[Previous Pass outcome](#pass-outcome-number-94)	|	[Next Pass outcome](#pass-outcome-number-96)

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
|[Section top](#pass-outcome-number-95)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-95)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-95)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 96

[Jump to summary definition](#summary-Pass-96)	|	[Previous Pass outcome](#pass-outcome-number-95)	|	[Next Pass outcome](#pass-outcome-number-97)

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
|[Section top](#pass-outcome-number-96)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-96)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-96)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 97

[Jump to summary definition](#summary-Pass-97)	|	[Previous Pass outcome](#pass-outcome-number-96)	|	[Next Pass outcome](#pass-outcome-number-98)

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
|[Section top](#pass-outcome-number-97)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-97)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-97)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 98

[Jump to summary definition](#summary-Pass-98)	|	[Previous Pass outcome](#pass-outcome-number-97)	|	[Next Pass outcome](#pass-outcome-number-99)

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
|[Section top](#pass-outcome-number-98)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-98)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-98)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 99

[Jump to summary definition](#summary-Pass-99)	|	[Previous Pass outcome](#pass-outcome-number-98)	|	[Next Pass outcome](#pass-outcome-number-100)

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
|[Section top](#pass-outcome-number-99)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-99)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-99)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 100

[Jump to summary definition](#summary-Pass-100)	|	[Previous Pass outcome](#pass-outcome-number-99)	|	[Next Pass outcome](#pass-outcome-number-101)

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
|[Section top](#pass-outcome-number-100)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-100)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-100)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 101

[Jump to summary definition](#summary-Pass-101)	|	[Previous Pass outcome](#pass-outcome-number-100)	|	[Next Pass outcome](#pass-outcome-number-102)

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
|[Section top](#pass-outcome-number-101)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-101)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-101)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 102

[Jump to summary definition](#summary-Pass-102)	|	[Previous Pass outcome](#pass-outcome-number-101)	|	[Next Pass outcome](#pass-outcome-number-103)

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
|[Section top](#pass-outcome-number-102)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-102)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-102)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 103

[Jump to summary definition](#summary-Pass-103)	|	[Previous Pass outcome](#pass-outcome-number-102)	|	[Next Pass outcome](#pass-outcome-number-104)

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
|[Section top](#pass-outcome-number-103)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-103)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-103)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 104

[Jump to summary definition](#summary-Pass-104)	|	[Previous Pass outcome](#pass-outcome-number-103)	|	[Next Pass outcome](#pass-outcome-number-105)

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
|[Section top](#pass-outcome-number-104)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-104)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-104)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 105

[Jump to summary definition](#summary-Pass-105)	|	[Previous Pass outcome](#pass-outcome-number-104)	|	[Next Pass outcome](#pass-outcome-number-106)

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
|[Section top](#pass-outcome-number-105)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-105)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-105)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 106

[Jump to summary definition](#summary-Pass-106)	|	[Previous Pass outcome](#pass-outcome-number-105)	|	[Next Pass outcome](#pass-outcome-number-107)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-106)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-106)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-106)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 107

[Jump to summary definition](#summary-Pass-107)	|	[Previous Pass outcome](#pass-outcome-number-106)	|	[Next Pass outcome](#pass-outcome-number-108)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-107)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-107)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-107)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 108

[Jump to summary definition](#summary-Pass-108)	|	[Previous Pass outcome](#pass-outcome-number-107)	|	[Next Pass outcome](#pass-outcome-number-109)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-108)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-108)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-108)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 109

[Jump to summary definition](#summary-Pass-109)	|	[Previous Pass outcome](#pass-outcome-number-108)	|	[Next Pass outcome](#pass-outcome-number-110)

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
|[Section top](#pass-outcome-number-109)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-109)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-109)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 110

[Jump to summary definition](#summary-Pass-110)	|	[Previous Pass outcome](#pass-outcome-number-109)	|	[Next Pass outcome](#pass-outcome-number-111)

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
|[Section top](#pass-outcome-number-110)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-110)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-110)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 111

[Jump to summary definition](#summary-Pass-111)	|	[Previous Pass outcome](#pass-outcome-number-110)	|	[Next Pass outcome](#pass-outcome-number-112)

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
|[Section top](#pass-outcome-number-111)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-111)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-111)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 112

[Jump to summary definition](#summary-Pass-112)	|	[Previous Pass outcome](#pass-outcome-number-111)	|	[Next Pass outcome](#pass-outcome-number-113)

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
|[Section top](#pass-outcome-number-112)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-112)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-112)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 113

[Jump to summary definition](#summary-Pass-113)	|	[Previous Pass outcome](#pass-outcome-number-112)	|	[Next Pass outcome](#pass-outcome-number-114)

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
|[Section top](#pass-outcome-number-113)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-113)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-113)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 114

[Jump to summary definition](#summary-Pass-114)	|	[Previous Pass outcome](#pass-outcome-number-113)	|	[Next Pass outcome](#pass-outcome-number-115)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-114)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-114)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-114)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 115

[Jump to summary definition](#summary-Pass-115)	|	[Previous Pass outcome](#pass-outcome-number-114)	|	[Next Pass outcome](#pass-outcome-number-116)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-115)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-115)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-115)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 116

[Jump to summary definition](#summary-Pass-116)	|	[Previous Pass outcome](#pass-outcome-number-115)	|	[Next Pass outcome](#pass-outcome-number-117)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-116)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-116)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-116)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 117

[Jump to summary definition](#summary-Pass-117)	|	[Previous Pass outcome](#pass-outcome-number-116)	|	[Next Pass outcome](#pass-outcome-number-118)

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
|[Section top](#pass-outcome-number-117)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-117)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-117)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 118

[Jump to summary definition](#summary-Pass-118)	|	[Previous Pass outcome](#pass-outcome-number-117)	|	[Next Pass outcome](#pass-outcome-number-119)

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
|[Section top](#pass-outcome-number-118)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-118)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-118)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 119

[Jump to summary definition](#summary-Pass-119)	|	[Previous Pass outcome](#pass-outcome-number-118)	|	[Next Pass outcome](#pass-outcome-number-120)

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
|[Section top](#pass-outcome-number-119)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-119)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-119)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 120

[Jump to summary definition](#summary-Pass-120)	|	[Previous Pass outcome](#pass-outcome-number-119)	|	[Next Pass outcome](#pass-outcome-number-121)

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
|[Section top](#pass-outcome-number-120)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-120)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-120)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 121

[Jump to summary definition](#summary-Pass-121)	|	[Previous Pass outcome](#pass-outcome-number-120)	|	[Next Pass outcome](#pass-outcome-number-122)

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
|[Section top](#pass-outcome-number-121)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-121)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-121)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 122

[Jump to summary definition](#summary-Pass-122)	|	[Previous Pass outcome](#pass-outcome-number-121)	|	[Next Pass outcome](#pass-outcome-number-123)

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
|[Section top](#pass-outcome-number-122)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-122)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-122)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 123

[Jump to summary definition](#summary-Pass-123)	|	[Previous Pass outcome](#pass-outcome-number-122)	|	[Next Pass outcome](#pass-outcome-number-124)

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
|[Section top](#pass-outcome-number-123)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-123)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-123)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 124

[Jump to summary definition](#summary-Pass-124)	|	[Previous Pass outcome](#pass-outcome-number-123)	|	[Next Pass outcome](#pass-outcome-number-125)

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
|[Section top](#pass-outcome-number-124)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-124)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-124)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 125

[Jump to summary definition](#summary-Pass-125)	|	[Previous Pass outcome](#pass-outcome-number-124)	|	[Next Pass outcome](#pass-outcome-number-126)

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
|[Section top](#pass-outcome-number-125)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-125)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-125)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 126

[Jump to summary definition](#summary-Pass-126)	|	[Previous Pass outcome](#pass-outcome-number-125)	|	[Next Pass outcome](#pass-outcome-number-127)

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
|[Section top](#pass-outcome-number-126)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-126)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-126)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 127

[Jump to summary definition](#summary-Pass-127)	|	[Previous Pass outcome](#pass-outcome-number-126)	|	[Next Pass outcome](#pass-outcome-number-128)

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
|[Section top](#pass-outcome-number-127)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-127)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-127)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 128

[Jump to summary definition](#summary-Pass-128)	|	[Previous Pass outcome](#pass-outcome-number-127)	|	[Next Pass outcome](#pass-outcome-number-129)

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
|[Section top](#pass-outcome-number-128)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-128)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-128)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 129

[Jump to summary definition](#summary-Pass-129)	|	[Previous Pass outcome](#pass-outcome-number-128)	|	[Next Pass outcome](#pass-outcome-number-130)

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
|[Section top](#pass-outcome-number-129)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-129)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-129)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 130

[Jump to summary definition](#summary-Pass-130)	|	[Previous Pass outcome](#pass-outcome-number-129)	|	[Next Pass outcome](#pass-outcome-number-131)

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
|[Section top](#pass-outcome-number-130)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-130)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-130)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 131

[Jump to summary definition](#summary-Pass-131)	|	[Previous Pass outcome](#pass-outcome-number-130)	|	[Next Pass outcome](#pass-outcome-number-132)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-131)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-131)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-131)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 132

[Jump to summary definition](#summary-Pass-132)	|	[Previous Pass outcome](#pass-outcome-number-131)	|	[Next Pass outcome](#pass-outcome-number-133)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-132)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-132)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-132)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 133

[Jump to summary definition](#summary-Pass-133)	|	[Previous Pass outcome](#pass-outcome-number-132)	|	[Next Pass outcome](#pass-outcome-number-134)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-133)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-133)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-133)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 134

[Jump to summary definition](#summary-Pass-134)	|	[Previous Pass outcome](#pass-outcome-number-133)	|	[Next Pass outcome](#pass-outcome-number-135)

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
|[Section top](#pass-outcome-number-134)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-134)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-134)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 135

[Jump to summary definition](#summary-Pass-135)	|	[Previous Pass outcome](#pass-outcome-number-134)	|	[Next Pass outcome](#pass-outcome-number-136)

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
|[Section top](#pass-outcome-number-135)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-135)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-135)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 136

[Jump to summary definition](#summary-Pass-136)	|	[Previous Pass outcome](#pass-outcome-number-135)	|	[Next Pass outcome](#pass-outcome-number-137)

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
|[Section top](#pass-outcome-number-136)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-136)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-136)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 137

[Jump to summary definition](#summary-Pass-137)	|	[Previous Pass outcome](#pass-outcome-number-136)	|	[Next Pass outcome](#pass-outcome-number-138)

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
|[Section top](#pass-outcome-number-137)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-137)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-137)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 138

[Jump to summary definition](#summary-Pass-138)	|	[Previous Pass outcome](#pass-outcome-number-137)	|	[Next Pass outcome](#pass-outcome-number-139)

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
|[Section top](#pass-outcome-number-138)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-138)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-138)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 139

[Jump to summary definition](#summary-Pass-139)	|	[Previous Pass outcome](#pass-outcome-number-138)	|	[Next Pass outcome](#pass-outcome-number-140)

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
|[Section top](#pass-outcome-number-139)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-139)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-139)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 140

[Jump to summary definition](#summary-Pass-140)	|	[Previous Pass outcome](#pass-outcome-number-139)	|	[Next Pass outcome](#pass-outcome-number-141)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-140)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-140)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-140)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 141

[Jump to summary definition](#summary-Pass-141)	|	[Previous Pass outcome](#pass-outcome-number-140)	|	[Next Pass outcome](#pass-outcome-number-142)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-141)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-141)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-141)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 142

[Jump to summary definition](#summary-Pass-142)	|	[Previous Pass outcome](#pass-outcome-number-141)	|	[Next Pass outcome](#pass-outcome-number-143)

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
|[Section top](#pass-outcome-number-142)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-142)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-142)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 143

[Jump to summary definition](#summary-Pass-143)	|	[Previous Pass outcome](#pass-outcome-number-142)	|	[Next Pass outcome](#pass-outcome-number-144)

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
|[Section top](#pass-outcome-number-143)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-143)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-143)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 144

[Jump to summary definition](#summary-Pass-144)	|	[Previous Pass outcome](#pass-outcome-number-143)	|	[Next Pass outcome](#pass-outcome-number-145)

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
|[Section top](#pass-outcome-number-144)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-144)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-144)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 145

[Jump to summary definition](#summary-Pass-145)	|	[Previous Pass outcome](#pass-outcome-number-144)	|	[Next Pass outcome](#pass-outcome-number-146)

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
|[Section top](#pass-outcome-number-145)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-145)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-145)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 146

[Jump to summary definition](#summary-Pass-146)	|	[Previous Pass outcome](#pass-outcome-number-145)	|	[Next Pass outcome](#pass-outcome-number-147)

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
|[Section top](#pass-outcome-number-146)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-146)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-146)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 147

[Jump to summary definition](#summary-Pass-147)	|	[Previous Pass outcome](#pass-outcome-number-146)	|	[Next Pass outcome](#pass-outcome-number-148)

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
|[Section top](#pass-outcome-number-147)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-147)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-147)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 148

[Jump to summary definition](#summary-Pass-148)	|	[Previous Pass outcome](#pass-outcome-number-147)	|	[Next Pass outcome](#pass-outcome-number-149)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-148)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-148)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-148)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 149

[Jump to summary definition](#summary-Pass-149)	|	[Previous Pass outcome](#pass-outcome-number-148)	|	[Next Pass outcome](#pass-outcome-number-150)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)|

#### Criterion detail
|Identifier|[linked-schema](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/linked-schema.shacl#criterion)|
|----|----|
|Title|Linked&#32;schema&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;isolated&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-149)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-149)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-149)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 150

[Jump to summary definition](#summary-Pass-150)	|	[Previous Pass outcome](#pass-outcome-number-149)	|	[Next Pass outcome](#pass-outcome-number-151)

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
|[Section top](#pass-outcome-number-150)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-150)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-150)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 151

[Jump to summary definition](#summary-Pass-151)	|	[Previous Pass outcome](#pass-outcome-number-150)	|	[Next Pass outcome](#pass-outcome-number-152)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-151)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-151)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-151)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 152

[Jump to summary definition](#summary-Pass-152)	|	[Previous Pass outcome](#pass-outcome-number-151)	|	[Next Pass outcome](#pass-outcome-number-153)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-152)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-152)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-152)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 153

[Jump to summary definition](#summary-Pass-153)	|	[Previous Pass outcome](#pass-outcome-number-152)	|	[Next Pass outcome](#pass-outcome-number-154)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-153)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-153)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-153)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 154

[Jump to summary definition](#summary-Pass-154)	|	[Previous Pass outcome](#pass-outcome-number-153)	|	Next Pass outcome

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- [Module too-close-terms](https://github.com/acimov-tools/model-test/blob/main/src/too-close-terms.ttl)<br/>- [Module unlabeled](https://github.com/acimov-tools/model-test/blob/main/src/unlabeled.ttl)<br/>- [Module not-rl](https://github.com/acimov-tools/model-test/blob/main/src/not-rl.ttl)<br/>- [Module not-ql](https://github.com/acimov-tools/model-test/blob/main/src/not-ql.ttl)<br/>- [Module not-el](https://github.com/acimov-tools/model-test/blob/main/src/not-el.ttl)<br/>- [Module range-outer](https://github.com/acimov-tools/model-test/blob/main/src/range-outer.ttl)<br/>- [Module inconsistent](https://github.com/acimov-tools/model-test/blob/main/src/inconsistent.ttl)<br/>- [Module domain-outer](https://github.com/acimov-tools/model-test/blob/main/src/domain-outer.ttl)<br/>- [Module unreferenced](https://github.com/acimov-tools/model-test/blob/main/src/unreferenced.ttl)<br/>- [Modelet zedomain/differenciation](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/differenciation/onto.ttl)<br/>- [Modelet zedomain/rangeout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/rangeout/onto.ttl)<br/>- [Modelet zedomain/compatQL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatQL/onto.ttl)<br/>- [Modelet zedomain/dovrov](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/dovrov/onto.ttl)<br/>- [Modelet zedomain/compatEL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatEL/onto.ttl)<br/>- [Modelet zedomain/domainout](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/domainout/onto.ttl)<br/>- [Modelet zedomain/inconsistence](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/inconsistence/onto.ttl)<br/>- [Modelet zedomain/compatRL](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/compatRL/onto.ttl)<br/>- [Modelet zedomain/label](https://github.com/acimov-tools/model-test/blob/main/domains/zedomain/label/onto.ttl)|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-154)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-154)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-154)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***

</details>

***
