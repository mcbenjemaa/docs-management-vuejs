<template>

<div>

<div class="container-fluid">
  <div class="block-header">
    <h2>DASHBOARD</h2>
  </div>

  <!-- Widgets -->
  <div class="row clearfix">
    <div class="col-lg-2 col-md-2 col-sm-6 col-xs-12 ">
      <div class="info-box bg-purple hover-expand-effect" [routerLink]="['conception']">
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
<div>    <router-view/>
</div>

</div>

</template>
