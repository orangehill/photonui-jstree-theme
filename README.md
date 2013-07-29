Photon UI jsTree Theme
=====================
Since there aren't many jsTree themes out there, we thought we'd make this one freely available.

Photon UI jsTree Theme was created as a part of [Photon UI Responsive Admin Panel Theme](http://themeforest.net/item/photon-ui-responsive-admin-panel-theme/3995029) (available on Themeforest).

##What is jsTree?

jsTree is a javascript based, most awesome cross browser tree component. It is packaged as a jQuery plugin.

It is available absolutely free at [http://www.jstree.com/](http://www.jstree.com/) or at [https://github.com/vakata/jstree](https://github.com/vakata/jstree).

For your convenience entire `jsTree pre 1.0 fix2` version is included with this theme.

##Theme Demo
A demo with five detailed examples is available at [Photon UI jsTree Theme Demo](http://orangehilldev.com/photonui-jstree-theme/demo/) page.

*Desktop Version Screenshot:*

![Desktop Version Screenshot](http://orangehilldev.com/photonui-jstree-theme/Photon_UI_jsTree_Theme_Demo.jpg "Desktop Version Screenshot")

*Responsive Version Screenshot:*

![Responsive Version Screenshot](http://orangehilldev.com/photonui-jstree-theme/Photon_UI_jsTree_Theme_Demo_Responsive.jpg "Responsive Version Screenshot")

##Responsiveness
Photon UI jsTree Theme is [Responsive](http://en.wikipedia.org/wiki/Responsive_web_design). To see the effect [open the demo](http://orangehilldev.com/photonui-jstree-theme/demo/) and scale a browser window down until the window width is less then 768 pixels. 

Mobile friendly design should make it easier to tap nodes with more precision.

##LESS CSS support

If you wish to further customize the theme you might find it convenient to use included [LESS](http://lesscss.org/) files. 

To develop using LESS files please uncomment this section in `/demo/index.html`

		<!-- Include LESS files for development only (otherwise style.css is auto-loaded by jsTree plugin) -->
		<!--
			<link rel="stylesheet/less" href="../themes/photonui/style.less?1375004169" media="all" />
			<script type="text/javascript" src="../themes/photonui/less-1.3.1.min.js"></script>
		-->
		
After that, it's important to empty the contents of `/themes/photonui/style.css` as it is loaded automatically via jsTree plugin.

Once done with tweaking all you have to do is compile the files to style.css using lessc command line utility, and remove/comment out the lines reffering to LESS files in `/demo/index.html` head section.

	// compile less to css file example
	
	lessc /path-to/photonui-jstree-theme/themes/photonui/style.less > /path-to/photonui-jstree-theme/themes/photonui/style.css
