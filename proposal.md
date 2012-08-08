Ripple, A Mobile Environment Emulator
=====================================

Abstract
========

Ripple is a browser based mobile phone emulator to aid in the development
of HTML5 based mobile applications.  Ripple is a cross platform and cross
runtime based tool. It currently supports such runtimes as Cordova, WebWorks
and the Mobile Web.

Proposal
========

Ripple is going to be (in some circles already is) the goto emulator for rapid development of mobile web applications. This
will be accomplished by quickly keeping up with the mobile web platforms as they arise (Cordova, Tizen, WAC, WebWorks, etc).

Background
==========

Ripple started as a product of tinyHippos who was later aquired by Research in Motion.  Ripple was then open sourced
under the Apache license and hosted on the blackberry github account. 

Ripple is a browser based mobile phone emulator that runs as a chrome extension.  It fills the gap for developers
needing to quickly edit-refresh-continue while working on web content that will be embedded and distributed as a native 
application.

Rationale
=========

The project is currently opensourced and managed by a small team at Research in Motion.  We are starting to have some
more community engagement but the project needs more.  Our team overlaps highly with the Cordova group and watching
the success for that project in Apache as inspired us to put ripple there as well.

Ripple fills a large gap in the toolset for most mobile web developers between development on the desktop and the
phone.  

Current Status
==============

Currently all development is managed on github via the issues and the direction of the project is strongly influenced by
Research in Motion.  A more clear project plan and more open communication will be needed by this project to abide by 
the apache guidelines.

Transition to Apache
===================

Metriocracy
===========

Community
=========


Core Developers
===============

- Gord Tanner 
- Dan Silivestru
- Brent Lintner

Alignment
=========

Known Risks
===========

Orphaned Products
-----------------

Ripple is still core to the toolset at RIM and the Cordova / Phonegap community has embrased ripple into their tooling 
as well. This project has been under active development for 2 years and a lot of vested interest from both RIM and the
community is already present to keep the tool up to date.

Inexperience with Open Source
-----------------------------

Homogenous Developers
----------------------

Ripple's core team currently all works at RIM with contributions for some features done by third parties.  There is a
backlog of features currently done / being put in by third parties such as Adobe and IBM. 

Reliance on Salaried Developers
-------------------------------

Most of the developers are paid by their employer to contribute to this project but are all highly involved on a personal
level with this project and the mobile web community. 

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
Source is currently licensed via the Apache 2.0 license, so most of that should just transfer over fine.  All files currently
have an apache header on them with a copyright of Research in motion (https://github.com/blackberry/Ripple-UI).

Also we have some images that are not licensed under Apache (see https://github.com/blackberry/Ripple-UI/blob/master/ext/assets/images/README.md)
The images are of some BlackBerry phones but can be removed if this is an issue.

External Dependencies
======================

- 3d.js (http://wiioperasdk.com)
- Math.uuid.js (http://www.broofa.com)
- OpenLayers.js (ttp://svn.openlayers.org/trunk/openlayers)
- almond.js (http://github.com/jrburke/almond)
- draw.js (http://wiioperasdk.com)
- jWorkflow (http://github.com/tinyhippos/jworkflow)
- jXHR.js (https://github.com/blackberry/Ripple-UI/blob/master/thirdparty/jXHR.js)
- jasmine (https://github.com/pivotal/jasmine)
- jquery (http://jquery.com)
- jquery.tooltip (http://bassistance.de/jquery-plugins/jquery-plugin-tooltip/)
- jQuery UI (http://jqueryui.com)
- node (http://nodejs.org)
- jake (git://github.com/mde/jake.git)
- jshint (http://github.com/jshint/node-jshint)
- csslint (http://github.com/stubbornella/csslint.git)
- uglify-js (git@github.com:mishoo/UglifyJS.git)
- connect (git://github.com/senchalabs/connect.git)
- argsparser (git://github.com/kof/node-argsparser.git)
- jsdom (http://github.com/tmpvar/jsdom.git)

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
  * Micheal Brooks
