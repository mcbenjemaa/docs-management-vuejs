<template>

<div>


  <div class="page-loader-wrapper">
   <div class="loader">
     <div class="preloader">
       <div class="spinner-layer pl-red">
         <div class="circle-clipper left">
           <div class="circle"></div>
         </div>
         <div class="circle-clipper right">
           <div class="circle"></div>
         </div>
       </div>
     </div>
     <p>Please wait...</p>
   </div>
 </div>
 <!-- #END# Page Loader -->
 <!-- Overlay For Sidebars -->
 <div class="overlay"></div>
 <!-- #END# Overlay For Sidebars -->
 <!-- Search Bar -->
 <div class="search-bar">
   <div class="search-icon">
     <i class="material-icons">search</i>
   </div>
   <input type="text" placeholder="START TYPING...">
   <div class="close-search">
     <i class="material-icons">close</i>
   </div>
 </div>
 <section>
   <!-- Left Sidebar -->
   <aside id="leftsidebar" class="sidebar">
     <!-- User Info -->
     <div class="user-info">
       <div class="image">
         <img src="/static/assets/images/user.png" width="48" height="48" alt="User" />
       </div>
       <div class="info-container">
         <div class="name" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">John Doe</div>
         <div class="email">john.doe@example.com</div>
         <div class="btn-group user-helper-dropdown">
           <!--<i class="material-icons" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">keyboard_arrow_down</i>-->
           <ul class="dropdown-menu pull-right">
             <li><a href="javascript:void(0);"><i class="material-icons">person</i>Profile</a></li>
             <li role="separator" class="divider"></li>
             <li><a href="javascript:void(0);"><i class="material-icons">group</i>Followers</a></li>
             <li><a href="javascript:void(0);"><i class="material-icons">shopping_cart</i>Sales</a></li>
             <li><a href="javascript:void(0);"><i class="material-icons">favorite</i>Likes</a></li>
             <li role="separator" class="divider"></li>
             <li><a href="javascript:void(0);"><i class="material-icons">input</i>Sign Out</a></li>
           </ul>
         </div>
       </div>
     </div>
     <!-- #User Info -->
     <!-- Menu -->
     <div class="menu">
       <ul class="list">
         <li class="header">MAIN NAVIGATION</li>
         <li class="active">
           <a href="javascript:void(0);" class="menu-toggle">
             <i class="material-icons">widgets</i>
             <span>Projets</span>
           </a>
           <ul class="ml-menu">
             <li>
               <a href="javascript:void(0);">
                 <button type="button" class="btn btn-xs bg-blue-grey waves-effect" style="width: 232px">
                   <i class="material-icons">add_to_queue</i>
                   <span style="color: white">Ajouter Nouveau Projet</span>
                 </button>
               </a>
             </li>
             <li>
               <a href="profile" >
                 <span>test</span>
               </a>
             </li>
             <li>
               <a href="javascript:void(0);" class="menu-toggle">
                 <span>Infobox</span>
               </a>
               <ul class="ml-menu">
                 <li>
                   <a href="pages/widgets/infobox/infobox-1.html">Infobox-1</a>
                 </li>
                 <li>
                   <a href="pages/widgets/infobox/infobox-2.html">Infobox-2</a>
                 </li>
                 <li>
                   <a href="pages/widgets/infobox/infobox-3.html">Infobox-3</a>
                 </li>
                 <li>
                   <a href="pages/widgets/infobox/infobox-4.html">Infobox-4</a>
                 </li>
                 <li>
                   <a href="pages/widgets/infobox/infobox-5.html">Infobox-5</a>
                 </li>
               </ul>
             </li>
           </ul>
         </li>
       </ul>
     </div>
     <!-- #Menu -->
     <!-- Footer -->
     <div class="legal">
       <div class="copyright">
       </div>
       <div class="version">
         <b>Version: </b> 1.0.0
       </div>
     </div>
     <!-- #Footer -->
   </aside>
   <!-- #END# Left Sidebar -->
   <!-- Right Sidebar -->
   <aside id="rightsidebar" class="right-sidebar">
     <ul class="nav nav-tabs tab-nav-right" role="tablist">
       <li role="presentation" class="active"><a href="#skins" data-toggle="tab">SKINS</a></li>
       <li role="presentation"><a href="#settings" data-toggle="tab">SETTINGS</a></li>
     </ul>
     <div class="tab-content">
       <div role="tabpanel" class="tab-pane fade in active in active" id="skins">
         <ul class="demo-choose-skin">
           <li data-theme="red" class="active">
             <div class="red"></div>
             <span>Red</span>
           </li>
           <li data-theme="pink">
             <div class="pink"></div>
             <span>Pink</span>
           </li>
           <li data-theme="purple">
             <div class="purple"></div>
             <span>Purple</span>
           </li>
           <li data-theme="deep-purple">
             <div class="deep-purple"></div>
             <span>Deep Purple</span>
           </li>
           <li data-theme="indigo">
             <div class="indigo"></div>
             <span>Indigo</span>
           </li>
           <li data-theme="blue">
             <div class="blue"></div>
             <span>Blue</span>
           </li>
           <li data-theme="light-blue">
             <div class="light-blue"></div>
             <span>Light Blue</span>
           </li>
           <li data-theme="cyan">
             <div class="cyan"></div>>
             <span>Cyan</span>
           </li>
           <li data-theme="teal">
             <div class="teal"></div>
             <span>Teal</span>
           </li>
           <li data-theme="green">
             <div class="green"></div>
             <span>Green</span>
           </li>
           <li data-theme="light-green">
             <div class="light-green"></div>
             <span>Light Green</span>
           </li>
           <li data-theme="lime">
             <div class="lime"></div>
             <span>Lime</span>
           </li>
           <li data-theme="yellow">
             <div class="yellow"></div>
             <span>Yellow</span>
           </li>>
           <li data-theme="amber">
             <div class="amber"></div>
             <span>Amber</span>
           </li>
           <li data-theme="orange">
             <div class="orange"></div>
             <span>Orange</span>
           </li>
           <li data-theme="deep-orange">
             <div class="deep-orange"></div>
             <span>Deep Orange</span>
           </li>
           <li data-theme="brown">
             <div class="brown"></div>
             <span>Brown</span>
           </li>
           <li data-theme="grey">
             <div class="grey"></div>
             <span>Grey</span>
           </li>
           <li data-theme="blue-grey">
             <div class="blue-grey"></div>
             <span>Blue Grey</span>
           </li>
           <li data-theme="black">
             <div class="black"></div>
             <span>Black</span>
           </li>
         </ul>
       </div>
       <div role="tabpanel" class="tab-pane fade" id="settings">
         <div class="demo-settings">
           <p>GENERAL SETTINGS</p>
           <ul class="setting-list">
             <li>>
               <span>Report Panel Usage</span>
               <div class="switch">
                 <label><input type="checkbox" checked><span class="lever"></span></label>
               </div>
             </li>
             <li>
               <span>Email Redirect</span>
               <div class="switch">
                 <label><input type="checkbox"><span class="lever"></span></label>
               </div>
             </li>
           </ul>
           <p>SYSTEM SETTINGS</p>
           <ul class="setting-list">
             <li>
               <span>Notifications</span>
               <div class="switch">
                 <label><input type="checkbox" checked><span class="lever"></span></label>
               </div>
             </li>
             <li>
               <span>Auto Updates</span>
               <div class="switch">
                 <label><input type="checkbox" checked><span class="lever"></span></label>
               </div>
             </li>
           </ul>
           <p>ACCOUNT SETTINGS</p>
           <ul class="setting-list">
             <li>
               <span>Offline</span>
               <div class="switch">
                 <label><input type="checkbox"><span class="lever"></span></label>
               </div>
             </li>
             <li>
               <span>Location Permission</span>
               <div class="switch">
                 <label><input type="checkbox" checked><span class="lever"></span></label>
               </div>
             </li>
           </ul>
         </div>
       </div>
     </div>
   </aside>
   <!-- #END# Right Sidebar -->
 </section>

 <section class="content">
     <!--<router-view/>-->


 <div class="container-fluid">
   <div class="block-header">
     <h2>DASHBOARD</h2>
   </div>

   <!-- Widgets -->
   <div class="row clearfix">
     <div class="col-lg-2 col-md-2 col-sm-6 col-xs-12 ">
       <div class="info-box bg-purple hover-expand-effect" href="conception">
         <div class="icon">
           <i class="material-icons">assignment</i>
         </div>
         <div class="content" >
           <div class="text">CONCEPTION</div>
         </div>
       </div>
     </div>
     <div class="col-lg-2 col-md-2 col-sm-6 col-xs-12">
       <div class="info-box bg-pink hover-expand-effect">
         <div class="icon">
           <i class="material-icons">extension</i>
         </div>
         <div class="content">
           <div class="text">COMPOSANT</div>
         </div>
       </div>
     </div>
     <div class="col-lg-2 col-md-2 col-sm-6 col-xs-12">
       <div class="info-box bg-cyan hover-expand-effect">
         <div class="icon">
           <i class="material-icons">link</i>
         </div>
         <div class="content">
           <div class="text">API</div>
         </div>
       </div>
     </div>
     <div class="col-lg-2 col-md-2 col-sm-6 col-xs-12">
       <div class="info-box bg-light-green hover-expand-effect">
         <div class="icon">
           <i class="material-icons">text_format</i>
         </div>
         <div class="content">
           <div class="text">CODE</div>
         </div>
       </div>
     </div>
     <div class="col-lg-2 col-md-2 col-sm-6 col-xs-12">
       <div class="info-box bg-orange hover-expand-effect">
         <div class="icon">
           <i class="material-icons">insert_drive_file</i>
         </div>
         <div class="content" >
           <div class="text" style="margin-top: 2px">MANUEL UTILISATEUR</div>
         </div>
       </div>
     </div>
   </div>
 </div>
 <div>


  <router-view></router-view>




             <!-- end -->

 </div>



 </section>
</div>



</template>


<script>


export default {

  name : 'container'

}


</script>


<style>



</style>
