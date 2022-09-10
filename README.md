# VSF REST Store - eCommerce REST API for Vue Storefront

[![license](http://img.shields.io/badge/license-CC0%201.0%20Universal-blue.svg)](https://github.com/GorillaSystemsEG/VsfRestStore/blob/master/LICENSE.md)
[![release](http://img.shields.io/github/release/GorillaSystemsEG/VsfRestStore.svg)](https://github.com/GorillaSystemsEG/VsfRestStore/releases)
[![commits since release](http://img.shields.io/github/commits-since/GorillaSystemsEG/VsfRestStore/v1.0.0.svg)](https://github.com/GorillaSystemsEG/VsfRestStore/commits/master)

[![Discourse Forum](https://img.shields.io/badge/moqui%20forum-discourse-blue.svg)](https://forum.moqui.org)
[![Google Group](https://img.shields.io/badge/google%20group-moqui-blue.svg)](https://groups.google.com/d/forum/moqui)
[![LinkedIn Group](https://img.shields.io/badge/linked%20in%20group-moqui-blue.svg)](https://www.linkedin.com/groups/4640689)
[![Stack Overflow](https://img.shields.io/badge/stack%20overflow-moqui-blue.svg)](http://stackoverflow.com/questions/tagged/moqui)

VSF REST Store is a REST API for the Vue Storefront eCommerce website. The code started as a fork of PopRestStore. 

This component is does not contain an admin application, for that use the POP Commerce ERP app. There is sample configuration data
in the XML data files in this component. 

This component is used in tandem with the Vue Storefront Moqui Integration (@vuestorefront-community/moqui).

We would love to improve this component, feel free to  fork and modify this git repository and create pull requests for bug fixes, and/or features you believe should be included.

To add this component to Moqui the easiest approach is to use the Gradle get component task:

    $ ./gradlew getComponent -Pcomponent=VsfRestStore

Or add a dependency in your component.xml file like:

    <depends-on name="VsfRestStore"/>

Or navigate to moqui/runtime/component and clone this repository.
