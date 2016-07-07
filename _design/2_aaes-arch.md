---
layout: page_collection
title: AAES Architecture
collection: design
permalink: design/2_aaes-arch/
---
<script>
$(function() {
  $( "#accordion" ).accordion({
    heightStyle: "content",
    collapsible: "true",
    active: "false"
  });
});
</script>
--------------------------------------

Designing an AAES solution architecture requires agencies to consier the capabilities presented in the ICAM target state, existing ICAM investments (e.g., logical access solutions), and the agency's overall IT infrastructure. The objective of this effort is to determine how an AAES capability will integrate with the agency's IT infrastructure and provide digital identity attribute sharing services, as defined in the ICAM Services Framework.

This section provides a high-level AAES solution architecture diagram illustrating the services and capabilities introduced in the ICAM segment architecture.

<div style="text-align:center"><img src="{{site.baseurl}}/img/aaes.png"/></div>

The diagram above is intended to serve as a high-level depiction of the ICAM target state for an AAES capability. It is representative of the various solutions that an agency may choose to implement. The solution components within the AAES Infrastructure are represented generically and could be implemented using a variety of Commercial Off-The-Shelf (COTS) or purpose-built products. Agencies should evaluate their existing ICAM and infrastructure investments and select the approach that best meets their needs.

As depicted above, an AAES provides a consolidated mechanism for securely  and electronically exchanging digital identity attributes between authoritative data sources and the agency applications that consume those attributes. In many cases, this data is spread across multiple authoritative sources within an agency, thereby complicating the challenge of exchanging attributes between sources and consumers. The Authoritative Attribute Manager provides the capability to present a single, authoriative view of that data by reconciling and aggregating attributes from the various sources. The Authoritative Distributor is the component that integrates with attribute consumers and conducts the data exchange. 

















