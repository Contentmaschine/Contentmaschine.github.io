---
driveId: 1UXorbQjZRcKPEizMDZQVeko2pXgKfgRc/preview
title: I was not built for this
klappentext: wenn einem die worte fehlen
---

<!--
<p class="mobile">
<a href="https://drive.google.com/file/d/1UXorbQjZRcKPEizMDZQVeko2pXgKfgRc/view?usp=sharing">SharedGoogleDriveFile</a>
</p> 
<p class="desktop">
<a href="https://drive.google.com/file/d/1UXorbQjZRcKPEizMDZQVeko2pXgKfgRc/view?usp=sharing">SharedGoogleDriveFile</a>
</p> -->

<p id="changeMe">{% include googleDrivePlayer.html id=page.driveId %}</p>
<script>
if (navigator.userAgent.match(/Mobile/)) {
document.getElementById("changeMe").innerHTML ='<a href="https://drive.google.com/file/d/1UXorbQjZRcKPEizMDZQVeko2pXgKfgRc/view?usp=sharing">SharedGoogleDriveFile</a>';
}
</script>


