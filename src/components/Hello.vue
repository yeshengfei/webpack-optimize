<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
      <br>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
    <div id="chart"></div>
  </div>
</template>

<script>


export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
    },
    mounted( ) {
        // var option = {
        //     title: {
        //         text: '堆叠区域图'
        //     },
        //     tooltip : {
        //         trigger: 'axis',
        //         axisPointer: {
        //             type: 'cross',
        //             label: {
        //                 backgroundColor: '#6a7985'
        //             }
        //         }
        //     },
        //     legend: {
        //         data:['邮件营销','联盟广告','视频广告','直接访问','搜索引擎']
        //     },
        //     toolbox: {
        //         feature: {
        //             saveAsImage: {}
        //         }
        //     },
        //     grid: {
        //         left: '3%',
        //         right: '4%',
        //         bottom: '3%',
        //         containLabel: true
        //     },
        //     xAxis : [
        //         {
        //             type : 'category',
        //             boundaryGap : false,
        //             data : ['周一','周二','周三','周四','周五','周六','周日']
        //         }
        //     ],
        //     yAxis : [
        //         {
        //             type : 'value'
        //         }
        //     ],
        //     series : [
        //         {
        //             name:'邮件营销',
        //             type:'line',
        //             stack: '总量',
        //             areaStyle: {normal: {}},
        //             data:[120, 132, 101, 134, 90, 230, 210]
        //         },
        //         {
        //             name:'联盟广告',
        //             type:'line',
        //             stack: '总量',
        //             areaStyle: {normal: {}},
        //             data:[220, 182, 191, 234, 290, 330, 310]
        //         },
        //         {
        //             name:'视频广告',
        //             type:'line',
        //             stack: '总量',
        //             areaStyle: {normal: {}},
        //             data:[150, 232, 201, 154, 190, 330, 410]
        //         },
        //         {
        //             name:'直接访问',
        //             type:'line',
        //             stack: '总量',
        //             areaStyle: {normal: {}},
        //             data:[320, 332, 301, 334, 390, 330, 320]
        //         },
        //         {
        //             name:'搜索引擎',
        //             type:'line',
        //             stack: '总量',
        //             label: {
        //                 normal: {
        //                     show: true,
        //                     position: 'top'
        //                 }
        //             },
        //             areaStyle: {normal: {}},
        //             data:[820, 932, 901, 934, 1290, 1330, 1320]
        //         }
        //     ]
        // };
        //
        //
        // var echart = echarts.init(this.$el.querySelector("#chart"));
        // echart.setOption(option);
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

#chart {
    width: 500px;
    height: 400px;
}
</style>
