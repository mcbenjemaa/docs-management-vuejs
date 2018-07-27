<template>

    <div class="row clearfix">
                   <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
                       <div class="card">
                           <div class="header">
                               <div class="row clearfix">
                                   <div class="col-xs-12 col-sm-6">
                                       <h2>CPU USAGE (%)</h2>
                                   </div>
                                   <div class="col-xs-12 col-sm-6 align-right">
                                       <div class="switch panel-switch-btn">
                                           <span class="m-r-10 font-12">REAL TIME</span>
                                           <label>OFF<input type="checkbox" id="realtime" checked=""><span class="lever switch-col-cyan"></span>ON</label>
                                       </div>
                                   </div>
                               </div>
                               <ul class="header-dropdown m-r--5">
                                   <li class="dropdown">
                                       <a href="javascript:void(0);" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                                           <i class="material-icons">more_vert</i>
                                       </a>
                                       <ul class="dropdown-menu pull-right">
                                           <li><a href="javascript:void(0);" class=" waves-effect waves-block">Action</a></li>
                                           <li><a href="javascript:void(0);" class=" waves-effect waves-block">Another action</a></li>
                                           <li><a href="javascript:void(0);" class=" waves-effect waves-block">Something else here</a></li>
                                       </ul>
                                   </li>
                               </ul>
                           </div>
                           <div class="body">
                               <div id="real_time_chart" class="dashboard-flot-chart" style="padding: 0px; position: relative;"><canvas class="flot-base" width="890" height="275" style="direction: ltr; position: absolute; left: 0px; top: 0px; width: 890px; height: 275px;"></canvas><div class="flot-text" style="position: absolute; top: 0px; left: 0px; bottom: 0px; right: 0px; font-size: smaller; color: rgb(84, 84, 84);"><div class="flot-x-axis flot-x1-axis xAxis x1Axis" style="position: absolute; top: 0px; left: 0px; bottom: 0px; right: 0px; display: block;"><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 22px; text-align: center;">0</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 104px; text-align: center;">10</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 190px; text-align: center;">20</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 275px; text-align: center;">30</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 361px; text-align: center;">40</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 446px; text-align: center;">50</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 532px; text-align: center;">60</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 617px; text-align: center;">70</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 703px; text-align: center;">80</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 788px; text-align: center;">90</div><div class="flot-tick-label tickLabel" style="position: absolute; max-width: 80px; top: 258px; left: 871px; text-align: center;">100</div></div><div class="flot-y-axis flot-y1-axis yAxis y1Axis" style="position: absolute; top: 0px; left: 0px; bottom: 0px; right: 0px; display: block;"><div class="flot-tick-label tickLabel" style="position: absolute; top: 245px; left: 14px; text-align: right;">0</div><div class="flot-tick-label tickLabel" style="position: absolute; top: 196px; left: 7px; text-align: right;">20</div><div class="flot-tick-label tickLabel" style="position: absolute; top: 147px; left: 7px; text-align: right;">40</div><div class="flot-tick-label tickLabel" style="position: absolute; top: 98px; left: 7px; text-align: right;">60</div><div class="flot-tick-label tickLabel" style="position: absolute; top: 49px; left: 7px; text-align: right;">80</div><div class="flot-tick-label tickLabel" style="position: absolute; top: 0px; left: 1px; text-align: right;">100</div></div></div><canvas class="flot-overlay" width="890" height="275" style="direction: ltr; position: absolute; left: 0px; top: 0px; width: 890px; height: 275px;"></canvas></div>
                           </div>
                       </div>
                   </div>
               </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
