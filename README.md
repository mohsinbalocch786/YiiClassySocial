YiiClassySocial
===============

Yii New Social Extension

Can be use as below

<?php 
$this->widget("ext.ClassySocial.ClassySocial",array(
		'theme'=>'square',//- the current theme, can be default, square or slick
		'networks'=>'facebook,google,email',//- comma-separated list of social networks, networks values can be facebook,google,twitter,pinterest,linkedin,dribbble,email,socl,instagram,vimeo,youtube,github,blogger,deviantart,flickr,skype,steam,wordpress,yahoo
		'radius'=>90,//- the radius of the arc, default is 80
		'imagetype'=>'picture',//can be facebook if you want your Facebook profile image to be shown by default or picture, default is picture
		'picture' => 'mohsinkhan', //- can be either the name of the Facebook profile, an image url (ex images/test.jpg) or none, default is none
		'orientation'=>'arc',// - orientation, can be arc, line or linedown, default is arc
		//'gap'=>'50px',//the gap (in pixels) between the profile bubbles, default is 50 pixels 
		//'style'=>'float:left',//can set any css style 
		'arcstart'=>0,//- start of the arc, from 1 to 360, default is 0
		'arclength'=>180,// - length of the arc, from 1 to 360, default is 180
		'handle'=>array('facebook'=>'mohsinkhan.baloch','google'=>'102409429678683189860','email'=>'balochmohsin786@gmail.com'),

  
	));
?>
please +1 if you find useful

Attach is Source of extension, simple unzip in extensions directory and use it enjoy.

let me know if have any suggestion or issue
