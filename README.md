# raml-spec-cn
RAML规范（译）

作者：山人（Jeff Lu）
QQ：278400368
兴趣群：4399664

欢迎联系一起讨论，更欢迎一起翻译此文档！



## 进度条

* Introduction
* What's New and Different in RAML 1.0
* Markup Language
* The Root of the Document
	* User Documentation
	* Base URI and Base URI Parameters
	* Protocols
	* Default Media Types
	* Default Security
* RAML Data Types
	* Introduction [已完成]
	* Overview [已完成]
	* Defining Types [已完成]
	* Type Declarations [已完成]
	* Built-in Types [已完成]
		* The "Any" Type
		* Object Type
			* Property Declarations 
			* Additional Properties
			* Object Type Specialization
			* Using Discriminator
		* Array Type
		* Scalar Types
			* String
			* Number
			* Integer
			* Boolean
			* Date
			* File
			* Nil Type
		* Union Type
		* Using XML and JSON Schema
	* User-defined Facets [已完成]
	* Determine Default Types [已完成]
	* Type Expressions [已完成]
	* Multiple Inheritance [准备开始...]
	* Inline Type Declarations
	* Defining Examples in RAML
		* Multiple Examples
		* Single Example
		* Example of how to define example/examples in RAML
	* XML Serialization of Type Instances
	* Using Types in RAML
* Resources and Nested Resources
	* Resource Property
	* Template URIs and URI Parameters
* Methods
	* Headers
	* Query Strings and Query Parameters
		* The Query String as a Whole
		* Query Parameters in a Query String
	* Bodies
* Responses
* Resource Types and Traits
	* Declaration Resource Types and Traits
	* Applying Resource Types and Traits
	* Resource Type and Trait Parameters
	* Declaring HTTP Methods as Optional
	* Algorithm of Merging Traits and Methods
	* Resource Types and Traits Effect on Collections
* Security Schemes
	* Security Scheme Types
	* Security Scheme Declaration
		* describedBy
		* Settings
			* OAuth 1.0
			* OAuth 2.0
			* Basic Authentication
			* Digest Authentication
			* Pass Through
			* x-<other>
		* Applying Security Schemes
* Annotations
	* Declaring Annotation Types
	* Applying Annotations
		* Annotating Scalar-valued Nodes
		* Annotation Targets
* Modularization
	* Includes
		* Typed Fragments
		* Resolving Includes
	* Libraries
	* Overlays and Extensions
		* Overlays
		* Extensions
		* Merging Rules
* References