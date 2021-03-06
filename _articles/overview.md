---
title: Platform Overview
layout: article
overview: true
---

<div class="ui positive message">
<p>Key components of Sage's platform are:</p>

<dl>
    <dt><a href="/articles/rest.html">Bridge Services</a></dt>
	<dd>A set of REST-based web services that allow mobile apps to receive study configuration such as surveys and task schedules, manage participant registration and consent, and securely receive participant data.  Bridge Server <a href="https://github.com/Sage-Bionetworks/BridgePF">source code is available in GitHub</a> - however Sage recommends developers use Sage's hosted services rather than manage their own server instance.</dd>

    <dt><a href="/articles/ios.html">iOS and Research Kit SDKs</a></dt> 
	<dd>Open source libraries for building mobile health apps using Bridge Services and Apple's Research Kit.</dd>

	<dt><a href="/articles/android.html">Android SDKs</a></dt>
	<dd>Open source libraries for building mobile health apps using Bridge Services and the open source Research Stack framework.</dd>

	<dt><a href="/articles/java.html">Java REST Client</a></dt>
	<dd>A Java-based client for integration with the Bridge server.</dd>

	<dt><a href="https://research.sagebridge.org/">Bridge Study Manager</a></dt>
	<dd>A web interface to Bridge Services allowing mobile app developers and research teams to manage and monitor their study.</dd>
	
	<dt><a href="https://synapse.org">Synapse</a></dt>
	<dd>An open source software platform that data scientists can use to carry out, track, and communicate their research in real time. Synapse has seeded a growing number of large scale biomedical research projects centered around genomic, clinical, imaging, mobile health, and other biomedical data sets.</dd>
</dl>
</div>

Together, this platform provides the most complete set of support for the development, execution, and analysis of mobile health studies.

![Sage Platform](/images/Bridge%20-%20Sage%20Overview.png)

