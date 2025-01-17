---

copyright:
  years: 2018, 2019
lastupdated: "2019-04-29"

keywords: whitelisted IP addresses, CIS Edges

subcollection: cis

---
{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:term: .term}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:external: target="_blank" .external}
{:generic: data-hd-programlang="generic"}
{:download: .download}
{:DomainName: data-hd-keyref="DomainName"}

# {{site.data.keyword.cis_full_notm}}S whitelisted IP addresses
{:#cis-whitelisted-ip-addresses}

The following API lists all IP addresses used by the {{site.data.keyword.cis_full}} proxy. The {{site.data.keyword.cis_short_notm}} proxy uses only addresses from this list, for both client-to-proxy as well as proxy-to-origin communication.
{: shortdesc}

[https://api.cis.cloud.ibm.com/v1/ips](https://api.cis.cloud.ibm.com/v1/ips).

Polling this API once a week is sufficient to get the information you need to update your whitelists.

The IP addresses the {{site.data.keyword.cis_short_notm}} proxy uses for communication with the origins are not necessarily the same as the ones used for client-to-proxy communication, although all addresses are derived from the same list.
{:note}
