---
title: Build
layout: page
---

<h2>For Developers</h2>
<p>
Many technical resources available to you, the developer of Green Button applications. The <a href="{{ site.baseurl }}/library/index.html">library of technical documents</a> and presentations provides links to the standards and implementation guides you will want to review before starting your implementations. Most of these materials are directed to developers of DataCustodians, as the requirements of custodians are much more complex than those of a third party application.  Both may find the <a href="{{ site.baseurl }}/developers">Green Button Developers Guide</a> useful.
</p>
<h3>DataCustodians</h3>
<dl>
<dt><a href="https://services.greenbuttondata.org/DataCustodian/">Green Button Data Custodian</a></dt>
<dd>A fully functional Green Button Data Custodian maintained to allow community experimentation. The administrative functions are available when you sign-in using credentials:
  <ul>
    <li><b><i>grace : koala</i></b> (ROLE=ADMIN)  or <b><i>alan : koala</i></b> (ROLE:USER) </li>
  </ul>
You will then be able to review various functions of the sandbox. The short video <a href="">Using the DataCustodian</a> will provide a starting point for poking around.  <b>NOTE: this is a shared sandbox, so things you do may effect other concurrent users! please use the reset and initialize functions with care</b>
  </dd>
</dl>
<h3>Third Parties</h3>
The sandbox also contains a minimal <a href="https://services.greenbuttondata.org/ThirdParty/">Third Party Application</a>. It supports the minimal behavior of a Green Button Third Party and may be used to connect to any certified Green Button Data Custodian. It has an administrative account (grace:koala); as well as numerous retail customer accounts to work with.
<dl>
</dl>

<h3>RESTful API</h3>
The full complement of <a href="http://energyos.github.io/OpenESPI-GreenButton-API-Documentation/API/">Green Button RESTful APIs</a> are supported in the <a href="http://energyos.github.io/OpenESPI-GreenButton-API-Documentation/API/">DataCustodian sandbox</a>. You are encouraged to experiment with these APIs using the swagger based <a href"http://energyos.github.io/OpenESPI-GreenButton-API-Documentation/API/">API Sandbox</a>. Please keep in mind that certain of the actions (DELETE, PUT, and POST) will modify the state of the sandbox, so you should insure that you run DataCustodian Initialization following any experiments that perform modifications.
<dl>
</dl>
<h3>Open Source Implementation</h3>
<p>
Numerous tools and code bases are available on <a href="http://github.com/energyos">Github</a> and are available under the Apache 2 license. In addition to a full implementations of Green Button DataCustodain ThirdParty services,  a common java library is available for reuse. There are also numerous tools for testing and generation of Green Button sample data sets.
</p>
  <dt><a href="https://services.greenbuttondata.org/">Green Button Sandbox</a></dt>
  <dd>The sandbox is maintained to support developers as they implement their Green Button services. It is a deployment of the EnergyOS OpenESPI java spring code base running on a Tomcat 7 server. This effort, supported by NIST, is the result of a public collaboration with contributions maintained in the following Github repositories:
    <ul>
      <li><a href="https://github.com/energyos/OpenESPI-Common-java">OpenESPI Common Library</a></li>
      <li><a href="https://github.com/energyos/OpenESPI-DataCustodian-java">OpenESPI DataCustodian</a></li>
      <li><a href="https://github.com/energyos/OpenESPI-ThirdParty-java">OpenESPI ThirdParty</a></li>
    </ul>
  </dd>
  <dt><a href="https://github.com/energyos/OpenESPI-GreenbuttonDataSDK">Green Button Tools SDK</a></dt>
  <dd>
    The Tools SDK provides a set of stand-alone tools to help you work with Green Button XML data. Written primarily in Visual Basic and using Excel macros, you
    will be able to see simple code that parses Green Button XML and validates appropriate things like time and resource values.  These tools were used in the creation
    of the on-line <a href="http://www.greenbuttondata.org/greentest.aspx">Green Button validator</a>, where you can test your exported Green Button files for correctness.
  </dd>
  <dd>
    Also find a sample XSLT that will transform Green Button Data to human-readable table in a web browser: <a href="https://github.com/energyos/OpenESPI-GreenbuttonDataSDK/blob/master/GreenButtonDemoPage/data/GreenButtonDataStyleSheet.xslt">GreenButtonDataStyleSheet.xslt</a>
  </dd>
  <dt><a href="https://github.com/energyos/OpenESPI-GreenButtonCMDTest">Green Button Connect My Data Test Fixture</a></dt>
  <dd>
    The Connect My Data test services are currently being developed with support of NIST in collaboration with the OpenADE task group. This effort uses the <a href="http://www.soapui.org/">SOAPui automated
    testing platform</a> as well as the <a href="http://groovy.codehaus.org/">Groovy scripting environment</a>.  You may download, install, and run the test suits from the <a href="https://github.com/energyos/OpenESPI-GreenButtonCMDTest">github repository</a>.
  </dd>
  <dt><a href="https://github.com/energyos/OpenESPI-GreenButton-API-Documentation">Green Button RESTful API</a></dt>
  <dd>
  The <a href="http://swagger.wordnik.com/">swagger API platform</a> is used to provide a dynamic API sandbox for developers to work within. It is deployed and operable to review API calls to the <a href="https://services.greenbuttondata.org">Green Button Services Sandbox</a>. You may fork the github repository and use this repository to test against your own DataCustodian services as well. 
  </dd>
  </dl>


