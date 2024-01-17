# Test Report Markdown export

This file is an export of the RDF test report made out of [EARL vocabulary](https://www.w3.org/TR/EARL10/)

This test is powered by Corese, check the [website](https://project.inria.fr/corese/) and the [repository](https://github.com/Wimmics/corese)

The original test report is available in turtle syntax [here](./model-test-actions.ttl).

# Test Context

Here is some context about under which context this test was made

|Assertor|[NicoRobertIn](https://github.com/NicoRobertIn)|
|----|-----|
|Title|NicoRobertIn using actions script|
|Description|Test triggered by [@NicoRobertIn](https://github.com/NicoRobertIn) by actions trigger|
|Script|[suite.py](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/suite.py)
|Date|2024-01-17 13:38:34|

***


# Statistic summary

Here is a short overview for this test report

11 Assertions

:boom:1 MajorFail, :exclamation:0 MinorFail, :warning:0 CannotTell, :grey_question:10 NotTested, :white_check_mark:0 Pass

<div  style="border-radius: 12px; height: 25px; overflow: hidden"><img src="../assets/red.png" width="9%" height="25px"/><img src="../assets/orange.png" width="0%" height="25px"/><img src="../assets/grey.png" width="0%" height="25px"/><img src="../assets/white.png" width="90%" height="25px"/><img src="../assets/green.png" width="1%" height="25px"/></div>

<br/>

According to the [EARL](https://www.w3.org/TR/EARL10-Schema/) vocabulary, each outcome type means:
* :x: Fail: The subject failed the test. 
* :warning: CannotTell: It is unclear if the subject passed or failed the test. This happens when an automated test requires human judgement to make a definite decision.
* :grey_question: NotTested:  The test has not been carried out. Here this is because a previous test that was mandatory to be passed did not end up as Pass.
* :white_check_mark: Pass: The subject passed the test.

***


# MajorFail Assertions

Here is the chapter related to the MajorFail assertion

:boom:1 MajorFail assertions

<details>
<summary>Fold/Unfold the 1 summary and details</summary>

## MajorFail Assertions Summary

[Jump to statistic summary](#statistic-summary)

:boom:1 MajorFail assertions

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#majorfail-assertions-summary)|<div id="summary-MajorFail-1">1/1</div>|:boom:*MajorFail*|`wine`|[syntax](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#syntax)|Test subject has syntax errors|[Jump](#majorfail-assertion-number-1)|

***

## MajorFail Assertion Details

This subchapter gives more details to the :boom:MajorFail assertions

### MajorFail Assertion number 1

[Jump to summary definition](#summary-MajorFail-1)

:boom:MajorFail assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[syntax](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#syntax)|
|----|----|
|Title|Syntax test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:boom:MajorFail|
|----|----|
|Title|Test subject has syntax errors|
|Description|Encountered "\"\"\"Derived from the DAML Wine ontology at \n      http://ontolingua.stanford.edu/doc/chimaera/ontologies/wines.daml\n      Substantially changed, in particular the Region based relations.\n    \"\"\" ;" at line 15, column 43.|

***

</details>

***


# NotTested Assertions

Here is the chapter related to the NotTested assertion

:grey_question:10 NotTested assertions

<details>
<summary>Fold/Unfold the 10 summary and details</summary>

## NotTested Assertions Summary

[Jump to statistic summary](#statistic-summary)

:grey_question:10 NotTested assertions

|*Jump*|*Number*|*Status*|*Subject*|*Criterion*|*Title*|*Link*|
|------|--------|--------|---------|-----------|-------|------|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-1">1/10</div>|:grey_question:*NotTested*|`wine`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|The test could not be run|[Jump](#nottested-assertion-number-1)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-2">2/10</div>|:grey_question:*NotTested*|`wine`|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|The test could not be run|[Jump](#nottested-assertion-number-2)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-3">3/10</div>|:grey_question:*NotTested*|`wine`|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|The test could not be run|[Jump](#nottested-assertion-number-3)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-4">4/10</div>|:grey_question:*NotTested*|`wine`|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|The test could not be run|[Jump](#nottested-assertion-number-4)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-5">5/10</div>|:grey_question:*NotTested*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|The test could not be run|[Jump](#nottested-assertion-number-5)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-6">6/10</div>|:grey_question:*NotTested*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|The test could not be run|[Jump](#nottested-assertion-number-6)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-7">7/10</div>|:grey_question:*NotTested*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|The test could not be run|[Jump](#nottested-assertion-number-7)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-8">8/10</div>|:grey_question:*NotTested*|`wine`|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|The test could not be run|[Jump](#nottested-assertion-number-8)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-9">9/10</div>|:grey_question:*NotTested*|`wine`|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|The test could not be run|[Jump](#nottested-assertion-number-9)|
|[Table top](#nottested-assertions-summary)|<div id="summary-NotTested-10">10/10</div>|:grey_question:*NotTested*|`wine`|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|The test could not be run|[Jump](#nottested-assertion-number-10)|

***

## NotTested Assertion Details

This subchapter gives more details to the :grey_question:NotTested assertions

### NotTested Assertion number 1

[Jump to summary definition](#summary-NotTested-1)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The syntax of the subject and any of its imports must be syntaxically correct|

***
### NotTested Assertion number 2

[Jump to summary definition](#summary-NotTested-2)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[domain-and-range-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#domain-and-range-referencing)|
|----|----|
|Title|Domain and range referencing test|
|Description|A test case from the Best Practices tests checking if all the ranges and domains from the test subject point to terms that are defined in the vocabulary.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The syntax of the subject and any of its imports must be syntaxically correct|

***
### NotTested Assertion number 3

[Jump to summary definition](#summary-NotTested-3)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[labeled-terms](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#labeled-terms)|
|----|----|
|Title|Term labeling test|
|Description|A test case from the Best Practices tests checking if all the terms of the subject have a rdfs:label property pointing to a literal in English|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject and its recursive imports must be syntaxically correct|

***
### NotTested Assertion number 4

[Jump to summary definition](#summary-NotTested-4)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[owl-rl-constraint](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#owl-rl-constraint)|
|----|----|
|Title|OWL RL Constraint test|
|Description|A test meant to check wether the test subject is syntaxically correct or not.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject and its recursive imports must be syntaxically correct|

***
### NotTested Assertion number 5

[Jump to summary definition](#summary-NotTested-5)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject must be syntaxically correct|

***
### NotTested Assertion number 6

[Jump to summary definition](#summary-NotTested-6)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject must be syntaxically correct|

***
### NotTested Assertion number 7

[Jump to summary definition](#summary-NotTested-7)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject must be syntaxically correct|

***
### NotTested Assertion number 8

[Jump to summary definition](#summary-NotTested-8)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[profile-compatibility](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#profile-compatibility)|
|----|----|
|Title|Profile compatibility test|
|Description|A test meant to check whether the test subject is compatible with a profile or not, and if it is not, why.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject must be syntaxically correct|

***
### NotTested Assertion number 9

[Jump to summary definition](#summary-NotTested-9)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[term-referencing](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#term-referencing)|
|----|----|
|Title|Term referencing test|
|Description|A test case from the Best Practices tests checking if each term of the test subject is referenced to a module through a rdfs:isDefinedBy property.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject syntax must be correct|

***
### NotTested Assertion number 10

[Jump to summary definition](#summary-NotTested-10)

:grey_question:NotTested assertion
#### Subject detail
|Name|wine|
|----|----|
|Title|Standalone module src/wine.ttl from branch refs/heads/main|
|Composition|- [Module wine.ttl](https://github.com/acimov-tools/model-test/blob/refs/heads/main/src/wine.ttl)|

#### Criterion detail
|Identifier|[terms-differenciation](https://github.com/Wimmics/olivaw/blob/main/olivaw/test/model/model-test-onto.ttl#terms-differenciation)|
|----|----|
|Title|Terms differenciation test|
|Description|A test case from the Best Practices tests checking if all the terms are different enough from each other according to the Levenshtein distance metric.|

#### Outcome Detail
|Type|:grey_question:NotTested|
|----|----|
|Title|The test could not be run|
|Description|The subject needs to be syntaxically correct|

***

</details>

***
