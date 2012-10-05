Ripple, A Mobile Environment Emulator
=====================================

Abstract
========

Ripple is a browser based mobile phone emulator designed to aid in the development
of HTML5 based mobile applications.  Ripple is a cross platform and cross
runtime testing/debugging tool. It currently supports such runtimes as Cordova, WebWorks
and the Mobile Web.

Proposal
========

Ripple is going to be (in some circles already is) the goto emulator for rapid development of mobile web applications. This
will be accomplished by quickly keeping up with the mobile web platforms as they arise (Cordova, Tizen, WAC, WebWorks, etc).

Background
==========

Ripple started as a product of tinyHippos and was aquired by Research in Motion in late March 2011.  Ripple was then open sourced
under the Apache 2.0 License and hosted on the blackberry github account (http://github.com/blackberry/Ripple-UI). 

Ripple is a browser based mobile phone emulator that runs as a chrome extension.  It fills the gap for developers between
developing on their desktops/laptops and having to test on platform specific emulators or physical devices. Ripple allows develors
to quickly edit-refresh-test in Chrome on their desktops/laptops while working on web content that will be embedded and distributed 
as a native application.

Rationale
=========

The project is currently opensourced and managed by a small team at Research in Motion.  We are starting to have some
more community engagement but the project could benefit from greater exposure in the open source cummunity.  Our team 
overlaps highly with the Cordova group. Watching the success for that project in Apache has inspired us to contribute
Ripple to the ASF as well.

Ripple fills a large gap in the toolset for most mobile web developers between development on the desktop and testing
on the physical device.  

Current Status
==============

Currently all development is managed on github via the issues and the direction of the project is strongly influenced by
Research in Motion.  A more clear project plan and more open communication will be needed by this project to abide by 
the apache guidelines.

Metriocracy
===========

Ripple has been very accepting of letting in patches from 3rd party 
developers and has been functioning like apache in requiring a CLA
for code to be pulled in. The core team is hoping to grow and include more 
developers. 

Community
=========

The development community of Ripple is a small but tight knit group but
the users of the project number more than 40,000. With the launch of
emulate.phonegap.com (which is a portal for installing ripple) we are
getting approx 5000 hits a day to that site.


Core Developers
===============

See Inital Committers below.

Alignment
=========

Apache is a good match for this project due to it's close ties
to the Cordova Project. Cordova has been very successful as a project
since joining Apache and we hope Ripple will follow suit. 

Known Risks
===========

Orphaned Products
-----------------

Ripple is a core component to the toolset at RIM and the Cordova / Phonegap community has embrased ripple into their tooling 
as well. This project has been under active development for 3 years and a lot of vested interest from both RIM and the
community is already present to keep the tool up to date.

Inexperience with Open Source
-----------------------------

Ripple has been opensourced at RIM for the last year.  All of the work
is done in the open. There are a few extra measures we need to learn
how to take (mailing lists, project planning) for working within the ASF community.
However the team has a good understanding of what needs to happen, as some of the 
team are also contributers to the Apache Cordova Incubator project.

Homogenous Developers
----------------------

Ripple's core team currently all works at RIM with contributions for some features done by third parties.  There is a
backlog of features currently done / being put in by third parties such as Adobe and IBM. 

Reliance on Salaried Developers
-------------------------------

Most of the developers are paid by their employer to contribute to this project but are all highly involved on a personal
level with this project as well as the mobile web community. 

Relationships with Other Apache Products
----------------------------------------

There is a strong overlap and relationship between the ripple and cordova teams.  Gord Tanner is an active commiter in
both project and has been ensuring that both projects progress together.

An Excessive Fascination with the Apache Brand.
------------------------------------------------

A driver for this project going to apache is to get broader community enagagement and involvement.  Most of the developers
who would contribute to this project are already contributing to Cordova so migrating over and contribuiting to ripple
would be a simple

Documentation
=============

Initial Source
===============

Source can be found at: https://github.com/blackberry/Ripple-UI

Source and Intellectual Property Submission Plan
================================================
Source is currently licensed via the Apache 2.0 license which is inline with ASF.  All files currently
have an apache header on them with a copyright of Research in motion (https://github.com/blackberry/Ripple-UI).

Also we have some images that are not licensed under Apache (see https://github.com/blackberry/Ripple-UI/blob/master/ext/assets/images/README.md)
The images are of some BlackBerry phones but can be removed if this is an issue.

All external contributions to the project currently require that an ICLA or CCLA be signed by the contributor. Links to the documents can be found below:

  * http://www.blackberry.com/legal/pdfs/webworks/Research_In_Motion_Limited_CCLA_021811_cl.pdf
  * http://www.blackberry.com/legal/pdfs/webworks/Research_In_Motion_Limited_ICLA_021811_cl.pdf

We believe the CLAs we have on file will allow RIM to sign a Software Grant. (SGA)

External Dependencies
======================

- 3d.js (http://wiioperasdk.com) - Custom License: http://wiioperasdk.com/sdk/3d.js
- Math.uuid.js (http://www.broofa.com) - Dual licensed under the MIT and GPL licenses: http://www.broofa.com/Tools/Math.uuid.js
- OpenLayers.js (ttp://svn.openlayers.org/trunk/openlayers) - Licensed under Clear BSD: http://svn.openlayers.org/trunk/openlayers/license.txt
- almond.js (http://github.com/jrburke/almond) - Licensed under MIT: https://github.com/jrburke/almond/blob/master/LICENSE
- draw.js (http://wiioperasdk.com) - Custom License: http://wiioperasdk.com/sdk/draw.js 
- jWorkflow (http://github.com/tinyhippos/jworkflow) - Licensed under MIT: http://www.opensource.org/licenses/mit-license.php
- jXHR.js (https://github.com/blackberry/Ripple-UI/blob/master/thirdparty/jXHR.js) - Licensed under MIT: http://www.opensource.org/licenses/mit-license.php
- jasmine (https://github.com/pivotal/jasmine) - Licensed under MIT: http://www.opensource.org/licenses/mit-license.php
- jquery (http://jquery.com) - Dual licensed under MIT and GPL: http://jquery.org/license (includes sizzle.js, now licensed under MIT: https://github.com/jquery/sizzle/blob/master/LICENSE)
- jquery.tooltip (http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/) - Dual Licensed under MIT and GPL: http://www.opensource.org/licenses/mit-license.php http://www.gnu.org/licenses/gpl.html
- jQuery UI (http://jqueryui.com) - Licensed under MIT: http://www.opensource.org/licenses/mit-license.php
- node (http://nodejs.org) - Dependant on node.js, but we do not redistribute the source or binaries
- jake (git://github.com/mde/jake.git) - Dependant on jake, but we do not redistribute the source or binaries
- jshint (http://github.com/jshint/node-jshint) - Licensed under MIT: http://www.opensource.org/licenses/mit-license.php
- csslint (http://github.com/stubbornella/csslint.git) - License information here: https://github.com/stubbornella/csslint/blob/master/LICENSE
- uglify-js (git@github.com:mishoo/UglifyJS.git) - Licensed under BSD: https://github.com/mishoo/uglifyjs
- connect (git://github.com/senchalabs/connect.git) - Licensed under MIT: https://github.com/senchalabs/connect/blob/master/LICENSE
- argsparser (git://github.com/kof/node-argsparser.git) - No license specified: https://github.com/kof/node-argsparser
- jsdom (http://github.com/tmpvar/jsdom.git) - License information here: https://github.com/tmpvar/jsdom/blob/master/LICENSE.txt

Required Resources
==================

 * Mailing Lists
  - ripple-dev
  - ripple-commits
  - ripple-private
 * git
  - git://git.apache.org/incubator-ripple.git
  - Mirrored to: https://github.com/apache/incubator-ripple
 * issue tracking
  - Bugzilla (ripple)

Initial Committers
==================

  * Gord Tanner (gtanner@gmail.com)
  * Dan Silivestru (dan.silivestru@gmail.com)
  * Brent Lintner (brent.lintner@gmail.com)
  * Fil Maj (fil@adobe.com)
  * Micheal Brooks (mbrooks@adobe.com)
  * Mark Dineen (mark@dineen.biz)

Sponsors
========

Champion: Ross Gardler (rgardler@opendirective.com)
Mentor: Jukka Zitting (jukka.zitting@gmail.com)
