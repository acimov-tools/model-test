# Test Report Markdown Export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check [Corese website](https://project.inria.fr/corese/) and [Corese repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./model-test-actions.ttl).

# Test Activity

Here is some information about the testing activity that led to this report

|Title|Model&#32;tests&#32;of&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|--|--|
|Description|[NicoRobertIn](https://github.com/NicoRobertIn)&#32;launch&#32;actions&#32;run&#32;of&#32;model&#32;tests&#32;against&#32;[acimov-tools/model-test](https://github.com/acimov-tools/model-test)&#32;on&#32;branch&#32;main|
|Tester|[NicoRobertIn](https://github.com/NicoRobertIn)|
|Ontology|[acimov-tools/model-test](https://github.com/acimov-tools/model-test)|
|Ontology version|[95391d1bb292d1b6e48e8f796f098af5a8f5b980](https://github.com/acimov-tools/model-test/tree/95391d1bb292d1b6e48e8f796f098af5a8f5b980)|
|Ontology branch|[main](https://github.com/acimov-tools/model-test/tree/main)|
|Olivaw suite|[olivaw model test suite](https://github.com/Wimmics/olivaw/blob/v0.0.8/olivaw/test/model/suite.py)|
|Olivaw version|[v0.0.8](https://pypi.org/project/olivaw/0.0.8)|
|Generated turtle|[Turtle report](https://github.com/acimov-tools/model-test/blob/95391d1bb292d1b6e48e8f796f098af5a8f5b980/.acimov/output/model-test-actions.ttl)|
|Generated Markdown|[Markdown report](https://github.com/acimov-tools/model-test/blob/95391d1bb292d1b6e48e8f796f098af5a8f5b980/.acimov/output/model-test-actions.md)|

# Statistic summary

Here is a short overview for this test report

281 Outcomes

:boom:33 MajorFail, :exclamation:19 MinorFail, :warning:0 CannotTell, :grey_question:8 NotTested, :white_check_mark:221 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="11%" height="25px"/><img src="../assets/orange.png" width="6%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="2%" height="25px"/><img src="../assets/green.png" width="81%" height="25px"/></div>

<br/>

The different status types are an extension of the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary where the nextended terms can be found in the [olivaw ontology](https://ns.inria.fr/olivaw#), each outcome type means:
* :boom: MajorFail: This is an error that is critical and considered as blocking for production
* :exclamation: MinorFail: This is an error that should be fixed, but it cannot be considered as critical error
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a final decision.
* :grey_question: NotTested:  The test has not been carried out. It is because some prerequisite tests did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Outcomes

[Jump to statistic summary](#statistic-summary)	|	Previous section	|	[Next section](#minorfail-outcomes)

Here is the chapter related to the MajorFail outcome

:boom:33 MajorFail outcomes

<details>
<summary>Fold/Unfold the 33 summary and details</summary>

## MajorFail Outcomes Summary

:boom:33 MajorFail outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-1">1/33</div>|:boom:MajorFail|`module-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-1)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-2">2/33</div>|:boom:MajorFail|`module-unknown-prefix`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-2)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-3">3/33</div>|:boom:MajorFail|`module-too-close-terms`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-3)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-4">4/33</div>|:boom:MajorFail|`module-range-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-4)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-5">5/33</div>|:boom:MajorFail|`module-not-ql`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-5)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-6">6/33</div>|:boom:MajorFail|`module-not-el`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-6)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-7">7/33</div>|:boom:MajorFail|`module-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-7)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-8">8/33</div>|:boom:MajorFail|`module-inconsistent`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-8)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-9">9/33</div>|:boom:MajorFail|`module-inconsistent`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-9)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-10">10/33</div>|:boom:MajorFail|`module-domain-outer`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-10)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-11">11/33</div>|:boom:MajorFail|`module-domain-outer`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-11)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-12">12/33</div>|:boom:MajorFail|`module-broken`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-12)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-13">13/33</div>|:boom:MajorFail|`modelet-zedomain-syntax`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-13)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-14">14/33</div>|:boom:MajorFail|`modelet-zedomain-rangeout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-14)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-15">15/33</div>|:boom:MajorFail|`modelet-zedomain-prefix`|[syntax](https://ns.inria.fr/olivaw#syntax)|Test subject has syntax errors|[Jump](#majorfail-outcome-number-15)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-16">16/33</div>|:boom:MajorFail|`modelet-zedomain-label`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-16)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-17">17/33</div>|:boom:MajorFail|`modelet-zedomain-inconsistence`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-17)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-18">18/33</div>|:boom:MajorFail|`modelet-zedomain-dovrov`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-18)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-19">19/33</div>|:boom:MajorFail|`modelet-zedomain-dovrov`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-19)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-20">20/33</div>|:boom:MajorFail|`modelet-zedomain-domainout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-20)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-21">21/33</div>|:boom:MajorFail|`modelet-zedomain-domainout`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-21)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-22">22/33</div>|:boom:MajorFail|`modelet-zedomain-differenciation`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-22)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-23">23/33</div>|:boom:MajorFail|`modelet-zedomain-compatRL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-23)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-24">24/33</div>|:boom:MajorFail|`modelet-zedomain-compatQL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-24)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-25">25/33</div>|:boom:MajorFail|`modelet-zedomain-compatEL`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-25)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-26">26/33</div>|:boom:MajorFail|`all-modules`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-26)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-27">27/33</div>|:boom:MajorFail|`all-modules`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-27)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-28">28/33</div>|:boom:MajorFail|`all-modules`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-28)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-29">29/33</div>|:boom:MajorFail|`all-modules`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-29)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-30">30/33</div>|:boom:MajorFail|`all-fragments`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domain out of vocabulary|[Jump](#majorfail-outcome-number-30)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-31">31/33</div>|:boom:MajorFail|`all-fragments`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-31)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-32">32/33</div>|:boom:MajorFail|`all-fragments`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL Constraint violation|[Jump](#majorfail-outcome-number-32)|
|[Chapter top](#majorfail-outcomes)|<div id="summary-MajorFail-33">33/33</div>|:boom:MajorFail|`all-fragments`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Error on custom test |[Jump](#majorfail-outcome-number-33)|

***

## MajorFail Outcomes Details

This subchapter gives more details to the :boom:MajorFail outcomes

### MajorFail Outcome number 1

[Jump to summary definition](#summary-MajorFail-1)	|	Previous MajorFail outcome	|	[Next MajorFail outcome](#majorfail-outcome-number-2)

:boom:MajorFail outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>violation:9da4910c-ebc7-4966-a3af-b893deabb7ad&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-1)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 2

[Jump to summary definition](#summary-MajorFail-2)	|	[Previous MajorFail outcome](#majorfail-outcome-number-1)	|	[Next MajorFail outcome](#majorfail-outcome-number-3)

:boom:MajorFail outcome
#### Subject detail
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>violation:c2ce93f7-7608-49dc-8368-62a4af7b2725&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>violation:61a5a9e8-6c9a-45e5-882a-3ab053ce2667&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-3)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 4

[Jump to summary definition](#summary-MajorFail-4)	|	[Previous MajorFail outcome](#majorfail-outcome-number-3)	|	[Next MajorFail outcome](#majorfail-outcome-number-5)

:boom:MajorFail outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>violation:66ac491c-939d-4f70-861d-3e80244accd2&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-4)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 5

[Jump to summary definition](#summary-MajorFail-5)	|	[Previous MajorFail outcome](#majorfail-outcome-number-4)	|	[Next MajorFail outcome](#majorfail-outcome-number-6)

:boom:MajorFail outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>violation:6713c7f2-1183-4342-970e-d61e7d294d4c&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-5)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 6

[Jump to summary definition](#summary-MajorFail-6)	|	[Previous MajorFail outcome](#majorfail-outcome-number-5)	|	[Next MajorFail outcome](#majorfail-outcome-number-7)

:boom:MajorFail outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>violation:ebcb5951-9906-494f-9b4d-4f4455a3e0cc&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-6)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 7

[Jump to summary definition](#summary-MajorFail-7)	|	[Previous MajorFail outcome](#majorfail-outcome-number-6)	|	[Next MajorFail outcome](#majorfail-outcome-number-8)

:boom:MajorFail outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-7)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 8

[Jump to summary definition](#summary-MajorFail-8)	|	[Previous MajorFail outcome](#majorfail-outcome-number-7)	|	[Next MajorFail outcome](#majorfail-outcome-number-9)

:boom:MajorFail outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>violation:86358ee7-27a7-4d2e-976a-be28b709cb3a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>violation:a40f7c0b-fc0e-4a04-a453-20537b9e636b&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>violation:7645039c-20f1-4ed5-bdb1-7df09fe499bf&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-9)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;.</code></pre>|

***
### MajorFail Outcome number 10

[Jump to summary definition](#summary-MajorFail-10)	|	[Previous MajorFail outcome](#majorfail-outcome-number-9)	|	[Next MajorFail outcome](#majorfail-outcome-number-11)

:boom:MajorFail outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-10)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-10)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-10)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-10)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-10)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 11

[Jump to summary definition](#summary-MajorFail-11)	|	[Previous MajorFail outcome](#majorfail-outcome-number-10)	|	[Next MajorFail outcome](#majorfail-outcome-number-12)

:boom:MajorFail outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>violation:c2b961e9-3b8e-4d18-bc97-c980fbf41e5f&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 12

[Jump to summary definition](#summary-MajorFail-12)	|	[Previous MajorFail outcome](#majorfail-outcome-number-11)	|	[Next MajorFail outcome](#majorfail-outcome-number-13)

:boom:MajorFail outcome
#### Subject detail
|Name|module-broken|
|----|----|
|Title|Standalone&#32;module&#32;../../src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-12)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-12)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-12)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-12)|Pointer|<pre lang="Turtle"><code>Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;9,&#32;column&#32;23.</code></pre>|

***
### MajorFail Outcome number 13

[Jump to summary definition](#summary-MajorFail-13)	|	[Previous MajorFail outcome](#majorfail-outcome-number-12)	|	[Next MajorFail outcome](#majorfail-outcome-number-14)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-syntax|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-13)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-13)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-13)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-13)|Pointer|<pre lang="Turtle"><code>Encountered&#32; &#34;a&#34; &#32;at&#32;line&#32;7,&#32;column&#32;23.</code></pre>|

***
### MajorFail Outcome number 14

[Jump to summary definition](#summary-MajorFail-14)	|	[Previous MajorFail outcome](#majorfail-outcome-number-13)	|	[Next MajorFail outcome](#majorfail-outcome-number-15)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-14)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-14)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-14)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>violation:29c6cb8b-2c51-4283-8226-948d04b97e01&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-14)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 15

[Jump to summary definition](#summary-MajorFail-15)	|	[Previous MajorFail outcome](#majorfail-outcome-number-14)	|	[Next MajorFail outcome](#majorfail-outcome-number-16)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-prefix|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[syntax](https://ns.inria.fr/olivaw#syntax)|
|----|----|
|Title|Syntax&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-15)|Identifier|`syntax-error`|
|[Section top](#majorfail-outcome-number-15)|Title|Test&#32;subject&#32;has&#32;syntax&#32;errors|
|[Section top](#majorfail-outcome-number-15)|Description|The&#32;subject&#32;has&#32;turtle&#32;syntax&#32;errors&#32;that&#32;makes&#32;it&#32;unprocessable&#32;by&#32;an&#32;engine|
|[Section top](#majorfail-outcome-number-15)|Pointer|<pre lang="Turtle"><code>at&#32;line&#32;3&#32;of&#32; &#60;>:  &#10;Bad&#32;syntax&#32;(Prefix&#32; &#34;owl:&#34; &#32;not&#32;bound)&#32;at&#32;&Hat;&#32;in:  &#10; &#34;...b'fix&#32;:&#32; &#60;https://www.example.org/olivaw/> &#32;.&#92;n&#92;n:unknownPrefix&#32;a&#32;'&Hat;b'owl:Ontology&#32;.&#92;n&#92;n:Unknown&#32;a&#32;owl:Class&#32;;&#92;n&#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;'...&#34;</code></pre>|

***
### MajorFail Outcome number 16

[Jump to summary definition](#summary-MajorFail-16)	|	[Previous MajorFail outcome](#majorfail-outcome-number-15)	|	[Next MajorFail outcome](#majorfail-outcome-number-17)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>violation:7f24526d-cadb-48f4-a8e1-bd2d6fda15b3&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-16)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|

***
### MajorFail Outcome number 17

[Jump to summary definition](#summary-MajorFail-17)	|	[Previous MajorFail outcome](#majorfail-outcome-number-16)	|	[Next MajorFail outcome](#majorfail-outcome-number-18)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>violation:33480ed2-ff4b-4ec8-b91c-e1bbfdbfd138&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>violation:e343831c-29ca-48bc-8a77-2debcc03f2bd&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>violation:fb427dfe-157d-4e7c-8daf-84ea9d67fd2c&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|

***
### MajorFail Outcome number 18

[Jump to summary definition](#summary-MajorFail-18)	|	[Previous MajorFail outcome](#majorfail-outcome-number-17)	|	[Next MajorFail outcome](#majorfail-outcome-number-19)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-18)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-18)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-18)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-18)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-18)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 19

[Jump to summary definition](#summary-MajorFail-19)	|	[Previous MajorFail outcome](#majorfail-outcome-number-18)	|	[Next MajorFail outcome](#majorfail-outcome-number-20)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>violation:333b5164-fbfd-4162-a5db-295515a5a808&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-19)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 20

[Jump to summary definition](#summary-MajorFail-20)	|	[Previous MajorFail outcome](#majorfail-outcome-number-19)	|	[Next MajorFail outcome](#majorfail-outcome-number-21)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-20)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-20)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 21

[Jump to summary definition](#summary-MajorFail-21)	|	[Previous MajorFail outcome](#majorfail-outcome-number-20)	|	[Next MajorFail outcome](#majorfail-outcome-number-22)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>violation:59aa354a-a5d5-4034-b0da-443084e150b6&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-21)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|

***
### MajorFail Outcome number 22

[Jump to summary definition](#summary-MajorFail-22)	|	[Previous MajorFail outcome](#majorfail-outcome-number-21)	|	[Next MajorFail outcome](#majorfail-outcome-number-23)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>violation:5969c6a3-6d60-473f-a5d3-339548b64eb6&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>violation:dae659a4-e13c-45c8-b8ad-e4268e2ffdbc&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-22)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|

***
### MajorFail Outcome number 23

[Jump to summary definition](#summary-MajorFail-23)	|	[Previous MajorFail outcome](#majorfail-outcome-number-22)	|	[Next MajorFail outcome](#majorfail-outcome-number-24)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>violation:a963e647-b87d-49fd-bf4f-dee20218e9f5&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-23)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|

***
### MajorFail Outcome number 24

[Jump to summary definition](#summary-MajorFail-24)	|	[Previous MajorFail outcome](#majorfail-outcome-number-23)	|	[Next MajorFail outcome](#majorfail-outcome-number-25)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>violation:fd32d223-4134-450e-ad6c-d9cd746d013d&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-24)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|

***
### MajorFail Outcome number 25

[Jump to summary definition](#summary-MajorFail-25)	|	[Previous MajorFail outcome](#majorfail-outcome-number-24)	|	[Next MajorFail outcome](#majorfail-outcome-number-26)

:boom:MajorFail outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>violation:30937d3a-2766-48dc-a5bf-54b9eb1d9b1d&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-25)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|

***
### MajorFail Outcome number 26

[Jump to summary definition](#summary-MajorFail-26)	|	[Previous MajorFail outcome](#majorfail-outcome-number-25)	|	[Next MajorFail outcome](#majorfail-outcome-number-27)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-26)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-26)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-26)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-26)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-26)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 27

[Jump to summary definition](#summary-MajorFail-27)	|	[Previous MajorFail outcome](#majorfail-outcome-number-26)	|	[Next MajorFail outcome](#majorfail-outcome-number-28)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-27)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-27)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-27)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 28

[Jump to summary definition](#summary-MajorFail-28)	|	[Previous MajorFail outcome](#majorfail-outcome-number-27)	|	[Next MajorFail outcome](#majorfail-outcome-number-29)

:boom:MajorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-29)|Identifier|`comment-format`|
|[Section top](#majorfail-outcome-number-29)|Title|Error&#32;on&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-29)|Description|Error&#32;occured&#32;while&#32;running&#32;custom&#32;test&#32;|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:shape&#32;a&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;sh:property&#32; &#91;&#32;sh:message&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Violation&#32;],  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#91;&#32;sh:languageIn&#32;(&#32; &#34;en&#34; &#32;)&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:message&#32; &#34;Comment&#32;not&#32;in&#32;@en/without&#32;line&#32;break/ending&#32;with&#32;full&#32;stop&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:path&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:pattern&#32; &#34;&Hat;&#91;&Hat;&#92; &#92;n]+&#92; &#92;.$&#34; &#32;;  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;sh:severity&#32;sh:Warning&#32;]&#32;;  &#10; &#32; &#32; &#32; &#32;sh:targetSubjectsOf&#32;rdfs:isDefinedBy&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:310b442e-65dd-4f69-bd74-ac4d511db582&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:5c25f38e-20f7-42de-b4e6-9d5c028dc9d8&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:9f2b1a11-1d3b-4e46-a27f-01da27ea9556&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:030c5abb-1acf-40ad-9e92-8fd3971bfcac&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:c50a0433-9866-494a-89ab-5d387741d372&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:66ec3718-36f7-42ac-861e-be2aaf36c523&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:6d4ce19e-dd82-43f6-b05d-7e47a8ba7917&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:9c9a45f0-4709-4d4c-9e47-356f51bf5926&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:b3e19fe0-efcf-4be7-9b5d-cb39d29ad84e&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:a3168a90-6aad-443b-9797-7b6ea95a313a&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>violation:040286aa-3c7b-4a44-aef9-15d59c7f6999&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-29)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|

***
### MajorFail Outcome number 30

[Jump to summary definition](#summary-MajorFail-30)	|	[Previous MajorFail outcome](#majorfail-outcome-number-29)	|	[Next MajorFail outcome](#majorfail-outcome-number-31)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-30)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#majorfail-outcome-number-30)|Title|Domain&#32;out&#32;of&#32;vocabulary|
|[Section top](#majorfail-outcome-number-30)|Description|Some&#32;properties&#32;have&#32;a&#32;domain&#32;out&#32;of&#32;the&#32;ontology|
|[Section top](#majorfail-outcome-number-30)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-30)|Pointer|http://www.w3.org/ns/shacl#NodeShape|

***
### MajorFail Outcome number 31

[Jump to summary definition](#summary-MajorFail-31)	|	[Previous MajorFail outcome](#majorfail-outcome-number-30)	|	[Next MajorFail outcome](#majorfail-outcome-number-32)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:boom:MajorFail|
|----|----|----|
|[Section top](#majorfail-outcome-number-31)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#majorfail-outcome-number-31)|Title|OWL&#32;RL&#32;Constraint&#32;violation|
|[Section top](#majorfail-outcome-number-31)|Description|http://www.w3.org/2002/07/owl#AllDisjointClasses&#32; &#10;rdf:type&#32;sp:ConstraintViolation&#32; &#10;sp:violationRoot&#32; &#60;https://www.example.org/olivaw/BrokenSubclass> &#32; &#10;rdfs:label&#32; &#34;Violates&#32;owl:AllDisjointClasses&#34; &#32; &#10;sp:arg1&#32; &#60;https://www.example.org/olivaw/DisjointTheFirst> &#32; &#10;sp:arg2&#32; &#60;https://www.example.org/olivaw/DisjointTheSecond> &#32; &#10; &#32; &#10;|

***
### MajorFail Outcome number 32

[Jump to summary definition](#summary-MajorFail-32)	|	[Previous MajorFail outcome](#majorfail-outcome-number-31)	|	[Next MajorFail outcome](#majorfail-outcome-number-33)

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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

[Jump to summary definition](#summary-MajorFail-33)	|	[Previous MajorFail outcome](#majorfail-outcome-number-32)	|	Next MajorFail outcome

:boom:MajorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:d2cabcc2-7367-4920-bf84-da4eb226f1a9&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notQLTermCauseTransitive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notQL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:62b50a39-3f0f-4277-abf3-7cfddf460581&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:unlabeledTerm&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:unlabeledTerm&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32;&#32; &#32;rdfs:isDefinedBy&#32;:unlabeled&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:69d04750-8314-4d94-992e-c592eee56efe&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notELTermCauseAsymmetric&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notEL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:7fc06da5-a76f-4287-8ab7-0d15a25090f1&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:domainReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:domainReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;property&#32;has&#32;a&#32;domain&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:domain&#32;sh:NodeShape&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:domainOuter&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:775c0dfb-78ac-4b8e-8867-d02e6f61d065&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:notRLTermCauseReflexive&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:notRLTermCauseReflexive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ReflexiveObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;RL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:notRL&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:4d75a3ac-c464-4ede-9c9e-be5d0e6445a1&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:BrokenSubclass&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:BrokenSubclass&#32;a&#32;owl:Class,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;is&#32;broken&#32;because&#32;it&#32;is&#32;a&#32;subclass&#32;of&#32;disjoint&#32;cl...&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:subClassOf&#32;:DisjointTheFirst,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;:DisjointTheSecond&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:647e4a83-bbd4-449f-ab01-e8da22829899&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheSecond&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:DisjointTheSecond&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;second&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;forst&#32;one&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheFirst&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:5580426a-43ed-4ed2-8739-067da52288df&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassB&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:ClassB&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;B&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:a1286588-4e08-45b0-b67d-efa9ae7cad5c&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:rangeReferencingOut&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:rangeReferencingOut&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;range&#32;out&#32;of&#32;vocabulary&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:rangeOuter&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:range&#32;sh:NodeShape&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:d888e162-4ab1-48cd-8c61-66e5a1850cff&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:ClassA&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:ClassA&#32;a&#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;class&#32;has&#32;a&#32;name&#32;too&#32;close&#32;to&#32;class&#32;A&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:tooCloseTerms&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>violation:96fc1c6e-b29f-40f3-98f5-3204b78dd82e&#32;a&#32;sh:ValidationResult&#32;;  &#10; &#32; &#32; &#32; &#32;sh:focusNode&#32;sand:DisjointTheFirst&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultMessage&#32; &#34;Ontology&#32;term&#32;should&#32;have&#32;one&#32;and&#32;only&#32;one&#32;rdfs:comment&#34; &#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultPath&#32;rdfs:comment&#32;;  &#10; &#32; &#32; &#32; &#32;sh:resultSeverity&#32;sh:Violation&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceConstraintComponent&#32;sh:MinCountConstraintComponent&#32;;  &#10; &#32; &#32; &#32; &#32;sh:sourceShape&#32; &#91;&#32;]&#32;.</code></pre>|
|[Section top](#majorfail-outcome-number-33)|Pointer|<pre lang="Turtle"><code>:DisjointTheFirst&#32;a&#32;owl:Class&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;first&#32;class&#32;is&#32;disjoint&#32;from&#32;the&#32;other&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;:inconsistent&#32;;  &#10; &#32; &#32; &#32; &#32;owl:disjointWith&#32;:DisjointTheSecond&#32;.</code></pre>|

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
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-1">1/19</div>|:exclamation:MinorFail|`module-unreferenced`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-1)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-2">2/19</div>|:exclamation:MinorFail|`module-unlabeled`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-2)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-3">3/19</div>|:exclamation:MinorFail|`module-too-close-terms`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-3)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-4">4/19</div>|:exclamation:MinorFail|`module-not-ql`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-4)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-5">5/19</div>|:exclamation:MinorFail|`module-not-el`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-5)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-6">6/19</div>|:exclamation:MinorFail|`modelet-zedomain-label`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-6)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-7">7/19</div>|:exclamation:MinorFail|`modelet-zedomain-differenciation`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-7)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-8">8/19</div>|:exclamation:MinorFail|`modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-8)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-9">9/19</div>|:exclamation:MinorFail|`modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-9)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-10">10/19</div>|:exclamation:MinorFail|`all-modules`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-10)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-11">11/19</div>|:exclamation:MinorFail|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-11)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-12">12/19</div>|:exclamation:MinorFail|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-12)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-13">13/19</div>|:exclamation:MinorFail|`all-modules`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-13)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-14">14/19</div>|:exclamation:MinorFail|`all-modules`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-14)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-15">15/19</div>|:exclamation:MinorFail|`all-fragments`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|Terms not labeled|[Jump](#minorfail-outcome-number-15)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-16">16/19</div>|:exclamation:MinorFail|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile incompatible|[Jump](#minorfail-outcome-number-16)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-17">17/19</div>|:exclamation:MinorFail|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile incompatible|[Jump](#minorfail-outcome-number-17)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-18">18/19</div>|:exclamation:MinorFail|`all-fragments`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Term not referenced to a module|[Jump](#minorfail-outcome-number-18)|
|[Chapter top](#minorfail-outcomes)|<div id="summary-MinorFail-19">19/19</div>|:exclamation:MinorFail|`all-fragments`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Too close terms|[Jump](#minorfail-outcome-number-19)|

***

## MinorFail Outcomes Details

This subchapter gives more details to the :exclamation:MinorFail outcomes

### MinorFail Outcome number 1

[Jump to summary definition](#summary-MinorFail-1)	|	Previous MinorFail outcome	|	[Next MinorFail outcome](#minorfail-outcome-number-2)

:exclamation:MinorFail outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

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
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-11)|Identifier|`owl-el-profile-error`|
|[Section top](#minorfail-outcome-number-11)|Title|OWL&#32;EL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-11)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-11)|Pointer|<pre lang="Turtle"><code>sand:notELTermCauseAsymmetric&#32;a&#32;owl:AsymmetricProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:ObjectProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;EL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notEL&#32;.</code></pre>|

***
### MinorFail Outcome number 12

[Jump to summary definition](#summary-MinorFail-12)	|	[Previous MinorFail outcome](#minorfail-outcome-number-11)	|	[Next MinorFail outcome](#minorfail-outcome-number-13)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:exclamation:MinorFail|
|----|----|----|
|[Section top](#minorfail-outcome-number-17)|Identifier|`owl-ql-profile-error`|
|[Section top](#minorfail-outcome-number-17)|Title|OWL&#32;QL&#32;Profile&#32;incompatible|
|[Section top](#minorfail-outcome-number-17)|Description|Statement&#32;not&#32;supported|
|[Section top](#minorfail-outcome-number-17)|Pointer|<pre lang="Turtle"><code>sand:notQLTermCauseTransitive&#32;a&#32;owl:ObjectProperty,  &#10; &#32; &#32; &#32; &#32; &#32; &#32; &#32; &#32;owl:TransitiveProperty&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:label&#32; &#34;This&#32;term&#32;has&#32;a&#32;statement&#32;that&#32;is&#32;not&#32;QL&#32;compatible&#34;@en&#32;;  &#10; &#32; &#32; &#32; &#32;rdfs:isDefinedBy&#32;sand:notQL&#32;.</code></pre>|

***
### MinorFail Outcome number 18

[Jump to summary definition](#summary-MinorFail-18)	|	[Previous MinorFail outcome](#minorfail-outcome-number-17)	|	[Next MinorFail outcome](#minorfail-outcome-number-19)

:exclamation:MinorFail outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-1">1/8</div>|:grey_question:NotTested|`module-unknown-prefix`|[comment-format](https://ns.inria.fr/olivaw#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-1)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-2">2/8</div>|:grey_question:NotTested|`module-unknown-prefix`|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-2)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-3">3/8</div>|:grey_question:NotTested|`module-broken`|[comment-format](https://ns.inria.fr/olivaw#comment-format)|Error on custom test |[Jump](#nottested-outcome-number-3)|
|[Chapter top](#nottested-outcomes)|<div id="summary-NotTested-4">4/8</div>|:grey_question:NotTested|`module-broken`|[subclass-cycle](https://ns.inria.fr/olivaw#subclass-cycle)|Error on custom test |[Jump](#nottested-outcome-number-4)|
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
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unknown-prefix|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unknown-prefix.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-broken|
|----|----|
|Title|Standalone&#32;module&#32;../../src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-broken|
|----|----|
|Title|Standalone&#32;module&#32;../../src/broken.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/syntax/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/prefix/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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

:white_check_mark:221 Pass outcomes

<details>
<summary>Fold/Unfold the 221 summary and details</summary>

## Pass Outcomes Summary

:white_check_mark:221 Pass outcomes

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-1">1/221</div>|:white_check_mark:Pass|`module-unreferenced`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-1)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-2">2/221</div>|:white_check_mark:Pass|`module-unreferenced`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-2)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-3">3/221</div>|:white_check_mark:Pass|`module-unreferenced`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-3)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-4">4/221</div>|:white_check_mark:Pass|`module-unreferenced`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-4)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-5">5/221</div>|:white_check_mark:Pass|`module-unreferenced`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-5)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-6">6/221</div>|:white_check_mark:Pass|`module-unreferenced`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-6)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-7">7/221</div>|:white_check_mark:Pass|`module-unreferenced`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-7)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-8">8/221</div>|:white_check_mark:Pass|`module-unreferenced`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-8)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-9">9/221</div>|:white_check_mark:Pass|`module-unreferenced`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-9)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-10">10/221</div>|:white_check_mark:Pass|`module-unreferenced`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-10)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-11">11/221</div>|:white_check_mark:Pass|`module-unreferenced`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-11)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-12">12/221</div>|:white_check_mark:Pass|`module-unreferenced`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-12)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-13">13/221</div>|:white_check_mark:Pass|`module-unreferenced`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-13)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-14">14/221</div>|:white_check_mark:Pass|`module-unlabeled`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-14)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-15">15/221</div>|:white_check_mark:Pass|`module-unlabeled`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-15)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-16">16/221</div>|:white_check_mark:Pass|`module-unlabeled`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-16)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-17">17/221</div>|:white_check_mark:Pass|`module-unlabeled`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-17)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-18">18/221</div>|:white_check_mark:Pass|`module-unlabeled`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-18)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-19">19/221</div>|:white_check_mark:Pass|`module-unlabeled`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-19)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-20">20/221</div>|:white_check_mark:Pass|`module-unlabeled`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-20)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-21">21/221</div>|:white_check_mark:Pass|`module-unlabeled`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-21)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-22">22/221</div>|:white_check_mark:Pass|`module-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|OWL EL Profile compatible|[Jump](#pass-outcome-number-22)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-23">23/221</div>|:white_check_mark:Pass|`module-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|OWL QL Profile compatible|[Jump](#pass-outcome-number-23)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-24">24/221</div>|:white_check_mark:Pass|`module-unlabeled`|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|OWL RL Profile compatible|[Jump](#pass-outcome-number-24)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-25">25/221</div>|:white_check_mark:Pass|`module-unlabeled`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-25)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-26">26/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-26)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-27">27/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-27)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-28">28/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-28)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-29">29/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-29)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-30">30/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-30)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-31">31/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-31)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-32">32/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-32)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-33">33/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-33)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-34">34/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-34)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-35">35/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-35)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-36">36/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-36)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-37">37/221</div>|:white_check_mark:Pass|`module-too-close-terms`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-37)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-38">38/221</div>|:white_check_mark:Pass|`module-range-outer`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-38)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-39">39/221</div>|:white_check_mark:Pass|`module-range-outer`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-39)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-40">40/221</div>|:white_check_mark:Pass|`module-range-outer`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-40)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-41">41/221</div>|:white_check_mark:Pass|`module-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-41)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-42">42/221</div>|:white_check_mark:Pass|`module-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-42)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-43">43/221</div>|:white_check_mark:Pass|`module-range-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-43)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-44">44/221</div>|:white_check_mark:Pass|`module-range-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-44)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-45">45/221</div>|:white_check_mark:Pass|`module-range-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-45)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-46">46/221</div>|:white_check_mark:Pass|`module-range-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-46)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-47">47/221</div>|:white_check_mark:Pass|`module-range-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-47)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-48">48/221</div>|:white_check_mark:Pass|`module-range-outer`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-48)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-49">49/221</div>|:white_check_mark:Pass|`module-range-outer`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-49)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-50">50/221</div>|:white_check_mark:Pass|`module-range-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-50)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-51">51/221</div>|:white_check_mark:Pass|`module-not-ql`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-51)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-52">52/221</div>|:white_check_mark:Pass|`module-not-ql`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-52)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-53">53/221</div>|:white_check_mark:Pass|`module-not-ql`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-53)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-54">54/221</div>|:white_check_mark:Pass|`module-not-ql`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-54)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-55">55/221</div>|:white_check_mark:Pass|`module-not-ql`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-55)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-56">56/221</div>|:white_check_mark:Pass|`module-not-ql`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-56)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-57">57/221</div>|:white_check_mark:Pass|`module-not-ql`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-57)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-58">58/221</div>|:white_check_mark:Pass|`module-not-ql`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-58)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-59">59/221</div>|:white_check_mark:Pass|`module-not-ql`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-59)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-60">60/221</div>|:white_check_mark:Pass|`module-not-ql`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-60)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-61">61/221</div>|:white_check_mark:Pass|`module-not-ql`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-61)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-62">62/221</div>|:white_check_mark:Pass|`module-not-ql`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-62)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-63">63/221</div>|:white_check_mark:Pass|`module-not-el`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-63)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-64">64/221</div>|:white_check_mark:Pass|`module-not-el`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-64)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-65">65/221</div>|:white_check_mark:Pass|`module-not-el`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-65)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-66">66/221</div>|:white_check_mark:Pass|`module-not-el`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-66)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-67">67/221</div>|:white_check_mark:Pass|`module-not-el`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-67)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-68">68/221</div>|:white_check_mark:Pass|`module-not-el`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-68)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-69">69/221</div>|:white_check_mark:Pass|`module-not-el`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-69)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-70">70/221</div>|:white_check_mark:Pass|`module-not-el`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-70)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-71">71/221</div>|:white_check_mark:Pass|`module-not-el`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-71)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-72">72/221</div>|:white_check_mark:Pass|`module-not-el`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-72)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-73">73/221</div>|:white_check_mark:Pass|`module-not-el`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-73)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-74">74/221</div>|:white_check_mark:Pass|`module-not-el`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-74)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-75">75/221</div>|:white_check_mark:Pass|`module-inconsistent`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-75)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-76">76/221</div>|:white_check_mark:Pass|`module-inconsistent`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-76)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-77">77/221</div>|:white_check_mark:Pass|`module-inconsistent`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-77)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-78">78/221</div>|:white_check_mark:Pass|`module-inconsistent`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-78)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-79">79/221</div>|:white_check_mark:Pass|`module-inconsistent`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-79)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-80">80/221</div>|:white_check_mark:Pass|`module-inconsistent`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-80)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-81">81/221</div>|:white_check_mark:Pass|`module-inconsistent`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-81)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-82">82/221</div>|:white_check_mark:Pass|`module-inconsistent`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-82)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-83">83/221</div>|:white_check_mark:Pass|`module-inconsistent`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-83)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-84">84/221</div>|:white_check_mark:Pass|`module-inconsistent`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-84)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-85">85/221</div>|:white_check_mark:Pass|`module-inconsistent`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-85)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-86">86/221</div>|:white_check_mark:Pass|`module-inconsistent`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-86)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-87">87/221</div>|:white_check_mark:Pass|`module-domain-outer`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-87)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-88">88/221</div>|:white_check_mark:Pass|`module-domain-outer`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-88)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-89">89/221</div>|:white_check_mark:Pass|`module-domain-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-89)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-90">90/221</div>|:white_check_mark:Pass|`module-domain-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-90)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-91">91/221</div>|:white_check_mark:Pass|`module-domain-outer`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-91)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-92">92/221</div>|:white_check_mark:Pass|`module-domain-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-92)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-93">93/221</div>|:white_check_mark:Pass|`module-domain-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-93)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-94">94/221</div>|:white_check_mark:Pass|`module-domain-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-94)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-95">95/221</div>|:white_check_mark:Pass|`module-domain-outer`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-95)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-96">96/221</div>|:white_check_mark:Pass|`module-domain-outer`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-96)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-97">97/221</div>|:white_check_mark:Pass|`module-domain-outer`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-97)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-98">98/221</div>|:white_check_mark:Pass|`module-domain-outer`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-98)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-99">99/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-99)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-100">100/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-100)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-101">101/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-101)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-102">102/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-102)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-103">103/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-103)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-104">104/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-104)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-105">105/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-105)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-106">106/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-106)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-107">107/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-107)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-108">108/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-108)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-109">109/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-109)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-110">110/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-110)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-111">111/221</div>|:white_check_mark:Pass|`modelet-zedomain-rangeout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-111)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-112">112/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-112)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-113">113/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-113)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-114">114/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-114)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-115">115/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-115)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-116">116/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-116)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-117">117/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-117)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-118">118/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-118)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-119">119/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-119)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-120">120/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-120)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-121">121/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-121)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-122">122/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-122)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-123">123/221</div>|:white_check_mark:Pass|`modelet-zedomain-label`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-123)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-124">124/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-124)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-125">125/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-125)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-126">126/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-126)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-127">127/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-127)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-128">128/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-128)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-129">129/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-129)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-130">130/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-130)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-131">131/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-131)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-132">132/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-132)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-133">133/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-133)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-134">134/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-134)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-135">135/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-135)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-136">136/221</div>|:white_check_mark:Pass|`modelet-zedomain-inconsistence`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-136)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-137">137/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-137)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-138">138/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-138)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-139">139/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-139)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-140">140/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-140)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-141">141/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-141)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-142">142/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-142)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-143">143/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-143)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-144">144/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-144)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-145">145/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-145)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-146">146/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-146)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-147">147/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-147)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-148">148/221</div>|:white_check_mark:Pass|`modelet-zedomain-dovrov`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-148)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-149">149/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-149)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-150">150/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-150)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-151">151/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-151)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-152">152/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-152)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-153">153/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-153)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-154">154/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-154)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-155">155/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-155)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-156">156/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-156)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-157">157/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-157)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-158">158/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-158)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-159">159/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-159)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-160">160/221</div>|:white_check_mark:Pass|`modelet-zedomain-domainout`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-160)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-161">161/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-161)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-162">162/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-162)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-163">163/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-163)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-164">164/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-164)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-165">165/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-165)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-166">166/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-166)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-167">167/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-167)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-168">168/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-168)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-169">169/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-169)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-170">170/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-170)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-171">171/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-171)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-172">172/221</div>|:white_check_mark:Pass|`modelet-zedomain-differenciation`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-172)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-173">173/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-173)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-174">174/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-174)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-175">175/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-175)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-176">176/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-176)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-177">177/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-177)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-178">178/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-178)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-179">179/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-179)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-180">180/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-180)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-181">181/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-181)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-182">182/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-182)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-183">183/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-183)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-184">184/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-184)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-185">185/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatRL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-185)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-186">186/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-186)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-187">187/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-187)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-188">188/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-188)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-189">189/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL EL Profile compatible|[Jump](#pass-outcome-number-189)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-190">190/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-190)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-191">191/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-191)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-192">192/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-192)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-193">193/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-193)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-194">194/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-194)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-195">195/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-195)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-196">196/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-196)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-197">197/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatQL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-197)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-198">198/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|Domains properly defined|[Jump](#pass-outcome-number-198)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-199">199/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|All terms labeled|[Jump](#pass-outcome-number-199)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-200">200/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|OWL RL consistent|[Jump](#pass-outcome-number-200)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-201">201/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL QL Profile compatible|[Jump](#pass-outcome-number-201)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-202">202/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-202)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-203">203/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-203)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-204">204/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-204)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-205">205/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-205)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-206">206/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-206)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-207">207/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|Any term is referenced|[Jump](#pass-outcome-number-207)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-208">208/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|Terms differenciated enough|[Jump](#pass-outcome-number-208)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-209">209/221</div>|:white_check_mark:Pass|`modelet-zedomain-compatEL`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-209)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-210">210/221</div>|:white_check_mark:Pass|`all-modules`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-210)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-211">211/221</div>|:white_check_mark:Pass|`all-modules`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-211)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-212">212/221</div>|:white_check_mark:Pass|`all-modules`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-212)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-213">213/221</div>|:white_check_mark:Pass|`all-modules`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-213)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-214">214/221</div>|:white_check_mark:Pass|`all-modules`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-214)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-215">215/221</div>|:white_check_mark:Pass|`all-modules`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-215)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-216">216/221</div>|:white_check_mark:Pass|`all-fragments`|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|OWL RL Profile compatible|[Jump](#pass-outcome-number-216)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-217">217/221</div>|:white_check_mark:Pass|`all-fragments`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No class subproperty|[Jump](#pass-outcome-number-217)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-218">218/221</div>|:white_check_mark:Pass|`all-fragments`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No property subclass|[Jump](#pass-outcome-number-218)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-219">219/221</div>|:white_check_mark:Pass|`all-fragments`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subclass of property|[Jump](#pass-outcome-number-219)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-220">220/221</div>|:white_check_mark:Pass|`all-fragments`|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|No subproperty of class|[Jump](#pass-outcome-number-220)|
|[Chapter top](#pass-outcomes)|<div id="summary-Pass-221">221/221</div>|:white_check_mark:Pass|`all-fragments`|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|Test  passed|[Jump](#pass-outcome-number-221)|

***

## Pass Outcomes Details

This subchapter gives more details to the :white_check_mark:Pass outcomes

### Pass Outcome number 1

[Jump to summary definition](#summary-Pass-1)	|	Previous Pass outcome	|	[Next Pass outcome](#pass-outcome-number-2)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-4)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-4)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-4)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 5

[Jump to summary definition](#summary-Pass-5)	|	[Previous Pass outcome](#pass-outcome-number-4)	|	[Next Pass outcome](#pass-outcome-number-6)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-5)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-5)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-5)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 6

[Jump to summary definition](#summary-Pass-6)	|	[Previous Pass outcome](#pass-outcome-number-5)	|	[Next Pass outcome](#pass-outcome-number-7)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

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
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-7)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-7)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-7)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 8

[Jump to summary definition](#summary-Pass-8)	|	[Previous Pass outcome](#pass-outcome-number-7)	|	[Next Pass outcome](#pass-outcome-number-9)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-8)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-8)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-8)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 9

[Jump to summary definition](#summary-Pass-9)	|	[Previous Pass outcome](#pass-outcome-number-8)	|	[Next Pass outcome](#pass-outcome-number-10)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-9)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-9)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-9)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 10

[Jump to summary definition](#summary-Pass-10)	|	[Previous Pass outcome](#pass-outcome-number-9)	|	[Next Pass outcome](#pass-outcome-number-11)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-10)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-10)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-10)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 11

[Jump to summary definition](#summary-Pass-11)	|	[Previous Pass outcome](#pass-outcome-number-10)	|	[Next Pass outcome](#pass-outcome-number-12)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unreferenced|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unreferenced.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-14)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-14)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-14)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 15

[Jump to summary definition](#summary-Pass-15)	|	[Previous Pass outcome](#pass-outcome-number-14)	|	[Next Pass outcome](#pass-outcome-number-16)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-15)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-15)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-15)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 16

[Jump to summary definition](#summary-Pass-16)	|	[Previous Pass outcome](#pass-outcome-number-15)	|	[Next Pass outcome](#pass-outcome-number-17)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
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
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
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
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-18)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-18)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-18)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 19

[Jump to summary definition](#summary-Pass-19)	|	[Previous Pass outcome](#pass-outcome-number-18)	|	[Next Pass outcome](#pass-outcome-number-20)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-19)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-19)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-19)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 20

[Jump to summary definition](#summary-Pass-20)	|	[Previous Pass outcome](#pass-outcome-number-19)	|	[Next Pass outcome](#pass-outcome-number-21)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-20)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-20)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-20)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 21

[Jump to summary definition](#summary-Pass-21)	|	[Previous Pass outcome](#pass-outcome-number-20)	|	[Next Pass outcome](#pass-outcome-number-22)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-21)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-21)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-21)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 22

[Jump to summary definition](#summary-Pass-22)	|	[Previous Pass outcome](#pass-outcome-number-21)	|	[Next Pass outcome](#pass-outcome-number-23)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

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
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-23)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-23)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-23)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 24

[Jump to summary definition](#summary-Pass-24)	|	[Previous Pass outcome](#pass-outcome-number-23)	|	[Next Pass outcome](#pass-outcome-number-25)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[comment-format](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/comment-format.shacl#criterion)|
|----|----|
|Title|Comment&#32;format&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;a&#32;comment&#32;format|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-24)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-24)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-24)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 25

[Jump to summary definition](#summary-Pass-25)	|	[Previous Pass outcome](#pass-outcome-number-24)	|	[Next Pass outcome](#pass-outcome-number-26)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-unlabeled|
|----|----|
|Title|Standalone&#32;module&#32;../../src/unlabeled.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-29)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-29)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-29)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 30

[Jump to summary definition](#summary-Pass-30)	|	[Previous Pass outcome](#pass-outcome-number-29)	|	[Next Pass outcome](#pass-outcome-number-31)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-31)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-31)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-31)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 32

[Jump to summary definition](#summary-Pass-32)	|	[Previous Pass outcome](#pass-outcome-number-31)	|	[Next Pass outcome](#pass-outcome-number-33)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-32)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-32)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-32)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 33

[Jump to summary definition](#summary-Pass-33)	|	[Previous Pass outcome](#pass-outcome-number-32)	|	[Next Pass outcome](#pass-outcome-number-34)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-33)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-33)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-33)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 34

[Jump to summary definition](#summary-Pass-34)	|	[Previous Pass outcome](#pass-outcome-number-33)	|	[Next Pass outcome](#pass-outcome-number-35)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-34)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-34)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-34)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 35

[Jump to summary definition](#summary-Pass-35)	|	[Previous Pass outcome](#pass-outcome-number-34)	|	[Next Pass outcome](#pass-outcome-number-36)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-35)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-35)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-35)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 36

[Jump to summary definition](#summary-Pass-36)	|	[Previous Pass outcome](#pass-outcome-number-35)	|	[Next Pass outcome](#pass-outcome-number-37)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-36)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-36)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-36)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 37

[Jump to summary definition](#summary-Pass-37)	|	[Previous Pass outcome](#pass-outcome-number-36)	|	[Next Pass outcome](#pass-outcome-number-38)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-too-close-terms|
|----|----|
|Title|Standalone&#32;module&#32;../../src/too-close-terms.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-38)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-38)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-38)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 39

[Jump to summary definition](#summary-Pass-39)	|	[Previous Pass outcome](#pass-outcome-number-38)	|	[Next Pass outcome](#pass-outcome-number-40)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-39)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-39)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-39)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 40

[Jump to summary definition](#summary-Pass-40)	|	[Previous Pass outcome](#pass-outcome-number-39)	|	[Next Pass outcome](#pass-outcome-number-41)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-40)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-40)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-40)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 41

[Jump to summary definition](#summary-Pass-41)	|	[Previous Pass outcome](#pass-outcome-number-40)	|	[Next Pass outcome](#pass-outcome-number-42)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-41)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-41)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-41)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 42

[Jump to summary definition](#summary-Pass-42)	|	[Previous Pass outcome](#pass-outcome-number-41)	|	[Next Pass outcome](#pass-outcome-number-43)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-42)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-42)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-42)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 43

[Jump to summary definition](#summary-Pass-43)	|	[Previous Pass outcome](#pass-outcome-number-42)	|	[Next Pass outcome](#pass-outcome-number-44)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-43)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-43)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-43)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 44

[Jump to summary definition](#summary-Pass-44)	|	[Previous Pass outcome](#pass-outcome-number-43)	|	[Next Pass outcome](#pass-outcome-number-45)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-44)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-44)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-44)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 45

[Jump to summary definition](#summary-Pass-45)	|	[Previous Pass outcome](#pass-outcome-number-44)	|	[Next Pass outcome](#pass-outcome-number-46)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-45)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-45)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-45)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 46

[Jump to summary definition](#summary-Pass-46)	|	[Previous Pass outcome](#pass-outcome-number-45)	|	[Next Pass outcome](#pass-outcome-number-47)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-46)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-46)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-46)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 47

[Jump to summary definition](#summary-Pass-47)	|	[Previous Pass outcome](#pass-outcome-number-46)	|	[Next Pass outcome](#pass-outcome-number-48)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-47)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-47)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-47)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 48

[Jump to summary definition](#summary-Pass-48)	|	[Previous Pass outcome](#pass-outcome-number-47)	|	[Next Pass outcome](#pass-outcome-number-49)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-49)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-49)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-49)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 50

[Jump to summary definition](#summary-Pass-50)	|	[Previous Pass outcome](#pass-outcome-number-49)	|	[Next Pass outcome](#pass-outcome-number-51)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-range-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/range-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-50)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-50)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-50)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 51

[Jump to summary definition](#summary-Pass-51)	|	[Previous Pass outcome](#pass-outcome-number-50)	|	[Next Pass outcome](#pass-outcome-number-52)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-51)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-51)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-51)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 52

[Jump to summary definition](#summary-Pass-52)	|	[Previous Pass outcome](#pass-outcome-number-51)	|	[Next Pass outcome](#pass-outcome-number-53)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-52)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-52)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-52)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 53

[Jump to summary definition](#summary-Pass-53)	|	[Previous Pass outcome](#pass-outcome-number-52)	|	[Next Pass outcome](#pass-outcome-number-54)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-53)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-53)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-53)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 54

[Jump to summary definition](#summary-Pass-54)	|	[Previous Pass outcome](#pass-outcome-number-53)	|	[Next Pass outcome](#pass-outcome-number-55)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-54)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-54)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-54)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 55

[Jump to summary definition](#summary-Pass-55)	|	[Previous Pass outcome](#pass-outcome-number-54)	|	[Next Pass outcome](#pass-outcome-number-56)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-55)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-55)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-55)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 56

[Jump to summary definition](#summary-Pass-56)	|	[Previous Pass outcome](#pass-outcome-number-55)	|	[Next Pass outcome](#pass-outcome-number-57)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-56)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-56)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-56)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 57

[Jump to summary definition](#summary-Pass-57)	|	[Previous Pass outcome](#pass-outcome-number-56)	|	[Next Pass outcome](#pass-outcome-number-58)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-57)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-57)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-57)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 58

[Jump to summary definition](#summary-Pass-58)	|	[Previous Pass outcome](#pass-outcome-number-57)	|	[Next Pass outcome](#pass-outcome-number-59)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-58)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-58)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-58)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 59

[Jump to summary definition](#summary-Pass-59)	|	[Previous Pass outcome](#pass-outcome-number-58)	|	[Next Pass outcome](#pass-outcome-number-60)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-59)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-59)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-59)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 60

[Jump to summary definition](#summary-Pass-60)	|	[Previous Pass outcome](#pass-outcome-number-59)	|	[Next Pass outcome](#pass-outcome-number-61)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-61)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-61)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-61)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 62

[Jump to summary definition](#summary-Pass-62)	|	[Previous Pass outcome](#pass-outcome-number-61)	|	[Next Pass outcome](#pass-outcome-number-63)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-ql|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-ql.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-62)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-62)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-62)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 63

[Jump to summary definition](#summary-Pass-63)	|	[Previous Pass outcome](#pass-outcome-number-62)	|	[Next Pass outcome](#pass-outcome-number-64)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-63)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-63)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-63)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 64

[Jump to summary definition](#summary-Pass-64)	|	[Previous Pass outcome](#pass-outcome-number-63)	|	[Next Pass outcome](#pass-outcome-number-65)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-64)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-64)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-64)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 65

[Jump to summary definition](#summary-Pass-65)	|	[Previous Pass outcome](#pass-outcome-number-64)	|	[Next Pass outcome](#pass-outcome-number-66)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-65)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-65)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-65)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 66

[Jump to summary definition](#summary-Pass-66)	|	[Previous Pass outcome](#pass-outcome-number-65)	|	[Next Pass outcome](#pass-outcome-number-67)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-66)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-66)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-66)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 67

[Jump to summary definition](#summary-Pass-67)	|	[Previous Pass outcome](#pass-outcome-number-66)	|	[Next Pass outcome](#pass-outcome-number-68)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-67)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-67)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-67)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 68

[Jump to summary definition](#summary-Pass-68)	|	[Previous Pass outcome](#pass-outcome-number-67)	|	[Next Pass outcome](#pass-outcome-number-69)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-68)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-68)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-68)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 69

[Jump to summary definition](#summary-Pass-69)	|	[Previous Pass outcome](#pass-outcome-number-68)	|	[Next Pass outcome](#pass-outcome-number-70)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-69)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-69)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-69)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 70

[Jump to summary definition](#summary-Pass-70)	|	[Previous Pass outcome](#pass-outcome-number-69)	|	[Next Pass outcome](#pass-outcome-number-71)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-70)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-70)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-70)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 71

[Jump to summary definition](#summary-Pass-71)	|	[Previous Pass outcome](#pass-outcome-number-70)	|	[Next Pass outcome](#pass-outcome-number-72)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-71)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-71)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-71)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 72

[Jump to summary definition](#summary-Pass-72)	|	[Previous Pass outcome](#pass-outcome-number-71)	|	[Next Pass outcome](#pass-outcome-number-73)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-not-el|
|----|----|
|Title|Standalone&#32;module&#32;../../src/not-el.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-75)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-75)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-75)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 76

[Jump to summary definition](#summary-Pass-76)	|	[Previous Pass outcome](#pass-outcome-number-75)	|	[Next Pass outcome](#pass-outcome-number-77)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-76)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-76)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-76)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 77

[Jump to summary definition](#summary-Pass-77)	|	[Previous Pass outcome](#pass-outcome-number-76)	|	[Next Pass outcome](#pass-outcome-number-78)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-77)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-77)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-77)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 78

[Jump to summary definition](#summary-Pass-78)	|	[Previous Pass outcome](#pass-outcome-number-77)	|	[Next Pass outcome](#pass-outcome-number-79)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-78)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-78)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-78)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 79

[Jump to summary definition](#summary-Pass-79)	|	[Previous Pass outcome](#pass-outcome-number-78)	|	[Next Pass outcome](#pass-outcome-number-80)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-79)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-79)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-79)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 80

[Jump to summary definition](#summary-Pass-80)	|	[Previous Pass outcome](#pass-outcome-number-79)	|	[Next Pass outcome](#pass-outcome-number-81)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-80)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-80)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-80)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 81

[Jump to summary definition](#summary-Pass-81)	|	[Previous Pass outcome](#pass-outcome-number-80)	|	[Next Pass outcome](#pass-outcome-number-82)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-81)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-81)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-81)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 82

[Jump to summary definition](#summary-Pass-82)	|	[Previous Pass outcome](#pass-outcome-number-81)	|	[Next Pass outcome](#pass-outcome-number-83)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-82)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-82)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-82)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 83

[Jump to summary definition](#summary-Pass-83)	|	[Previous Pass outcome](#pass-outcome-number-82)	|	[Next Pass outcome](#pass-outcome-number-84)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-83)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-83)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-83)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 84

[Jump to summary definition](#summary-Pass-84)	|	[Previous Pass outcome](#pass-outcome-number-83)	|	[Next Pass outcome](#pass-outcome-number-85)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-84)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-84)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-84)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 85

[Jump to summary definition](#summary-Pass-85)	|	[Previous Pass outcome](#pass-outcome-number-84)	|	[Next Pass outcome](#pass-outcome-number-86)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-85)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-85)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-85)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 86

[Jump to summary definition](#summary-Pass-86)	|	[Previous Pass outcome](#pass-outcome-number-85)	|	[Next Pass outcome](#pass-outcome-number-87)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-inconsistent|
|----|----|
|Title|Standalone&#32;module&#32;../../src/inconsistent.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-86)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-86)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-86)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 87

[Jump to summary definition](#summary-Pass-87)	|	[Previous Pass outcome](#pass-outcome-number-86)	|	[Next Pass outcome](#pass-outcome-number-88)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-87)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-87)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-87)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 88

[Jump to summary definition](#summary-Pass-88)	|	[Previous Pass outcome](#pass-outcome-number-87)	|	[Next Pass outcome](#pass-outcome-number-89)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-88)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-88)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-88)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 89

[Jump to summary definition](#summary-Pass-89)	|	[Previous Pass outcome](#pass-outcome-number-88)	|	[Next Pass outcome](#pass-outcome-number-90)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-89)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-89)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-89)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 90

[Jump to summary definition](#summary-Pass-90)	|	[Previous Pass outcome](#pass-outcome-number-89)	|	[Next Pass outcome](#pass-outcome-number-91)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

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
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-91)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-91)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-91)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 92

[Jump to summary definition](#summary-Pass-92)	|	[Previous Pass outcome](#pass-outcome-number-91)	|	[Next Pass outcome](#pass-outcome-number-93)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-92)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-92)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-92)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 93

[Jump to summary definition](#summary-Pass-93)	|	[Previous Pass outcome](#pass-outcome-number-92)	|	[Next Pass outcome](#pass-outcome-number-94)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-93)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-93)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-93)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 94

[Jump to summary definition](#summary-Pass-94)	|	[Previous Pass outcome](#pass-outcome-number-93)	|	[Next Pass outcome](#pass-outcome-number-95)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-94)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-94)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-94)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 95

[Jump to summary definition](#summary-Pass-95)	|	[Previous Pass outcome](#pass-outcome-number-94)	|	[Next Pass outcome](#pass-outcome-number-96)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-95)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-95)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-95)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 96

[Jump to summary definition](#summary-Pass-96)	|	[Previous Pass outcome](#pass-outcome-number-95)	|	[Next Pass outcome](#pass-outcome-number-97)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-96)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-96)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-96)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 97

[Jump to summary definition](#summary-Pass-97)	|	[Previous Pass outcome](#pass-outcome-number-96)	|	[Next Pass outcome](#pass-outcome-number-98)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-97)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-97)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-97)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 98

[Jump to summary definition](#summary-Pass-98)	|	[Previous Pass outcome](#pass-outcome-number-97)	|	[Next Pass outcome](#pass-outcome-number-99)

:white_check_mark:Pass outcome
#### Subject detail
|Name|module-domain-outer|
|----|----|
|Title|Standalone&#32;module&#32;../../src/domain-outer.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-98)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-98)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-98)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 99

[Jump to summary definition](#summary-Pass-99)	|	[Previous Pass outcome](#pass-outcome-number-98)	|	[Next Pass outcome](#pass-outcome-number-100)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-99)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-99)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-99)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 100

[Jump to summary definition](#summary-Pass-100)	|	[Previous Pass outcome](#pass-outcome-number-99)	|	[Next Pass outcome](#pass-outcome-number-101)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-100)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-100)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-100)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 101

[Jump to summary definition](#summary-Pass-101)	|	[Previous Pass outcome](#pass-outcome-number-100)	|	[Next Pass outcome](#pass-outcome-number-102)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-101)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-101)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-101)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 102

[Jump to summary definition](#summary-Pass-102)	|	[Previous Pass outcome](#pass-outcome-number-101)	|	[Next Pass outcome](#pass-outcome-number-103)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-102)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-102)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-102)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 103

[Jump to summary definition](#summary-Pass-103)	|	[Previous Pass outcome](#pass-outcome-number-102)	|	[Next Pass outcome](#pass-outcome-number-104)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-103)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-103)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-103)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 104

[Jump to summary definition](#summary-Pass-104)	|	[Previous Pass outcome](#pass-outcome-number-103)	|	[Next Pass outcome](#pass-outcome-number-105)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-104)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-104)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-104)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 105

[Jump to summary definition](#summary-Pass-105)	|	[Previous Pass outcome](#pass-outcome-number-104)	|	[Next Pass outcome](#pass-outcome-number-106)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-105)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-105)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-105)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 106

[Jump to summary definition](#summary-Pass-106)	|	[Previous Pass outcome](#pass-outcome-number-105)	|	[Next Pass outcome](#pass-outcome-number-107)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-106)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-106)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-106)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 107

[Jump to summary definition](#summary-Pass-107)	|	[Previous Pass outcome](#pass-outcome-number-106)	|	[Next Pass outcome](#pass-outcome-number-108)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-107)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-107)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-107)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 108

[Jump to summary definition](#summary-Pass-108)	|	[Previous Pass outcome](#pass-outcome-number-107)	|	[Next Pass outcome](#pass-outcome-number-109)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-108)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-108)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-108)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 109

[Jump to summary definition](#summary-Pass-109)	|	[Previous Pass outcome](#pass-outcome-number-108)	|	[Next Pass outcome](#pass-outcome-number-110)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-109)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-109)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-109)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 110

[Jump to summary definition](#summary-Pass-110)	|	[Previous Pass outcome](#pass-outcome-number-109)	|	[Next Pass outcome](#pass-outcome-number-111)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-110)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-110)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-110)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 111

[Jump to summary definition](#summary-Pass-111)	|	[Previous Pass outcome](#pass-outcome-number-110)	|	[Next Pass outcome](#pass-outcome-number-112)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-rangeout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/rangeout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-111)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-111)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-111)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 112

[Jump to summary definition](#summary-Pass-112)	|	[Previous Pass outcome](#pass-outcome-number-111)	|	[Next Pass outcome](#pass-outcome-number-113)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-112)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-112)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-112)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 113

[Jump to summary definition](#summary-Pass-113)	|	[Previous Pass outcome](#pass-outcome-number-112)	|	[Next Pass outcome](#pass-outcome-number-114)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-113)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-113)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-113)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 114

[Jump to summary definition](#summary-Pass-114)	|	[Previous Pass outcome](#pass-outcome-number-113)	|	[Next Pass outcome](#pass-outcome-number-115)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-114)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-114)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-114)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 115

[Jump to summary definition](#summary-Pass-115)	|	[Previous Pass outcome](#pass-outcome-number-114)	|	[Next Pass outcome](#pass-outcome-number-116)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

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
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-116)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-116)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-116)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 117

[Jump to summary definition](#summary-Pass-117)	|	[Previous Pass outcome](#pass-outcome-number-116)	|	[Next Pass outcome](#pass-outcome-number-118)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-117)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-117)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-117)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 118

[Jump to summary definition](#summary-Pass-118)	|	[Previous Pass outcome](#pass-outcome-number-117)	|	[Next Pass outcome](#pass-outcome-number-119)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-118)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-118)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-118)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 119

[Jump to summary definition](#summary-Pass-119)	|	[Previous Pass outcome](#pass-outcome-number-118)	|	[Next Pass outcome](#pass-outcome-number-120)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-119)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-119)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-119)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 120

[Jump to summary definition](#summary-Pass-120)	|	[Previous Pass outcome](#pass-outcome-number-119)	|	[Next Pass outcome](#pass-outcome-number-121)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-120)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-120)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-120)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 121

[Jump to summary definition](#summary-Pass-121)	|	[Previous Pass outcome](#pass-outcome-number-120)	|	[Next Pass outcome](#pass-outcome-number-122)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-121)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-121)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-121)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 122

[Jump to summary definition](#summary-Pass-122)	|	[Previous Pass outcome](#pass-outcome-number-121)	|	[Next Pass outcome](#pass-outcome-number-123)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-122)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-122)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-122)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 123

[Jump to summary definition](#summary-Pass-123)	|	[Previous Pass outcome](#pass-outcome-number-122)	|	[Next Pass outcome](#pass-outcome-number-124)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-label|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/label/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-123)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-123)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-123)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 124

[Jump to summary definition](#summary-Pass-124)	|	[Previous Pass outcome](#pass-outcome-number-123)	|	[Next Pass outcome](#pass-outcome-number-125)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-124)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-124)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-124)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 125

[Jump to summary definition](#summary-Pass-125)	|	[Previous Pass outcome](#pass-outcome-number-124)	|	[Next Pass outcome](#pass-outcome-number-126)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-125)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-125)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-125)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 126

[Jump to summary definition](#summary-Pass-126)	|	[Previous Pass outcome](#pass-outcome-number-125)	|	[Next Pass outcome](#pass-outcome-number-127)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-126)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-126)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-126)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 127

[Jump to summary definition](#summary-Pass-127)	|	[Previous Pass outcome](#pass-outcome-number-126)	|	[Next Pass outcome](#pass-outcome-number-128)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-127)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-127)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-127)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 128

[Jump to summary definition](#summary-Pass-128)	|	[Previous Pass outcome](#pass-outcome-number-127)	|	[Next Pass outcome](#pass-outcome-number-129)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-128)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-128)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-128)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 129

[Jump to summary definition](#summary-Pass-129)	|	[Previous Pass outcome](#pass-outcome-number-128)	|	[Next Pass outcome](#pass-outcome-number-130)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-129)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-129)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-129)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 130

[Jump to summary definition](#summary-Pass-130)	|	[Previous Pass outcome](#pass-outcome-number-129)	|	[Next Pass outcome](#pass-outcome-number-131)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-130)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-130)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-130)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 131

[Jump to summary definition](#summary-Pass-131)	|	[Previous Pass outcome](#pass-outcome-number-130)	|	[Next Pass outcome](#pass-outcome-number-132)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-131)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-131)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-131)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 132

[Jump to summary definition](#summary-Pass-132)	|	[Previous Pass outcome](#pass-outcome-number-131)	|	[Next Pass outcome](#pass-outcome-number-133)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-132)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-132)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-132)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 133

[Jump to summary definition](#summary-Pass-133)	|	[Previous Pass outcome](#pass-outcome-number-132)	|	[Next Pass outcome](#pass-outcome-number-134)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-133)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-133)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-133)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 134

[Jump to summary definition](#summary-Pass-134)	|	[Previous Pass outcome](#pass-outcome-number-133)	|	[Next Pass outcome](#pass-outcome-number-135)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-134)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-134)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-134)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 135

[Jump to summary definition](#summary-Pass-135)	|	[Previous Pass outcome](#pass-outcome-number-134)	|	[Next Pass outcome](#pass-outcome-number-136)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-135)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-135)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-135)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 136

[Jump to summary definition](#summary-Pass-136)	|	[Previous Pass outcome](#pass-outcome-number-135)	|	[Next Pass outcome](#pass-outcome-number-137)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-inconsistence|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/inconsistence/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-136)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-136)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-136)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 137

[Jump to summary definition](#summary-Pass-137)	|	[Previous Pass outcome](#pass-outcome-number-136)	|	[Next Pass outcome](#pass-outcome-number-138)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-137)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-137)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-137)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 138

[Jump to summary definition](#summary-Pass-138)	|	[Previous Pass outcome](#pass-outcome-number-137)	|	[Next Pass outcome](#pass-outcome-number-139)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-138)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-138)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-138)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 139

[Jump to summary definition](#summary-Pass-139)	|	[Previous Pass outcome](#pass-outcome-number-138)	|	[Next Pass outcome](#pass-outcome-number-140)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-139)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-139)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-139)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 140

[Jump to summary definition](#summary-Pass-140)	|	[Previous Pass outcome](#pass-outcome-number-139)	|	[Next Pass outcome](#pass-outcome-number-141)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-140)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-140)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-140)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 141

[Jump to summary definition](#summary-Pass-141)	|	[Previous Pass outcome](#pass-outcome-number-140)	|	[Next Pass outcome](#pass-outcome-number-142)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-141)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-141)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-141)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 142

[Jump to summary definition](#summary-Pass-142)	|	[Previous Pass outcome](#pass-outcome-number-141)	|	[Next Pass outcome](#pass-outcome-number-143)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-142)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-142)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-142)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 143

[Jump to summary definition](#summary-Pass-143)	|	[Previous Pass outcome](#pass-outcome-number-142)	|	[Next Pass outcome](#pass-outcome-number-144)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-143)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-143)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-143)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 144

[Jump to summary definition](#summary-Pass-144)	|	[Previous Pass outcome](#pass-outcome-number-143)	|	[Next Pass outcome](#pass-outcome-number-145)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-144)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-144)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-144)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 145

[Jump to summary definition](#summary-Pass-145)	|	[Previous Pass outcome](#pass-outcome-number-144)	|	[Next Pass outcome](#pass-outcome-number-146)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-145)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-145)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-145)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 146

[Jump to summary definition](#summary-Pass-146)	|	[Previous Pass outcome](#pass-outcome-number-145)	|	[Next Pass outcome](#pass-outcome-number-147)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-dovrov|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/dovrov/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-148)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-148)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-148)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 149

[Jump to summary definition](#summary-Pass-149)	|	[Previous Pass outcome](#pass-outcome-number-148)	|	[Next Pass outcome](#pass-outcome-number-150)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-149)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-149)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-149)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 150

[Jump to summary definition](#summary-Pass-150)	|	[Previous Pass outcome](#pass-outcome-number-149)	|	[Next Pass outcome](#pass-outcome-number-151)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-150)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-150)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-150)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 151

[Jump to summary definition](#summary-Pass-151)	|	[Previous Pass outcome](#pass-outcome-number-150)	|	[Next Pass outcome](#pass-outcome-number-152)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-151)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-151)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-151)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 152

[Jump to summary definition](#summary-Pass-152)	|	[Previous Pass outcome](#pass-outcome-number-151)	|	[Next Pass outcome](#pass-outcome-number-153)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-152)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-152)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-152)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 153

[Jump to summary definition](#summary-Pass-153)	|	[Previous Pass outcome](#pass-outcome-number-152)	|	[Next Pass outcome](#pass-outcome-number-154)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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

[Jump to summary definition](#summary-Pass-154)	|	[Previous Pass outcome](#pass-outcome-number-153)	|	[Next Pass outcome](#pass-outcome-number-155)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-154)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-154)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-154)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 155

[Jump to summary definition](#summary-Pass-155)	|	[Previous Pass outcome](#pass-outcome-number-154)	|	[Next Pass outcome](#pass-outcome-number-156)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-155)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-155)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-155)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 156

[Jump to summary definition](#summary-Pass-156)	|	[Previous Pass outcome](#pass-outcome-number-155)	|	[Next Pass outcome](#pass-outcome-number-157)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-156)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-156)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-156)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 157

[Jump to summary definition](#summary-Pass-157)	|	[Previous Pass outcome](#pass-outcome-number-156)	|	[Next Pass outcome](#pass-outcome-number-158)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-157)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-157)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-157)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 158

[Jump to summary definition](#summary-Pass-158)	|	[Previous Pass outcome](#pass-outcome-number-157)	|	[Next Pass outcome](#pass-outcome-number-159)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[term-referencing](https://ns.inria.fr/olivaw#term-referencing)|
|----|----|
|Title|Term&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;referenced&#32;to&#32;a&#32;module&#32;through&#32;a&#32;rdfs:isDefinedBy&#32;property.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-158)|Identifier|`no-reference-module`|
|[Section top](#pass-outcome-number-158)|Title|Any&#32;term&#32;is&#32;referenced|
|[Section top](#pass-outcome-number-158)|Description|Each&#32;term&#32;of&#32;the&#32;test&#32;subject&#32;is&#32;linked&#32;to&#32;a&#32;module&#32;by&#32;a&#32;rdfs:isDefinedBy&#32;property|

***
### Pass Outcome number 159

[Jump to summary definition](#summary-Pass-159)	|	[Previous Pass outcome](#pass-outcome-number-158)	|	[Next Pass outcome](#pass-outcome-number-160)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[terms-differenciation](https://ns.inria.fr/olivaw#terms-differenciation)|
|----|----|
|Title|Terms&#32;differenciation&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;are&#32;different&#32;enough&#32;from&#32;each&#32;other&#32;according&#32;to&#32;the&#32;Levenshtein&#32;distance&#32;metric.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-159)|Identifier|`too-close-terms`|
|[Section top](#pass-outcome-number-159)|Title|Terms&#32;differenciated&#32;enough|
|[Section top](#pass-outcome-number-159)|Description|All&#32;the&#32;terms&#32;have&#32;have&#32;a&#32;satisfying&#32;Levenshtein&#32;distance&#32;from&#32;each&#32;other&#32;term.|

***
### Pass Outcome number 160

[Jump to summary definition](#summary-Pass-160)	|	[Previous Pass outcome](#pass-outcome-number-159)	|	[Next Pass outcome](#pass-outcome-number-161)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-domainout|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/domainout/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-160)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-160)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-160)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 161

[Jump to summary definition](#summary-Pass-161)	|	[Previous Pass outcome](#pass-outcome-number-160)	|	[Next Pass outcome](#pass-outcome-number-162)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-161)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-161)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-161)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 162

[Jump to summary definition](#summary-Pass-162)	|	[Previous Pass outcome](#pass-outcome-number-161)	|	[Next Pass outcome](#pass-outcome-number-163)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-162)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-162)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-162)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 163

[Jump to summary definition](#summary-Pass-163)	|	[Previous Pass outcome](#pass-outcome-number-162)	|	[Next Pass outcome](#pass-outcome-number-164)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-163)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-163)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-163)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 164

[Jump to summary definition](#summary-Pass-164)	|	[Previous Pass outcome](#pass-outcome-number-163)	|	[Next Pass outcome](#pass-outcome-number-165)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-164)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-164)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-164)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 165

[Jump to summary definition](#summary-Pass-165)	|	[Previous Pass outcome](#pass-outcome-number-164)	|	[Next Pass outcome](#pass-outcome-number-166)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-165)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-165)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-165)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 166

[Jump to summary definition](#summary-Pass-166)	|	[Previous Pass outcome](#pass-outcome-number-165)	|	[Next Pass outcome](#pass-outcome-number-167)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-166)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-166)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-166)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 167

[Jump to summary definition](#summary-Pass-167)	|	[Previous Pass outcome](#pass-outcome-number-166)	|	[Next Pass outcome](#pass-outcome-number-168)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-167)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-167)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-167)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 168

[Jump to summary definition](#summary-Pass-168)	|	[Previous Pass outcome](#pass-outcome-number-167)	|	[Next Pass outcome](#pass-outcome-number-169)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-168)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-168)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-168)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 169

[Jump to summary definition](#summary-Pass-169)	|	[Previous Pass outcome](#pass-outcome-number-168)	|	[Next Pass outcome](#pass-outcome-number-170)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-169)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-169)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-169)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 170

[Jump to summary definition](#summary-Pass-170)	|	[Previous Pass outcome](#pass-outcome-number-169)	|	[Next Pass outcome](#pass-outcome-number-171)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-170)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-170)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-170)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 171

[Jump to summary definition](#summary-Pass-171)	|	[Previous Pass outcome](#pass-outcome-number-170)	|	[Next Pass outcome](#pass-outcome-number-172)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-differenciation|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/differenciation/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-172)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-172)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-172)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 173

[Jump to summary definition](#summary-Pass-173)	|	[Previous Pass outcome](#pass-outcome-number-172)	|	[Next Pass outcome](#pass-outcome-number-174)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-173)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-173)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-173)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 174

[Jump to summary definition](#summary-Pass-174)	|	[Previous Pass outcome](#pass-outcome-number-173)	|	[Next Pass outcome](#pass-outcome-number-175)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-174)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-174)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-174)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 175

[Jump to summary definition](#summary-Pass-175)	|	[Previous Pass outcome](#pass-outcome-number-174)	|	[Next Pass outcome](#pass-outcome-number-176)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-175)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-175)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-175)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 176

[Jump to summary definition](#summary-Pass-176)	|	[Previous Pass outcome](#pass-outcome-number-175)	|	[Next Pass outcome](#pass-outcome-number-177)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-176)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-176)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-176)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;EL&#32;sublanguage|

***
### Pass Outcome number 177

[Jump to summary definition](#summary-Pass-177)	|	[Previous Pass outcome](#pass-outcome-number-176)	|	[Next Pass outcome](#pass-outcome-number-178)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-177)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-177)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-177)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 178

[Jump to summary definition](#summary-Pass-178)	|	[Previous Pass outcome](#pass-outcome-number-177)	|	[Next Pass outcome](#pass-outcome-number-179)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-178)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-178)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-178)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 179

[Jump to summary definition](#summary-Pass-179)	|	[Previous Pass outcome](#pass-outcome-number-178)	|	[Next Pass outcome](#pass-outcome-number-180)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-179)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-179)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-179)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 180

[Jump to summary definition](#summary-Pass-180)	|	[Previous Pass outcome](#pass-outcome-number-179)	|	[Next Pass outcome](#pass-outcome-number-181)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-180)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-180)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-180)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 181

[Jump to summary definition](#summary-Pass-181)	|	[Previous Pass outcome](#pass-outcome-number-180)	|	[Next Pass outcome](#pass-outcome-number-182)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-181)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-181)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-181)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 182

[Jump to summary definition](#summary-Pass-182)	|	[Previous Pass outcome](#pass-outcome-number-181)	|	[Next Pass outcome](#pass-outcome-number-183)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-182)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-182)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-182)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 183

[Jump to summary definition](#summary-Pass-183)	|	[Previous Pass outcome](#pass-outcome-number-182)	|	[Next Pass outcome](#pass-outcome-number-184)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatRL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatRL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-186)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-186)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-186)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 187

[Jump to summary definition](#summary-Pass-187)	|	[Previous Pass outcome](#pass-outcome-number-186)	|	[Next Pass outcome](#pass-outcome-number-188)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-187)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-187)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-187)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 188

[Jump to summary definition](#summary-Pass-188)	|	[Previous Pass outcome](#pass-outcome-number-187)	|	[Next Pass outcome](#pass-outcome-number-189)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-188)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-188)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-188)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 189

[Jump to summary definition](#summary-Pass-189)	|	[Previous Pass outcome](#pass-outcome-number-188)	|	[Next Pass outcome](#pass-outcome-number-190)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-189)|Identifier|`owl-el-profile-error`|
|[Section top](#pass-outcome-number-189)|Title|OWL&#32;EL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-189)|Description|Statement&#32;not&#32;supported|

***
### Pass Outcome number 190

[Jump to summary definition](#summary-Pass-190)	|	[Previous Pass outcome](#pass-outcome-number-189)	|	[Next Pass outcome](#pass-outcome-number-191)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-190)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-190)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-190)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 191

[Jump to summary definition](#summary-Pass-191)	|	[Previous Pass outcome](#pass-outcome-number-190)	|	[Next Pass outcome](#pass-outcome-number-192)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-191)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-191)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-191)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 192

[Jump to summary definition](#summary-Pass-192)	|	[Previous Pass outcome](#pass-outcome-number-191)	|	[Next Pass outcome](#pass-outcome-number-193)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-192)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-192)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-192)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 193

[Jump to summary definition](#summary-Pass-193)	|	[Previous Pass outcome](#pass-outcome-number-192)	|	[Next Pass outcome](#pass-outcome-number-194)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-193)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-193)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-193)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 194

[Jump to summary definition](#summary-Pass-194)	|	[Previous Pass outcome](#pass-outcome-number-193)	|	[Next Pass outcome](#pass-outcome-number-195)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-194)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-194)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-194)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 195

[Jump to summary definition](#summary-Pass-195)	|	[Previous Pass outcome](#pass-outcome-number-194)	|	[Next Pass outcome](#pass-outcome-number-196)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatQL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatQL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://ns.inria.fr/olivaw#domain-and-range-referencing)|
|----|----|
|Title|Domain&#32;and&#32;range&#32;referencing&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;ranges&#32;and&#32;domains&#32;from&#32;the&#32;test&#32;subject&#32;point&#32;to&#32;terms&#32;that&#32;are&#32;defined&#32;in&#32;the&#32;vocabulary.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-198)|Identifier|`domain-out-of-vocabulary`|
|[Section top](#pass-outcome-number-198)|Title|Domains&#32;properly&#32;defined|
|[Section top](#pass-outcome-number-198)|Description|Each&#32;rdfs:domain&#32;is&#32;defined&#32;within&#32;the&#32;fragment|

***
### Pass Outcome number 199

[Jump to summary definition](#summary-Pass-199)	|	[Previous Pass outcome](#pass-outcome-number-198)	|	[Next Pass outcome](#pass-outcome-number-200)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[labeled-terms](https://ns.inria.fr/olivaw#labeled-terms)|
|----|----|
|Title|Term&#32;labeling&#32;test|
|Description|A&#32;test&#32;case&#32;from&#32;the&#32;Best&#32;Practices&#32;tests&#32;checking&#32;if&#32;all&#32;the&#32;terms&#32;of&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;property&#32;pointing&#32;to&#32;a&#32;literal&#32;in&#32;English|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-199)|Identifier|`not-labeled-term`|
|[Section top](#pass-outcome-number-199)|Title|All&#32;terms&#32;labeled|
|[Section top](#pass-outcome-number-199)|Description|All&#32;the&#32;terms&#32;defined&#32;in&#32;the&#32;subject&#32;have&#32;a&#32;rdfs:label&#32;in&#32;English|

***
### Pass Outcome number 200

[Jump to summary definition](#summary-Pass-200)	|	[Previous Pass outcome](#pass-outcome-number-199)	|	[Next Pass outcome](#pass-outcome-number-201)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://ns.inria.fr/olivaw#owl-rl-constraint)|
|----|----|
|Title|OWL&#32;RL&#32;Constraint&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;wether&#32;the&#32;test&#32;subject&#32;is&#32;syntaxically&#32;correct&#32;or&#32;not.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-200)|Identifier|`owl-rl-constraint-violation`|
|[Section top](#pass-outcome-number-200)|Title|OWL&#32;RL&#32;consistent|
|[Section top](#pass-outcome-number-200)|Description|The&#32;provided&#32;graph&#32;is&#32;consistent&#32;for&#32;any&#32;OWL&#32;RL&#32;constraint|

***
### Pass Outcome number 201

[Jump to summary definition](#summary-Pass-201)	|	[Previous Pass outcome](#pass-outcome-number-200)	|	[Next Pass outcome](#pass-outcome-number-202)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-201)|Identifier|`owl-ql-profile-error`|
|[Section top](#pass-outcome-number-201)|Title|OWL&#32;QL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-201)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;QL&#32;sublanguage|

***
### Pass Outcome number 202

[Jump to summary definition](#summary-Pass-202)	|	[Previous Pass outcome](#pass-outcome-number-201)	|	[Next Pass outcome](#pass-outcome-number-203)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-202)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-202)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-202)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 203

[Jump to summary definition](#summary-Pass-203)	|	[Previous Pass outcome](#pass-outcome-number-202)	|	[Next Pass outcome](#pass-outcome-number-204)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-203)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-203)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-203)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 204

[Jump to summary definition](#summary-Pass-204)	|	[Previous Pass outcome](#pass-outcome-number-203)	|	[Next Pass outcome](#pass-outcome-number-205)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-204)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-204)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-204)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 205

[Jump to summary definition](#summary-Pass-205)	|	[Previous Pass outcome](#pass-outcome-number-204)	|	[Next Pass outcome](#pass-outcome-number-206)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-205)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-205)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-205)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 206

[Jump to summary definition](#summary-Pass-206)	|	[Previous Pass outcome](#pass-outcome-number-205)	|	[Next Pass outcome](#pass-outcome-number-207)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-206)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-206)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-206)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 207

[Jump to summary definition](#summary-Pass-207)	|	[Previous Pass outcome](#pass-outcome-number-206)	|	[Next Pass outcome](#pass-outcome-number-208)

:white_check_mark:Pass outcome
#### Subject detail
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|modelet-zedomain-compatEL|
|----|----|
|Title|Standalone&#32;modelet&#32;../../domains/zedomain/compatEL/onto.ttl&#32;from&#32;branch&#32;main|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl|

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
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[profile-compatibility](https://ns.inria.fr/olivaw#profile-compatibility)|
|----|----|
|Title|Profile&#32;compatibility&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;check&#32;whether&#32;the&#32;test&#32;subject&#32;is&#32;compatible&#32;with&#32;a&#32;profile&#32;or&#32;not,&#32;and&#32;if&#32;it&#32;is&#32;not,&#32;why.|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-210)|Identifier|`owl-rl-profile-error`|
|[Section top](#pass-outcome-number-210)|Title|OWL&#32;RL&#32;Profile&#32;compatible|
|[Section top](#pass-outcome-number-210)|Description|The&#32;subject&#32;is&#32;included&#32;in&#32;the&#32;OWL&#32;RL&#32;sublanguage|

***
### Pass Outcome number 211

[Jump to summary definition](#summary-Pass-211)	|	[Previous Pass outcome](#pass-outcome-number-210)	|	[Next Pass outcome](#pass-outcome-number-212)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-211)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-211)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-211)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 212

[Jump to summary definition](#summary-Pass-212)	|	[Previous Pass outcome](#pass-outcome-number-211)	|	[Next Pass outcome](#pass-outcome-number-213)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-212)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-212)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-212)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 213

[Jump to summary definition](#summary-Pass-213)	|	[Previous Pass outcome](#pass-outcome-number-212)	|	[Next Pass outcome](#pass-outcome-number-214)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-213)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-213)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-213)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 214

[Jump to summary definition](#summary-Pass-214)	|	[Previous Pass outcome](#pass-outcome-number-213)	|	[Next Pass outcome](#pass-outcome-number-215)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-214)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-214)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-214)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 215

[Jump to summary definition](#summary-Pass-215)	|	[Previous Pass outcome](#pass-outcome-number-214)	|	[Next Pass outcome](#pass-outcome-number-216)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-modules|
|----|----|
|Title|All&#32;the&#32;modules&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[subclass-cycle](https://raw.githubusercontent.com/acimov-tools/model-test/main/.acimov/custom-tests/model/subclass-cycle.shacl#criterion)|
|----|----|
|Title|Subclass&#32;cycle&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;detect&#32;rdfs:subclass&#32;cycles|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-215)|Identifier|`subclass-cycle`|
|[Section top](#pass-outcome-number-215)|Title|Test&#32; &#32;passed|
|[Section top](#pass-outcome-number-215)|Description|The&#32;custom&#32;test&#32; &#32;passed|

***
### Pass Outcome number 216

[Jump to summary definition](#summary-Pass-216)	|	[Previous Pass outcome](#pass-outcome-number-215)	|	[Next Pass outcome](#pass-outcome-number-217)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-217)|Identifier|`class-subpropertyof`|
|[Section top](#pass-outcome-number-217)|Title|No&#32;class&#32;subproperty|
|[Section top](#pass-outcome-number-217)|Description|No&#32;ontology&#32;class&#32;is&#32;a&#32;subproperty|

***
### Pass Outcome number 218

[Jump to summary definition](#summary-Pass-218)	|	[Previous Pass outcome](#pass-outcome-number-217)	|	[Next Pass outcome](#pass-outcome-number-219)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-218)|Identifier|`property-subclassof`|
|[Section top](#pass-outcome-number-218)|Title|No&#32;property&#32;subclass|
|[Section top](#pass-outcome-number-218)|Description|No&#32;ontology&#32;property&#32;is&#32;a&#32;subclass|

***
### Pass Outcome number 219

[Jump to summary definition](#summary-Pass-219)	|	[Previous Pass outcome](#pass-outcome-number-218)	|	[Next Pass outcome](#pass-outcome-number-220)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-219)|Identifier|`subclassof-property`|
|[Section top](#pass-outcome-number-219)|Title|No&#32;subclass&#32;of&#32;property|
|[Section top](#pass-outcome-number-219)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subclass&#32;of&#32;a&#32;property|

***
### Pass Outcome number 220

[Jump to summary definition](#summary-Pass-220)	|	[Previous Pass outcome](#pass-outcome-number-219)	|	[Next Pass outcome](#pass-outcome-number-221)

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

#### Criterion detail
|Identifier|[proper-extension-predicate](https://ns.inria.fr/olivaw#proper-extension-predicate)|
|----|----|
|Title|Predicate&#32;extension&#32;test|
|Description|A&#32;test&#32;meant&#32;to&#32;test&#32;the&#32;proper&#32;use&#32;of&#32;predicates&#32;rdfs:subClassOf&#32;and&#32;rdfs:subPropertyOf&#32;on&#32;the&#32;ontology&#32;terms|

#### Outcome Detail
|Jump|Type|:white_check_mark:Pass|
|----|----|----|
|[Section top](#pass-outcome-number-220)|Identifier|`subpropertyof-class`|
|[Section top](#pass-outcome-number-220)|Title|No&#32;subproperty&#32;of&#32;class|
|[Section top](#pass-outcome-number-220)|Description|No&#32;ontology&#32;term&#32;is&#32;a&#32;subproperty&#32;of&#32;a&#32;class|

***
### Pass Outcome number 221

[Jump to summary definition](#summary-Pass-221)	|	[Previous Pass outcome](#pass-outcome-number-220)	|	Next Pass outcome

:white_check_mark:Pass outcome
#### Subject detail
|Name|all-fragments|
|----|----|
|Title|All&#32;the&#32;fragments&#32;from&#32;branch&#32;main&#32;that&#32;are&#32;syntaxically&#32;correct&#32;as&#32;well&#32;as&#32;their&#32;recursive&#32;imports|
|Composition|- https://github.com/acimov-tools/model-test/blob/main/modelet.ttl<br/>- https://github.com/acimov-tools/model-test/blob/main/module.ttl|

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

</details>

***
