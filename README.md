![CLAW Logo](resources/logo_full_black.png)


The CLAW Project is an open-source project including a directive language
specification and a reference compiler targeting performance portability in
climate and weather application written in Fortran.

## CLAW Compiler
The CLAW Compiler is a source-to-source translator working on the XcodeML
intermediate representation. It implements the necessary transformation to the
CLAW Directive Language Specifications.
Intent of this language is to achieve performance portability on weather and
climate code, especially for column- or point-wise computation.

* **CLAW Directive Language**
  * [Official repository](https://github.com/claw-project/claw-language-specification)
  * [Specification v0.4.0 ](./resources/claw_language_specifications_v0.4.0.pdf)
  * [Specification v1.1.0](./resources/claw_language_specifications_v1.1.0.pdf)
  * Specification v2.0 - _coming soon ..._


* **CLAW Compiler code**
  * [Official repository](https://github.com/claw-project/claw-compiler)
  * [Releases](https://github.com/claw-project/claw-compiler/releases)


* **CLAW Compiler - Developer's Guide**
  * [Guide version 1.0](./resources/developers_guide_v1.0.pdf)

### CLAW X2T
CLAW X2T (XcodeML to XcodeML Translator) is the part in charge of the AST
analysis and transformations based on the directives.

The [Java documentation](./javadoc/index.html) of the CLAW X2T libraries is
available.

### Contributing
The CLAW Project is welcoming contribution. More information can be found on the official
repository.
A [Slack](https://claw-compiler.slack.com/) workspace is available for discussions.

### Resources

##### Papers
*  *The CLAW DSL: Abstractions for Performance Portable Weather and Climate Models.* In Proceedings of the Platform for Advanced Scientific Computing Conference (PASC '18)  [[doi]((https://doi.org/10.1145/3218176.3218226))]


##### Talks
* Plenary Talk at **PASC'18**: *The CLAW DSL: Abstractions for Performance Portable
  Weather and Climate Models* [[Slides](./resources/20180702_claw_pasc18.pdf)]

<iframe width="560" height="315" src="https://www.youtube.com/embed/zns7JcbuKB4?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### About
This work was initially funded by the ETH zürich and the PASC initiative under
the [ENIAC](http://www.pasc-ch.org/projects/2017-2020/eniac/) project.


<div style="text-align:center">
<a href="http://www.c2sm.ethz.ch" target="_blank"><img src ="resources/c2sm_logo_black.png"/></a>
<a href="https://www.pasc-ch.org" target="_blank"><img src ="resources/pasc_logo.svg"/></a>
<a href="http://www.meteoswiss.admin.ch" target="_blank"><img src ="resources/mch_logo_1.png"/></a>
</div>

---
CLAW logo by [adrienbachmann.ch](http://www.adrienbachmann.ch)
